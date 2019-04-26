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

---

#### Roadmap

* Add more transition types
* Add distance/intensity variants (.slide-in-from-top-lg)

#### Steller Family

* [steller-css](https://github.com/tjhillard/steller-css)
