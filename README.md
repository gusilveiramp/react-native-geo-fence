
# react-native-react-native-geo-fence

## Getting started

`$ npm install react-native-react-native-geo-fence --save`

### Mostly automatic installation

`$ react-native link react-native-react-native-geo-fence`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-react-native-geo-fence` and add `RNReactNativeGeoFence.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNReactNativeGeoFence.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNReactNativeGeoFencePackage;` to the imports at the top of the file
  - Add `new RNReactNativeGeoFencePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-react-native-geo-fence'
  	project(':react-native-react-native-geo-fence').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-react-native-geo-fence/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-react-native-geo-fence')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNReactNativeGeoFence.sln` in `node_modules/react-native-react-native-geo-fence/windows/RNReactNativeGeoFence.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Com.Reactlibrary.RNReactNativeGeoFence;` to the usings at the top of the file
  - Add `new RNReactNativeGeoFencePackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNReactNativeGeoFence from 'react-native-react-native-geo-fence';

// TODO: What to do with the module?
RNReactNativeGeoFence;
```
  