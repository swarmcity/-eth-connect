# \<eth-connect\>

A web component that exposes ethjs and connects to the provided http provider

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) and npm (packaged with [Node.js](https://nodejs.org)) installed. Run `npm install` to install your element's dependencies, then run `polymer serve` to serve your element locally.

## Install eth-connect

```
$ npm install eth-connect
```

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```
## Import

```
$ import 'eth-connect';
```

## Basic Use

```html
<eth-connect  
    eth="{{eth}}"
    http-provider="https://ropsten.infura.io">
</eth-connect>
```