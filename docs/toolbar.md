---
id: toolbar
title: Toolbar
sidebar_label: Toolbar
---

Component that renders as Header (navbar) for your screen.

## Usage

```javascript
import { Toolbar, Text } from "cidro";

const App = () => (
    <Toolbar
      left={<Text>Back</Text>}
      leftHandler={() => alert("left handler")}
      center={<Text>CIDRO UI 🔥</Text>}
      right={<Text>Logout</Text>}
      rightHandler={() => alert("right handler")}
);
```

## Available Props

| Property     |   Type    | Default  | Description                                                                   |
| ------------ | :-------: | :------: | ----------------------------------------------------------------------------- |
| left         | component |   null   | set your own component (eg: Text or Icon)                                     |
| leftHandler  | function  | () => {} | Take an arrow function and everytime the user presses the function is called. |
| center       |  [color]  |   null   | set your own component                                                        |
| right        |   color   |   null   | change the shadow color                                                       |
| rightHandler |   style   |  () =>   | Take an arrow function and everytime the user presses the function is called. |
| style        |   style   |   null   | add any style to the whole container                                          |
