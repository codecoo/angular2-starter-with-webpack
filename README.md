##Installation  AngularJs2

quick start angularjs2 follow instruction https://angular.io/docs/ts/latest/quickstart.html and manual install cor-js

```sh
$ node_modules/.bin/typings install --global --save dt~core-js                                    
```
to compile all typescript 

```sh
$ node_modules/.bin/tsc --rootDir src --outDir dist      
```
                         
##Installation Webpack

```sh
$ npm install webpack --save-dev
```
download typescript loader 

```sh                                                                     
$ npm install ts-loader --save-dev
```
##Usage

```sh
$ node_modules/.bin/webpack --progress
```
build html to dist

```sh
$ npm install --save-dev html-webpack-plugin
```
set environment to mode development

```sh
$ npm install --save-dev webpack-dev-server 
```