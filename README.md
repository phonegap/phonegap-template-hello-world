# Hello World PhoneGap Application

> A Hello World application built with PhoneGap

## Usage

### Run Application

    /www/index.html

### Run Tests

    /www/spec.html

### PhoneGap/Build

Create a new app with the following repository:

    https://github.com/phonegap/phonegap-app-hello-world.git

## Contributing

This application is a modification of the [Apache Cordova Hello World][1].

For issues with __the application__, please submit an issue or pull request
to the [Apache Cordova source code][1].

For issues with __the PhoneGap Build integration__, please submit
an issue or pull request to this project.

## Updating the Application

The application is based on the Apache Cordova Hello World example.

### 1. Update the Source

    cp /cordova-app-hello-world/www www/

__Do not replace `www/config.xml`.__

__Do not replace `www/img/logo.png`.__

### 2. Update index.html

Replace `<h1>Apache Cordova</h1>` with `<h1>PhoneGap</h1>`.

### 3. Update PhoneGap Version

    <preference name="phonegap-version" value="x.x.x" />

### 4. Commit

    $ git commit -am "Version x.x.x"

### 5. Tag

    $ git tag x.x.x

[1]: http://github.com/apache/cordova-app-hello-world

