# Wireless-debugging-in-Android-11+
1. In Device:
```
Enable USB debugging
Enable Wireless debugging > click it > Pair device with pairing code
You see: [address:port](1) and [Pairing code](2)
```
2. In MacOs > open Terminal
```
cd $ANDROID_HOME
cd platform-tools 
adb pair 10.10.9.74:37205   (1)
Enter pairing code: 896946  (2)
Successfully paired to 10.10.9.74:37205 [guid=adb-8B6Y0U913-Zj8Omz]
```
More: https://developer.android.com/studio/command-line/adb
