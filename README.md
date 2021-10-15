# Android Keylogger

# Deploy Cloud VPS Work Fine

# Support Android 11

Project for CS460 Spring 2017 by Brian Shu (bshu2). This is a proof of concept and not intended for actual use. 

This app is a keylogger for rooted Android devices that logs view click, view focus, and text change events and sends the data to a remote server. It makes use of an Android accessibility service to read and extract info across apps. Root access is used to automatically enable the service without the user's knowledge, but the keylogger will still work on unrooted devices if the user manually enables the accessibility service in the settings. 

To install and run: Download the source and open the AndroidKeylogger folder as a project in Android Studio. Then run the app on an emulator or a connected device.  

[Video demo](https://youtu.be/LI7RyYb7qIA)
