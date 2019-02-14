# Portfolio
Some of my past mobile app work both personal and professional. Not in any particular order. <br/>
The features I took part in will be mentioned in each project's description.
Most of the apps have been designed around the MVVM / MVC pattern with the exception of GRUM which was designed with the Coordinator pattern.

Native iOS Swift/Objective-C</br>
[GRUM](#grum)<br/>
[Inventory Management](#inventorymanagement)<br/>
[MachineryTrader](#machinery-trader)<br/>
[Mobile Application Versioning](#mobile-application-versioning)<br/>

Xamarin C#<br/>
[Piedmontese Beef](#piedmontese-beef)<br/>
[EVSlideshow]()<br/>
[GoetiaGuide]()<br/>
[InstantChat](#instant-chat)<br/>
[DigitalEditions Template]()<br/>




## GRUM
**Language**: Swift 4 <br/>
**Backend**: Firestore, Firebase storage <br/>
**Features**: QR code generation, QR Reader, Email and Facebook authentication, custom layout, taking photos, programmatic UI <br/>
**Dependencies**: SnapKit, Firebase, FBSDKLoginKit, SWRevealViewController, IGListKit, Presentr, NVActivityIndicatorView <br/>
This is my most recent project(s). 2 apps, 1 customer facing, 1 client facing, still under development

#### ScreenShots
[login](https://github.com/daniel112/Portfolio/blob/master/GRUM/Simulator%20Screen%20Shot%20-%20iPhone%208%20Plus%20-%202019-02-13%20at%2022.33.10.png?raw=true)<br/>
[signup](https://github.com/daniel112/Portfolio/blob/master/GRUM/Simulator%20Screen%20Shot%20-%20iPhone%208%20Plus%20-%202019-02-13%20at%2022.33.37.png?raw=true)<br/>
[QR Generation](https://github.com/daniel112/Portfolio/blob/master/GRUM/Simulator%20Screen%20Shot%20-%20iPhone%208%20Plus%20-%202019-02-13%20at%2022.42.26.png?raw=true)<br/>
[QR Scanning](https://github.com/daniel112/Portfolio/blob/master/GRUM/scanQR.png?raw=true)<br/>
[QR Scanning pt 2](https://github.com/daniel112/Portfolio/blob/master/GRUM/scanQR2.png?raw=true)<br/>
[QR Scanning pt 3](https://github.com/daniel112/Portfolio/blob/master/GRUM/detailsInprogress.png?raw=true)<br/>

## Piedmontese Beef
**Language**: Xamarin Native C# <br/>
**Backend**: .NET, MySql <br/>
**Features**: Programmatic UI, consume RESTful API for digital editions, web views for placeholder feature, parallax home page, responsive UI, custom layout<br/>
**Dependencies**: MVVMCross, Xam.Plugin.Connectivity, NewtonSoft.Json, PureLayout.Net <br/>
Sole developer from initial design to first initial release. [App store link](https://itunes.apple.com/us/app/certified-piedmontese-beef/id1377359924?mt=8)

#### ScreenShots
[home page example](https://i.imgur.com/uSdO8JZ.mp4)<br/>
[landscape](https://github.com/daniel112/Portfolio/blob/master/Piedmontese/landscape_sidemenu.png?raw=true)<br/>
[digital edition](https://github.com/daniel112/Portfolio/blob/master/Piedmontese/digitalEditions.png?raw=true)<br/>
[list view](https://github.com/daniel112/Portfolio/blob/master/Piedmontese/cuts.png?raw=true)<br/>
[details view](https://github.com/daniel112/Portfolio/blob/master/Piedmontese/details.png?raw=true)<br/>


## InventoryManagement
**Language**: Swift 4 <br/>
**Backend**: Realm, .NET, MySQL <br/>
**Features**: TBA <br/>
**Dependencies**: Realm, Firebase, RestKit, FLKAutoLayout, NBProgressHUD, OrStackView <br/>
App used by dealers to add / edit their inventory information that is then displayed on the tradepub websites or mobile apps. <br/>
My contribution to this app are the following: QR Reader, list view toolbar / drop down navigation, updating edit inventory view logic, delete inventory, sorting list view, updating offline edit and save feature with new properties. Optimizing solution by tracking down memory leaks.<br/>
[App store link](https://itunes.apple.com/us/app/sandhills-cloud-inventory/id1140187048?mt=8)
#### ScreenShots
[search demo](https://github.com/daniel112/Portfolio/blob/master/InventoryManagement/searchDemo.gif?raw=true)
[edit inventory view](https://github.com/daniel112/Portfolio/blob/master/InventoryManagement/editiventory.png?raw=true)


## MachineryTrader
**Language**: Objective-C <br/>
**Backend**: .NET, MySQL <br/>
**Features**: DoubleClick Ads, partial localization, texting, Universal Links  <br/>
**Dependencies**: RestKit, FLKAutoLayout, Masonry, Firebase, Crashlytics, MBProgressHUD, Google-mobile-ads-sdk, IGListKit <br/>
[App store link](https://itunes.apple.com/us/app/machinery-trader/id380184450?mt=8)

#### ScreenShots
[doubleclick ads](https://github.com/daniel112/Portfolio/blob/master/machinery/dblclickads.png?raw=true)
[details view](https://github.com/daniel112/Portfolio/blob/master/machinery/details.png?raw=true)

## Mobile Application Versioning
**Language**: Objective-C <br/>
**Backend**: .NET, MySQL <br/>
**Features**: Add/Edit/Delete app version information <br/>
**Dependencies**: IGListKit, SWRevealViewController, RestKit <br/>
Versioning app to keep track of all of the company's existing apps. We're able to automatically deprecate a live app's version via this tool. This app is used internally only

#### ScreenShots
n/a<br/>


## InstantChat
**Language**: Xamarin Forms C# <br/>
**Backend**: .NET, MySQL, OneSignal <br/>
**Features**: texting, authentication <br/>
**Dependencies**: OneSignal, Xamarin Forms, internal networking library <br/>
Texting platform to be utilized by dealers who are tied with the sandhills system. Customers interested in an inventory are able to text the dealer via the website or mobile apps. The dealer will then get a notification on InstantChat that a customer is interested in their piece.
[iOS store link](https://itunes.apple.com/us/app/sandhills-cloud-instant-chat/id1448044398?mt=8)
[Android store link](https://play.google.com/store/apps/details?id=com.sandhills.InstantChat&hl=en_US)
#### ScreenShots
n/a<br/>
