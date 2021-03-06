Elastos.Carrier.Demo.Remoter
============================

Carrier Demo is a demo application to show what can do via elastos carrier network. It shows you can use this app to control each other even inside NAT traversal.

## Features:

The items for remote control currently includes:

- Turn on/off torch (or light)
- Turn on/off ringtone
- Increase/Decrease ringtone volume
- Turn on/off camera video

## Build from source

You should get source code from the following repository on github.com:

```shell
$ git clone https://github.com/elastos/Elastos.NET.Carrier.Demo.Remoter.iOS.git CarrierDemo
$ cd CarrierDemo
```
Then you can use Apple Xcode to build it.

## Build dependencies

The dependencies to CarrierDemo have been outlined below:

- ElastosCarrier.framework
- ffmpeg
- QRCode

Before to use Xcode to build distributions, run the following commands to install all needed dependencies:

```shell
$ sudo gem install cocoapods
$ pod install
```

Notices: If some issues happen, try fix it with command below:

```shell
$ pod update
```

Finally, use **Xcode** to open project file **CarrierDemo.xcworkspace** or directly run the following command to open it so as to build the whole workspace:

```shell
$ open -a Xcode.app CarrierDemo.xcworkspace
```

## Deploy && Run

Run on Phone with iOS version 9.0 or higher.

## License

GPLv3
