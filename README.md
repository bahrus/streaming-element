# \<streaming-element\>

Jake Archibald&#39;s Hack for Fast Streaming of HTML content

In light of the phasing out of HTML Imports, it seems appropriate to re-examine best approaches for loading HTML content using native web browser capabilities as much as possible.  Jake Archibald proposed a [promising "hack"](https://jakearchibald.com/2016/fun-hacks-faster-content/) that seems to have good performance metrics.  Credit for original idea may go to GitHub.  This component is simply a port of the code from Jake Archibald's [demo page] into webcomponents.org.

The web component has no dependencies.  The Polymer stubs are there simply to make integration into WebComponents.org smoother.   

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
