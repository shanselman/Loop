# Loop for iOS

![App Icon](/Loop/Assets.xcassets/AppIcon.appiconset/40%402x.png?raw=true) ![WatchApp Icon](/WatchApp/Assets.xcassets/AppIcon.appiconset/watch-40%402x.png?raw=true)

[![Build Status](https://travis-ci.org/loudnate/Loop.svg?branch=naterade)](https://travis-ci.org/loudnate/Loop)

Naterade is my artificial pancreas. It is a stone resting on the boulders of work done by [@bewest](https://github.com/bewest/decoding-carelink), [@ps2](https://github.com/ps2/rileylink) and many others.

Please understand that this project:
- Is highly experimental
- Is not approved for therapy

<a href="/Documentation/Screenshots/Phone%20Graphs.png"><img src="/Documentation/Screenshots/Phone%20Graphs.png?raw=true" alt="Screenshot of status screen" width="170"></a>
<a href="/Documentation/Screenshots/Phone%20Bolus.png"><img src="/Documentation/Screenshots/Phone%20Bolus.png?raw=true" alt="Screenshot of bolus screen" width="170"></a>
<a href="/Documentation/Screenshots/Phone%20Notification%20Battery.png"><img src="/Documentation/Screenshots/Phone%20Notification%20Battery.png?raw=true" alt="Screenshot of battery change notification" width="170"></a>
<a href="/Documentation/Screenshots/Phone%20Notification%20Loop%20Failure.png"><img src="/Documentation/Screenshots/Phone%20Notification%20Loop%20Failure.png?raw=true" alt="Screenshot of loop failure notification" width="170"></a>
<a href="/Documentation/Screenshots/Phone%20Notification%20Bolus%20Failure.png"><img src="/Documentation/Screenshots/Phone%20Notification%20Bolus%20Failure.png?raw=true" alt="Screenshot of bolus failure notification" width="170"></a>

<a href="/Documentation/Screenshots/Watch%20Complication.png"><img src="/Documentation/Screenshots/Watch%20Complication.png?raw=true" alt="Screenshot of glucose complication on Apple Watch" width="141"></a>
<a href="/Documentation/Screenshots/Watch%20Carb%20Entry.png"><img src="/Documentation/Screenshots/Watch%20Carb%20Entry.png?raw=true" alt="Screenshot of carb entry on Apple Watch" width="141"></a>
<a href="/Documentation/Screenshots/Watch%20Bolus.png"><img src="/Documentation/Screenshots/Watch%20Bolus.png?raw=true" alt="Screenshot of bolus entry on Apple Watch" width="141"></a>
<a href="/Documentation/Screenshots/Watch%20Menu.png"><img src="/Documentation/Screenshots/Watch%20Menu.png?raw=true" alt="Screenshot of the app menu on Apple Watch" width="141"></a>
<a href="/Documentation/Screenshots/Watch%20Notification%20Reservoir.png"><img src="/Documentation/Screenshots/Watch%20Notification%20Reservoir.png?raw=true" alt="Screenshot of bolus failure notification on Apple Watch" width="141"></a>
<a href="/Documentation/Screenshots/Watch%20Notification%20Bolus%20Failure.png"><img src="/Documentation/Screenshots/Watch%20Notification%20Bolus%20Failure.png?raw=true" alt="Screenshot of bolus failure notification on Apple Watch" width="141"></a>

### RileyLink

Bluetooth LE communication with Minimed pumps is enabled by the [RileyLink](https://github.com/ps2/rileylink), a compact BLE-to-916MHz bridge device designed by the incredible [@ps2](https://github.com/ps2). Please visit the [repository](https://github.com/ps2/rileylink) and the [gitter room](https://gitter.im/ps2/rileylink) for more information.

### LoopKit

Naterade is built on top of [LoopKit](https://github.com/loudnate/LoopKit). LoopKit is a set of frameworks that provide data storage, retrieval, and calcluation, as well as boilerplate view controllers.

## Can I run Naterade?

Unless your name is Nate, that might be weird for you. Instead, I'd encourage you to look at [Loop](https://github.com/loudnate/Loop), which is nearly identical to Naterade but it has some additional benefits, like:

* Setup and customization instructions
* Stable, [gitflow](http://nvie.com/posts/a-successful-git-branching-model/)-based release process

Just remember **Your Diabetes May Vary**. Your physiology, habits, and risk-tolerance are not the same as mine. Use these tools at your own risk!

# License and Code of Conduct

Please read the [LICENSE](/LICENSE.md) and [CODE_OF_CONDUCT](/CODE_OF_CONDUCT.md)
