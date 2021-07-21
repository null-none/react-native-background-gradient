# react-native-background-gradient

Provides a native React view that transitions between multiple colors in a linear direction

### Install

```js
yarn add react-native-background-gradient
// or
npm install react-native-background-gradient --save
```

### Usage

```js
import Background from "react-native-background-gradient";
import { Text } from "react-native";

export default () => (
    <Background from="rgb(255, 255, 255)" to="rgb(0,102,84)">
        <Text>Hello world</Text>
    </Background>
);
```

### License

MIT