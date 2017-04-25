**Cordova / PhoneGap Plugin to allow localized buttons on keyboards and other native components**

## Install

#### Latest published version on npm (with Cordova CLI >= 5.0.0)

```
cordova plugin add cordova-plugin-allow-mixed-localization
```

#### Latest version from GitHub

```
cordova plugin add https://github.com/enyosolutions/cordova-plugin-allow-mixed-localization.git
```

## Usage
```
For the changes to `plugin.xml` to take effect, you must refresh the `ios.json` file (inside the `/plugin` folder):
```
$ cordova platform rm ios
$ cordova platform add ios
```


## Platforms

Applies to iOS (9+) only.

## License

[MIT License](http://ilee.mit-license.org)
