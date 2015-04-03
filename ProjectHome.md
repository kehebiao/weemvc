**WeeMVC 是一种面向 Flash IDE 的、简洁的 ActionScript 快速开发框架。**


适用场景：

在使用 FLASH IDE 开发强交互、视觉导向项目的时候；

新手入门开发的时候；

快速开发的时候。


<font color='#ff0000'><b>重要更新</b></font>

**2011-06-15 AS3 版本框架兼用 Flex SDK。**

2010-08-22 同步 AS2 框架到当前版本。更新 demos。

2009-05-11 新增 model 与 view 的数据绑定。即：不通过 controller 即可将 model 的数据专递到 view。


---


**缘起**

虽然在ActionScript领域优秀的框架数不胜数，最常见的如 PureMVC 、Cairngorm 等等，都提供了接近完美的 MVC 开发解决方案。但是我觉得有时候使用这些 NB 的框架反而不太合适，比如以下情况：

  1. 在使用 FLASH IDE 开发较小型项目的时候；
  1. 新手入门开发的时候；
  1. 快速开发的时候。


虽然 PureMVC 对 FLASH 的支持也很不错，但是个人觉得在使用 FLASH 开发的时候，很多都是一些不大的项目，所以用这个就有点不太合适，有点大才小用的感觉。Cairngorm 在这点上做得不错，但是目前对 FLASH 的支持却又不怎么好。

当然有很多朋友会说，在开发较小的项目的时候不用框架会更好，代码量少，编译的 swf 重量轻。我个人认为，这个可以取一个权衡：用框架，那么代码的可扩展性、可维护性和代码可复用性都将大大增加，不好的地方就是增加了对此框架的学习成本和应用成本。

基于以上的考虑，我在参考了 PureMVC 和 Cairngorm 之后，根据自己的理解写了这个超级微型的框架，开发此框架的目的主要有以下几点：

  * 超级微型，简洁、简单，上手快，适合新手学习和开发小型项目；
  * 整合 PureMVC 与 Cairngorm 的优点进行设计；
  * FLASH 友好设计，对于 FLASH 的相关小型项目开发效率较高；
  * 在解耦上做了优化处理，使得 model 和 view 复用更容易。


项目主页：http://weemvc.org

SVN：http://weemvc.googlecode.com/svn/trunk/


**示例**

FlashCS3 V1.2 之后版本 demo：http://weemvc.googlecode.com/files/FlashCS3_V1.2.rar

Flash8 版本 demo：http://code.google.com/p/weemvc/source/browse/#svn/trunk/examples/Flash8

[![](http://weemvc.googlecode.com/files/weemvc.jpg)](http://www.weemvc.org)