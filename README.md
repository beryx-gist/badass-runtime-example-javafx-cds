[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/beryx-gist/badass-runtime-example-javafx-cds/blob/master/LICENSE)
[![Build Status](https://img.shields.io/travis/beryx-gist/badass-runtime-example-javafx-cds/master.svg?label=Build)](https://travis-ci.org/beryx-gist/badass-runtime-example-javafx-cds)

## Badass Runtime Plugin Example: JavaFX Application with Class Data Sharing ##

A small JavaFX 14 non-modular application that shows how to use the [Badass Runtime Plugin](https://github.com/beryx/badass-runtime-plugin/).

It allows you to create a custom runtime image of your application. The start script configures the application to use class data sharing.

### Usage
**Running with gradle:**
```
./gradlew run
```

A window containing the text `Hello, OpenJFX!` should appear on the screen.


**Creating and executing a custom runtime image:**
```
./gradlew runtime
cd build/image/bin
./hellofx
```

A window containing the text `Hello, OpenJFX!` should appear on the screen.
