[![Bundle size](https://img.shields.io/bundlephobia/minzip/react-radial-progress-indicator.svg)](https://bundlephobia.com/result?p=react-radial-progress-indicator)
[![GitHub issues](https://img.shields.io/github/issues/twisty/react-radial-progress-indicator.svg)](https://github.com/twisty/react-radial-progress-indicator/issues)
[![GitHub license](https://img.shields.io/github/license/twisty/react-radial-progress-indicator.svg)](https://github.com/twisty/react-radial-progress-indicator/blob/master/LICENSE)

# react-radial-progress-indicator

A React component that displays a customisable circular progress gauge.

This component displays a circular progress gauge, useful for displaying progress on a completeable action, like:

* “you’re on step 3/10”, or 
* “you're 30% there”

<img alt="3/10" src="docs/example.png" width="100" height="100" />

## Features

* **Lightweight:** [~2kb when minified and gzipped](https://bundlephobia.com/result?p=react-radial-progress-indicator)
* **Responsive:** draws natively at the pixel density of your screen using HTML5 canvas.
* **Tweakable:** colours, layout metrics, and text can be fine-tuned for your layout.
* **Animatable:** animates between steps with customisable speed.

## Demo

* Have a look at [this storybook](https://twisty.github.io/react-radial-progress-indicator/).

## Install

Install with yarn…

```
yarn add react-radial-progress-indicator
```

…or npm:

```
npm install react-radial-progress-indicator
```

## Usage

```jsx
import React, { Component } from 'react'
import { RadialProgress } from 'react-radial-progress-indicator';

class MyComponent extends Component {
  render() {
    return (
      <RadialProgress
        width={100}
        height={100}
        steps={10}
        step={3}
      />
    )
  }
}
```

See the `jsx` tab in [the storybook](https://twisty.github.io/react-radial-progress-indicator/) for more usage examples.

## API

A full list of `props` available to customise the component can be found here: [docs/api.md](docs/api.md)
