# 🧑‍💻 Overview of Angular js

**AngularJS**
- AngularJS é um framework JavaScript de código aberto que é utilizado para desenvolver aplicativos web dinâmicos. Ele permite o uso de um vocabulário HTML estendido para a construção de páginas web, tornando mais fácil para os desenvolvedores criar aplicações web interativas.

**angular.module**
- angular.module é um objeto global que permite a criação de módulos em um aplicativo AngularJS. Esses módulos podem ser utilizados para organizar e reutilizar código em uma aplicação.

**angular.module().controller()**
- angular.module().controller() é um método utilizado para criar um novo controlador dentro de um módulo AngularJS. O controlador é responsável por controlar o fluxo de dados entre a view e o modelo de dados.

**$scope**  
- scope é um objeto especial do AngularJS que permite que as propriedades e métodos definidos no controlador sejam acessados a partir da view. Ele é utilizado para criar uma conexão entre a view e o controlador.

**Interpolação {{}}**
- A interpolação {{}} é uma expressão do AngularJS que permite a exibição de valores de variáveis na view. Ela é usada para fazer o binding de dados entre a view e o controlador.

# 🛩 Diretivas

- As diretivas no AngularJS permitem criar novos elementos HTML personalizados ou adicionar comportamentos personalizados a elementos existentes. Elas são definidas como funções que recebem o escopo do AngularJS e o elemento HTML a ser manipulado. As diretivas são usadas para criar componentes personalizados e são uma das características mais poderosas do AngularJS para criar aplicações web dinâmicas e interativas.

**ng**
- ng é uma diretiva do AngularJS que é utilizada para criar outras diretivas personalizadas. Ela é a base para a criação de diretivas no AngularJS.

**ng-app**
- ng-app é uma diretiva do AngularJS que define o elemento HTML que será utilizado como a raiz da aplicação AngularJS.

**ng-controller**
- ng-controller é uma diretiva do AngularJS que define o controlador que será utilizado para controlar a lógica de uma seção da view.

**ng-bind**
- ng-bind é uma diretiva do AngularJS que faz o binding de um valor de uma variável para um elemento HTML na view. É semelhante a interpolação {{}}.

**ng-click**
- ng-click é uma diretiva do AngularJS que adiciona um evento de clique a um elemento HTML na view. Quando o elemento é clicado, a função definida é executada.

**ng-repeat**
- ng-repeat é uma diretiva do AngularJS que permite a criação de listas iteráveis na view. Ela permite que os itens de uma lista sejam renderizados na view usando uma estrutura de repetição.

**ng-disabled**
- ng-disabled é uma diretiva do AngularJS que desabilita um elemento HTML quando a expressão definida é verdadeira.

**ng-options**
- ng-options é uma diretiva do AngularJS que é usada para gerar um elemento HTML de seleção de opções '(select)' com as opções definidas pelo desenvolvedor.

**ng-class**
- ng-class é uma diretiva do AngularJS que permite a adição e remoção de classes CSS a um elemento HTML com base na expressão definida.

**ng-style**
- ng-style é uma diretiva do AngularJS que permite a definição de estilos CSS a um elemento HTML com base na expressão definida.

**ng-show**
- ng-show é uma diretiva do AngularJS que mostra um elemento HTML quando a expressão definida é verdadeira.

**ng-hide**
- ng-hide é uma diretiva do AngularJS que esconde um elemento HTML quando a expressão definida é verdadeira.

**ng-if** 
- é uma diretiva do AngularJS que permite a renderização condicional de um elemento HTML na view. Ela adiciona ou remove o elemento da view com base na expressão definida. Se a expressão é verdadeira, o elemento é adicionado à view. Caso contrário, ele é removido da view.

**ng-include"''"**
- ng-include: Uma diretiva do AngularJS que é usada para incluir conteúdo HTML de um arquivo externo em uma página da web. Pode ser usado para incluir partes de uma página em várias outras páginas, como um cabeçalho ou um rodapé comum.

## 📝 Validações de formulários

**ng-required**
- Uma diretiva do AngularJS que é usada para validar se um campo de entrada está vazio ou não. Se o campo estiver vazio e a diretiva estiver presente, o formulário será considerado inválido.

**$invalid**
- Uma propriedade que indica se um formulário ou campo de entrada é inválido. É definido como verdadeiro se uma validação falhar.

**$valid**
- Uma propriedade que indica se um formulário ou campo de entrada é válido. É definido como verdadeiro se todas as validações forem bem-sucedidas.

**$dirty**
- Uma propriedade que indica se um campo de entrada foi modificado pelo usuário. Se o campo foi modificado, a propriedade será definida como verdadeira.

**$setPristine()**
- Um método usado para definir um campo de entrada como "puro" ou "não sujo", o que significa que o campo ainda não foi modificado pelo usuário.

**ng-minlength**
 - Uma diretiva do AngularJS que é usada para validar se um campo de entrada tem um comprimento mínimo especificado. Se o campo de entrada não atender ao comprimento mínimo especificado, o formulário será considerado inválido.

**ng-maxlength** 
- Uma diretiva do AngularJS que é usada para validar se um campo de entrada tem um comprimento máximo especificado. Se o campo de entrada exceder o comprimento máximo especificado, o formulário será considerado inválido.

**$error**
- Uma propriedade que contém um objeto com todos os erros de validação associados a um formulário ou campo de entrada.

**ng-pattern**
- Uma diretiva do AngularJS que é usada para validar um campo de entrada com base em uma expressão regular especificada. O formulário será considerado inválido se o valor do campo de entrada não corresponder à expressão regular.

**ng-messages**
- Uma diretiva do AngularJS que permite exibir mensagens de erro de validação para campos de entrada em formulários. Ela exibe uma mensagem de erro associada a uma determinada validação somente se essa validação falhar.

**ng-message**
- Uma diretiva do AngularJS que é usada para exibir uma mensagem de erro específica para um campo de entrada com base em uma determinada validação. É usado em conjunto com a diretiva ng-messages para exibir mensagens de erro personalizadas.