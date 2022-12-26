# Introduction

**❗️This repository is not maintained anymore❗️**

# How to setup?

## Windows

Run the file called `latest.cmd`, then the main library will be located at **./bin/v9.11.1-winDisplaySettings-x64.node**

if you are a versions of the RPG Maker MV is to 1.5.2 or less, you can call below code so you change the build config. As you can see, it would add the version number of used node in the node library file prefix.

```cmd
latest.cmd "0.12.3"
```

it automatically finds the version number in an executable file called 'Game.exe' from `<YOUR_MV_DIR>/nwjs-win-test/` directory.

However, To achieve this, you don't need to compile directly. That's because you have a one choice that you can use prebuilt libraries! (I recommended you would compile directly)

[v1.2.0-winDisplaySettings-ia32.node](./bin/v1.2.0-winDisplaySettings-ia32.node)

[v1.2.0-winDisplaySettings-x64.node](./bin/v1.2.0-winDisplaySettings-x64.node)

[v9.11.1-winDisplaySettings-ia32.node](./bin/v9.11.1-winDisplaySettings-ia32.node)

[v9.11.1-winDisplaySettings-x64.node](./bin/v9.11.1-winDisplaySettings-x64.node)

if you have the library called \*.node already, please place it under your **/js/libs directory** and then
insert the plugin called **"RS_ScreenManager.js"** in your Plugin Manager.

## MacOS and Linux

They are not supported yet.

# Dependencies

-   Microsoft Visual Studio (2015 or above)
-   [Native Abstractions for Node.js](https://github.com/nodejs/nan)
-   nw-gyp and node-gyp

# Supports

This plugin works fine only in RPG Maker MV 1.6.1 or above. and then this is just one platform in mind.

# Releases

-   🌡️ RS_ScreenManager.js v1.1.2 (Standard)

    -   [RS_ScreenManager.js v1.1.2](https://github.com/biud436/MV-Resolutions/blob/main/RS_ScreenManager.js)

-   ❗️ RS_ScreenManager.js v1.0.22 (Legacy)

    -   [RS_ScreenManager.js](https://github.com/biud436/MV-Resolutions/raw/main/dist/RS_ScreenManager.js)
    -   [RS_ScreenManager.js.map](https://github.com/biud436/MV-Resolutions/raw/main/dist/RS_ScreenManager.js.map)
    -   \*.node (means the DLL file on Windows) file required
