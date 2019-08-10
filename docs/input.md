---
id: input
title: Input
sidebar_label: Input
---

## Usage

```javascript
import { TextInput } from "cidro";

const App = () => (
  <TextInput
    label="Email"
    value="cidro@ui.good"
    keyboardType="email-address"
    onChangeText={() => alert("Text On Change")}
  />
);
```

## Available Props

| Property |  Type  | Default | Description                                          |
| -------- | :----: | :-----: | ---------------------------------------------------- |
| label    | string |  null   | set your label                                       |
| message  | string |  null   | set your message (eg: "Whops your email is invalid") |
| type     | string |  null   | Available type "success", "error"                    |
