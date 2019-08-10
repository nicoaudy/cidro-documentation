---
id: block
title: Block
sidebar_label: Block
---

Most used components for wrap everthing.

## Usage

```javascript
import { Block, Text } from "cidro";

const App = () => (
  <Block safe>
    <Text h1>CIDRO 🔥</Text>
  </Block>
);
```

## Available Props

| Property |     Type     | Default  | Description                                      |
| -------- | :----------: | :------: | ------------------------------------------------ |
| row      |     bool     |  false   | flexDirection: 'row'                             |
| column   |     bool     |  false   | flexDirection: 'column'                          |
| flex     | bool, number | false, 1 | flex: 1 or <yourNumber>                          |
| safe     |     bool     |  false   | Wrap the block with SafeAreaView                 |
| center   |     bool     |  false   | alignItems: 'center' alignSelf: 'center'         |
| middle   |     bool     |  false   | alignItems: 'center' alignSelf: 'center'         |
| top      |     bool     |  false   | alignItems: 'flex-start' alignSelf: 'flex-start' |
| bottom   |     bool     |  false   | alignItems: 'flex-end' alignSelf: 'flex-end'     |
| left     |     bool     |  false   | alignItems: 'flex-start'                         |
| right    |     bool     |  false   | alignItems: 'flex-start'                         |
| card     |     bool     |  false   | changes the border-radius, -width and -color     |
| fluid    |     bool     |  false   | width: 'auto'                                    |
| height   |    number    |   null   | changes the height of the Block                  |
| space    |    string    |   null   | options are: 'between', 'around' or 'evently'    |
| width    |    number    |   null   | changes the width of the Block                   |
