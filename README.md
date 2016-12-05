# plug.ionic-segment
![GitHub version](https://img.shields.io/github/release/frontexpert/plug.ionic-segment.svg?style=flat-square)
![Ionic version](https://img.shields.io/badge/ionic-%5E1.3.2-yellow.svg?style=flat-square)
![License](https://img.shields.io/github/license/frontexpert/plug.ionic-segment.svg?style=flat-square)

Ionic iOS segment plugin.
Feel free to contribute to this project.

#Screenshots

<img src="/../screenshots/segment.png?raw=true" alt="Segment" width="239">

## Usage

Install manually, or from bower:

```
$ bower install plug.ionic-segment --save
```

Include `plug.ionic-segment.js` and `segment.css` in your index.html:

```html

<link href="lib/plug.ionic-segment/dist/segment.css" media="all" rel="stylesheet" type="text/css">
...
<script src="lib/plug.ionic-segment/dist/plug.ionic-segment.js"></script>

```

Add the module plug.ionic-segment to your application dependencies:

```javascript

angular.module('starter', ['ionic', 'plug.ionic-segment']);

```

And you're ready to go.

## Examples

```html
<ion-segment ng-model="period" full="true" positive>
  <ion-segment-button value="today">
    Today
  </ion-segment-button>
  <ion-segment-button value="month">
    Month
  </ion-segment-button>
  <ion-segment-button value="year">
    Year
  </ion-segment-button>
</ion-segment>
```

## LICENSE
plug.ionic-segment is licensed under the MIT Open Source license. For more information, see the LICENSE file in this repository.