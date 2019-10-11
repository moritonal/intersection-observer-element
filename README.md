# \<intersection-observer-element\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/moritonal/intersection-observer-element)

Set's `visible` to true when the viewport crosses the set threshold of the element.

```
<intersection-observer-element visible="{{visible}}">
    <div>  
        ...
    </div>
</intersection-observer-element>
```
## Install

```
bower install --save intersection-observer-element
```

## Options

### thresholds

Default: [0.0, 0.25, 0.5, 0.75, 1.0]

The percentages across the element where an event is raised that the intersection has changed.

### visibleLimit

Default: 0.5

The percentage whereby the element swaps between visible or not.

### rootMargin

Default: 0px

Directly passed into IntersectionObserver class as rootMargin

## Polyfills

This element uses the Intersection Observer Api, which whilst most modern browsers currently support, it is missing from iOS Safari. More detailed information can be found at [CanIUse](https://caniuse.com/#search=intersection).

If you wish to support multiple browsers it's recommended you also use one of the Polyfills from [here](https://github.com/w3c/IntersectionObserver/tree/gh-pages/polyfill).
 
## Developing

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

### Viewing Your Element

```
$ polymer serve
```

### Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
