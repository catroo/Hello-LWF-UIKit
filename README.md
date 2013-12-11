Hello-LWF-UIKit
===============

An example of LWF for C++ with UIKit renderer.

What is LWF?
------------

LWF http://gree.github.io/lwf/

> LWF is an animation engine which can play animation data converted from **FLASH contents** in HTML5, Unity, Cocos2d-x, **iOS UIKit**, and more. LWF is designed to make game development easy and fun.

It means that LWF allows you to make animation using Adobe Flash for your iOS Application.

How to run this example
-----------------------

Open Hello-LWF-UIKit.xcworkspace using Xcode 5 or later and run it. You'll see a Flash movie which is embedded on iOS UIView.

How to install LWF into your project
------------------------------------

Use [CocoaPods](cocoapods.org) with Podfile as the following.

    pod 'LWF/UIKit'

How to use Adobe Flash for making animation
-------------------------------------------

Please take a look at [LWF Presentation](http://gree.github.io/lwf/presentation20121115) and [LWF Production Guide](http://gree.github.io/lwf-demo/pdf/FLASHforLWFproductionguideline.pdf).

Install LWFS https://github.com/gree/lwfs to convert Adobe Flash data into LWF data. It automatically converts in ~/Desktop/LWFS_work folder and shows the data on Web browser.