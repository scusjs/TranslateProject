专访Ubuntu Tweak的作者周鼎
================================================================================
[Ubuntu tweak][1]是一款知名度很高的应用程序软件，Ubuntu用户可以用它来调整系统的性能、功能等各个细节。项目的创始人，周鼎又名Tualatrix Chou，正与我们分享Ubuntu Tweak的特性、使用感觉以及它跟Canonical的关系，并且勾勒了项目的未来计划蓝图。享受吧！

**你什么时候开始使用linux的，并基于什么使你决定开发Ubuntu tweak？**

我开始使用Linux是在2006年底，那时刚开始我的大学生活。当时我正在学C编程语言，一个朋友建议说要学习编程的话Linux是最好的平台环境，所以我就开始了我的Linux生涯，是从Fedora Core 6开始的。但用了仅仅只有一周的时间，我就换成Ubuntu 6.10,因为Ubuntu在中国有更好的社区，也有更好更快的源库/镜像。我立马就爱上了Ubuntu，就一周时间，就从Windows环境完全切换到Ubuntu环境。

在苦乐参半的半年使用时间后，我意识到Ubuntu对中国用户来说不是太友好，因为全新安装系统后，用户必须得自己配置字体、输入法以及其它很多很多设置。所以，我决定开发出一款应用程序来帮助新手，让他们很简单的就可以对系统做相应配置。

因此在2007年7月，我就开始开发Ubuntu Tweak,刚开始的时候，仅仅提供了汉语版本的，但很快就考虑了Ubuntu Tweak的国际版本，并且在2007年9月份就发布了首个国际版本。

**Ubuntu tweak已经是非常成功的项目了。很多Ubutu用户用它来调整系统的性能、功能等各个细节。能给我们谈论下Ubuntu Tweak能做些什么吗？**

![](http://180016988.r.cdn77.net/wp-content/uploads/2012/03/tualatrix1.jpg)

Ubuntu Tweak可以用来切换桌面图表的显示方式、设置字体、启用/禁用多用户切换功能以及登陆的标识（logo）等等。

在最新的Ubuntu Tweak 0.6版本中，你也可以调整你的Unity桌面以及关机功能。

你也能使用Ubuntu Tweak来清理系统的垃圾以释放空间和使系统保持干净。

**Canonical在他们的默认发布源中不考虑加入Ubuntu Tweak。这意味着什么？这对那些没有经验，但又想要使用你的应用程序来调整他们的系统的用户来说，存在某些风险吗？**

对的。因为在以前的Ubuntu Tweak发布版本中，为流行的PPA都提供了可用源，但我不能保证所有的PPA都是安全的，所以Ubuntu Tweak会有一些安全风险。

如你们所见，从0.6版本后Ubuntu Tweak就已经从源中心（Source Center）移除了，但请不要混淆“Ubuntu默认包含”和“加入源仓库”这两个概念。Ubuntu Tweak首先应该要被加入通用资源仓库，然后才能被Ubuntu默认包含。

从错误报告和用户反馈来看，Ubuntu Tweak已经比老版本更加稳定及更易使用。

**你有收到来自Canonical和Ubuntu开发者的支持或有跟他们合作（不论什么）的事项吗，是哪些方面的？**

当然，我得到Canonical公司的一些帮助，他们试着帮我把Ubuntu Tweak放入源仓库。这工作现在仍然在进行。

也得到社区的很多热心帮助，他们帮我翻译、设计、测试、报告错误，甚至提交代码分支。

**开发Ubuntu Tweak的有多少人？**

如果你说的是“代码开发者”，就仅仅我一个，但我们有很多设计人员：logo是M.Sharp设计的，Kevin Chou帮助设计了Ubuntu Tweak的用户界面(UI)原型，他就是0.6版本的样子。现在Jeonkwan Chan正在帮我重新美化用户界面,将会用在0.7版本上。任何人，只要愿意就可以加入到Ubuntu Tweak的开发中来:)

**在Ubuntu11.04版本中当Unity出现时，许多Ubuntu用户抱怨其可配置性不好，您对这个怎么看的？这个特殊的桌面环境能有些什么多适用性的配置能力呢？**

我喜欢桌面系统的可配置高适应性，这是Linux系统的优点，不是吗？

