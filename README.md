# LuCI Network Speed Test

### Screenshots

![speedtest](.img/speedtest.png "speedtest")

### How to install

#### Prerequisites

- Requires curl and ca-certificates
- The app can download the official Ookla Speedtest CLI from within the UI, storing it at /usr/libexec/netspeedtest/speedtest

#### Installation

1. Goto ~~releases~~ https://fantastic-packages.github.io/packages/
2. Download the latest version of the ipk
3. Login to the router and go to System --> Software
4. Upload and install the ipk
5. Reboot if the app is not automatically added in the page
6. Go to Network --> SpeedTest

### Build

- Compile from the OpenWrt SDK

```
# Example for x86_64
# After configuring feeds and selecting LuCI -> Applications -> luci-app-netspeedtest
make package/luci-app-netspeedtest/compile V=99
```

### License

- This project is licensed under the MIT License
