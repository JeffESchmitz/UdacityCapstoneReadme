## 1. App Title
# RideNiceRide

### [Udacity iOS Developer Nanodegree](https://www.udacity.com/course/ios-developer-nanodegree--nd003) Capstone Project
In this capstone project, students will create an app of their own design that showcases our iOS development skills.

### App Description:
RideNiceRide is the best way to enjoy Boston's Hubway bike sharing system on iOS.  
*Inspired and based upon the fantastic Android application, [Moyeu](https://github.com/garuma/Moyeu) developed by [Jérémie Laval](https://github.com/garuma?tab=overview&from=2016-12-01&to=2016-12-31&utf8=✓).*

## 2. User Experience
## Screen Shots here

## Usage
- On startup, the application will center the map on Boston, MA. and plot up-to-date bicycle station information as Pin's on the map.
- On app startup, the user will be presented a map of the Boston Hubway bicycle sharing system map of current availabilty of bicycles for rent.
- Pins on the map represent stations containing bicyles.
- Each pin displays the number of bicycles available and are color-coded to quickly determine general bicycle availability.

Color | Description
--- | ---
Blue | Station Locked
Red | No bikes
Orange | 1 to 4 bikes
Light Green | 5 to 9 bikes
Green | 10 to 16 bikes

- Tapping a pin on the map will slide up a menu at the bottom of the screen displaying the name of the sation and the active bikes available for rent as well as the total number of bikes the docking station can hold.
- Sliding the bottom menu up will display a panoramic view of the surrounding area.
- This panorama view allows the user to visualize what the bike station should appear like and allow them to quickly pinpoint the station if they choose to seek out and rent a bicycle.
- Clicking on a star while a map pin has been activated will store that map location into a favorite. 
- The favorite is another view allowing the user to access via the left-hand slide menu (hamburger menu), displaying a list of all of stored favorite stations.


- Tapping on the upper left hamburger menu will open up the menu to select the favorites for you. The favorites you shows the list of stations that the user has starred and swiping to the left the user is able to remove a favorite from the favorite list.

<br />
<br />
<br />
## 3. Rubric review

<br />
<br />
<br />
## 4. Credits
## Credits
Artwork:

- [Mass-bike](https://pbs.twimg.com/profile_banners/90715747/1483463516/1500x500) from [MassBike.org](http://www.massbike.org)
- [Noun_536.svg - Bicycle](https://thenounproject.com/term/bicycle/536/) from [Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)
- [Star_on.svg, Star_off.svg](https://github.com/jamesmontemagno/BikeNow) from [James Montemagno's](https://github.com/jamesmontemagno) [BikeNow](https://github.com/jamesmontemagno/BikeNow) GitHub repository.
- [Map Pin images](https://www.shutterstock.com/image-vector/25-simple-mapping-pins-icon-web-66302356?src=download_history) designed by [Vector Illustration](https://www.shutterstock.com/g/vector+illustration#)
- [Bicycle](http://thenounproject.com/noun/bicycle/#icon-No3535) designed by [Ugur Akdemir](http://thenounproject.com/ugur.akdemir) from The Noun Project
- [Hubway](https://flic.kr/p/q386Lu) by Tony Webster (CC BY)

Data provided by [Hubway](https://www.thehubway.com) at [http://thehubway.com/data/stations/bikeStations.json](http://thehubway.com/data/stations/bikeStations.json)

## 5. Tech Details
### Getting Started

Run the following command in root directory to populate CocoaPods.
```bash
pod install
```
Now you can open `RideNiceRide.xcworkspace` and Run the `RideNiceRide` target onto your simulator or iOS device.

### Code style

This project will follow the [GitHub Swift Styleguide](https://github.com/github/swift-style-guide) in every way possible.

In order to enforce this, the project will also have a [Swiftlint](https://github.com/realm/SwiftLint) build phase to run the linter everytime the app is built.

## Dependencies

### Model

- [Sync](https://github.com/SyncDB/Sync): Modern Swift JSON synchronization to Core Data
- [DATAStack](https://github.com/SyncDB/DATAStack): 100% Swift Simple Boilerplate Free Core Data Stack
- [DATASource](https://github.com/SyncDB/DATASource): Core Data's NSFetchedResultsController wrapper for UITableView and UICollectionView
- [SYNCPropertyMapper](https://github.com/SyncDB/SYNCPropertyMapper): Map your Core Data properties with ease

### Networking

- [Alamofire](https://github.com/Alamofire/Alamofire): HTTP networking library written in Swift

### UI

- [ISHPullUp](https://github.com/iosphere/ISHPullUp): Vertical split view controller with pull up gesture as seen in the iOS 10 Maps app
- [SlideMenuControllerSwift](https://github.com/dekatotoro/SlideMenuControllerSwift): iOS Slide Menu View based on Google+, iQON, Feedly, Ameba iOS app. It is written in pure swift
- [GoogleMaps](https://developers.google.com/maps/documentation/ios-sdk/): Enrich your app with interactive maps and immersive street view panoramas
- [GooglePlaces](https://developers.google.com/places/ios-api/): Add up-to-date information about millions of locations to your iOS App
- [PKHUD](https://github.com/pkluz/PKHUD): A Swift based reimplementation of the Apple HUD (Volume, Ringer, Rotation,…)

### Utilities

- [Sugar](https://github.com/hyperoslo/Sugar): ☕️ Something sweet that goes great with your Cocoa
- [Cent](https://github.com/ankurp/Cent): Library that extends certain Swift object types using the extension feature and gives its two cents to Swift language
- [Dollar](https://github.com/ankurp/Dollar): A functional tool-belt for Swift Language similar to Lo-Dash or Underscore.js in Javascript
- [Device](https://github.com/Ekhoo/Device): Light weight tool for detecting the current device and screen size written in swift
- [Willow](https://github.com/Nike-Inc/Willow): Willo is a powerful, yet lightweight logging library written in Swift
- [AsyncSwift](https://github.com/duemunk/Async): Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch

### Environment

- [SwiftLint](https://github.com/realm/SwiftLint): A tool to enforce Swift style and conventions.
- [SwiftGen](https://github.com/AliSoftware/SwiftGen): A collection of Swift tools to generate Swift code (enums for your assets, storyboards, Localizable.strings, …)
- [Fabric](https://docs.fabric.io/apple/fabric/overview.html): Fabric is a mobile platform with modular kits you can mix and match to build the best apps
- [Crashlytics](https://fabric.io/kits/ios/crashlytics/install): The most powerful, yet lightest weight crash reporting solution
