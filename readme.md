# APK Package Detector v0.1.3-beta

[![Chileno](https://img.shields.io/badge/From-Chile-blue.svg)](https://es.wikipedia.org/wiki/Chile)
[![Licencia](https://img.shields.io/badge/license-GPL%20(%3E%3D%202)-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.html)
[![Contribuciones](https://img.shields.io/badge/contributions-welcome-blue.svg)](https://github.com/WHK102/apk-package-detector/issues)
[![Donaciones](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://paypal.me/whk102)

APK Package Detector is a tool for **pentesters**, get the most common
compilation and security properties of APK types of files.

*It does not require installing Java, SDK or external applications.*


## Requirements

- Python 3


## Use

Example of execution:

```bash
$ python3 apd.py
~ APK Package Detector v0.1.3-beta - whk@elhacker.net ~
Get extended info from APK file.
Use      : apd.py [options] [APK target file]
Options  :
  -h, --help         Print the help message.
  -o, --out-format   Out format: human, json
Examples :
  apd.py test.apk
  apd.py -o json test.apk

$ python3 apd.py test.apk 
~ APK Package Detector v0.1.3-beta - whk@elhacker.net ~
+ Metadata
  - App name       : Example
  - Package        : com.example
  - Author         : WHK
  - Packer         : 1.8.0_181 (Oracle Corporation)
  - Compile SDK    : None
  - Platform Build : 8.0.0
+ Frameworks used
  - Apache Cordova - https://cordova.apache.org/
+ Protection systems :
  - Appcelerator Assets Obfuscation   : Yes
  - OkHttp3 Certificate Pinning       : No
  - Root and Virtual Machine detector : No
```


## Binaries supported

- Android APK


## Frameworks supported to detection

- Apache Cordova
- Ionic
- Appcelerator Titanium
- React Native
- CoronaSDK
- Onsen UI
- Cocos2d-x Game Engine
- Godot Game Engine
- Unity3d Game Engine
- Unreal Game Engine