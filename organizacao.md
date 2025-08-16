# Projeto Final - Organização

## 📁 Pastas

    📂 nosso_projeto
    ├─📁 public - recursos estáticos públicos que são servidos pela aplicação, acessíveis diretamente pela url
    ├─📁 src
    │  ├──📁 assets - recursos estáticos que são importados no código
    │  ├──📁 components - componentes gerais, utilizados em mais de uma página
    │  ├──📁 layouts
    │  ├──📂 pages
    │  │   ├──📂 home
    │  │   │   ├──📁 components - componentes específicos da página
    │  │   │   └──📄 Home.jsx
    │  │   └──📂 login
    │  │       ├──📁 components
    │  │       └──📄 Login.jsx
    // ...


<br>

## 🏷️ Nomenclatura

### Arquivos
- **Componentes:** PascalCase
- **Configurações, utils, etc:** camelCase
- Em Inglês (?)

### Componentes
- PascalCase
- Em Inglês (?)

### Variáveis
- camelCase
- Em Inglês (?)

### Comentários
- Em Português (?)

<br>

## 🧩 Componentes
- Definição de componente: sintaxe de **function**
- Definição de funções dentro de componentes: sintaxe de **arrow function (const)**

<br>

## 📍 Commits
### Fontes e mais exemplos
- [iuricode | GitHub](https://github.com/iuricode/padroes-de-commits)
- [Conventional Commits Pattern | Medium](https://medium.com/linkapi-solutions/conventional-commits-pattern-3778d1a1e657)

### Estrutura do commit:
-   “`tipo`: mensagem”

Escreva a mensagem no imperativo (criar, mudar, adicionar), no sentido de dizer o que o commit fará se for aplicado. Pense na frase **“Se aplicado, esse commit irá (mensagem)”**. Exemplo:

-   “`feat`: adicionar página de login”
-   “Se aplicado, esse commit irá adicionar página de login”

Dê preferência a mensagens pequenas e explicativas.

### Tipos:
O tipo é responsável por nos dizer qual o tipo de alteração ou iteração está sendo feita. Das regras da convenção, temos os seguintes tipos:

-   `test`: indica qualquer tipo de criação ou alteração de códigos de teste.
-   `feat`: indica o desenvolvimento de uma nova *feature* (novo recurso) no projeto.
-   `refactor`: usado quando houver uma refatoração de código que **não tenha qualquer tipo de impacto na lógica**/regras de negócio do sistema.
    -   Ex: Trocar functions para arrow functions
-   `style`: empregado quando há mudanças de formatação e estilo do código que **não alteram** o sistema de nenhuma forma.
    -   Mudar o *style-guide*, mudar de convenção *lint*, arrumar indentações, remover espaços em brancos, remover comentários, etc.
-   `fix`: utilizado quando há correção de erros que estão gerando bugs no sistema.
-   `chore`: indica mudanças no projeto que não afetem o sistema ou arquivos de testes. São mudanças de desenvolvimento.
    -   Mudar regras do *eslint*, adicionar *prettier*, adicionar mais extensões de arquivos ao *.gitignore*.
-   `docs`: usado quando há mudanças na documentação do projeto.
    -   Adicionar informações na documentação da API, mudar o *README*, etc.
-   `build`: utilizada para indicar mudanças que afetam o processo de build do projeto ou dependências externas.
    -   *Gulp*, adicionar/remover dependências do *npm*, etc.
-   `perf`: indica uma alteração que melhorou a performance do sistema.
    -   Alterar *forEach* por *while*, melhorar a query ao banco, etc.
-   `ci`: utilizada para mudanças nos arquivos de configuração de CI.
-   `revert`: indica a reverão de um commit anterior.
-   `cleanup`: indica remoção de código comentado, trechos desnecessários ou qualquer outra forma de limpeza do código-fonte, visando aprimorar sua legibilidade e manutenibilidade.
-   `remove`: indica a exclusão de arquivos, diretórios ou funcionalidades obsoletas ou não utilizadas, reduzindo o tamanho e a complexidade do projeto e mantendo-o mais organizado.
