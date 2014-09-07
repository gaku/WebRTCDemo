# Android Studio project for AppRTCDemo of WebRTC project

This should let you build AppRTCDemo without much effort.
I built WebRTC distribution on 9/6/2014, extracted `trunk/talk/examples/android`,
and it is imported to Android Studio.

## Background

It is not straightforward to build WebRTC for Android on Mac OS X.

- WebRTC can be only built on Linux.
- You need to have 6G+ disk space to build.
- Git clone takes up an hour.
- It requries a lot of libraries/packages installed.

However, it turned out that at the end of the day, you just need a few files to
build it on Android.

## Prerequisite

While this requries almost no effort to build, you need:

- Android NDK installed on your machine.
- Point the NDK installation via `local.properties`
