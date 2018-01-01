# Curl for iOS

<p align="center">
  <a href="https://github.com/IMcD23/openssl-ios">openssl-ios</a> &bull;
  <b>libcurl-ios</b> &bull;
  <a href="https://github.com/IMcD23/libssh2-ios">libssh2-ios</a> &bull;
  <a href="https://github.com/IMcD23/libgit2-ios">libgit2-ios</a>
</p>

--------

Curl, built for iOS as a static library and framework

[![Build Status](http://img.shields.io/travis/IMcD23/libcurl-ios.svg)](https://travis-ci.org/IMcD23/libcurl-ios)
[![Version](https://img.shields.io/github/release/IMcD23/libcurl-ios.svg)](https://github.com/IMcD23/libcurl-ios/releases/latest)
![Package Managers](https://img.shields.io/badge/supports-Carthage-orange.svg)
[![Contact](https://img.shields.io/badge/contact-%40ian__mcdowell-3a8fc1.svg)](https://twitter.com/ian_mcdowell)

# Requirements

* Xcode 9 or later

# Installation

## Carthage
To install libcurl-ios using [Carthage](https://github.com/Carthage/Carthage), add the following line to your Cartfile:

```
github "IMcD23/libcurl-ios" "master"
```

# Submodule
To install libcurl-ios as a submodule into your git repository, run the following command:

```
git submodule add -b master https://github.com/IMcD23/libcurl-ios.git Path/To/libcurl-ios
git submodule update --init --recursive
```

Then, add the `.xcodeproj` in the root of the repository into your Xcode project, and add it as a build dependency.

# Build System
This repository is a framework wrapper around the actual project you are building. All this library does is automate the build process and integrate it nicely with Xcode. This is all done using the [ibuild](https://github.com/IMcD23/ibuild) build system.

Check out the `build.plist` file in this repo to see its build configuration.

# Author
Created by [Ian McDowell](https://ianmcdowell.net)

# License
All code in this project is available under the license specified in the LICENSE file. However, since this project also bundles code from other projects, you are subject to those projects' licenses as well.