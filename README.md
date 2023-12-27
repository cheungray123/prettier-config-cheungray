<div style="text-align: center;" align="center">
  # prettier-config-cheungray
</div>

> 请在使用前确保您本地安装了 prettier

## 安装教程

```shell
# 使用pnpm安装
pnpm install -D prettier-config-cheungray

# 使用yarn安装
yarn add prettier-config-cheungray --dev

# 使用npm安装
npm install prettier-config-cheungray -D
```

## 使用说明

### 方法 1. 修改 package.json

编辑您项目 package.json 加上下面这一行

```json
{
  "prettier": "prettier-config-cheungray"
}
```

### 方法 2. 创建/修改本地.prettierrc.js 文件

```js
// 编辑.prettierrc.js
module.exports = require("prettier-config-cheungray");
```

# 详细配置翻译

```json
{
  // $schema 用于指定此文件所使用的 JSON Schema，可以帮助编辑器提供针对 Prettier 配置的智能提示和验证。
  "$schema": "http://json.schemastore.org/prettierrc",
  
  // arrowParens 指定箭头函数参数是否带括号，值为 always, avoid, 或 preserve。
  "arrowParens": "always",
  
  // bracketSameLine 指定对象大括号是否与对象名称在同一行，值为 true 或 false。
  "bracketSameLine": true,
  
  // bracketSpacing 指定对象大括号内部是否有空格，值为 true 或 false。
  "bracketSpacing": true,
  
  // embeddedLanguageFormatting 指定嵌入式语言（如 HTML、CSS）的格式化方式，值为 auto、off、或 on。
  "embeddedLanguageFormatting": "auto",
  
  // endOfLine 指定换行符类型，值为 lf、cr、或 crlf。
  "endOfLine": "lf",
  
  // htmlWhitespaceSensitivity 指定 HTML 中空白符的敏感度，值为 css、strict、或 ignore。
  "htmlWhitespaceSensitivity": "css",
  
  // insertPragma 指定是否在文件开头插入一个特殊的注释，以便其他工具知道该文件已经进行了格式化。
  "insertPragma": false,
  
  // jsxSingleQuote 指定 JSX 属性值是否使用单引号，值为 true 或 false。
  "jsxSingleQuote": true,
  
  // printWidth 指定每行的最大字符数。
  "printWidth": 80,
  
  // proseWrap 指定换行方式，值为 always、never、或 preserve。
  "proseWrap": "preserve",
  
  // quoteProps 指定对象属性名是否加引号，值为 as-needed、consistent、或 preserve。
  "quoteProps": "as-needed",
  
  // requirePragma 指定是否只格式化带特殊注释的文件。
  "requirePragma": false,
  
  // semi 指定是否在语句末尾添加分号，值为 true 或 false。
  "semi": false,
  
  // singleAttributePerLine 指定是否将标签的每个属性放在单独的一行，值为 true 或 false。
  "singleAttributePerLine": true,
  
  // singleQuote 指定是否使用单引号，值为 true 或 false。
  "singleQuote": true,
  
  // tabWidth 指定一个制表符应该占据的空格数。
  "tabWidth": 2,
  
  // trailingComma 指定是否在对象和数组的最后一个元素后面添加逗号，值为 none、es5、或 all。
  "trailingComma": "none",
  
  // useTabs 指定是否使用制表符代替空格缩进，值为 true 或 false。
  "useTabs": true
}

```