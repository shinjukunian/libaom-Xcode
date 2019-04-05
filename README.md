# libaom + Xcode

[![CI Status](http://img.shields.io/travis/SDWebImage/libaom-Xcode.svg?style=flat)](https://travis-ci.org/SDWebImage/libaom-Xcode)
[![Version](https://img.shields.io/cocoapods/v/libaom.svg?style=flat)](http://cocoapods.org/pods/libaom)
[![License](https://img.shields.io/cocoapods/l/libaom.svg?style=flat)](http://cocoapods.org/pods/libaom)
[![Platform](https://img.shields.io/cocoapods/p/libaom.svg?style=flat)](http://cocoapods.org/pods/libaom)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/SDWebImage/libaom-Xcode)

A wrapper for [libaom](https://aomedia.googlesource.com/aom/) + Xcode project.
This enables Carthage support

This repo also including the CocoaPods's spec file to use libaom.

## Requirements

+ iOS 8
+ macOS 10.6
+ tvOS 9.0
+ watchOS 2.0

## Note
Current macOS using the `AVX/AVX2` instruction. If the target Mac CPU does not support, wait for upstream to support the dynamic CPU detect.

On iOS, due to lack of dynamic CPU detect and the suck of CocoaPods/Carthage, we disable the NEON instruction.

## Installation

### Carthage

libaom is (via this repo) available through [Carthage](https://github.com/Carthage/Carthage).

```
github "SDWebImage/libaom-Xcode"
```

### CocoaPods

libaom is available through [CocoaPods](https://github.com/CocoaPods/CocoaPods).

```
pod 'libaom'
```

## Usage

Use libaom as you would normally, this is just a repo that adds an Xcode proj.

## License

libaom is available under the [Alliance for Open Media Patent License](https://aomedia.org/license/software-license/).

