# \<hot-polymer-monkey\>

Series of monkey patches for the polymer project, waiting for PRs to be evaluated/accepted/rejected — Edit

MONKEY PATCH iron-ajax, IMPLEMENTS:
 * https://github.com/PolymerElements/iron-form/issues/153
 * https://github.com/PolymerElements/iron-ajax/issues/214
 * https://github.com/PolymerElements/iron-ajax/issues/183

MONKEY PATCH paper-dropdown-menu, IMPLEMENTS:
 * https://github.com/PolymerElements/paper-dropdown-menu/pull/195
 * https://github.com/PolymerElements/paper-dropdown-menu/pull/207


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
