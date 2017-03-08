# This is a fork ment for the sole purpose of installing this package via NPM

CKEditor + AngularJS
====================
[![Build Status](https://travis-ci.org/esvit/ng-ckeditor.png)](https://travis-ci.org/esvit/ng-ckeditor) [![Coverage Status](https://coveralls.io/repos/esvit/ng-ckeditor/badge.png)](https://coveralls.io/r/esvit/ng-ckeditor)


Code licensed under New BSD License.
## Installing with npm
Add the following to your `package.json`
```
"ng-ckeditor": "git://github.com/aviadhahami/ng-ckeditor.git"
```
run `npm i` and somewhere in your code:
```js
import 'ng-ckeditor';
import 'ng-ckeditor/ng-ckeditor.css';
```
and in your app depenedencies add
```js
angular.module('appLib', [
    ...
	'ngCkeditor',
])
```


## Installing via Bower
```
bower install ng-ckeditor
```

##Usage
```html
<textarea ckeditor="editorOptions" ng-model="modelName"></textarea>
```

```js
// add dependency
angular.module('app', ['ngCkeditor'])

// setup editor options
$scope.editorOptions = {
    language: 'ru',
    uiColor: '#000000'
};
```
