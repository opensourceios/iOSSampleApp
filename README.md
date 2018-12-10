# iOS Sample App

[![Travis CI](https://travis-ci.org/igorkulman/iOSSampleApp.svg?branch=master)](https://travis-ci.org/igorkulman/iOSSampleApp)
[![codecov](https://codecov.io/gh/igorkulman/iOSSampleApp/branch/master/graph/badge.svg)](https://codecov.io/gh/igorkulman/iOSSampleApp)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Platforms](https://img.shields.io/badge/platform-iOS-lightgrey.svg)
[![Swift Version](https://img.shields.io/badge/Swift-4.1-F16D39.svg?style=flat)](https://developer.apple.com/swift)
[![Twitter](https://img.shields.io/badge/twitter-@igorkulman-blue.svg)](http://twitter.com/igorkulman)

Sample iOS app written the way I write iOS apps because I cannot share the app I currently work on.

## Shown concepts

### Architecture concepts

* [Coordinators](https://blog.kulman.sk/architecting-ios-apps-coordinators/)
* Dependency Injection (using [Swinject](https://github.com/Swinject/Swinject))
* MVVM
* [Data Binding](https://blog.kulman.sk/using-data-binding-in-ios/) (using [RxSwift](https://github.com/ReactiveX/RxSwift))
* Dependencies management (using [Carthage](https://github.com/Carthage/Carthage))

### Other concepts

* Localization to 2 languages with [safer string usage](https://blog.kulman.sk/using-ios-strings-in-a-safer-way/) and checking for missing translations
* Continuous integration (using [Travis](https://travis-ci.org/igorkulman/iOSSampleApp))
* Unit testing, including testing view controllers for leaks (using [SpecLeaks](https://github.com/leandromperez/specleaks))
* Using (multiple) Storyboards just as glorified XIBs
* Using static UITableView cells in a typed way with enums
* Image literals
* Automated AppStore screenshots taking in multiple languages (using [Fastlane](https://fastlane.tools/)) 

## Getting started

### Prerequisites

* [Carthage](https://github.com/Carthage/Carthage)
* XCode 10+
* [SwiftGen](https://github.com/SwiftGen/SwiftGen)
* [SwifLint](https://github.com/realm/SwiftLint) (optional)
* [Fastlane](https://fastlane.tools/) (optional)

### Bootstraping the project

To get started with the project run `./bootstrap.sh` to install Carthage, SwifLint, SwiftGen, Fastlane and build all the Carthage dependencies. 

If you already have Carthage installed and do not want or need the other tools, just run `carthage bootstrap --platform iOS` to build all the Carthage dependencies. 

This need to be done **just once** for the initial setup.

## Author

Igor Kulman - igor@kulman.sk

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
