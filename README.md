# cordova-sunmi-inner-printer

#V1.0.0
Changed from canvas.save(Canvas.ALL_SAVE_FLAG) to canvas.save()
Added android:exported="false" in plugin.xml ( Androidmanifest section)

Steps to follow

1. cordova platform rm android
2. cordova plugin add https://github.com/kakans/cordova-sunmi-inner-printer.git
3. cordova platform add android   ( Testing for android 10)


sunmiInnerPrinter.printOriginalText("Hello World!")

you can see the list of available command in 

www\innerprinter.js file.

