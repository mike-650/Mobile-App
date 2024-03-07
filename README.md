**Learning React Native**
- Unlike React where we render HTML elements, with React Native we render native mobile components

**Text and View Components:**
```
import { View, Text } from 'react-native'

const App = () => {
  return (
    <View>
      <Text>This is text!</Text>
    </View>
  )
}
```

* The ```<Text>``` component is similar the the ```<p>,<h1>``` tags in React.
* The ```<View>``` component is used to create a container or "view" for the other components
  - You can think of it as a box or container that holds other components
  - Similar to the ```<div>``` element in HTML but with added functionality specific to mobile apps
