PHP, JS and CSS Minifier
====================

## Description
With this plugin, you can minify you js's and css's via PHP providing input and output path's.


## Download
* [Master branch](https://github.com)

## Setup
* How to setup the plugin:

```php
include_once 'minifier.php';

$js = [
    'js/main.js' => 'js/main.min.js',
    // ...
];
$css = [
    'css/main.css'=> 'css/main.min.css',
    // ...
];

minifyJS($js);
minifyCSS($css);
```

## Features
* **Instantly compress all your JS's and CSS's**  
  This allows you to add js and css files to a list, that you can minify at any time.

## Requirements
* PHP Webserver

## License
Released under the [MIT license](http://www.opensource.org/licenses/MIT).
