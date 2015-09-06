# SimpleScrollbar
Very simple javascript library for creating a custom scrollbar cross-browser and cross-devices.

Extremely lightweight, and it uses the native scroll events, so the performance is awesome!

No dependencies, developed on both vanilla Javascript (ES5) and ES6 (ES2015) - you choose what fits best for you.

## Usage
### Auto-binding
`<div ss-container></div>`

`<script>SimpleScrollbar.initAll();</script>`

### Manual binding
`<div class="myClass"></div>`

`<script>SimpleScrollbar.initEl(document.querySelector(".myClass"));</script>`

[DEMO](//buzinas.github.io/simple-scrollbar)


---

Based on [yairEO's fakeScroll] (https://github.com/yairEO/fakescroll) jQuery plugin.
