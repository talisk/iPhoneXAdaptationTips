# iPhone X 适配指南
最新的iOS设备，iPhone X的适配指南。

[English](https://github.com/talisk/iPhoneXAdaptationTips/blob/master/README.md)

**现在，Xcode 9 GM版本已经集成了iPhone X的模拟器，你可以到https://developer.apple.com去下载Xcode 9 GM**

## 适配指引

[iOS Human Interface Guidlines - iPhone X](https://developer.apple.com/ios/human-interface-guidelines/overview/iphone-x/)

## 适配贴士

### 应用不能占满屏幕，顶部和底部均有黑边 

解决方案：

你应该在Images.xcassets中为iPhone X添加一个启动图，新的启动图尺寸为1125像素 * 2436像素，458ppi。

由老版本Xcode创建的Images.xcassets中没有iPhone X版本的Image Set，你应该手动创建一个新的Image Set来代替之前的。

在添加新的启动图之前，UIViewController实例的view的尺寸是375pt * 667pt。

## 贡献

欢迎大家为本适配指南提供贡献，有任何问题可以提issue进行讨论。
