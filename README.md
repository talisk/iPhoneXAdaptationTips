# iPhoneXAdaptationTips
The latest iOS device, iPhone X's adaptation tips

**Now, the iPhone X Simulator has integrated into the Xcode 9 GM. You can download Xcode 9 GM at https://developer.apple.com**

## Adaptation Guides

[iOS Human Interface Guidlines - iPhone X](https://developer.apple.com/ios/human-interface-guidelines/overview/iphone-x/)

## Tips

### Q: App cannot fills in the blank below UITabBar and the blank above the UINavigationBar

Solution:

You should add a LaunchImage in the Images.xcassets for iPhone X. The new LaunchImage's size is 1125px * 2436px.

The Images.xcassets created by old version Xcode doesn't include the iPhone X version Image Set, you should create a new Image Set to replace the old one.

Before adding Launch Image, the UIViewController instance's view size is 375pt * 667pt.

## Contributions

Welcome contribute to the repository. Raise issues if you have any questions.
