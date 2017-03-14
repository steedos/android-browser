# CrosswalkDemo
A simple project showing how to embed Crosswalk into an Android application.

1、首先确认本机已安装Android sdk

2、在项目根目录下创建local.properties文件，在文件中输入sdk的路径，例如：
```
sdk.dir = /Users/chenzhipei/Library/Android/sdk/
```

3、通过以下命令打包成apk：

`./gradlew assembleRelease`

or

`./gradlew assembleDebug

More details here: [https://diego.org/2015/01/07/embedding-crosswalk-in-android-studio/](https://diego.org/2015/01/07/embedding-crosswalk-in-android-studio/)
