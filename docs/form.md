---
id: form
title: Form
sidebar_label: Form
---

## Usage

```javascript
import { Form } from "cidro";

const App = () => (
  <Form title="Helo 🔥" subtitle="Cidro is awesome because built with ❤️">
    <View style={{ flex: 1, backgroundColor: "papayawhip" }} />
  </Form>
);
```

## Available Props

| Property |     Type     |   Default   | Description            |
| -------- | :----------: | :---------: | ---------------------- |
| children |  component   |    null     | set your own component |
| title    | bool, string | false, null | set your title         |
| subtitle | bool, string | false, null | set your subtitle      |
