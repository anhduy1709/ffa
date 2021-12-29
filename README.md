# TopsMarketFlutter

A demo app showcasing how Flutter can deliver a great multi-platform experience, targeting iOS, Android, and Web. Built by [gskinner](https://gskinner.com) in partnership with Google, TopsMarketFlutter purposefully considers user expectations, input devices and idioms for each platform, ensuring it feels at home on every device.

### Installation

If you're new to Flutter the first thing you'll need is to follow the [setup instructions](https://flutter.dev/docs/get-started/install). 

Once Flutter is setup, you can use the default `stable` channel, or switch to the latest `dev` version to get the most current fixes for web:
 * Run `flutter channel stable`
 * Run `flutter upgrade`

Once you're on `stable` channel or `dev` channel, you're ready to run the app:
* `flutter run -d [android-device-name]`
* `flutter run -d [ios-device-name]`
* `flutter run -d [web-app-name]`

If you re-start your IDE, you should also see a new launch option for your current platform.

### Client Keys
This repo includes a set of Keys for Cloudinary and Firebase that are on the free pricing plans. Depending on traffic, these may reach their limit. If that happens, you will need to provide your own keys in order to run the app locally, those can be found in `AppKeys.dart`. These limits should refresh each month, so your mileage will vary here.

### License

This application is released under the [MIT license](LICENSE.md). You can use the code for any purpose, including commercial projects.

[![license](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

