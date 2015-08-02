# 目录

[注意事项](#zhiYiShiXiang)

[资源](#ziYuan)

[第三方库](#disanfang)

<h1 id="zhiYiShiXiang">注意事项</h1>


1. Xcode7、swift2.0 (虽然现在还是测试版本，但是很快就发布正式版本了。所以我们使用这样的版本来开发，对以后有利)。
2. 用Github来做我们的代码管理，各自都要加入到Organizatin中来。尽快来测试一下，你是否能直接向代码库中提交代码。那么Git的基本使用也是必须要知道的。
3. 使用Cocoapods来添加第三方库，所以你要知道Cocoapods的基本使用方法。并且安装它。
4. 在项目的文件里会以每个人的名字的缩写来创建文件夹，目的是为了使每个人的代码放在一个地方，方便管理。
5. 同时为了避免出现命名的冲突，我们在创建类的时候添加自己名字的缩写例如`Yxl_ViewController.swift`。
6. 因为使用故事版来开发界面的话不利于我们代码版本的控制。解决的办法，我们用多故事版开发。在iOS9中加强了对故事版的团队开发使用。可以去看一下WWDC2015关于这部分的介绍。[小波汉化的关于这部分的视屏](http://www.hcxy.me/course/43)。在视频中所用到的代码应该可以在Xcode7中的文档中找到。
7. 我们现在只去开发 iPhone设备的App，所以在项目中我们把`Use Size Classes`去掉，选则iPhone。但是不去掉`Use auto Layout`。这样的目的是为了简单省事！
8.  数据库我之后会和凯凯去设计一下。
10. 美工美女先了解下iOS下的图片都是怎么命名的（因为命名是有规则的），区分二倍图，三倍图是怎么回事。回头我会给你一些资料，快速入门一下。
11. 所有的一切就是要多沟通，虽然建立了一个讨论组可是觉得那样的交流并不好（有时会漏掉很多信息，原因就是大伙太活跃了）。建议发邮件或者是扣扣一对一的交流。除非是有必要大家一起交流的话，在讨论组里交流。
11.  不知道还需要写些什么，要等到任杰同学需求分析出来，具体分任务

<h2 id="ziYuan">资源</h2>
(你有什么好的资源都可以写在这里) 

1. [Swift2.0新特性](http://segmentfault.com/a/1190000002922232)

2. [讲解 Markdown](http://alfred-sun.github.io/blog/2015/01/10/markdown-syntax-documentation/)
3. [What's New in StoryBoards](http://www.hcxy.me/course/43)




<h2 id = "disanfang">第三方库</h2>
现在cocoapods好像和 Xcode7有点不兼容。我的cocoapods版本有点低，没有更新到最新的版本。回头更新到最新版本试试。


1. [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON)
2. [Alamofire](https://github.com/Alamofire/Alamofire)