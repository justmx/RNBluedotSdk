
# react-native-bluedot-sdk

## Getting started

`$ npm install react-native-bluedot-sdk --save`

### Mostly automatic installation

`$ react-native link react-native-bluedot-sdk`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-bluedot-sdk` and add `RNBluedotSdk.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNBluedotSdk.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNBluedotSdkPackage;` to the imports at the top of the file
  - Add `new RNBluedotSdkPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-bluedot-sdk'
  	project(':react-native-bluedot-sdk').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-bluedot-sdk/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-bluedot-sdk')
  	```


## Usage
```javascript
import RNBluedotSdk from 'react-native-bluedot-sdk';

// TODO: What to do with the module?
RNBluedotSdk;
```
  