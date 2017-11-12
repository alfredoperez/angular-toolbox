# Angular Toolbox
[![Marketplace](https://vsmarketplacebadge.apphb.com/version-short/alfredoperez.angular-toolbox.svg)](https://marketplace.visualstudio.com/items?itemName=alfredoperez.angular-toolbox)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/alfredoperez.angular-toolbox.svg)](https://marketplace.visualstudio.com/items?itemName=alfredoperez.angular-toolbox)
[![GitHub issues](https://img.shields.io/github/issues/alfredoperez/angular-toolbox.svg)](https://github.com/alfredoperez/angular-toolbox/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/alfredoperez/angular-toolbox.svg)](https://github.com/alfredoperez/angular-toolbox/pulls)
[![License](https://img.shields.io/github/license/alfredoperez/angular-toolbox.svg)](https://github.com/alfredoperez/angular-toolbox/blob/master/LICENSE)

This extension pack contains a collection of extensions and configurations to ensure code quality and consistency.

It has configurations to follow **Angular Style Guide** and even the style lint configuration that the **Angular Material team** uses.

### Linters

**[TS Lint](https://github.com/alfredoperez/angular-toolbox/blob/master/resources/configuration-files/tslint.json)**

 These rules are set to enforce a consistent code style for Angular development. This were copied from [ng-seed/angular-tslint-rules](https://github.com/ng-seed/angular-tslint-rules)

 Make sure to add your selector to the directive-selector, component-selector and pipe-naming in the tslint.json file:
```
"directive-selector": [
  true,
  "attribute", [
  "ngx",
  "test"
  ],
  "camelCase"
],
"component-selector": [
  true,
  "element", [
    "ngx",
    "test"
    ],
  "kebab-case"
],

"pipe-naming": [
  true,
  "camelCase",
  "ngx"
],
```


**[Style Lint](https://github.com/alfredoperez/angular-toolbox/blob/master/resources/stylelint/.stylelintrc)**

These rules are the ones that the Angular Material team uses. This were copied from [angular/material2](https://github.com/angular/material2).

To enable it:  
* Install stylelint in your project:
  ```
  npm install --save-dev stylelint
  ```
* Copy the contents of resources/stylelint to the root of your project 
* Also, you can set the following configuration for Visual Studio Code to enable autosave
  
   ```
  "tslint.autoFixOnSave": true,
  "tslint.enable": false
   ```
**[Beautify](https://github.com/alfredoperez/angular-toolbox/blob/master/resources/configuration-files/.jsbeautifyrc)**

This file has a set of rules to Beautify javascript, JSON, CSS, Sass, and HTML.

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

It analyzes your code and creates the necessary stubs, configures the TestBed, and it even generates tests for you.

- [Angular Files](https://marketplace.visualstudio.com/items?itemName=alexiv.vscode-angular2-files)

### TypeScript

- [TypeScript  Hero](https://marketplace.visualstudio.com/items?itemName=rbbit.typescript-hero)

- [Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)

- [Move TS](https://marketplace.visualstudio.com/items?itemName=stringham.move-ts)

### Extra 

 Install FiraCode: Monospaced font with programming ligatures
 
  Settings: 
```
"editor.fontLigatures": true
"editor.fontFamily": "Fira Code, Consolas, 'Courier New', monospace"
```

**[VS Code Settings](https://github.com/alfredoperez/angular-toolbox/blob/master/resources/configuration-files/.vscodesettings)**

This file is an example of VS Code IDE Settings, that helps to enable and configure the extensions installed

### Other Extensions 

These extensions are not included with the toolbox but can help your development. 

- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)

- [Output Colorizer](https://marketplace.visualstudio.com/items?itemName=IBM.output-colorizer)