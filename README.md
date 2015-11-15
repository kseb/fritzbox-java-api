# fritzbox-java-api

[![Build Status](https://travis-ci.org/kaklakariada/fritzbox-java-api.svg?branch=master)](https://travis-ci.org/kaklakariada/fritzbox-java-api)

Java API for managing FritzBox HomeAutomation using [AVM Home Automation HTTP Interface](https://avm.de/fileadmin/user_upload/Global/Service/Schnittstellen/AHA-HTTP-Interface.pdf) inspired by grundid's [fritzbox-java-api](https://github.com/grundid/fritzbox-java-api). This also runs on Android devices.

## Usage
* Copy file `application.properties.template` to `application.properties` and enter settings for your device.
* Run example class [`TestDriver`](https://github.com/kaklakariada/fritzbox-java-api/blob/master/src/main/java/com/github/kaklakariada/fritzbox/TestDriver.java).
* Use API in your program.

## Building
* Install library to local maven repository:
```./gradlew install```
