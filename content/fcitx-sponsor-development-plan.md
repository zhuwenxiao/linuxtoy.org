Title: Fcitx 有偿开发资助计划
Date: 2012-07-21 11:07
Author: liangsuilong
Category: Apps
Tags: Fcitx, Qt, sponsor
Slug: fcitx-sponsor-development-plan

Weng Xuetian 童鞋正式公布了 Fcitx 有偿开发资助计划。

作者原文：<https://www.csslayer.info/wordpress/fcitx-dev/fcitx-needs-you-again/>

前段时间并没有时间，估计申请成为 GSoC
的项目也无望，现在将会有一些时间，如果对 Fcitx
开发有兴趣的，可以申请以下任务的开发。

按照Feature的完成算，我个人会提供一定的资金，虽然资金并不算多，但也就是表示下我的心意。奖励的多寡按照我内心的难度排序。

无论你开发了以下的哪个 Feature，不必承担这个 Task
之后的维护，当然如果你乐意加入长期的开发，我表示欢迎（当然……奖励仅此一次）。

下面会列出相关的任务，以及需要的技能。如果纯粹的什么都不了解，我不希望你来给我发信，毕竟还有很多不需要编程技能的任务，例如
Fcitx 其他语言的翻译，Wiki 的维护。

1、Mac 移植 （当然最好你有 Mac 环境，了解 Mac
的输入法开发大概是不可能的，那么至少了解
Objective-C），800￥，完成到可以使用，界面无需支持皮肤功能。

2*、GNOME 集成 （Glib，Gtk 的开发），400￥，完成 gnome-control-center 和
gnome-settings-daemon 的 patch。

**3*、基于图形界面的工具（Qt
优先，语言不限，但你最好别找忒冷门语言的）**

**3.1 码表管理，管理码表的词库**  
**3.2 已有附加组件的配置文件编辑，包括**  
**双拼方案，快速输入，拼音符号，标点**

**以上两项每项 200￥，可分别参与。（By kevinchou）**

4、Maliit 支持 （需要 Qt，最好了解 QDBus）
600￥，要求的完成程度，完全能使用。

5*、Sunpinyin 的多词库支持（这个准确来说不是 Fcitx
的项目，但是我也表示赞助一下……），需要技能 sqlite，c++，qt
优先。500￥，要求支持多词库，并且界面也完整。

6*、将 fcitx 的 dbus 移植一份 private dbus server，但依然保持支持和系统
dbus 的通信，采用的方式无论是多进程还是单进程都无所谓，即使使用
dbus-launch 都可以。要求是，Fcitx 退出时完成退出，让 im module 可以通过
private dbus server 和 Fcitx 通信。200￥

另外，标注有 *
的项，表示我脑中已经有了至少一种如何实现以及相关细节的方式。

以上条目可能不断增加，并且在完成前长期有效。如果我自己有时间，我不保证我自己不会去实现（当然……我是不会请我自己吃相应的
RMB 的饭的 XD ）

以上所有项目，都要求在github进行开发，我会尽我可能 review
code，如果有需要 fcitx 主程序扩展的部分我也会提供帮助，所有代码的
License（除了 Sunpinyin 的之外，那个需要按照 Sunpinyin 的 License
发布）需要按照 GPLv2+ 发布。

较长的讨论我希望在
[fcitx-dev.googlegroups.com](fcitx-dev.googlegroups.com)
上进行。另外补充是，每项仅限一人，这是为了效率，如果你现在不懂你以后也会懂的。

以上任务视完成情况，我还会提供额外原始之外的 0～50% 的附加。

关于我为什么要采用这样的方式，准确说法就是我个人能力是绝对有限的，如果你把它当作
Fcitx 自己的 GSoC 也无可厚非，我愿意为 Fcitx 付出这些。

另外对于那些潜在的受众，列出一些可以分享的任务也有助于回答“我应该从哪开始”这样的问题。

我的联系方式： wengxt  AT gmail DOT com

P.S.

以下是无聊的杂谈。当然首先我担心的是没有人
Care，不过在过去的一小段时间过去之后似乎这个担心是多余的。这里并没有任何大义的名分，说到底我只有两句话，“我时间不够！我需要人手！”。采取的手段也许你们并不认同，不过单从效果上来说如果能达到受到关注这个目的，我也满足了。

即使达到我目标的手段其实对参与到这个活动中的人有帮助，那么有帮助的目的也是为了吸引人来参与，这样想就好了。如果要问我为什么为它进行投入，其实也没什么特别的理由，证明自己和对现实进行反抗而已。自私才是进步的源泉。

全文完。

**结语：有时候呢，土壕也会是一个好人。。。**

<div>

</div>
