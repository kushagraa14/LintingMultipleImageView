# MultipleImageView

![Swift 5.x](https://img.shields.io/badge/language-Swift%205.x-orange?logo=apple)
![Cocoapods platforms](https://img.shields.io/cocoapods/p/MultipleImageView?logo=cocoapods)
![Cocoapods](https://img.shields.io/cocoapods/v/MultipleImageView?logo=cocoapods)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![Swfit Package Manager supported](https://img.shields.io/badge/Swift%20Package%20Manager-supported-DE5C43.svg?style=flat&logo=swift)](https://swift.org/package-manager)  
[![Actions Lint](https://github.com/nnsnodnb/MultipleImageView/actions/workflows/actionlint.yml/badge.svg)](https://github.com/nnsnodnb/MultipleImageView/actions/workflows/actionlint.yml)
[![CocoaPods Trunk](https://github.com/nnsnodnb/MultipleImageView/actions/workflows/pod_trunk.yml/badge.svg)](https://github.com/nnsnodnb/MultipleImageView/actions/workflows/pod_trunk.yml)
[![Podspec](https://github.com/nnsnodnb/MultipleImageView/actions/workflows/podspec.yml/badge.svg)](https://github.com/nnsnodnb/MultipleImageView/actions/workflows/podspec.yml)
[![Swift build](https://github.com/nnsnodnb/MultipleImageView/actions/workflows/build.yml/badge.svg)](https://github.com/nnsnodnb/MultipleImageView/actions/workflows/build.yml)
[![Swift build](https://github.com/nnsnodnb/MultipleImageView/actions/workflows/build.yml/badge.svg)](https://github.com/nnsnodnb/MultipleImageView/actions/workflows/build.yml)

Displaying multiple images like Twitter.

## Installation

### CocoaPods

```ruby
pod 'MultipleImageView'
```

### Carthage

```
github "nnsnodnb/MultipleImageView"
```

### Swift Package Manager

```swift
// swift-tools-version:5.0
import PackageDescription

let package = Package(
    name: "SampleApp",
    dependencies: [
        .package(name: "MultipleImageView",
                 url: "https://github.com/nnsnodnb/MultipleImageView.git",
                 from: "0.1.0")
    ],
    .targets: [
        .target(name: "SampleApp,
                dependencies: ["MultipleImageView"])
    ]
)
```

## Example

Please see Example project.

## License

[MultipleImageView](https://github.com/nnsnodnb/MultipleImageView) is released under the MIT license. See [LICENSE](https://github.com/nnsnodnb/MultipleImageView/blob/main/LICENSE) for details.
