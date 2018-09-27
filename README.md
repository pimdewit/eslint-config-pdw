# What?
This ESLint config aims to aid you with writing compact, standalone methods whilst paying attention to documentation and type checking. It is built on top of the Google code style.


## Installation

NPM: `npm install --save-dev eslint-plugin-import eslint-plugin-react eslint-plugin-jsdoc eslint-plugin-html eslint-config-google eslint-config-pdw`

Yarn: `yarn add --dev eslint-plugin-import eslint-plugin-react eslint-plugin-jsdoc eslint-plugin-html eslint-config-google eslint-config-pdw`

In package.json add the following object top-level:

```
"eslintConfig": {
  "extends": "pdw"
}
```
