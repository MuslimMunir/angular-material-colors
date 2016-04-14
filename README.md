# Angular Material background anf foreground colors
### Introduction
This modules help to set theme colors on div , content background and foreground colors 

### Install

You can install this package  with `bower`.

```js
var angular = require('angular');
angular.module('yourModule', ['ngMaterial' , 'angularMaterialColors' ]);
```

### Bower

```shell
bower install angularMaterialColors --save

```
### Html 

```shell
<body ng-init="th.loadColors(theme);">
```
where theme can be 'blue-grey' or any valid angular theme it should be your theme you have used in angular md theme provider

### Example 

<div class="md-fg-50"></div>

<div class="md-bg-50"></div>

* 50    md-fg-50:    Foreground     md-bg-50:  Background

* 100    md-fg-100:    Foreground     md-bg-100:  Background

* 200    md-fg-200:    Foreground     md-bg-200:  Background    

* 300    md-fg-300:    Foreground     md-bg-300:  Background

* 400    md-fg-400:    Foreground     md-bg-400:  Background

* 500    md-fg-500:    Foreground     md-bg-500:  Background

* 600    md-fg-600:    Foreground     md-bg-600:  Background

* 700    md-fg-700:    Foreground     md-bg-700:  Background

* 800    md-fg-800:    Foreground     md-bg-800:  Background
 
* 900    md-fg-900:    Foreground     md-bg-900:  Background
 
* A100    md-fg-A100:    Foreground     md-bg-600:  Background

* A200    md-fg-A200:    Foreground     md-bg-A200:  Background

* A400    md-fg-A400:    Foreground     md-bg-A400:  Background

* A700    md-fg-A700:    Foreground     md-bg-A700:  Background



#### DEMO 
This is [on Plnkr](http://plnkr.co/edit/SHkXcAQDNPHWloBnVxrw?p=preview) so let me know if I've b0rked it somewhere.
### Contact 
muslim028@gmail.com , muslim.munir@nxb.com.pk