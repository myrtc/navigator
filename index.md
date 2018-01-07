## 欢迎来到实时互联网技术大百科

这里汇集了实时通讯有关的众多资料

如果大家想体验下 Agora 的产品，以便对延时，清晰度，流畅度等等有个直观的认识，可以直接下载我们的应用

##### Agora Video Call(视频聊天类应用)
- iOS: [https://itunes.apple.com/cn/app/agora-video-call/id1080303824?mt=8](https://itunes.apple.com/cn/app/agora-video-call/id1080303824?mt=8)
- macOS: [https://itunes.apple.com/cn/app/agora-video-call/id1112106913?mt=12](https://itunes.apple.com/cn/app/agora-video-call/id1112106913?mt=12)
- Android: [http://android.myapp.com/myapp/detail.htm?apkName=io.agora.vcall](http://android.myapp.com/myapp/detail.htm?apkName=io.agora.vcall)
- Web: [https://webdemo.agora.io/videocall/](https://webdemo.agora.io/videocall/)
- Windows: [Zip Package](http://download.agora.io/avc/AgoraVideoCall_for_Windows_v2.0.0.201.zip)

##### Agora Live(视频直播类应用)
- iOS: [https://itunes.apple.com/cn/app/agora-live/id1116886856?mt=8](https://itunes.apple.com/cn/app/agora-live/id1116886856?mt=8)
- Android: [http://android.myapp.com/myapp/detail.htm?apkName=io.agora.vlive](http://android.myapp.com/myapp/detail.htm?apkName=io.agora.vlive)
- Windows: [Zip Package](http://download.agora.io/avc/AgoraLiveBroadcast_for_Windows_v2.0.0.201.zip)


### 开源项目

#### 媒体部分

##### 1) 简单上手类
```markdown
通过少许的步骤，展示如何集成 Agora RTC SDK 到一个简单的应用当中，
对于初次使用 Agora SDK 的开发者来说，这是一个容易上手的示例，我们提供了完整的源码。
```
###### 音频
|Platform|Language|   GitHub   |
|:------:|:------:|:-------------:|
|   iOS  |Swift|[https://github.com/AgoraIO/Agora-iOS-Voice-Tutorial-Swift-1to1](https://github.com/AgoraIO/Agora-iOS-Voice-Tutorial-Swift-1to1)|
| Android|Java|[https://github.com/AgoraIO/Agora-Android-Voice-Tutorial-1to1](https://github.com/AgoraIO/Agora-Android-Voice-Tutorial-1to1)|

###### 视频
|Platform|Language|   GitHub   |
|:------:|:------:|:-------------:|
|   iOS  |Swift|[https://github.com/AgoraIO/Agora-iOS-Tutorial-Swift-1to1](https://github.com/AgoraIO/Agora-iOS-Tutorial-Swift-1to1)|
|   iOS  |Objective-C|[https://github.com/AgoraIO/Agora-iOS-Tutorial-Objective-C-1to1](https://github.com/AgoraIO/Agora-iOS-Tutorial-Objective-C-1to1)|
| Android|Java|[https://github.com/AgoraIO/Agora-Android-Tutorial-1to1](https://github.com/AgoraIO/Agora-Android-Tutorial-1to1)|
| Android|Kotlin|[https://github.com/AgoraIO/Agora-Android-Tutorial-Kotlin-1to1](https://github.com/AgoraIO/Agora-Android-Tutorial-Kotlin-1to1)|
|    Web |JavaScript|[https://github.com/AgoraIO/Agora-Web-Tutorial-1to1](https://github.com/AgoraIO/Agora-Web-Tutorial-1to1)|
| Windows| C++  |[https://github.com/AgoraIO/Agora-Windows-Tutorial-1to1](https://github.com/AgoraIO/Agora-Windows-Tutorial-1to1)|
|  macOS |Objective-C|[https://github.com/AgoraIO/Agora-macOS-Tutorial-Objective-C-1to1](https://github.com/AgoraIO/Agora-macOS-Tutorial-Objective-C-1to1)|

##### 2) 复杂场景类
```markdown
这部分示例代码稍微复杂点，提供了多人的演示，允许设置视频参数，频道内消息，
黑白滤镜，切换摄像头等等，另外还提供了多种视频界面切换(比如大小窗口，平铺窗口)。
Agora RTC SDK 轻松就可以完成这些复杂实用的功能。
```
###### 视频聊天(通话)
|Platform|Language|   GitHub   |
|:------:|:------:|:-------------:|
|   iOS  |Swift|[https://github.com/AgoraIO/OpenVideoCall-iOS](https://github.com/AgoraIO/OpenVideoCall-iOS)|
|   iOS  |Objective-C|[https://github.com/AgoraIO/OpenVideoCall-iOS-Objective-C](https://github.com/AgoraIO/OpenVideoCall-iOS-Objective-C)|
| Android|Java|[https://github.com/AgoraIO/OpenVideoCall-Android](https://github.com/AgoraIO/OpenVideoCall-Android)|
| Windows| C++  |[https://github.com/AgoraIO/OpenVideoCall-Windows](https://github.com/AgoraIO/OpenVideoCall-Windows)|
|  macOS |Swift |[https://github.com/AgoraIO/OpenVideoCall-macOS](https://github.com/AgoraIO/OpenVideoCall-macOS)|

###### 视频直播(直播)
|Platform|Language|   GitHub   |
|:------:|:------:|:-------------:|
|   iOS  |Swift|[https://github.com/AgoraIO/OpenLive-iOS](https://github.com/AgoraIO/OpenLive-iOS)|
|   iOS  |Objective-C|[https://github.com/AgoraIO/OpenLive-iOS-Objective-C](https://github.com/AgoraIO/OpenLive-iOS-Objective-C)|
| Android|Java|[https://github.com/AgoraIO/OpenLive-Android](https://github.com/AgoraIO/OpenLive-Android)|
| Windows| C++  |[https://github.com/AgoraIO/OpenLive-Windows](https://github.com/AgoraIO/OpenLive-Windows)|
|  macOS |Swift |[https://github.com/AgoraIO/OpenLive-macOS](https://github.com/AgoraIO/OpenLive-macOS)|

##### 3)特殊场景类
```markdown
开发者会有各种丰富多彩的想法，产生出多种需求，所以我们这里也提供了一些示例代码。
会不断增加，也欢迎更多的开发者贡献出自己的实现，可能还会收到神秘礼品哦。
```
###### 00 屏幕共享(很容易实现把整个屏幕内容共享给他人，也能包含声音哦)
|Platform|Language|   GitHub   |
|:------:|:------:|:-------------:|
|   iOS  |Swift|[https://github.com/AgoraIO/Agora-Screen-Sharing-iOS](https://github.com/AgoraIO/Agora-Screen-Sharing-iOS)|
| Android|Java|[https://github.com/AgoraIO/Agora-Screen-Sharing-Android](https://github.com/AgoraIO/Agora-Screen-Sharing-Android)|

###### 01 客户端推流(把音视频数据拷贝一份传给其他内容接收者，比如 CDN 或者存成本地文件)
|Platform|Language|   GitHub   |
|:------:|:------:|:-------------:|
|   iOS  |Swift|[https://github.com/AgoraIO/Agora-client-side-AV-capturing-for-streaming-iOS](https://github.com/AgoraIO/Agora-client-side-AV-capturing-for-streaming-iOS)|
| Android|Java|[https://github.com/AgoraIO/Agora-client-side-AV-capturing-for-streaming-Android](https://github.com/AgoraIO/Agora-client-side-AV-capturing-for-streaming-Android)|

###### 02 自定义视频数据源(由开发者提供视频数据给 Agora RTC SDK，玩法更多样)
|Platform|Language|   GitHub   |
|:------:|:------:|:-------------:|
|   iOS  |Swift|[https://github.com/AgoraIO/Agora-Video-Source-iOS](https://github.com/AgoraIO/Agora-Video-Source-iOS)|
| Android|Java|[https://github.com/AgoraIO/Agora-Video-Source-Android](https://github.com/AgoraIO/Agora-Video-Source-Android)|

###### 03 画中画模式(Android 8.0 支持的新特性，对视频类应用非常友好)
|Platform|Language|   GitHub   |
|:------:|:------:|:-------------:|
| Android|Java|[https://github.com/AgoraIO/Agora-Picture-in-Picture-Android](https://github.com/AgoraIO/Agora-Picture-in-Picture-Android)|

#### 信令部分

##### 1) 简单上手类
```markdown
通过少许的步骤，展示如何集成 Agora Signaling SDK 到一个简单的应用当中，
Agora Signaling SDK 提供消息的发送，接收，
容易实现点对点，群组等等面向场景的功能。
对于初次使用 Agora SDK 的开发者来说，这是一个容易上手的示例，我们提供了完整的源码。
```
|Platform|Language|   GitHub   |
|:------:|:------:|:-------------:|
|   iOS  |Swift|[https://github.com/AgoraIO/Agora-Signaling-Tutorial-iOS-Swift](https://github.com/AgoraIO/Agora-Signaling-Tutorial-iOS-Swift)|
| Android|Java|[https://github.com/AgoraIO/Agora-Signaling-Tutorial-Android](https://github.com/AgoraIO/Agora-Signaling-Tutorial-Android)|
|    Web |JavaScript|[https://github.com/AgoraIO/Agora-Signaling-Tutorial-Web](https://github.com/AgoraIO/Agora-Signaling-Tutorial-Web)|
| Windows| C++  |[https://github.com/AgoraIO/Agora-Signaling-Tutorial-Windows](https://github.com/AgoraIO/Agora-Signaling-Tutorial-Windows)|
|  macOS |Swift|[https://github.com/AgoraIO/Agora-Signaling-Tutorial-macOS-Swift](https://github.com/AgoraIO/Agora-Signaling-Tutorial-macOS-Swift)|
| Linux | C++ |[https://github.com/AgoraIO/Agora-Signaling-Tutorial-Linux](https://github.com/AgoraIO/Agora-Signaling-Tutorial-Linux)|
| Platform-independent | Java |[https://github.com/AgoraIO/Agora-Signaling-Tutorial-Java](https://github.com/AgoraIO/Agora-Signaling-Tutorial-Java)|
| Platform-independent | Python |[https://github.com/AgoraIO/Agora-Signaling-Tutorial-Python](https://github.com/AgoraIO/Agora-Signaling-Tutorial-Python)|

##### 2) 复杂场景类
```markdown
这部分示例代码稍微复杂点，只要对方在线，可以呼叫对方，建立一个视频通话，
这是一个典型的 Agora Signaling SDK 和 Agora RTC SDK 结合的示例。
```
|Platform|Language|   GitHub   |
|:------:|:------:|:-------------:|
|   iOS  |Objective-C|[https://github.com/AgoraIO/OpenDuo-iOS-Objective-C](https://github.com/AgoraIO/OpenDuo-iOS-Objective-C)|
| Android|Java|[https://github.com/AgoraIO/OpenDuo-Android](https://github.com/AgoraIO/OpenDuo-Android)|
|    Web |JavaScript|[https://github.com/AgoraIO/OpenDuo-Web](https://github.com/AgoraIO/OpenDuo-Web)|


### 动态密钥鉴权

建议计划上线的项目使用 [动态密钥鉴权](https://docs.agora.io/cn/2.0.2/product/Video/Product%20Overview/key?platform=All%20Platforms)，这是一个更为安全的用户身份验证方案，可以避免一些非法/故意破坏行为，详细使用参见前面的链接。动态密钥的生成算法已经 [开源](https://github.com/AgoraIO/AgoraDynamicKey/)，并且提供了主流编程语言的版本，欢迎大家来贡献更多的编程语言版本。

我们提供了动态密钥鉴权可一键部署的工程，可以很容易的部署在服务端做测试。

[https://github.com/AgoraIO/DynamicKeyServer-nodejs](https://github.com/AgoraIO/DynamicKeyServer-nodejs)


### 技术文章

- [https://www.agora.io/cn/blog/](https://www.agora.io/cn/blog/)
- [https://www.agora.io/en/blog/](https://www.agora.io/en/blog/)


### 联系我们

- 更多内容参见参见 [开发者中心](https://docs.agora.io/cn/)
- 如果在集成中遇到问题，你可以到 [开发者社区](https://dev.agora.io/cn/) 提问
- 如果有售前咨询问题，可以拨打 400 632 6626，或加入官方Q群 12742516 提问
- 如果需要售后技术支持，你可以在 [Agora Dashboard](https://dashboard.agora.io) 提交工单
