# react-native-clear-cache

This app is a clone of [react-native-clear-app-cache](https://github.com/midas-gufei/react-native-clear-app-cache/) but transformed to work with RN 0.60+
####修改了已知安卓bug

## Getting started

Go:

`npm i oa-react-native-clear-cache --save`

### Mostly automatic installation

No need to link as of RN 0.60.

## Usage
```javascript
import ClearCache from 'oa-react-native-clear-cache';

// get the storage usage
ClearCache.getAppCacheSize(data => {
  alert(data) // will show the App's storage usage in the app's cache.
});


// clear the storage
ClearCache.clearAppCache(data => {
  alert(data) // will alert the new size
});
```
