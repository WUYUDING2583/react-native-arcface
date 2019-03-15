
# react-native-arcface

## Getting started

`$ npm install react-native-arcface --save`

### Mostly automatic installation

`$ react-native link react-native-arcface`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.arc.arcface.RNArcfacePackage;` to the imports at the top of the file
  - Add `new RNArcfacePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-arcface'
  	project(':react-native-arcface').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-arcface/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-arcface')
  	```


## Usage
```javascript
import RNArcface from 'react-native-arcface';

// TODO: What to do with the module?
RNArcface;
```
  