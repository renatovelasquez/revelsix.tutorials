## Start with your app using React Native Reusables!

### 1. **Set Up Your Environment**
First, make sure you have Node.js and npm installed. Then, install the React Native CLI:
```bash
npm install -g react-native-cli
```

### 2. **Create a New React Native Project**
Create a new project using the React Native CLI:
```bash
npx react-native init MyNewApp
cd MyNewApp
```

### 3. **Install React Native Reusables**
Add React Native Reusables to your project:
```bash
npm install @react-native-reusables/core
```

### 4. **Use Reusable Components**
Now, you can start using the reusable components in your app. For example, to use an Alert component:
```jsx
import React from 'react';
import { View } from 'react-native';
import { Alert } from '@react-native-reusables/core';

const App = () => {
  return (
    <View>
      <Alert message="This is an alert!" type="success" />
    </View>
  );
};

export default App;
```

### 5. **Customize Components**
You can customize the components to fit your design needs. Each component comes with various props for customization. Check the documentation for more details on available props and customization options.

### 6. **Run Your App**
Finally, run your app to see the components in action:
```bash
npx react-native run-android
# or
npx react-native run-ios
```
### Support my work, thanks!
<a href="https://www.buymeacoffee.com/rvelasquez" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
