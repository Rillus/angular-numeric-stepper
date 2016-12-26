# Angular stepper directive ![](https://img.shields.io/badge/maintained%3F-no!-red.svg?style=flat)

A simple numeric stepper for angular 1.x.

Has "step-by" attribute and a different layout

## Usage

To use the directive at this moment, there are two ways. (Pretty boring ways if you ask me)

1. One is to clone this repo and then manually copy to your project
2. Other is to follow the instructions on https://github.com/revolunet/angular-stepper
    and then implement the changes here

after installing add a dependency

Or npm : `npm install --save angular-stepper`

add a dependency to your app :
```javascript
angular.module('MyApp', [
    'revolunet.stepper'
]);
```
use the directive :
```html
<div rn-stepper ng-model="product.quantity" ng-disabled="config.totalAvailable < 1" min="config.min" max="config.max"></div>
```
Note: Optionaly, you can add a detailed label
```html
<div rn-stepper ng-model="product.quantity" ng-disabled="config.totalAvailable < 1" min="config.min" max="config.max" label="point"></div>
```

## Licence
Licensed under the permissive MIT license, contributions welcome

