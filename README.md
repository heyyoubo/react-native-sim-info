
# react-native-sim-info

## Getting started

`$ npm install react-native-sim-info --save`

### Mostly automatic installation

`$ react-native link react-native-sim-info`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-sim-info` and add `RNSimInfo.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNSimInfo.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNSimInfoPackage;` to the imports at the top of the file
  - Add `new RNSimInfoPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-sim-info'
  	project(':react-native-sim-info').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-sim-info/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-sim-info')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNSimInfo.sln` in `node_modules/react-native-sim-info/windows/RNSimInfo.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Com.Reactlibrary.RNSimInfo;` to the usings at the top of the file
  - Add `new RNSimInfoPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNSimInfo from 'react-native-sim-info';

// TODO: What to do with the module?
RNSimInfo;
```
  