# vaadin-mobile-drag-drop

Ships an initialization script for a drag and drop [polyfill](https://github.com/timruffles/mobile-drag-drop) for mobile devices that don't support HTML5 D&D natively. Includes special configuration for the polyfill to support Web Components (with shadow root).

## Installation

### Bower

```sh
bower i vaadin/vaadin-mobile-drag-drop --save
```

Once installed, import the polyfill and the initializer in your application:

```html
<script src="bower_components/vaadin-mobile-drag-drop/mobile-drag-drop/release/index.min.js"></script>
<script src="bower_components/vaadin-mobile-drag-drop/vaadin-mobile-drag-drop.js"></script>
```
### Npm

```sh
npm install @vaadin/vaadin-mobile-drag-drop
```

Once installed, import the polyfill and the initializer in your application:

```html
<script src="node_modules/vaadin-mobile-drag-drop/mobile-drag-drop/index.min.js"></script>
<script src="node_modules/vaadin-mobile-drag-drop/vaadin-mobile-drag-drop.js"></script>
