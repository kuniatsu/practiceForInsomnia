$ npm -v
6.13.7



$ npm install -g cordova
npm WARN deprecated request@2.88.2: request has been deprecated, see https://github.com/request/request/issues/3142
/Users/kuniatsu/.npm-global/bin/cordova -> /Users/kuniatsu/.npm-global/lib/node_modules/cordova/bin/cordova
+ cordova@9.0.0
removed 2 packages and updated 22 packages in 19.735s


$ cordova plugin add https://github.com/EddyVerbruggen/Insomnia-PhoneGap-Plugin.git


$ cordova platforms ls

$ cordova platforms ls
Installed platforms:
  
Available platforms: 
  android ^8.0.0
  browser ^6.0.0
  electron ^1.0.0
  ios ^5.0.0
  osx ^5.0.0
  windows ^7.0.0


$ cordova platform add android
$ cordova platform add ios
$ cordova platforms ls


mbp:test_insomnia kuniatsu$ cordova platform add android
Using cordova-fetch for cordova-android@^8.0.0
Adding android project...
Creating Cordova project for the Android platform:
        Path: platforms/android
        Package: io.cordova.hellocordova
        Name: HelloCordova
        Activity: MainActivity
        Android target: android-28
Subproject Path: CordovaLib
Subproject Path: app
Android project created with cordova-android@8.1.0
Installing "cordova-plugin-insomnia" for android
Plugin 'cordova-plugin-whitelist' found in config.xml... Migrating it to package.json
Discovered saved plugin "cordova-plugin-whitelist". Adding it to the project
Installing "cordova-plugin-whitelist" for android
Adding cordova-plugin-whitelist to package.json
mbp:test_insomnia kuniatsu$ cordova platform add ios
Using cordova-fetch for cordova-ios@^5.0.0
Adding ios project...
Creating Cordova project for the iOS platform:
        Path: platforms/ios
        Package: io.cordova.hellocordova
        Name: HelloCordova
iOS project created with cordova-ios@5.1.1





$ cordova prepare


$ cordova build

$ npm i ios-sim

$ cordova emulate ios



No target specified for emulator. Deploying to "iPhone-SE--2nd-generation-, 13.4" simulator.
Running command: /Users/kuniatsu/src/cordova/practiceForInsomnia/test_insomnia/node_modules/ios-sim/bin/ios-sim launch /Users/kuniatsu/src/cordova/practiceForInsomnia/test_insomnia/platforms/ios/build/emulator/HelloCordova.app --devicetypeid com.apple.CoreSimulator.SimDeviceType.iPhone-SE--2nd-generation-, 13.4 --log /Users/kuniatsu/src/cordova/practiceForInsomnia/test_insomnia/platforms/ios/cordova/console.log --exit
Error: Unhandled error. ('[ios-sim] /Users/kuniatsu/src/cordova/practiceForInsomnia/test_insomnia/node_modules/ios-sim/src/commands/launch.js:51\n' +
  '          this.log(`logPath: ${path.resolve(flags.log)}`)\n' +
  '               ^\n' +
  '\n' +
  "TypeError: Cannot read property 'log' of undefined\n" +
  '    at /Users/kuniatsu/src/cordova/practiceForInsomnia/test_insomnia/node_modules/ios-sim/src/commands/launch.js:51:16\n' +
  '    at withInjectedEnvironmentVariablesToProcess (/Users/kuniatsu/src/cordova/practiceForInsomnia/test_insomnia/node_modules/ios-sim/src/helpers.js:172:3)\n' +
  '    at /Users/kuniatsu/src/cordova/practiceForInsomnia/test_insomnia/node_modules/ios-sim/src/commands/launch.js:40:7\n' +
  '    at tryParseBuffer (/Users/kuniatsu/src/cordova/practiceForInsomnia/test_insomnia/node_modules/ios-sim/node_modules/bplist-parser/bplistParser.js:34:23)\n' +
  '    at /Users/kuniatsu/src/cordova/practiceForInsomnia/test_insomnia/node_modules/ios-sim/node_modules/bplist-parser/bplistParser.js:46:7\n' +
  '    at FSReqCallback.readFileAfterClose [as oncomplete] (internal/fs/read_file_context.js:63:3)\n')






