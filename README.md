Elastos Trinity Runs DApps
==========================
|Android & IOS|Android(Windows)|
|:-:|:-:|
|[![Build Status](https://travis-ci.org/elastos/Elastos.Trinity.svg)](https://travis-ci.org/elastos/Elastos.Trinity)|[![Build status](https://ci.appveyor.com/api/projects/status/hjyv761on883jors?svg=true)](https://ci.appveyor.com/project/Elastos/elastos-trinity)|

Elastos.Trinity is composite repository to Elastos Trinity infrastructure, which can be divided into the following submodules:

* [Elastos.Trinity.Runtime](https://github.com/elastos/Elastos.Trinity.Runtime)
* Elastos.Trinity.DApps
* [Elastos.Trinity.Plugins](https://github.com/elastos/Elastos.Trinity.Plugins)
* [Elastos.Trinity.Toolchains](https://github.com/elastos/Elastos.Trinity.Toolchains)

where category **DApps** includes several specific DApps repositories:

* [Elastos.Trinity.DApps.Launcher](https://github.com/elastos/Elastos.Trinity.DApps.Launcher)
* [Elastos.Trinity.DApps.Wallet](https://github.com/elastos/Elastos.Trinity.DApps.Wallet)
* Elastos.Trinity.DApps.IM (Todo)

while category **Plugins** includes the following repostiories:

* [Elastos.Trinity.Plugins.Dialog](https://github.com/elastos/Elastos.Trinity.Plugins.Dialog)
* [Elastos.Trinity.Plugins.Dialog](https://github.com/elastos/Elastos.Trinity.Plugins.Dialog)
* [Elastos.Trinity.Plugins.Vibration](https://github.com/elastos/Elastos.Trinity.Plugins.Vibration)
* [Elastos.Trinity.Plugins.Camera](https://github.com/elastos/Elastos.Trinity.Plugins.Camera)
* [Elastos.Trinity.Plugins.Whitelist](https://github.com/elastos/Elastos.Trinity.Plugins.Whitelist)
* [Elastos.Trinity.Plugins.Device](https://github.com/elastos/Elastos.Trinity.Plugins.Device)
* [Elastos.Trinity.Plugins.Statusbar](https://github.com/elastos/Elastos.Trinity.Plugins.Statusbar)
* [Elastos.Trinity.Plugins.QRCode](https://github.com/elastos/Elastos.Trinity.Plugins.QRCode)
* [Elastos.Trinity.Plugins.Media](https://github.com/elastos/Elastos.Trinity.Plugins.Media)
* [Elastos.Trinity.Plugins.File](https://github.com/elastos/Elastos.Trinity.Plugins.File)
* [Elastos.Trinity.Plugins.SplashScreen](https://github.com/elastos/Elastos.Trinity.Plugins.SplashScreen)
* [Elastos.Trinity.Plugins.MediaCapture](https://github.com/elastos/Elastos.Trinity.Plugins.MediaCapture)
* [Elastos.Trinity.Plugins.ScreenOrientation](https://github.com/elastos/Elastos.Trinity.Plugins.ScreenOrientation)
* [Elastos.Trinity.Plugins.InappBrowser](https://github.com/elastos/Elastos.Trinity.Plugins.InappBrowser)
* [Elastos.Trinity.Plugins.BatteryStatus](https://github.com/elastos/Elastos.Trinity.Plugins.BatteryStatus)
* [Elastos.Trinity.Plugins.NetWorkInformation](https://github.com/elastos/Elastos.Trinity.Plugins.NetWorkInformation)
* [Elastos.Trinity.Plugins.Runtime](https://github.com/elastos/Elastos.Trinity.Plugins.Runtime)

TL;DR
-----

To clone current project with submodules, type:

```bash
git clone --recurse-submodules -b dev -j8 git@github.com:elastos/Elastos.Trinity.git
```

To update submodules with the lastest changes, type:

```bash
git submodule update --rebase --remote
```

And then use git add, commit and push to submit your changes to current project.
