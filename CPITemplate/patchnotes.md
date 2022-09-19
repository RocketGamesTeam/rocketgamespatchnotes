[Details](./README.md)

### Version 17
---
#### Features
1. Added Panteon Tool Downloader for frequently used packages.


### Version 16
---
#### Features
1. Added ability to enable Deep Profiling from Jenkins builds.

#### Fixes
1. Bug that occurs on some builds that removes the icon when it's not set from Jenkins.
2. Android bug that fails the build when other builds are completed.
3. Updated build failure conditions due to new/deprecated error messages.


### Version 15
---
#### Fixes
1. CurrencyElement is aligned with Level text in panels. (InGamePanel, GameOverPanel)



### Version 14
---
#### Features
1. Development and Autoconnect profiler settings are added seperately to the AutoBuilder as well as Jenkins

#### Fixes
1. Some codes refactored.



### Version 13
---
#### Features
1. Unity Analytics will be visible in SROptions.
2. Version control system is active from now on. Which will prevent the teams from downloading the old CPITemplate versions.

#### Fixes
1. Fixed a bug that prevents Jenkins to move the build to installer when project name includes `'` char.
2. GameOverPanel coin image pivots are adjusted.
3. Some assets moved to their corresponding folders for better understanding/finding.



### Version 12
---
#### Features
1. Now bundle version, bundle version code (Android only) and iOS build number (iOS only) will be visible in SR options window
2. Reworked the confetti particle VFX
3. Added settings popup to control volume and purchase restore actions
4. Added FPS view, it can be enabled by using SR options window
5. Added Time (shows total seconds elapsed) view, it can be enabled by using SR options window

#### Fixes
1. Adjusted the size of the SR options window to prevent overlapping issues with banner ads
2. Now template will not be imported with enabled LOCAL mode



### Version 11
----
#### Features
1. MultiTouch setting moved from `GameController.cs` to `InputController.cs` with better support
2. Added Drag&Drop NoAds UI elements *(Requires **RocAd** & **RocGMPurchase**)*
3. Added ability to change game icons from Jenkins items
4. Added ability to clear Project Library from Jenkins items
5. Added swipe tutorial
6. Updated compatibility of CPI package to Unity Engine version 2020.3.9f1 *LTS FOR PANTEON*



### Version 10
----
#### Features
1. Now Jenkins build informations *(Item name, build number and passed build parameters)* will be available on **SROptions** debug panel Works on builds only 
2. **UIScaleUtility** added. *(In case "Canvas Scaler" doesn't work properly on differently shaped popups etc. this utility may be used to scale content responsive to the screen resolution)*

#### Fixes
1. Fixed using statement of `UnityEditor.iOS.Xcode` in `AutoBuilder.cs`
2. Fixed the initial position of moving coin animators
3. Now emoji background animation/tween will not be freezed after a short period of time
	1. Animation/tween won't skip frames from now on
4. Default level text will no longer stuck at value 14
5. Now gauge bar will be only available if ads are available
	1. When ads are not available, coins won't multiply anymore
6. Claim reward/Reject buttons will not be available before fake leaderboard animations
7. Fixed the default position of CoinElement in GameOverPanel



----
<p><a href="javascript:history.back()">Go Back</a></p>






<p><a href="#top" class="btn" title="Go Top">Top</a></p>