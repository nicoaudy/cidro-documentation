---
id: avatar
title: Avatar
sidebar_label: Avatar
---

## Usage

```javascript
import { Avatar } from "cidro";
 
const App = () => (
  <Avatar source={{ uri: "https://facebook.github.io/react/logo-og.png" }} />
);
```

## Available Props

| Property |  Type   | Default | Description                                               |
| -------- | :-----: | :-----: | --------------------------------------------------------- |
| size     | number  |   60    | set size                                                  |
| source   |   any   |  null   | set image source, can be static from your app or external |
| circle   | boolean |  false  | set border radius / 2 if set true                         |
| style    |  style  |  null   | add any style to the whole container                      |