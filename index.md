# Inicia con tu app usando React Native Reusables!

### 1. **Configura tu entorno**
Primero, asegúrate de tener Node.js y npm instalados. Luego, instala el CLI de React Native:
```bash
npm install -g react-native-cli
```

### 2. **Crea un nuevo proyecto de React Native**
Crea un nuevo proyecto usando el CLI de React Native:
```bash
npx react-native init miNuevaApp
cd miNuevaApp
```

### 3. **Instala React Native Reusables**
Agrega React Native Reusables a tu proyecto:
```bash
npm install @react-native-reusables/core
```

### 4. **Usa componentes reutilizables**
Ahora, puedes comenzar a usar los componentes reutilizables en tu aplicación. Por ejemplo, para usar un componente de alerta:
```jsx
import React from 'react';
import { View } from 'react-native';
import { Alert } from '@react-native-reusables/core;

const App = () => {
  return (
    <View>
      <Alert message="¡Esta es una alerta!" type="success" />
    </View>
  );
};

export default App;
```

### 5. **Personaliza los componentes**
Puedes personalizar los componentes para que se ajusten a tus necesidades de diseño. Cada componente viene con varias propiedades para personalización. Consulta la documentación para más detalles sobre las propiedades disponibles y opciones de personalización.

### 6. **Ejecuta tu aplicación**
Finalmente, ejecuta tu aplicación para ver los componentes en acción:
```bash
npx react-native run-android
# o
npx react-native run-ios
```

### Apoya mi trabajo, gracias!
<a href="https://www.buymeacoffee.com/rvelasquez" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
