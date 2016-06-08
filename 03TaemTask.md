## 小组信息
- 小组名称：03组 飞车组
- 组长：CapJack
- 组员：喵喵、王晟-Eric

----
## 本周认领任务清单
- 问题1 :说说自己可以用 Github 做些什么，不少于 6 条。
- 问题3 :用实例介绍如何使用 Pull Request 和 Merge 实现团队工作协同？
- 问题5 :通过 Github 的操作来说明工作区、暂存区、版本库之间的关系。

------
## 作业详情
- 问题1 :说说自己可以用 Github 做些什么，不少于 6 条。
> 答案：

因为我不是程序员，不会IT编程，所有的IT软件对我来说就是工具，我只管用。所以对我来说根据Github的几个特点，我觉得可以有以下应用。

###Github特点：
- 版本控制工具：我的理解是写东西可以管理前后修改的各个版本；
- 分布式：我的理解是方便协同工作，易于项目管理；

###Github应用：

**1. 写书**

- 写书最容易理解了，可以用Github轻松进行文档版本控制，协作修改及编辑，实现分布式共同写作。

**2. 用GitHub搭建博客、个人网站或者公司官网**

- 建立一个有自己域名的独立博客
- GitHub本身提供免费的托管服务，又提供了贴心的 Pages 功能，可以绑定你自己的域名，免费、高效、不限流量，做一个个人页面绰绰有余。
- Jekyll 的教程：借助于[http://jekyllbootstrap.com/]，可以在Github上快速搭建一个基于jekyll的博客系统。

**3. 记录健身打卡日志、工作日志、课程笔记等**

 - 用Github快速建立个repo，专门用来放健身打卡日志（文档，表单等都可以）、工作日志、课程笔记等，设置成公开，也方便大家来观察监督，方便领导查看工作进度，或者方便自己查阅笔记。
 - Eg: EveryDay body-build[https://github.com/hoosin/EveryDaySport]

**4. 项目管理**

- 充分发挥Github易于协同，便于管理各分支的特点，在一个期限较长的项目，比如我的Eternova创业项目，就可以用它来进行项目管理、跟踪，回顾，决策记录，经验沉淀。
- 资源：使用GitHub进行团队合作[http://link.zhihu.com/?target=http%3A//xiaocong.github.io/blog/2013/03/20/team-collaboration-with-github/]

**5. 开源项目协作-比如协作翻译项目**

- 苹果官方发布的各种官方手册，比如最近开源的 Swift numbbbbb/the-swift-programming-language-in-chinese · GitHub[http://link.zhihu.com/?target=https%3A//github.com/numbbbbb/the-swift-programming-language-in-chinese] 就是国内一个自发组织起来的团队，30多个人用9天时间即将翻译和校对工作全部完成，他们每人都还有自己的事情，上班、上线、创业，这么大的工作量在以往简直是不可能完成的任务！

**6. 寻找设计资源库**

- 做 ppt 不知道到哪里去找高质量美图？Design- Resource List项目：[http://link.zhihu.com/?target=https%3A//github.com/timmy3131/design-resource]，
旨在让更多的设计师找资源变得有章可循。

这些资源都可以直接Fork，大大节省了时间！
-------------------------------------------------------------
以上部分文字源自：
作者：珊姗是个小太阳
链接：http://www.zhihu.com/question/20070065/answer/79557687
来源：知乎
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。


- 问题3：用实例介绍如何使用 Pull Request 和 Merge 实现团队工作协同？
> 答案：

我们举一个例子，Mary和John要开发一个大工程——“星际航行”任务。John是项目总监，Mary是项目开发人员。John有一个公开的项目仓库Bitbucket。
###Mary- fork正式项目
Mary首先要把John的Bitbucket仓库fork到自己的仓库里，开始项目的开发。点击fork按钮，然后为fork出来的仓库填写名字和描述，这样Mary就有了服务端的项目拷贝了。

![](http://upload-images.jianshu.io/upload_images/1757077-9d90de8bc7a5b6c3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![](http://upload-images.jianshu.io/upload_images/1757077-e1676e28733d9e0c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
###Mary克隆到她的本地Bitbucket仓库
Mary将自己刚才fork出来的Bitbucket仓库，克隆到本地，在本地进行接下来的工作。克隆命令如下：
```
git clone git@github.com: username/Bitbucket.git
```
##Mary开发新功能
在开始开发新功能之前，Mary先为新功能新建了一个分支feature，她会用这个分支作为Pull Request的源分支。
```
git checkout -b feature
```
在新功能分支上，Mary进过几天奋战，终于开发出来了spacetravel.py文件。
然后添加、提交、push到自己的远程github端。
```
git add spacetravel.py
git commit -m "spacetravel to Mars"
git push origin feature
```

![](http://upload-images.jianshu.io/upload_images/1757077-d1d48b6760829e21.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
###Mary发起Pull Request
这时她要通知John，自己已经把项目新功能完成了。Bitbucket上有了她的功能分支后，Mary在她fork出来的仓库界面，点击右上角的【Pull Request】按钮，发起一个Pull Request。设置Mary的仓库为源仓库，feature分支为源分支，目标仓库为John的公开仓库，目标分支为John的master分支。设置好之后，通知就会以系统消息或邮件发给John。

![](http://upload-images.jianshu.io/upload_images/1757077-831de5caee718a26.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


![](http://upload-images.jianshu.io/upload_images/1757077-dd5c65867eff03dc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###John要review Mary的Pull Request

![](http://upload-images.jianshu.io/upload_images/1757077-d51d0c87bec4784b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

在John的Bitbucket仓库页面的【Pull Request】可以看到有人发起的Pull Request。点击Mary的Pull Request会显示出具体的描述、功能的提交历史和每个变更的差异。
John看到之后打算合并到自己的主分支下，在按下【Merge】按钮就可以同意Pull Request并合并到自己的master分支。
突然发现Mary的提交项目中有一个小bug，需要Mary先修复这个bug再进行合并。John于是在整个Pull Request上加上评注，要求Mary先修复bug。


![](http://upload-images.jianshu.io/upload_images/1757077-3e3c58da85747cc1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

Mary于是修复bug，并重新提交，接着Pull Request到John。
John很满意这次的提交文件，合并Mary的功能分支到自己的master主分支，并关闭Pull Request。

*至此项目成功完成，宇宙飞船准备飞往火星了。。。*

- 问题5：xxxxxxx
> 答案：xxxxxx




