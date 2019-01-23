# Carthage Specifications

There are some great frameworks out there, but unfortunately not all of them offer [Carthage](https://github.com/Carthage/Carthage) support. Luckily there is an easy workaround to include raw frameworks in your project. It works by hosting a JSON file that provides a mapping between the versions and the matching urls of the framework. After that, all you have to do is to refer to that JSON url in your Cartfile.

This repository was set up in an effort to centralize these JSON files.

## Frameworks

### Answers
Analytics engine that powers the Fabric platform (requires the Fabric framework).<br>
Website: [https://fabric.io/kits/ios/answers](https://fabric.io/kits/ios/answers)

| Platform | Lines to add to your Cartfile |
| --------- | -------- |
| Universal | `binary "https://building42.github.io/Specs/Carthage/Universal/Answers.json"`<br>`binary "https://building42.github.io/Specs/Carthage/Universal/Fabric.json"` |
| iOS       | `binary "https://building42.github.io/Specs/Carthage/iOS/Answers.json"`<br>`binary "https://building42.github.io/Specs/Carthage/iOS/Fabric.json"` |
| tvOS      | `binary "https://building42.github.io/Specs/Carthage/tvOS/Answers.json"`<br>`binary "https://building42.github.io/Specs/Carthage/tvOS/Fabric.json"` |
| macOS     | `binary "https://building42.github.io/Specs/Carthage/macOS/Answers.json"`<br>`binary "https://building42.github.io/Specs/Carthage/macOS/Fabric.json"` |

### Crashlytics
Powerful, yet lightweight crash reporting solution (requires the Fabric framework).<br>
Website: [https://fabric.io/kits/ios/crashlytics](https://fabric.io/kits/ios/crashlytics)

| Platform | Lines to add to your Cartfile |
| --------- | -------- |
| Universal | `binary "https://building42.github.io/Specs/Carthage/Universal/Crashlytics.json"`<br>`binary "https://building42.github.io/Specs/Carthage/Universal/Fabric.json"` |
| iOS       | `binary "https://building42.github.io/Specs/Carthage/iOS/Crashlytics.json"`<br>`binary "https://building42.github.io/Specs/Carthage/iOS/Fabric.json"` |
| tvOS      | `binary "https://building42.github.io/Specs/Carthage/tvOS/Crashlytics.json"`<br>`binary "https://building42.github.io/Specs/Carthage/tvOS/Fabric.json"` |
| macOS     | `binary "https://building42.github.io/Specs/Carthage/macOS/Crashlytics.json"`<br>`binary "https://building42.github.io/Specs/Carthage/macOS/Fabric.json"` |

## Contribute

If you want to add a popular framework to this list or if you notice that one of the JSON files is outdated, feel free to drop me a [pull request](https://github.com/Building42/Specs/pulls) and I'll merge it in.
