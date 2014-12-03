MAS.500 OpenFrameworks iOS Example
==================================

This is a tiny iOS example for OpenFrameworks. I made two fixes to get this to build in Xcode 6 on Mavericks.

Installation
------------

This assumes you are using Mavericks (ie. Mac OS X 10.10.x).

1. Get Xcode from the App Store - it should be version 6.1
2. Download and unzip OpenFrameworks v0.8.4 for iOS ( [direct link](http://www.openframeworks.cc/versions/v0.8.4/of_v0.8.4_ios_release.zip) )
3. Git clone this code and put it in the `of_v0.8.4_ios_release/examples/ios/` directory

Building
--------

1. Open the `emptyExample.xcodeproj` file.
2. Next to the stop button in the title bar, select "iPhone + OF Static Library" and then run Product > Build
3. In the same place, switch back emptyExample and hit the play button

This should start a simulator and run your app!
