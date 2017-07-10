This is a starter template for [Ionic](http://ionicframework.com/docs/) projects.

## How to use this template

*This template does not work on its own*. The shared files for each starter are found in the [ionic2-app-base repo](https://github.com/ionic-team/ionic2-app-base).

To use this template, either create a new ionic project using the ionic node.js utility, or copy the files from this repository into the [Starter App Base](https://github.com/ionic-team/ionic2-app-base).

### With the Ionic CLI:

Take the name after `ionic2-starter-`, and that is the name of the template to be used when using the `ionic start` command below:

```bash
$ sudo npm install -g ionic cordova
$ ionic start myBlank blank
```

Then, to run it, cd into `myBlank` and run:

```bash
$ ionic cordova platform add ios
$ ionic cordova run ios
```

Substitute ios for android if not on a Mac.

```bash
$ ionic info
```
global packages:

    @ionic/cli-utils : 1.4.0
    Ionic CLI        : 3.4.0

local packages:

    @ionic/app-scripts              : 1.3.12
    @ionic/cli-plugin-ionic-angular : 1.3.1
    Ionic Framework                 : ionic-angular 3.5.0

System:

    Node       : v8.1.3
    OS         : macOS Sierra
    Xcode      : Xcode 8.3.3 Build version 8E3004b
    ios-deploy : 1.9.1
    ios-sim    : 5.0.13
    npm        : 5.0.3
