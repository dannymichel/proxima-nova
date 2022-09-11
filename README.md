# Fontsource Proxima Nova

[![npm (scoped)](https://img.shields.io/npm/v/@dannymichel/proxima-nova?color=brightgreen)](https://www.npmjs.com/package/@dannymichel/proxima-nova) [![Generic badge](https://img.shields.io/badge/dannymichel-passing-brightgreen)](https://github.com/dannymichel/proxima-nova) [![Monthly downloads](https://badgen.net/npm/dm/@dannymichel/proxima-nova)](https://github.com/dannymichel/proxima-nova) [![Total downloads](https://badgen.net/npm/dt/@dannymichel/proxima-nova)](https://github.com/dannymichel/proxima-nova) [![GitHub stars](https://img.shields.io/github/stars/dannymichel/proxima-nova.svg?style=social&label=Star)](https://github.com/dannymichel/proxima-nova/stargazers)

The CSS and web font files to easily self-host the “Proxima Nova” font. Please visit the main [Fontsource website](https://dannymichel.org/fonts/proxima-nova) to view more details on this package.

## Quick Installation

Fontsource has a variety of methods to import CSS, such as using a bundler like Webpack. Alternatively, it supports SASS. Full documentation can be found [here](https://dannymichel.org/docs/introduction).

```javascript
yarn add @dannymichel/proxima-nova // npm install @dannymichel/proxima-nova
```

Within your app entry file or site component, import it in.

```javascript
import "@dannymichel/proxima-nova"; // Defaults to weight 400.
```

Supported variables:

- Weights: `[400,700]`
- Styles: `[italic,normal]`
- Supported subsets: `[latin]`

Finally, you can reference the font name in a CSS stylesheet, CSS Module, or CSS-in-JS.

```css
body {
  font-family: "Proxima Nova";
}
```

## Licensing

It is important to always read the license for every font that you use.
Most of the fonts in the collection use the SIL Open Font License, v1.1. Some fonts use the Apache 2 license. The Ubuntu fonts use the Ubuntu Font License v1.0.

[Google Fonts License Attributions](https://fonts.google.com/attribution)

## Other Notes

Font version (provided by source): `v21`.

Feel free to star and contribute new ideas to this repository that aim to improve the performance of font loading, as well as expanding the existing library we already have. Any suggestions or ideas can be voiced via an [issue](https://github.com/dannymichel/proxima-nova/issues).
