# \<intersection-observer-element\>

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

Default - [0.0, 0.25, 0.5, 0.75, 1.0]

The percentages across the element where an event is raised that the intersection has changed.

### visibleLimit

Default - 0.5

The percentage whereby the element swaps between visible or not.

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
