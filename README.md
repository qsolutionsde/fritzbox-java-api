# fritzbox-java-api

[![Download](https://api.bintray.com/packages/qsolutionsde/maven/fritzbox-java-api/images/download.svg)](https://bintray.com/qsolutionsde/maven/fritzbox-java-api/_latestVersion)

Java API for managing FritzBox HomeAutomation using [AVM Home Automation HTTP Interface](https://avm.de/fileadmin/user_upload/Global/Service/Schnittstellen/AHA-HTTP-Interface.pdf) inspired by grundid's [fritzbox-java-api](https://github.com/grundid/fritzbox-java-api). This also runs on Android devices (see [Andect](https://github.com/kaklakariada/Andect)).

## Changelog

See [CHANGELOG.md](CHANGELOG.md).

## Usage in pom.xml

* Add jcenter maven repository:
```xml
    <repositories>
        <repository>
            <id>jcenter</id>
            <name>jcenter</name>
            <url>https://jcenter.bintray.com</url>
        </repository>
    </repositories>
```
* Add dependency
```xml
    <dependency>
        <groupId>io.github.qsolutionsde</groupId>
        <artifactId>fritzbox-java-api</artifactId>
        <version>1.0.1</version>
    </dependency>
```

### Run sample program

1. Copy file `application.properties.template` to `application.properties` and enter settings for your device.
2. Run example class [`TestDriver`](https://github.com/qsolutionsde/fritzbox-java-api/blob/master/src/main/java/com/github/kaklakariada/fritzbox/TestDriver.java).

