## 小组信息
- 小组名称：黑逗士
- 组长：Krystal.

- 组员：梁靖 紫易千荷 肩吾

----
## 本周认领任务清单
- 问题1 :说说自己可以用 Github 做些什么，不少于 6 条。（必选）
- 问题2 :用实例介绍如何使用 Github Pages 的 User or organization site 及 Project site 建立独立站点？
- 问题3 :用实例介绍如何使用 Pull Request 和 Merge 实现团队工作协同？

------
## 作业详情
- 问题1：必选：说说自己可以用 Github 做些什么，不少于 6 条。

> 黑逗们的答案：

* 通过学习我们发现，Github是功能特别强大，最通用的可以star喜欢的项目，fork并pull为他人项目打补丁，
以下我们列出了8条自己的见解。

> - 作为个人和团队的抒写平台
> - 实现有效的协同合作
> - 作为自我成长记录库
> - 交友，github一个超强交友平台
> - 发现其他优质内容
> - 建立个人静态网站
> - Github可以作为自己的简历
> - 托管和下载别人的代码


- 问题2：用实例介绍如何使用 Github Pages 的 User or organization site 及 Project site 建立独立站点？

> 黑逗们的答案：

#### 首先演示一下使用User or organization site 创建Github Pages.md

##### 第一步、创建一个新的仓库，设置你Project名字、描述，然后创建仓库（Create repository）。

> Respository name：自定义。 
> Description: 自定义。

