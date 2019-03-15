# AngularDemo

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

Github 笔记
# Angular2
### Angular2 相关技术  TypeScript webpack npm
##  TypeScript
TypeScript 是 Microsoft 开发和维护的一种面向对象的编程语言。它是 JavaScript 的超集，包含了 JavaScript 的所有元素，
可以载入 JavaScript 代码运行，并扩展了 JavaScript 的语法.
    TypeScript 是 Microsoft 推出的开源语言，使用 Apache 授权协议.
    TypeScript 增加了静态类型、类、模块、接口和类型注解.	
    JavaScript 和 TypeScript 的主要差异TypeScript 可以使用 JavaScript 中的所有代码和编码概念，TypeScript 是为了使 JavaScript 的开发变得更加容易而创建的。例如，TypeScript 使用类型和接口等概念来描述正在使用的数据，这使开发人员能够快速检测错误并调试应用程序
    TypeScript 从核心语言方面和类概念的模塑方面对 JavaScript 对象模型进行扩展。
    JavaScript 代码可以在无需任何修改的情况下与 TypeScript 一同工作，同时可以使用编译器将 TypeScript 代码转换为 JavaScript。
    TypeScript 通过类型注解提供编译时的静态类型检查。
    TypeScript 中的数据要求带有明确的类型，JavaScript不要求。
    TypeScript 为函数提供了缺省参数值。
    TypeScript 引入了 JavaScript 中没有的“类”概念。
    TypeScript 中引入了模块的概念，可以把声明、数据、函数和类封装在模块中
https://angular.io/guide/quickstart

https://code.visualstudio.com/docs/nodejs/angular-tutorial
    npm install -g @angular/cli
    ng new my-app
    cd my-app
    ng serve
    You should see "Welcome to app!!" on http://localhost:4200 in your browser
    cd my-app
    code .

    app.component.ts— the component class code, written in TypeScript.
    app.component.html— the component template, written in HTML.
    app.component.css— the component's private CSS styles.
### DNE CENTER 代码笔记
    http://www.runoob.com/angularjs2/angularjs2-architecture.html
    package.json
    @angular/animations
    @angular/cdk
    @angular/common
    @angular/compiler
    @angular/core
    @angular/forms
    @angular/http
    @angular/material
    @angular/platform-browser
    @angular/platform-browser-dynamic          bootstraping: get (oneself or something) into or out of a situation using existing resources.
    @angular/router
    core-js
    hammerjs
    ngx-bootstrap
    rxjs
    zone.js
    
    devDependencies
    @angular-devkit/build-angular
    @angular-cli
    @angular-compiler-cli
    @angular-language-service
    @type-jasmine
    @type-jasminewd2
    @types/node
    @codelyzer
    jasmine-core
    jasmine-spec-reporter
    karma
    karma-chrome-launcher
    karma-coverage-istanbul-reporter
    karma-jasmine
    karma-jasmine-html-reporter
    protractor
    ts-node
    tslint
    typescript
    
### 关于 @angular/ 的 @
    https://stackoverflow.com/questions/36667258/what-is-the-meaning-of-the-at-prefix-on-npm-packages
    

### webstorm live Templates
  在webstorm中输入rrc并点击那个提示小灯泡，可以打开一个窗口看到各种框架的模板生成快捷键。
  其中angular的很多，输入英文字母就可以搜到很多。

### const  let 
https://dev.to/sarah_chima/var-let-and-const--whats-the-difference-69e

const cannot be updated or re-declared

内存地址，== 与 ====

### \<ng-template matTabContent\>  延迟加载
    https://material.angular.io/components/tabs/overview
    https://dzone.com/articles/understanding-output-and-eventemitter-in-angular
    In Angular, a component can emit an event using @Output and EventEmitter.

    https://blog.csdn.net/wf19930209/article/details/79349164

###  @ViewChild 父子组件通信
    https://www.cnblogs.com/sghy/p/7244500.html

