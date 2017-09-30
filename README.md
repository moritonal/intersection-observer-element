# \<intersection-observer-element\>

Reflects contained elements visibility in attributes

<!-- START-HIDDEN-SECTION: Add imports and styling here. -->
<script src="../webcomponentsjs/webcomponents-lite.js"></script>
<link rel="import" href="intersection-observer-element.html">
<!-- END-HIDDEN-SECTION: Add the visible part of the demo below. -->
<style>
    intersection-observer-element {
        transition: background-color 1s;

        min-height: 50px;
        max-height: 50px;

        text-align: center;

        margin: 25px;
    }

    intersection-observer-element[visible] {
        background-color: lightblue;
    }
</style>

<intersection-observer-element>
    <span>Text</span>
</intersection-observer-element>

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
