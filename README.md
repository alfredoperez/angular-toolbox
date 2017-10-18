# Angular Toolbox
[![Marketplace](https://vsmarketplacebadge.apphb.com/version-short/alfredoperez.angular-toolbox.svg)](https://marketplace.visualstudio.com/items?itemName=alfredoperez.angular-toolbox)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/alfredoperez.angular-toolbox.svg)](https://marketplace.visualstudio.com/items?itemName=alfredoperez.angular-toolbox)
[![GitHub issues](https://img.shields.io/github/issues/alfredoperez/angular-toolbox.svg)](https://github.com/alfredoperez/angular-toolbox/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/alfredoperez/angular-toolbox.svg)](https://github.com/alfredoperez/angular-toolbox/pulls)
[![License](https://img.shields.io/github/license/alfredoperez/angular-toolbox.svg)](https://github.com/alfredoperez/angular-toolbox/blob/master/LICENSE)

This extension pack contains a collection of extensions and configurations to ensure code quality and consistency.

It has configurations to follow Angular Style Guide and even the style lint configuration that the Angular Material team uses.

# Table of Contents

  - [Configuration Files](#configuration-files)
      - [Linters](#linters)
      - [Extra](#extra)
  - [Extensions](#extensions)
      - [Angular](#angular)
      - [TypeScript](#typescript)
      - [Code Style and Linters](#code-style-and-linters)
      - [Tools](#tools)
---

## Configuration Files
---
### Linters

**[TS Lint](https://github.com/alfredoperez/angular-toolbox/blob/master/resources/configuration-files/tslint.json)**

 These rules are set to enforce a consistent code style for Angular development. This were copied from [ng-seed/angular-tslint-rules](https://github.com/ng-seed/angular-tslint-rules)

**[Style Lint](https://github.com/alfredoperez/angular-toolbox/blob/master/resources/stylelint/.stylelintrc)**

These rules are the ones that the Angular Material team uses. This were copied from [angular/material2](https://github.com/angular/material2).

To enable it,  Copy the contents of resources/stylelint to the root of your project and then install stylelint in your project:
  ```
  npm install --save-dev stylelint
  ```

**[Beautify](https://github.com/alfredoperez/angular-toolbox/blob/master/resources/configuration-files/.jsbeautifyrc)**

Set of rules to Beautify javascript, JSON, CSS, Sass, and HTML.

**[VS Code Settings](https://github.com/alfredoperez/angular-toolbox/blob/master/resources/configuration-files/.vscodesettings)**

An example of VS Code IDE Settings, to enable and configure the extensions installed

### Extra 

 Install FiraCode: Monospaced font with programming ligatures
 
  Settings: 
```
"editor.fontLigatures": true
"editor.fontFamily": "Fira Code, Consolas, 'Courier New', monospace"
```

## Extensions
---
### Angular
- [Angular v4 TypeScript Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)
- [Angular 2+ Snippets - TypeScript, Html, ngRx, Angular Flex Layout & Testing](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)
 
  Settings: 
    ```
    editor.snippetSuggestions": "top"
    ```
- [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
- [SimonTest](https://marketplace.visualstudio.com/items?itemName=SimonTest.simontest)
- [Angular Files](https://marketplace.visualstudio.com/items?itemName=alexiv.vscode-angular2-files)

### TypeScript

- [TypeScript  Hero](https://marketplace.visualstudio.com/items?itemName=rbbit.typescript-hero)
- [Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)
- [Move TS](https://marketplace.visualstudio.com/items?itemName=stringham.move-ts)

### Code Style and Linters

- [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)
- [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
 
  Settings: 
   ```
  "tslint.autoFixOnSave": true,
  "tslint.enable": false
     ```
- [StyleLint](https://marketplace.visualstudio.com/items?itemName=shinnn.stylelint)

 ***NOTE: This extension requires stylelint in your project. Install with the following command:
  ```
  npm install --save-dev stylelint
  ```

- [HTMLHint](https://marketplace.visualstudio.com/items?itemName=mkaufman.HTMLHint)
 
 ***NOTE: This extension requires HTMLHint. Install with the following command:
  ```
  npm install --global HTMLHint
  ```
 
    
### Tools
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
 
  Settings: 
  ``` 
  "auto-rename-tag.activationOnLanguage": [
          "html",
          "xml"   
  ],
  ```

- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
- [Output Colorizer](https://marketplace.visualstudio.com/items?itemName=IBM.output-colorizer)
- [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
- [TODO Parser](https://marketplace.visualstudio.com/items?itemName=minhthai.vscode-todo-parser)



