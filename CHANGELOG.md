# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<<<<<<< HEAD
## [1.0.1] - 2020-06-20

* fixed problem with fwversion attribute in device list xml on newer FritzBox firmwares
* changed build process to Maven
=======
## [1.5.0] - unreleased

### Updated
* Upgraded dependencies

## [1.4.0] - 2021-03-03

### Added
* [#18](https://github.com/kaklakariada/fritzbox-java-api/pull/18) Added new fields to be compatible with Fritz!OS 7.25
  * Device (Fritz!Dect440) serves now relative humidity
  * ColorControl (Fritz!Dect500) got some more fields
  * Added some getter for fields that did miss them
* [#19](https://github.com/kaklakariada/fritzbox-java-api/pull/19) Support for device groups

## [1.3.1] - 2021-02-26

* No changes, update deployment to Maven Central

## [1.3.0] - 2021-02-22

### Breaking Changes

* Requires Java 11 instead of Java 8
* Moved from JCenter to Maven Central due to [deprecation of JCenter](https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/). In your build script use

    ```gradle
    repositories {
        mavenCentral()
    }
    ```

## [1.2.2] - 2021-01-16

### Added

* [#17](https://github.com/kaklakariada/fritzbox-java-api/pull/17): Update for Fritz-Dect!4XX devices. Thanks to [SmokingDevices](https://github.com/SmokingDevices)!

## [1.2.1] - 2020-12-06

### Added

* [#16](https://github.com/kaklakariada/fritzbox-java-api/pull/16): Update for FRITZ-Dect 500 devices. Thanks to [SmokingDevices](https://github.com/SmokingDevices)!

## [1.2.0] - 2020-12-06 - invalid

## [1.1.0] - 2020-10-25

### Added

* [#15](https://github.com/kaklakariada/fritzbox-java-api/pull/15): Added new fields to be compatible with Fritz!OS 7.21. Thanks to [philippn](https://github.com/philippn)!
>>>>>>> a728dee93bd1ab0c4775eb84438332ad3b941a68

## [1.0.0] - 2019-12-27

### Breaking change

* Make Device properties `battery` and `batterylow` optional to distinguish between missing values and zero, see [issue #11](https://github.com/kaklakariada/fritzbox-java-api/issues/11).
