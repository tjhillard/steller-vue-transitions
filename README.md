# Steller Vue Transitions
Steller Vue Transitions is a StellerCSS module for integrating named [Vue.js transitions](https://vuejs.org/v2/guide/transitions.html#CSS-Transitions) into your Steller design system.

## Installation

```
npm i steller-vue-transitions
```

```
yarn add steller-vue-transitions
```

## Usage

```scss
// Assuming you are using webpack

@import 'steller-theme'; // Your config file
@import '~steller-vue-transitions/index';

$steller-modules: (
  $steller-vue-transitions,
);

@import '~steller-css/index'; // StellerCSS
```

## Config

```scss
$steller-vue-transitions-slide-distance-xs: 1px;
$steller-vue-transitions-slide-distance-sm: 2px;
$steller-vue-transitions-slide-distance-md: 4px;
$steller-vue-transitions-slide-distance-lg: 6px;
$steller-vue-transitions-slide-distance-xl: 10px;
```

## Speeds

This module uses the speed variables defined in StellerCSS.

```scss
$steller-speed-extra-slow: 500ms;
$steller-speed-slow: 400ms;
$steller-speed-normal: 300ms;
$steller-speed-fast: 200ms;
$steller-speed-extra-fast: 100ms;
```

## Utility Classes

### Slide In

```html
<transition name="slide-in-from-{$direction}-{$distance}-{$speed}">
  //
</transition>
```

* Directions: ('top', 'right', 'bottom', 'left')
* Distances: ('xs', 'sm', 'md', 'lg', 'xl')
* Speeds: ('extra-slow', 'slow', 'normal', 'fast', 'extra-fast')

### Fade

```html
<transition name="fade-{$speed}">
  //
</transition>
```

* Speeds: ('extra-slow', 'slow', 'normal', 'fast', 'extra-fast')

### Flip

```html
<transition name="flip-list-{$speed}">
  //
</transition>
```

* Speeds: ('extra-slow', 'slow', 'normal', 'fast', 'extra-fast')

---

#### Roadmap

* Add more transition types
* Tests

#### Steller Family

* [steller-css](https://github.com/tjhillard/steller-css)
