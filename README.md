AndroidCommon
==
一个简单的开源Android工具类库，提供许多常用的类帮助我们开发程序。

These are the Android Common Utils.

|Class|Introduction|
| ------ | ------------ |
|[AnimatorUtils][1]|Animation Unility Class|
|[AppUtils][2]|App Unility Class|
|[ArrayUtils][3]|Array Unility Class|
|[AssetsUtils][4]|Assets Unility Class|
|[BASE64Utils][5]|Base64 Unility Class|
|[BitmapUtils][6]|Bitmap Unility Class|
|[BlurUtils][7]|Blur Unility Class|
|[ByteUtils][8]|Byte Unility Class|
|[CalendarUtils][9]|Calendar Unility Class|
|[ClipboardUtils][10]|Clipboard Unility Class|
|[CollectionUtils][11]|Collection Unility Class|
|[CommonUtils][12]|Common Unility Class|
|[CpuUtils][13]|Cpu Unility Class|
|[DeviceUtils][14]|Device Unility Class|
|[DisplayUtils][15]|Display Unility Class|
|[FileUtils][16]|File Unility Class|
|[FragmentUtils][17]|Fragment Unility Class|
|[HandlerUtils][18]|Handler Unility Class|
|[IOUtils][19]|IO Unility Class|
|[ImageUtils][20]|Image Unility Class|
|[InputMethodUtils][21]|InputMethod Unility Class|
|[IntentUtils][22]|Intent Unility Class|
|[JsonUtils][23]|Json Unility Class|
|[LogUtils][24]|Log Unility Class|
|[MD5Utils][25]|Md5 Unility Class|
|[MapUtils][26]|Map Unility Class|
|[MemoryUtils][27]|Memory Unility Class|
|[NetworkUtils][28]|Network Unility Class|
|[NumberUtils][29]|Number Unility Class|
|[ObjectUtils][30]|Object Unility Class|
|[PackageUtils][31]|Package Unility Class|
|[PropertyUtils][32]|Property Unility Class|
|[RandomUtils][33]|Random Unility Class|
|[ResourceUtils][34]|Resource Unility Class|
|[SHA1Utils][35]|Sha1 Unility Class|
|[SerializableUtils][36]|Serializable Unility Class|
|[SharedPreferencesUtils][37]|SharedPreferences Unility Class|
|[ShellUtils][38]|Shell Unility Class|
|[StringUtils][39]|String Unility Class|
|[SystemUtils][40]|System Unility Class|
|[TelephonyUtils][41]|Telephony Unility Class|
|[ThreadUtils][42]|Thread Unility Class|
|[TimeUtils][43]|Time Unility Class|
|[ToastUtils][44]|Toast Unility Class|
|[UrlUtils][45]|Url Unility Class|
|[VibratorUtils][46]|Vibrator Unility Class|
|[ViewUtils][47]|View Unility Class|

Permission
--

```xml
<uses-permission android:name="android.permission.INTERNET" />
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
<uses-permission android:name="android.permission.READ_PHONE_STATE" />
<uses-permission android:name="android.permission.VIBRATE" />
<uses-permission android:name="android.permission.SYSTEM_ALERT_WINDOW" />
```

Proguard
--

``` xml
-keep class com.wx.android.common.** { *; }
-keepclassmembers class com.wx.android.common.** { *; }
-dontwarn com.wx.android.common.**
```

Setup
--
* Download the project from [GitHub](https://github.com/venshine/AndroidCommon.git)
* Import it to your Eclipse workspace or IntelliJ IDEA project
* Set your project properties, then add a android project library, and select AndroidCommon

Usage
--
##### Gradle:
```groovy
compile 'com.wx.android.common:common:1.0.1'
```

Author
--
* Email：venshine.cn@gmail.com

License
--
    Copyright (C) 2015 venshine.cn@gmail.com

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
    http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


[1]: common/src/main/java/com/wx/android/common/util/AnimatorUtils.java
[2]: common/src/main/java/com/wx/android/common/util/AppUtils.java
[3]: common/src/main/java/com/wx/android/common/util/ArrayUtils.java
[4]: common/src/main/java/com/wx/android/common/util/AssetsUtils.java
[5]: common/src/main/java/com/wx/android/common/util/BASE64Utils.java
[6]: common/src/main/java/com/wx/android/common/util/BitmapUtils.java
[7]: common/src/main/java/com/wx/android/common/util/BlurUtils.java
[8]: common/src/main/java/com/wx/android/common/util/ByteUtils.java
[9]: common/src/main/java/com/wx/android/common/util/CalendarUtils.java
[10]: common/src/main/java/com/wx/android/common/util/ClipboardUtils.java
[11]: common/src/main/java/com/wx/android/common/util/CollectionUtils.java
[12]: common/src/main/java/com/wx/android/common/util/CommonUtils.java
[13]: common/src/main/java/com/wx/android/common/util/CpuUtils.java
[14]: common/src/main/java/com/wx/android/common/util/DeviceUtils.java
[15]: common/src/main/java/com/wx/android/common/util/DisplayUtils.java
[16]: common/src/main/java/com/wx/android/common/util/FileUtils.java
[17]: common/src/main/java/com/wx/android/common/util/FragmentUtils.java
[18]: common/src/main/java/com/wx/android/common/util/HandlerUtils.java
[19]: common/src/main/java/com/wx/android/common/util/IOUtils.java
[20]: common/src/main/java/com/wx/android/common/util/ImageUtils.java
[21]: common/src/main/java/com/wx/android/common/util/InputMethodUtils.java
[22]: common/src/main/java/com/wx/android/common/util/IntentUtils.java
[23]: common/src/main/java/com/wx/android/common/util/JsonUtils.java
[24]: common/src/main/java/com/wx/android/common/util/LogUtils.java
[25]: common/src/main/java/com/wx/android/common/util/MD5Utils.java
[26]: common/src/main/java/com/wx/android/common/util/MapUtils.java
[27]: common/src/main/java/com/wx/android/common/util/MemoryUtils.java
[28]: common/src/main/java/com/wx/android/common/util/NetworkUtils.java
[29]: common/src/main/java/com/wx/android/common/util/NumberUtils.java
[30]: common/src/main/java/com/wx/android/common/util/ObjectUtils.java
[31]: common/src/main/java/com/wx/android/common/util/PackageUtils.java
[32]: common/src/main/java/com/wx/android/common/util/PropertyUtils.java
[33]: common/src/main/java/com/wx/android/common/util/RandomUtils.java
[34]: common/src/main/java/com/wx/android/common/util/ResourceUtils.java
[35]: common/src/main/java/com/wx/android/common/util/SHA1Utils.java
[36]: common/src/main/java/com/wx/android/common/util/SerializableUtils.java
[37]: common/src/main/java/com/wx/android/common/util/SharedPreferencesUtils.java
[38]: common/src/main/java/com/wx/android/common/util/ShellUtils.java
[39]: common/src/main/java/com/wx/android/common/util/StringUtils.java
[40]: common/src/main/java/com/wx/android/common/util/SystemUtils.java
[41]: common/src/main/java/com/wx/android/common/util/TelephonyUtils.java
[42]: common/src/main/java/com/wx/android/common/util/ThreadUtils.java
[43]: common/src/main/java/com/wx/android/common/util/TimeUtils.java
[44]: common/src/main/java/com/wx/android/common/util/ToastUtils.java
[45]: common/src/main/java/com/wx/android/common/util/UrlUtils.java
[46]: common/src/main/java/com/wx/android/common/util/VibratorUtils.java
[47]: common/src/main/java/com/wx/android/common/util/ViewUtils.java

