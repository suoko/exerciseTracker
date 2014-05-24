The http://www.waleedkhan.com/simple-gps-app-with-phonegap/ tutorial has been followed to create this firefox os app.


cordova create simpleGPS

cordova platform add firefoxos

cordova prepare firefoxos

And then I copied index, code and arrow files from the website to /platforms/firefoxos/www/...


I also tried to create an APK with APK FACTORY from https://www.npmjs.org/package/mozilla-apk-cli but:



simpleGPS/platforms/firefoxos/www$ mozilla-apk-cli ./ ./simpleGPS.apk

setting --overrideManifest to https://simplegpsgabriele.apk.cli.firefox.com/manifestebapp

Building with https://controller-review.apk.firefox.c
Generator response status code was 504

Since loqui.im apk gets generated just fine by mozilla-apkmozilla p
