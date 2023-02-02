# rn-contacts

Uses native contact picker apis to select and update contacts from react native based applications. 

// Disclaimer : This package is underdevelopment how ever following features are currently accessible


## Installation

```sh
npm install rn-contacts
```

## Add Permissions
Make sure to add following permissions in [AndroidManifest.xml]
```sh
<uses-permission android:name="android.permission.READ_CONTACTS"/>
<uses-permission android:name="android.permission.WRITE_CONTACTS" />
<uses-permission android:name="android.permission.READ_PROFILE" />
```

## Usage
This library is supported in both Android & IOS.

```js
import { requestPermission, openContacts } from 'rn-contacts';

// ...

const permission = await requestPermission(); // Expected return : 'authorized' | 'denied' | 'undefined'
```

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT

---

Made with [create-react-native-library](https://github.com/callstack/react-native-builder-bob)
