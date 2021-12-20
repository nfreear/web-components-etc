
[![Node.js CI][ci-img]][ci]

# My Web Components #

A collection of experimental Web Components, NOT yet open sourced!

## Rationale ##

* Experimental, particularly `<my-page>`, `<my-nav>` which are probably not for production !!
* Should be usable without a build system, minimalist,
* Accessible and usable for end-users - use WAI-ARIA where appropriate!
* Simple for developers to try out,
* ES6 classes in JS files, with associated HTML + CSS in `<template>` in `.tpl.html` files,
* Self-contained where possible - SVG icons embedded in `<template>`, except `<my-map>` (Leaflet.js)
* Use shadow DOM where possible - see notes on forms (below?)
* A playground, plus some components that I will use in my blog etc.
* Demo page, per component (almost?!),
* `semistandard` linting, etc.

About [Web Components][mdn].

## Usage

```
<my-skip-link></my-skip-link>


<my-options template-host="github.io">

<script src="https://nfreear.github.io/web-components/index.js"
  type="module" async crossorigin
></script>
```

[ci]: https://github.com/nfreear/web-components/actions/workflows/node.js.yml
[ci-img]: https://github.com/nfreear/web-components/actions/workflows/node.js.yml/badge.svg
[mdn]: https://developer.mozilla.org/en-US/docs/Web/Web_Components