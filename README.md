# Ilhan

# Android Bluetooth Project
The android library that provides a simple and customizable Bluetooth detector.

How does it look like?
--------

Getting started
--------
The library is available on `jcenter()`. Just add these lines in your `build.gradle`:

```groovy
dependencies {
    implementation 'androidx.appcompat:appcompat:1.4.2'
    implementation 'com.google.android.material:material:1.6.0'
}
```
Add AndroidManifest.xml for Bluetooth
```groovy
    <uses-permission android:name="android.permission.BLUETOOTH_CONNECT" />
    <uses-permission android:name="android.permission.BLUETOOTH_ADMIN" />
    <uses-permission android:name="android.permission.BLUETOOTH_ADVERTISE" />
    <uses-permission android:name="android.permission.BLUETOOTH_SCAN" />
    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />

```
Add AndroidManifest.xml for Internet
```groovy
    <uses-permission android:name="android.permission.INTERNET" />
```
