---
id: button
title: Button
sidebar_label: Button
---

## Usage

```javascript
import { Button } from "cidro";

const App = () => <Button title="Login" onPress={action("Button pressed")} />;
```

## Available Props

| Property |  Type  | Default | Description                                              |
| -------- | :----: | :-----: | -------------------------------------------------------- |
| title    | string |  null   | Title is required                                        |
| disabled |  bool  |  false  | Change the disabled button                               |
| loading  |  bool  |  false  | Show loading indicator                                   |
| size     | number |   10    | Change the size button                                   |
| width    | string |  null   | Change the width                                         |
| outline  |  bool  |  false  | Change button style                                      |
| type     | string | primary | Available type "primary", "success", "danger", "warning" |