例如，我不喜欢Unity Launcher的自动隐藏功能，所以我设置让他不会隐藏。

事实上，Unity是可配置的，仅仅是它缺少CompizConfig设置管理器，所以你不能把Unity Launcher放到桌面底部或右面，这对左撇子来说很不友好。哈哈，开玩笑的。

如大家所见，Ubuntu 12.04已经增加了隐藏/显示切换功能，Launcher的大小在系统设置中也可以自定义设置。我认为Unity将会有更多的可配置功能。

**一般来说，你认为Canonical公司开发Unity桌面环境是正确的决策吗？他们与 Gnome开发者之间有合作争议，这有些是不可避免的吗？**

是的，对于Canonical公司来说，我觉得他们的决策很正确。回顾三年前，当Ubuntu首次引入基于GNOME Panel的Indicator，它的设计就要比原来直接的GNOME Panel小程序更优雅。但Canonical开发者和GNOME开发者之间合作有些问题，因为他们从来没有着眼于GNOME。直到GNOME 3的面世，情况才有所好转，它的GNOME Shell已经从GNOME Panel移出来了，并且GNOME Shell的面板已经和上面提到的Indicator用的是同一套设计方式。如果他们之间共用相同的API的话，桌面Linux应该会更好用。

所以来自于公司、社区、GNOME桌面等的不同的关于用户界面的见解，综合起来最终就形成了Unity。

我认为这是好事。至少，到目前为至，比起GNOME Shell来说，我更喜欢Unity。

**虽然你正在开发的是一款Ubuntu系统专用的程序，但我假设你为了使用更多的高级用户功能，会使用其它的发行版本。你会选择哪些发行版本呢？为什么？**

当然，我已经玩过Fedora,、Arch、 OpenSUSE，特别是Gentoo，我已经整整使用了一年。它是我第二喜欢的Linux发行系统，因为它拥有一个最先进的包管理系统。

但现在我仅仅只会使用Ubuntu的桌面版本和服务版，也使用Mac OS X，很多的设计灵感就来自于它 :)

**Ubuntu Tweak能调整调整做几个分支或者改变一点点，以便能在其它的 linux 发行版本比如 Fedora、OpenSue 或者 Debian 上使用吗？有做成统一的一个叫做“Linux Tweak”的应用程序，用户不管选择什么样的发布版本或桌面环境都可以用这种想法吗？不知道是否可行？**

可以的，要让 Ubuntu Tweak 在其它发行版本中运行非常容易。它是模块化的，很轻松的就可以重构(hack)。

2008年的时候，我就发布了一版 Fedora 的“Ubuntu Tweak for Fedora”，但最终我放弃维护这个版本了，因为我主要关注Ubuntu版本的，所以没有那么多精力。

**那Ubuntu Tweak的未来计划是什么？也许Canonical公司会内嵌进系统，然后把它做为发布版本默认的工具或者他们会基于他们自己的系统调整工具来使用它。您认为呢？您的下一步计划会是什么的呢？**

Ubuntu Tweak的未来当然会一片光明。哈哈。

我已经开始实现把Ubuntu Tweak加入软件中心这个工作了。如果用户能从软件中心直接安装Ubuntu Tweak，它会更容易。

现在我正在开发0.7版本的，它将更美观，并且与Unity桌面的集成度更好，也加入了一些很有用的新功能。我想使Ubuntu Tweak在 Unity 桌面环境下尽可能的发挥作用。

跟随着Ubuntu 12.04的发布，我也计划发布新的版本，希望大家喜欢 :)

还有一件事要透露下，我已经加入Canonical北京公司，负责处理OEM的事情。虽然 Ubuntu Tweak 仍是一个个人项目，我还没有参与进Ubuntu的开发任务，但有可能话我会试着加入开发团队 :)

**太伟大了！谢谢Tualatrix。**

--------------------------------------------------------------------------------

via: http://www.unixmen.com/interview-with-ding-zhou-of-ubuntu-tweak/

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创翻译，[Linux中国](http://linux.cn/) 荣誉推出

译者：[runningwater](https://github.com/runningwater) 校对：[校对者ID](https://github.com/校对者ID)

[1]:http://ubuntu-tweak.com/