![](http://upload-images.jianshu.io/upload_images/1751342-e5e56081e51b27fe.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![](http://upload-images.jianshu.io/upload_images/1751342-603203a792a98a44.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##### 第二步、创建完成后，点击导航项目Settings，并找到Github Pages选项。

> Automatic page generator:自动化Page构造器，有优秀的模板供我们选择，小白选这个选项。 
> Custom and Jekyll - based sites:是用户通过使用Jekyll工具自定义Pages模板。

![](http://upload-images.jianshu.io/upload_images/1751342-9f77df5a0f123ac1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##### 第三步、在你点击了上图中Launch automatic page generator之后，会跳转page内容编辑界面，我在内容中随便加了一些我的解释，支持Markdown语法。然后点击Continue to layouts.

> ![](http://upload-images.jianshu.io/upload_images/1751342-5f0deefa919d69e7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#####第四步、这是模板选择界面，大家可以选择自己喜欢的模板。如果确定要发布点击Publish page.如果要回到第四步编辑内容可以点击Edit。

> ![](http://upload-images.jianshu.io/upload_images/1751342-8166d153abbf72b6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#####第五步、在你的浏览器中检查你的成果吧~

> ![](http://upload-images.jianshu.io/upload_images/1751342-57c65b8a6a7aad11.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

####接下来这一部分，介绍使用User or organization site 创建Github Pages

> 因为User 和 Project项目建议Pages非常相似，我在这里值列出哪些步骤不一致。

#####第一步、设置你的站点名
> Repository name：这里的站点名字必须和你的用户名保持一致，格式必须为username.github.io

> ![](http://upload-images.jianshu.io/upload_images/1751342-9f77df5a0f123ac1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#####第二步、Github pages 有一定区别，选择Overwrite site选项，相当于是Project Pages中的Automatic page generator,点击Launch automatic page generator

> ![](http://upload-images.jianshu.io/upload_images/1751342-0f443b539f926c40.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#####第三步，第四步与Project的步骤是相同的，所以这里就直接演示第五步啦、打开http://username.github.io查看自己的成果。

> ![](http://upload-images.jianshu.io/upload_images/1751342-b546c6991debba38.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

####最后，让我们来看一下两个站点的页面区别对比

> ![](http://upload-images.jianshu.io/upload_images/1751342-7c20c6e0dc6accc5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



- 问题3：用实例介绍如何使用 Pull Request 和 Merge 实现团队工作协同？

> 黑逗们答案：

#### 第一步：创建一个公共项目：
* 在一个合作项目中，首先需要创建一个公共项目，创建这个项目的人，就是项目的管理者，需要去处理其他协作者发送的pull request请求，需要审核提交内容，选择合并。首先管理者创建一个新的项目--blackbean
![1.png](http://upload-images.jianshu.io/upload_images/249863-3e96ca878df9b545.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 然后根据下图将本地创建的库Publish到Github仓库中去。 
![2.png](http://upload-images.jianshu.io/upload_images/249863-2d3a409943c94b22.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 项目创建人为项目新增了一个README.md文件
![3.png](http://upload-images.jianshu.io/upload_images/249863-9acf2974d8e57935.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 第二步：协作成员fork项目
* 有了公共项目之后，其他成员首先要fork。以下使用账号jacklyy为例，演示如何fork。 去到库管理员的主页，找到目标项目（blackbean）。
![4.png](http://upload-images.jianshu.io/upload_images/249863-e7acbdc14e9e48e1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 进入项目中。点击fork按钮
![5.png](http://upload-images.jianshu.io/upload_images/249863-cb480bebdba84f34.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 然后fork后的项目会在你的项目列表中出现
![6.png](http://upload-images.jianshu.io/upload_images/249863-ae2d4cdddd586c36.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 第三步：将fork后的项目clone到本地。
* 如下图，第一在github中点击clone按键复制SSH，第二在命令板中操作 输入口令 git clone +粘贴SSH 完成克隆 第三步 在 github desk 手动添加 clone文件 balckbean（拼写小错误，嘿嘿嘿~）
![7.png](http://upload-images.jianshu.io/upload_images/249863-78ffee294e6c40fd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 添加成功之后：
![8.png](http://upload-images.jianshu.io/upload_images/249863-f800c319ee5235be.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##### PS:

* 不要用Github去列表中clone项目，经常会报错，请用命令版Clone，然后用Github客户端收到Add项目到客户端中。 

下面是具体操作：再次注意，请使用图中最右红框中的Clone with SSH项目地址样式，在面板中clone。

#### 第四步、修改文件，准备pull request请求

* 1.如下图成员在本地README.md文件中，编辑入更改内容；这时在github desk中就可以看见相应改变，直接在desk中添加名称和描述，点击Commit to master。这里的操作就等同归于在命令板中的口令 “git add 文件名 git commit -m 描述改动”的操作，desk中的操作更简单啦，git使用小白的福音哦~

 ![](http://upload-images.jianshu.io/upload_images/1751342-3393d66c31227068.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 2.如下图commit to master 之后就是需要 pull request （不明白为什么要pull request？详见温馨小提示）

![](http://upload-images.jianshu.io/upload_images/1751342-4a1ec7c5ccbfee86.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 3.Pull request成功后，在源公共库项目主页中，会有下图你的Pull请求。

> ![](http://upload-images.jianshu.io/upload_images/1751342-e380e666e99c3509.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**温馨小提示**：
* 这里特别注需要注意哦，Commit to master之后，我们只是将文件的修改提交到了本地Clone的fork仓库中版本库里，并没有同步到我们Github网站的远程仓库中去，因为fork后clone到本地的仓库并不会直接与原公共仓库并不直接相连，不能从本地仓库直接发送Pull request请求到原公共仓库。所以我们必须要先将本地修改提交到我们自己的远程仓库中去，再生成Pull requst。 

* 但是问题来了，因为Github 的 Sync功能令人抓狂，我到目前为止还没有成功Sync过，不知道是伟大的墙有问题，还是HTTPs请求方式有问题，总之不靠谱。所以强烈推荐大家用命令版推送更新到远程仓库中。下图是具体事例：（这里如果推送失败，请检查你Clone库的时候用的是SSH url 还是 HTTPS url）。 

![](http://upload-images.jianshu.io/upload_images/1751342-745fbaafe2dc216e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 注意下图最优红框中，你必须要将Pull请求提交到哪个分支去，一个是你自己远程仓库fork后的默认分支，另一个是你源公共库的默认分支，这里我们肯定是想将更新提交到源公共库中去。所以选择源公共库的master分支。注意，你的项目可能有很多分支，所以要主动选择。 

* PS:这一步可能先报一个Sync的错，不用理会，然后才会提示Pull request是否成功，这里也可能失败，多试几次。当然我们也可以去自己的fork后的远程库中发起Pull request，那样成功有保障。

#### 第五步、源公共库管理者，需要去处理其他成员的 Pull request

* 点开具体的Pull request 查看详细内容
![](http://upload-images.jianshu.io/upload_images/1751342-7cd787765fba7e1f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 因为上图中提示了，这个Pull request和我们的分支没有冲突，所以直接点击上图中的Merge pull reqeust。如下图，选择默认项即可
![](http://upload-images.jianshu.io/upload_images/1751342-66e2353d73711462.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 两个选项的区别在于：前者会保持每次Pull request 合并时的档案，后者不保留,我们默认保留.

* 最后，源公共库中项目就会是合并之后的数据了
![](http://upload-images.jianshu.io/upload_images/1751342-1c6205ce2c74b81a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 这样我们小伙伴之间的协作就完成啦，是不是很简单？赶快试试吧~
