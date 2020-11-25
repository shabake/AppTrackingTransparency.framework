# AppTrackingTransparency.framework
解决framework not found AppTrackingTransparency


xcode12.0版本以下会找不到这个库文件而报错，

第一种方式就是升级Xcode到最新版本

第二种方式就是就下载这个库文件，将它拖入到你的工程中，再次编译就通过了

iOS开发 ios14系统广告标识idfa获取适配 AppTrackingTransparency.framework

下载地址：https://download.csdn.net/download/tianzhilan0/13076865

将下载后的frameowork放到指定的位置

真机 `/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk/System/Library/Frameworks/AppTrackingTransparency.framework`

模拟器 `/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator.sdk/System/Library/Frameworks/AppTrackingTransparency.framework`