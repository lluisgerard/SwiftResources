# SwiftResources
Swift Resources for iOS day to day development

This repository is about things that I end up using in day to day basis or information that can be useful for me when teaching others Swift or iOS in general. I thought about using a private repository because I'll add some personal notes about the stuff I use every day but it may be useful for others so I'll keep it public.

This is not intended to be a long list of resources but rather a short list of frameworks, documentation, etc... If you want a big list of resources and documentation I recommend you to take a look at these two awesome repositories:
* [Awesome Swift](https://github.com/matteocrippa/awesome-swift)
* [Swift Doc](https://github.com/SwiftDocOrg/swiftdoc.org)

## Libraries

*Auto Layout*
* [SnapKit](https://github.com/SnapKit/SnapKit) I've been using Masonry (Objective-C) since I started with iOS, building my views directly in code. SnapKit is the evolution of Masonry to Swift.

*Grand Central Dispatch*
* [Async](https://github.com/duemunk/Async) I always built my own helpers for GCD but this approach seems cleaner.

*Networking*
* [Moya](https://github.com/ashfurrow/Moya) Network abstraction layer. I will try it on my next app.

## Dependency Managers
* [Carthage](https://github.com/Carthage/Carthage) I still haven't tried it but it sounds promising, you can see [@jspahrsummers](https://github.com/jspahrsummers) himself here: http://realm.io/news/swift-dependency-management-with-carthage/
* [CocoaPods](https://cocoapods.org) Is very nice and useful but I never really liked the mechanism. I'd spent hours trying to fix linking problems and going from Xcode to CocoaPods trying to figure out how was to blame for. That's why I think that Carthage is something worth trying.

## Documentation / Learning
* [WWDC 2014 Videos](https://developer.apple.com/videos/wwdc/2014/) These videos are cool to get to know what's new from iOS 8. For Swift I think is better to start with the "Swift Programming Series (iBooks Store)". Don't like the website? [check this app](https://github.com/insidegui/WWDC)
* [Swift Resources from Apple](https://developer.apple.com/swift/resources/) The best place to start to learn Swift. The only problem about the current "Swift Programing Series" books is that only talk about the language itself and doesn't talk about it in the iOS or Mac OS X development environment.
