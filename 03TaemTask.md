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
- 问题1：xxxxxxx
> 答案：xxxxxx

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

