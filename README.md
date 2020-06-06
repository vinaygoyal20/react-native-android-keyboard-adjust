# react-native-android-keyboard-adjust

Change the input mode for the Android keyboard in a React Native app.

If you are having issues with the default keyboard screen adjust modes and need an easy way to instantly switch them in your app. Quickly go from `Pan` to `Resize` to `Nothing` to get the screen displayed perfectly with the keyboard.

#### Adjust Nothing Example
![adjust nothing keyboard down](http://i.imgur.com/A9bfdQY.png)
![adjust nothing keyboard up](http://i.imgur.com/sCt0EWn.png)

#### Adjust Resize Example
![adjust resize keyboard down](http://i.imgur.com/xgXi0iR.png)
![adjust resize keyboard up](http://i.imgur.com/7QdVbmZ.png)

## Installation instructions for Android

### Install the package

`npm install --save react-native-android-keyboard-adjust`
`That's it, you are good to go.`



## Example
```
import AndroidKeyboardAdjust from 'react-native-android-keyboard-adjust';

AndroidKeyboardAdjust.setAdjustNothing();
AndroidKeyboardAdjust.setAdjustPan();
AndroidKeyboardAdjust.setAdjustResize();
AndroidKeyboardAdjust.setAdjustUnspecified();
AndroidKeyboardAdjust.setAlwaysVisible();
AndroidKeyboardAdjust.setAlwaysHidden();
AndroidKeyboardAdjust.setVisible();
AndroidKeyboardAdjust.setHidden();
AndroidKeyboardAdjust.setUnchanged();
```
