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

## Setup

### Prerequisites

Install [npm](https://www.npmjs.com/) (or install [Node](https://nodejs.org/en/download/)):

``` bash
curl -L https://www.npmjs.com/install.sh | sh
```

Install [bower](https://bower.io/):

``` bash
npm install -g bower
```

### Tools

Install [polymer-cli](https://github.com/Polymer/polymer-cli):

``` bash
npm install -g polymer-cli
```

### Start the development server

This command serves the app at `http://localhost:8080/components/social-share-buttons/` and provides basic URL
routing for the app:

``` bash
polymer serve
```
