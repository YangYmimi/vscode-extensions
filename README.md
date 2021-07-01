# Some extensions in VSCode

### 记录 vscode 中经常用的扩展

- vetur : Vue 插件

  - Extension Id : octref.vetur

- ES7 React/Redux/GraphQL/React-Native snippets

  - Extension Id : dsznajder.es7-react-js-snippets

- Auto Import : 自动导入插件

  - Extension Id : steoates.autoimport

- EsLint

  - Extension Id : dbaeumer.vscode-eslint

- Prettier - Code formatter

  - Extension Id : esbenp.prettier-vscode

- jest : 测试插件

  - Extension Id : orta.vscode-jest

- Npm Dependency : 依赖升级插件

  - Extension Id : howardzuo.vscode-npm-dependency

- Color Highlight : 颜色插件

  - Extension Id : naumovs.color-highlight

- Formatting Toggle : A VS Code extension that allows you to toggle the formatter (Prettier, Beautify, …) ON and OFF with a simple click.

  - Extension Id : tombonnike.vscode-status-bar-format-toggle

### VS Code 配置

```JSON
{
    "explorer.confirmDelete": false,
    "eslint.alwaysShowStatus": true,
    "eslint.format.enable": true,
    "eslint.run": "onSave",
    "vetur.format.defaultFormatter.js": "prettier-eslint",
    "[vue]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "editor.tabSize": 2,
    "editor.renderWhitespace": "boundary",
    "editor.wordWrap": "wordWrapColumn",
    "editor.formatOnSave": true,
    "vetur.validation.template": false,
    "[json]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "explorer.confirmDragAndDrop": false,
    "files.eol": "\n",
    "editor.defaultFormatter": "dbaeumer.vscode-eslint",
    "prettier.trailingComma": "none",
    "prettier.proseWrap": "always",
    "prettier.jsxBracketSameLine": true,
    "autoimport.doubleQuotes": true,
    "prettier.insertPragma": true,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "security.workspace.trust.untrustedFiles": "open",
    "[go]": {
        "editor.renderWhitespace": "none",
        "editor.defaultFormatter": "golang.go"
    },
    "gopls": {
        "formatting.gofumpt": true
    },
    "go.lintTool": "golint"
}
```
