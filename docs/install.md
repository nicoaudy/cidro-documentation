---
id: install
title: How to Install
sidebar_label: How to Install
---

Some components like button still depends on another package called `styled-components` to easly switch from primary to outline, maybe further release will remove the `styled-components`. Install the requirements first: 

```
$ npm install styled-components
```

If styled components was installed, just add cidro as an npm/yarn dependency:

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