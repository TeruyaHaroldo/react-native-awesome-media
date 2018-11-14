
# react-native-awesome-media

## Getting started

`$ npm install react-native-awesome-media --save`

### Mostly automatic installation

`$ react-native link react-native-awesome-media`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-awesome-media` and add `ReactNativeAwesomeMedia.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libReactNativeAwesomeMedia.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.media.module.ReactNativeAwesomeMediaPackage;` to the imports at the top of the file
  - Add `new ReactNativeAwesomeMediaPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-awesome-media'
  	project(':react-native-awesome-media').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-awesome-media/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-awesome-media')
  	```


## Usage
```javascript
import ReactNativeAwesomeMedia from 'react-native-awesome-media';

// TODO: What to do with the module?
ReactNativeAwesomeMedia;
```
# react-native-awesome-media
