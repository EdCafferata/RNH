RNH Tracker for iOS + WatchOS
===============================================
[![Available on the app store](https://merlos.github.io/iOS-Open-GPX-Tracker/images/download-app-store.svg)](https://apps.apple.com/us/app/rnh-tracker/id1598986930)

RNH Tracker is a GPS logger for iOS (iPhone, iPad, iPod) with offline map cache support. 
Track your location, add waypoints and send your logs by email as GPX files.

This app has no annoying time restrictions, no ads and no in-app-purchases. Create unlimited GPX traces :).

You can use RNH tracker for:

 - to help RNH (YSY) with the REGATTA !
 - Creating real GPX files.

# Main Features

 - Displays tracking route in a map
 - Supports Apple Map Kit as map sources
 - Offline maps support (of browsed areas)
 - Pause / Resume tracking
 - Load on map a saved session and continue tracking
 - Displays current location and altitude
 - Displays tracked time
 - Displays user heading (device orientation) 
 - Displays location accuracy (in meters) 
 - Displays tracked distance (total and current segment)
 - GPX files can be imported from any other app using the share option
 - Share GPX files with other apps
 - File sharing through iTunes

## Apple Watch Features (since v1.6.0 )
- Create GPX Files on your Apple Watch
- Pause/Resume tracking
- Save into GPX File
- Send file to your paired device iPhone/iPad
- Display GPS Signal strength
- View current location information (speed, latitude, longitude, altitude)

# Install

Another option to install the app is to download the source code and compile it by yourself using Xcode. If you want to run it on a device, you also need an Apple developer account.

# Download Source code
This application is written in Swift. To download the code run this command in a console:

```
 git clone https://github.com/edcafferata/
```

Then, to test it open the file `RNHTracker.xcworkspace` with XCode.

# Contribute
You can contribute by forking and submitting a pull request.

Please note that by submitting any pull request you are providing me (Ed Cafferata) the rights to include and distribute those changes also on the binary app published on the App Store (which is released under Apple's Standard License Agreement)

License
====================

RNH Tracker app for iOS.  Copyright (C) 2019  Ed Cafferata

This program is free software: you can redistribute it and/or modify
it under the terms of the **GNU General Public License** as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

----

Please note that this source code was released under the GPL license.  So any change on the code shall be made publicly available and distributed under the GPL license (this does not apply to the pods included in the project which have their own license).

----

This app uses:
- [CoreGPX Framework](https://github.com/vincentneo/CoreGPX), a SWIFT library for using GPX files. Created by [@vincentneo](http://github.com/vincentneo)


Entry on the [Open Street Maps Wiki](https://wiki.openstreetmap.org/wiki/OpenGpxTracker)
