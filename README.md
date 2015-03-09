# iOS 开发面试问题

受 [Front end Developer Interview Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions) 启发，制作了这份 iOS 面试问题列表。

面试 iOS 开发时，切入点很重要，不同的切入点会导致不同的结果，没有找到合适的切入点也无法对应聘者有一个全面的了解。所以这份面试问题列表更多的是提供方向，没有固定的答案，而且可以根据应聘者的回应引出更多有意思深层次的讨论。

## 一般性问题
* 最近这两天你有学到什么知识/技能么？
* 最近有做过比较酷或者比较有挑战的项目么？
* 最近看过的书/文章有哪些？
* 为什么要学习编程，编程对你而言的乐趣在哪儿？
* 有没有在 Github 上发布过开源代码，参与过开源项目？
* 你最近遇到过的一个技术挑战是什么？怎么解决的？
* 开发常用的工具有哪些？
* 熟悉 CocoaPods 么？能大概讲一下工作原理么？
* 最常用的版本控制工具是什么，能大概讲讲原理么？
* 今年你最想掌握的一门技术是什么？为什么？目前已经做到了哪个程度？
* 你一般是怎么用 Instruments 的？
* 你一般是如何调试 Bug 的？
* 你在你的项目中用到了哪些设计模式？
* 如何实现单例，单例会有什么弊端？
* iOS 是如何管理内存的？

## 知识性问题
* 什么是响应链，它是怎么工作的？
* iOS Extension 是什么？能列举几个常用的 Extension 么？
* 如何把一个包含自定义对象的数组序列化到磁盘？
* Apple Pay 是什么？它的大概工作流程是怎样的？
* iOS 的沙盒目录结构是怎样的？ App Bundle 里面都有什么？
* iOS 的签名机制大概是怎样的？
* iOS 7的多任务添加了哪两个新的 API? 各自的使用场景是什么？
* Objective-C 的 `class` 是如何实现的？`Selector` 是如何被转化为 C 语言的函数的？
* `UIScrollView` 大概是如何实现的，它是如何捕捉、响应手势的？
* Objective-C 如何对已有的方法，添加自己的功能代码以实现类似记录日志这样的功能？
* `+load` 和 `+initialize` 的区别是什么？
* 如何让 Category 支持属性？
* `NSOperation` 相比于 GCD 有哪些优势？
* `strong` / `weak` / `unsafe_unretained` 的区别？
* `UIView` 和 `CALayer` 之间的关系？
* 什么时候会发生「隐式动画」？
* 如何处理异步的网络请求？
* `frame` 和 `bounds` 的区别是什么？
* 如何把一张大图缩小为1/4大小的缩略图？
* 一个 App 会处于哪些状态？
* Push Notification 是如何工作的？
* 什么是 Runloop？
* Toll-Free Bridging 是什么？什么情况下会使用？
* 当系统出现内存警告时会发生什么？

## 经验类问题
* 为什么 `UIScrollView` 的滚动会导致 `NSTimer` 失效？
* 为什么当 Core Animation 完成时，layer 又会恢复到原先的状态？
* 你会如何存储用户的一些敏感信息，如登录的 token。
* 有用过一些开源组件吧，能简单说几个么，大概说说它们的使用场景实现。
* 什么时候会发生 `EXC BAD ACCESS` 异常？
* 什么时候会使用 Core Graphics，有什么注意事项么？
* NSNotification 和 KVO 的使用场景？
* 使用 Block 时需要注意哪些问题？
* `performSelector:withObject:afterDelay:` 内部大概是怎么实现的，有什么注意事项么？

## 综合类问题
* 如何创建一个可以无限滚动并且支持自动定时滚动的 SlideView？
* 如何创建一个进度条？

## 参考

* http://way2ios.com/development/ios-development-2/iphone-interview-question-answers/
* https://blackpixel.com/writing/2013/04/interview-questions-for-ios-and-mac-developers-1.html
* https://github.com/CameronBanga/iOS-Developer-and-Designer-Interview-Questions
