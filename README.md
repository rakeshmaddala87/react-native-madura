
# react-native-react-native-madura

## Getting started

`$ npm install react-native-react-native-madura --save`

### Mostly automatic installation

`$ react-native link react-native-react-native-madura`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-react-native-madura` and add `RNReactNativeMadura.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNReactNativeMadura.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNReactNativeMaduraPackage;` to the imports at the top of the file
  - Add `new RNReactNativeMaduraPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-react-native-madura'
  	project(':react-native-react-native-madura').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-react-native-madura/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-react-native-madura')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNReactNativeMadura.sln` in `node_modules/react-native-react-native-madura/windows/RNReactNativeMadura.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using React.Native.Madura.RNReactNativeMadura;` to the usings at the top of the file
  - Add `new RNReactNativeMaduraPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNReactNativeMadura from 'react-native-react-native-madura';

// TODO: What to do with the module?
RNReactNativeMadura;
```
  