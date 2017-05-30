# react-text-marquee

![Downloads](https://img.shields.io/npm/dm/react-text-marquee.svg)
![Downloads](https://img.shields.io/npm/dt/react-text-marquee.svg)
![npm version](https://img.shields.io/npm/v/react-text-marquee.svg)
![dependencies](https://img.shields.io/david/jcgertig/react-text-marquee.svg)
![dev dependencies](https://img.shields.io/david/dev/jcgertig/react-text-marquee.svg)
![License](https://img.shields.io/npm/l/react-text-marquee.svg)

A <marquee> component for react.

## Getting Started

Install it via npm or yarn:

```shell
npm install --save react-text-marquee
```

```shell
yarn add react-text-marquee
```

## Example

```html
import React, { Component } from 'react';
import Marquee from 'react-text-marquee';
import './App.css';

class App extends Component {
  render() {
    return (
      <div className="App">
        <Marquee text="Wow this is really quite a long message but it can be handled by this component just fine" />
      </div>
    );
  }
}
```

## Props

### text
The text displayed in marquee.

- Type: String
- Default: `""`

### hoverToStop
By default, only hover makes the marquee move.

- Type: Bool
- Default: `false`

### loop
Whether or not loop the marquee.

- Type: Bool
- Default: `false`

### leading
The leading waiting time for the marquee to move.

- Type: Number
- Default: `0`

### trailing
The trailing waiting time for the marquee to start over.

- Type: Number
- Default: `0`

## License

MIT
