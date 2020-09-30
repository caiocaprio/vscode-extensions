# vscode-extensions

Meu Conjunto de plugins do VS Code.

## Extensões incluídas

- [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets) - Esta extensão fornece fragmentos de JavaScript e React / Redux no ES7 com recursos de plug-in Babel para VS Code

- [EditorConfig for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - Esse plugin sobreescreve as configurações do editor baseado no arquivo `.editorconfig` local.

- [VS Code ESLint extension](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integra o Eslint no editor para buscar erros.

- [Prettier Formatter for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - Um plugin que roda o prettier para formatar arquivos.

- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) - Automaticamente renomeia a tag par que está sendo modificada.

- [vscode-duplicate](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-duplicate) - Facilita para duplicar arquivos e também diretórios inteiros.

- [VSCode Advanced New File](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file) - Permite criar arquivos e pastas de forma mais prática.

- [Git Blame](https://marketplace.visualstudio.com/items?itemName=waderyan.gitblame) - Mostra na barra de status o commit que modificou a linha selecionada.


- [Apollo GraphQL for VS Code](https://marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo) - Um conjunto de ferramentas para trabalhar com GraphQL e Apollo, incluindo syntax highlighting e autocomplete.

- [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components) - Syntax highlighting para Styled Components.

- [VS Code JavaScript (ES6) snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) - Alguns snippets úteis para JavaScript.

- [vscode-jest-snippets](https://marketplace.visualstudio.com/items?itemName=andys8.jest-snippets) - Alguns snippets úteis para Jest (framework de testes).

- [JS JSX Snippets](https://marketplace.visualstudio.com/items?itemName=skyran.js-jsx-snippets) - Alguns snippets úteis para React e JSX em si.

- [Snippets úteis para NextJS](https://marketplace.visualstudio.com/items?itemName=PulkitGangwar.nextjs-snippets) - Alguns snippets úteis para NextJS.

- [JavaScript and TypeScript Nightly](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-next) - Habilita o suporte JavaScript e TypeScript para as próximas versões.

- [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) - Esta extensão estiliza as cores css / web encontradas no seu documento.

- [Doxygen Documentation Generator](https://marketplace.visualstudio.com/items?itemName=cschlosser.doxdocgen) - Fornece geração de documentação do Doxygen em tempo real, iniciando um bloco de comentário do Doxygen e pressionando enter.

- [Duplicate action](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-duplicate) - Capacidade de duplicar arquivos e diretórios no código VS

## Gostaria de instalar somente algumas extensões?

Para instalar somente algumas das extensões, basta editar o arquivo [package.json](package.json) removendo as extensões não desejadas do `extensionPack` e depois siga os procedimentos abaixo para instalar localmente.

## Como desenvolver e instalar localmente

- Clone o repositório

```bash
$ git clone https://github.com/caiocaprio/vscode-extensions
```

- Instale o vsce

```bash
$ npm install -g vsce
```

- Crie o pacote da extensão

```bash
$ vsce package
```

- Instale a extensão através do arquivo `.vsix`

1. Abra o VS Code
2. Selecione **Extensions** do menu
3. Clique em **More** > **Install from VSIX...**
4. Selecione o arquivo `vscode-extensions-x.x.x.vsix`
5. Clique em **Reload Now** para recarregar o VS Code

## Tem alguma extensão que gostaria e não tem?

Basta abrir um PR com a extensão e ficarei feliz em analisar =)
