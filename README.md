## About

An example JMonkeyEngine3 project for **Android Studio 3 Canary 6**, with desktop and android apps separation.

*Based on https://habrahabr.ru/post/249305/*

## Usage

This project is tested to work with (the default Android Studio 3 Canary 6 setup):
 - Android Studio 3 Canary 6
 - Gradle Plugin 3.0.0-alpha6
 - Gradle 4.1
 
## Issues

The dependency management does not actually work. When launching the **desktop** project via the `Desktop Launcher` class, you get the `NoClassDefFountError` message.