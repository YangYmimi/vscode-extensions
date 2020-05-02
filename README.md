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
    "prettier.endOfLine": "crlf",
    "prettier.printWidth": 120,
    "prettier.semi": false, // 句尾不添加分号
    "prettier.trailingComma": "none", // 在对象或数组最后一个元素后面是否加逗号（在ES5中加尾逗号）
    "prettier.arrowParens": "avoid", // (x) => {} 箭头函数参数只有一个时是否要有小括号。avoid：省略括号
    "prettier.bracketSpacing": true, // 在对象，数组括号与文字之间加空格 "{ foo: bar }"
    "eslint.format.enable": true,
    "[vue]": {
        "editor.defaultFormatter": "octref.vetur"
    },
    "vetur.format.defaultFormatter.ts": "prettier-tslint",
    "vetur.format.defaultFormatter.js": "prettier-eslint",
    "vetur.format.defaultFormatter.html": "prettier",
    "autoimport.useSemiColon": false,
    "editor.wordWrapColumn": 120,
    "editor.tabSize": 2,
    "editor.renderWhitespace": "boundary",
    "editor.formatOnPaste": true,
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.autoClosingBrackets": "always",
    "editor.autoClosingQuotes": "always",
    "editor.defaultFormatter": "dbaeumer.vscode-eslint",
    "terminal.integrated.shell.windows": "D:\\Git\\bin\\bash.exe"
}
```