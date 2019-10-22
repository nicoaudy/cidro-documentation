---
id: avatar_text
title: Avatar Text
sidebar_label: Avatar Text
---

## Usage

```javascript
import { AvatarText } from "cidro";
 
const App = () => <AvatarText title="Cidro UI" />;
```

## Available Props

| Property        |  Type   | Default | Description                          |
| --------------- | :-----: | :-----: | ------------------------------------ |
| title           | string  |  null   | set title for initials               |
| size            | number  |   60    | set size                             |
| backgroundColor | string  |  black  | set background color                 |
| textColor       | string  |  white  | set text title color                 |
| circle          | boolean |  false  | set border radius / 2 if set true    |
| style           |  style  |  null   | add any style to the whole container |