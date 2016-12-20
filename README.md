# \<social-share-buttons\>


## Installation

``` bash

bower install social-share-buttons --save

```

## Usage

```html

<link rel="import" href="bower_components/social-share-buttons/social-share-buttons.html">

<social-share-buttons media="https://my-domain.com/images/my-image.jpg" url="https://my-domain.com/product/detail/my-sku" title="Product Name">
   <span class="icon-social-facebook" data-id="facebook"></span>
   <span class="icon-social-twitter" data-id="twitter"></span>
   <span class="icon-social-pinterest" data-id="pinterest"></span>
</social-share-buttons>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
