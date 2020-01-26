# Ionic Audio Player (updated w/ Ionic v4 & Angular v8 in 2019)

This is a simple audio player created with **Ionic 4+** / **Angular 8+** (updated in 2019)

It features a **play/pause** button, **skip back/forward** buttons and a **progress bar** that displays the current position of the audio file. It also supports setting arbitrary positions using the **progress bar**.

The app will automatically download the speech ***I Have a Dream*** from the Internet and prep for playing. You'll have to have an actual Android or iOS device to use this app.

To peek into the code, feel free to clone the repo and navigate your way through. I think it's pretty straightforward.

To try it out, use the following commands to install the app on an actual device:

- For Android devices: make sure you have a wired connection from your phone to your Mac/PC, then run `ionic cordova run android --prod` in terminal.
- For iOS devices: make sure you have a Mac, and run `ionic cordova prepare ios`. Then use Xcode to open up the project and install it to your iOS devices.

## Ionic Native Plugins

- [File](https://ionicframework.com/docs/native/file/)
- [File Transfer](https://ionicframework.com/docs/native/file-transfer/)
- [Media](https://ionicframework.com/docs/native/media/)

## Support Platforms

- Android
- iOS

## UI Preview

### Android

<img width="250" alt="android" src="preview/interface/android.jpg">

### iOS

<img width="250" alt="android" src="preview/interface/ios.png">

### GIF

<img width="250" alt="demo" src="preview/demo/demo.gif">

## References

Thanks to the following posts and sources, I was able to come up with this solution:

- [Help: Using Cordova Media to create progress bar with ion-range](https://forum.ionicframework.com/t/using-cordova-media-to-create-progress-bar-with-ion-range/92368)
- [Ionic Component: Range](http://ionicframework.com/docs/api/components/range/Range/)
- [MediaManager isn't getting the correct duration #42](https://github.com/arielfaur/ionic-audio/issues/42)
- [Cordova Media Capture - Find duration of audio file](https://stackoverflow.com/questions/38266702/cordova-media-capture-find-duration-of-audio-file)

## Author

Created by suriya

Last updated: jan 26 2020
