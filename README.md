
# react-native-image-selector

## Getting started

`$ npm install react-native-image-selector --save`

### Mostly automatic installation

`$ react-native link react-native-image-selector`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-image-selector` and add `RNImageSelector.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNImageSelector.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNImageSelectorPackage;` to the imports at the top of the file
  - Add `new RNImageSelectorPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-image-selector'
  	project(':react-native-image-selector').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-image-selector/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-image-selector')
  	```

## Usage
```javascript
import RNImageSelector from 'react-native-image-selector';

// TODO: What to do with the module?
RNImageSelector;
```
  
