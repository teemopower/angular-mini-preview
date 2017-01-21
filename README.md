![](https://img.shields.io/badge/bower-1.0.0-green.svg) ![](https://img.shields.io/github/license/mashape/apistatus.svg) ![](https://img.shields.io/badge/npm-1.0.0-red.svg)

# angular-mini-preview
Display image, link, content, etc. preview on hover for angular

# Demo
![Angular Mini Preview Demo](https://codedrinker.github.io/repository/asserts/angular-mini-preview.gif)

## Usage

Install with Bower(Or NPM):

```bash
bower install angular-mini-preview

OR

npm install angular-mini-preview
```

Then reference the minified script:

```html
<script src="bower_components/angular-mini-preview/dist/js/angular-mini-preview.min.js"></script>
<link rel="stylesheet" href="bower_components/angular-mini-preview/dist/css/angular-mini-preview.min.css">

OR

<script src="node_modules/angular-mini-preview/dist/js/angular-mini-preview.min.js"></script>
<link rel="stylesheet" href="node_modules/angular-mini-preview/dist/css/angular-mini-preview.min.css">

```

Specify the angular mini preview as a dependency of your application:

```js
var app = angular.module('app', ['angular-mini-preview']);
```

Now just use mini-preview in any html:
```
<a href="https://codedrinker.github.com" mini-preview>
```

# Road Map
1.0.0 Preview Link

# MIT License

Copyright (c) 2017 Chunlei Wang

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
