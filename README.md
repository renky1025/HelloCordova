# HelloCordova
Create Mobile app with Cordova

IDE: https://netbeans.org/kb/docs/webclient/cordova-gettingstarted_zh_CN.html

On Mac
Step 1. set up cordova , create project
1. npm install -g cordova
2. cordova create my-mobile-app
3. cd my-mobile-app 
4. cordova platform add ios 
5. cordova platform add android
6. cordova requirements (show requirements info)

cordova plugin add cordova-plugin-camera
cordova plugin add cordova-plugin-device
cordova plugin add cordova-plugin-network-information
cordova plugin add cordova-plugin-device-motion
cordova plugin add cordova-plugin-device-orientation
cordova plugin add cordova-plugin-geolocation
cordova plugin add cordova-plugin-file
cordova plugin add cordova-plugin-file-transfer
cordova plugin add cordova-plugin-dialogs
cordova plugin add cordova-plugin-vibration
cordova plugin add cordova-plugin-contacts
cordova plugin add cordova-plugin-globalization
cordova plugin add cordova-plugin-splashscreen
cordova plugin add cordova-plugin-inappbrowser
cordova plugin add cordova-plugin-console

Step 2. modify html and js files 
cd /my-mobile-app/www
1. edit index.html
2. edit ./js/index.js

Step 3. build app
1. cordova build ios 
2. cordova build android

Step 4. run app
1. cordova run ios 
2. cordova run android
