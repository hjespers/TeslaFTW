TeslaFTW
========

Pebble App to control your Tesla Model S/X or hopefully soon the model E (economy).

Some screenshots:

![Screenshots](https://raw.github.com/ErikDeBruijn/TeslaFTW/master/Pebble-Screenshots.png)

It uses the Tesla API. To control your Tesla. It will allow you to do things like the following:

 - Turn on/off A/C (or car pre-heating in winter)
 - See indoor and outdoor temperature
 - Start/stop charging
 - See battery status, possible range and charge rate + cost information
 - Lock your car
 - Honk the horn
 - Flash the lights

The functions are ordered so that the menu's at the top are the things I use most. It will automatically start retrieving charge info once opened.

Installation
============

The easiest way is to use the new Pebble Store, from the Pebble App. It needs to be the latest version. When using Android, the store might still be in beta.
 - Android: Ensure you have the latest Pebble App for Android or at least 2.0 Beta 8. You can [download it from here](https://www.dropbox.com/s/fktcb3nuadqbzpp/PebbleApp-2.0-BETA8.apk).
 - Ensure that you're running firmware v2 on your pebble.
 - iOS: Use the Pebble App store to find Tesla FTW.
 - If the above doesn't work, use the PBW: Download the PBW file to your paired phone [here](https://github.com/ErikDeBruijn/TeslaFTW/blob/master/build/TeslaFTW.pbw?raw=true).
 - Install onto your device with the Pebble App on your phone.


Status / Warranty
=================

Using this application is entirely at your own risk. No guarantee is given I use the app all the time, but that doesn't mean it will work for you.

Compatibility
=============

Note: This watchapp is for Pebble firmware 2.0.

The app doesn't require a companion app on your Android/iOS device.

Development
===========

If you want to help out with development, that's great! The app needs some work in several areas.

Wishlist:

 - Stability in general
 - Lots of testing on more pebbles with more phones. Only used my own Android with a 'regular' black Pebble.
 - For one, it should be easier to set up for a new user. E.g. it should tell you to go to settings in the App when unconfigured.
 - Allow you to set up miles instead of kilometers, and other currencies (for charging cost calculation)