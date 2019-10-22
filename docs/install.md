---
id: install
title: How to Install
sidebar_label: How to Install
---

Just add cidro as an npm / yarn dependency:

```
$ npm install cidro 
```

And just import the component you want in your application:

```javascript
import { Block, Text } from 'cidro'
```

This seems really easy right? Just use your component like you would normally do with any other component.

```javascript
render() {
  return (
    <Block safe>
      <Text h1>Say it loud, CIDRO 🌶️</Text>
    </Block>
  );
}
```