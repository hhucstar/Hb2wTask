## 小组信息

- 小组名称：02组 能量棒

- 小组组长：四月

- 组员：柴茝、韩贤君、团子

----
## 本周认领任务清单

- 问题1:必选：说说自己可以用 Github 做些什么，不少于 6 条。
- 问题2:用实例介绍如何使用 Github Pages 的 User or organization site 及 Project site 建立独立站点？
- 问题3:用实例介绍如何使用 Pull Request 和 Merge 实现团队工作协同？
- 问题4:如果要用 200 字向一个对 Github 完全陌生的人介绍它，要如何介绍？
- 问题5:通过 Github 的操作来说明工作区、暂存区、版本库之间的关系。
- 问题6:整理一份可供小白入门学习 Github 的简明手册。

------
## 作业详情

- 问题1：说说自己可以用 Github 做些什么，不少于 6 条

>答案：

>1.像一个仓库，存储代码，项目。

>2.与团队协作完成项目。随时可以在分支上修改，上传，并留下记录。

>3.修改的文件会留下痕迹，方便更新与复查。

>4.集思广益。因为开源，所以可以随时被修改，新修改的内容可以推送请求，如果请求合理就会被接受。

>5.利用github pages来托管自己的博客，而且支持顶级域名绑定。博客就是放在github上的，写好textile（或者其他标记语言），上传至github后会自动生成html静态文件。

>6.关注下Github的blog, 看看有没有新闻，看下Github的tip.还可以去搜索下有意思的项目，看到有意思的人可以去他的博客看看。


- 问题2：用实例介绍如何使用 Github Pages 的 User or organization site 及 Project site 建立独立站点？

答案：

上一周大家学习了git,对git是什么,怎么用,原理是什么都应该了解了.这周又学习了github,都应该知道了github其实就是git的亲兄弟.那接下来我们讲的github pages又是什么呢?不要紧张,只要你掌握了git和github这俩亲兄弟,github pages绝对是送给你的福利.下面我就来一起学习吧.

>学习github pages你需要知道的

>1.git是什么

>2.分支的理解

>3.如何新建一个仓库

>3.知道什么是独立站点

一张图说明主要内容

![](http://ww1.sinaimg.cn/mw690/8edca89bgw1f4nkx3ngdpj212g0gejt3.jpg)

简单点说github pages就是由github为你提供的一个可以免费搭建个人博客的服务.下面我们将通过实例来介绍如何通过github pages搭建个人博客.

首先你要明白的是,我们有两种方式,如题目中提到的User or organization site 和 Project site,下面我们将分别举例说明.

#### User or organization site(个人/组织主页)

1.创建一个新仓库

![](http://ww2.sinaimg.cn/mw690/8edca89bgw1f4nj6u6sk8j20o40gzdi1.jpg)

**注意:**创建的这个仓库名格式必须是YourGithubName.github.io(YourGithubName就是你github的用户名).如果仓库名与你的用户名不匹配的话,这个是不会生效的.所以一定要确定你输入的仓库名是对的.

2.把创建好的仓库clone到本地

![](http://ww2.sinaimg.cn/mw690/8edca89bgw1f4nj6v7l3pj20t40j5tbr.jpg)

```
$ git clone https://github.com/YourGithubName/YourGithubName.github.io
```

3.新建index.html文件

```
$ cd username.github.io
$ echo "Hello World" > index.html
```

4.提交到github服务器

```
$ git add --all
$ git commit -m "Initial commit"
$ git push -u origin master
```

5.搭建完成

到这,我们人生的第一个独立站点就搭建完成了,有木有很激动.赶紧访问http://username.github.io/来看看效果吧.如果没有反应,要稍等片刻哦.

#### Project site(项目仓库)

上面我们介绍了使用User or organization site来搭建个人博客,其中我们特别强调了新建仓库的命名规范,必须是YourGithubName.github.io.到这不知道大家有没有发现一个问题?因为我们的githubName是唯一的,所以,我们只能建这样的一个仓库,也就是只能搭建一个博客站点.但是,有的时候我们需要搭建好几个不同的博客站点怎么办?不要着急,这就是我们接下来要讲的第二种方式,通过Project site来搭建博客站点.

需要提前说明的是,Project site这种方式又可以分两种情况:

- 通过新建一个仓库来创建(Generate a site)
- 直接从已有的仓库创建(Start from scratch)

其实,这两种方式可以算一种,除了新建仓库和已有仓库,再没有其他区别.

##### 通过新建仓库搭建

1.新建仓库（Create a repository）

![](http://ww1.sinaimg.cn/mw690/8edca89bgw1f4nj6vg2afj20ph0gsac7.jpg)

2.设置仓库（Repository Settings）

![](http://ww2.sinaimg.cn/mw690/8edca89bgw1f4nj6w6pb2j20vr0rtq79.jpg)

如上图,其他都不用管,点击`launch automatic page generator`按钮,自动生成页面

3.自动生成页面（Automatic Generator）

![](http://ww4.sinaimg.cn/mw690/8edca89bgw1f4nj6x0lc6j20vd0qytdr.jpg)

这个地方是做一些基本的设置,也先不用管,直接点击右下角绿色按钮.

4.设置博客主题

![](http://ww2.sinaimg.cn/mw690/8edca89bgw1f4nj6xr1xnj20vf0sm7c9.jpg)

在这个地方,github给我提供了很多种博客样式,可以挑自己喜欢的,然后点击发布.

5.搭建完成

![](http://ww4.sinaimg.cn/mw690/8edca89bgw1f4nj6yw1kej20u70eggo9.jpg)

至此如果你看到上面的这个页面,那就说明我们已经搭建完成.原先我们创建的空仓库里也多出很多的文件.

还等什么,赶紧在浏览器中输入http://username.github.io/repository,看看自己搭建的博客什么样.

最后提醒别忘了替换username和repository哦.

如果浏览器没有反应,要等一段时间github的设置才能生效哦.

#### 通过已有仓库搭建

1.创建gh-pages分支

![](http://ww4.sinaimg.cn/mw690/8edca89bgw1f4nj6yzgokj20pw0drabr.jpg)

2.新建一个index.html文件,提交修改

![](http://ww1.sinaimg.cn/mw690/8edca89bgw1f4nj708677j20vb0skwgy.jpg)

3.搭建成功

同上面的第五步哦.赶紧看看效果吧.

- 问题3：用实例介绍如何使用 Pull Request 和 Merge 实现团队工作协同？

>答案：

>pull Request用来发起你做的各个版本的讨论。pull是拉，request是请求。

>第一天，老板在自己的github客户端布置开启了一个项目，最初的项目只有master分支，在master分支下面，C1是最原始的项目概况，C2是老板补充细节后的项目。老板让我为项目提供新的想法，让项目更有活力。

>第二天，我有了思路和想法并想要写下项目，所以我便新建了一个idea分支，然后在idea下面写下了我的想法，就是C3版本。我对我的idea十分满意，所以我使用pull request功能，将这个idea分支和master分支进行比较。（注意哦，一经发布，老板那里就可以看到呢，团队其他成员也可以看到，这个时候，就可以针对你的新版本进行讨论）

>![](http://ww3.sinaimg.cn/mw690/8edca89bgw1f4no1bmcgfj209w06k0sk.jpg)

>第三天，老板收到了我pull request后的留言，也看到了我的C3版本，老板十分满意~~所以他点击同意合并，于是就出现了下面一步，合并merge.

>第四步，合并。老板点击合并，要把idea分支**合并merge**到master分支里，如下图此时，生成了一个CS版本。master指针指到CS版本上。这样，一个项目就做好了！点击master，我们在历史记录里可以看到每一步修改。可以看到C1、C2、到最后合并每一步的操作步骤。

>![](http://ww3.sinaimg.cn/mw690/8edca89bgw1f4no1c42gbj20ax07l0sl.jpg)

>总结：Pull request 功能和merge功能可以想象成，老板的交给我一个任务，我写好了，我使用pull request功能，提交项目到群组里，让团队成员和老板查看，听取大家的意见和评论，我再根据评论进行修改。当我修改了好了，老板和团队成员评论说，满意了，老板（或者我）就可以使用merge功能，将我的任务合并到母任务里。这样就完成了一次团队协作。

- 问题5：通过 Github 的操作来说明工作区、暂存区、版本库之间的关系。

答案:

>分别介绍一下在github web网页中和github desktop客户端中的体现

>1.在web网页中

>**版本区**

>![](http://ww3.sinaimg.cn/mw690/8edca89bgw1f4nk90277qj20v70rnn4u.jpg)

>如上图,我们进入github仓库看到的这个目录结构就是我们的版本区所在

>随便点一个文件进入下图

>![](http://ww1.sinaimg.cn/mw690/8edca89bgw1f4nk90t8ryj20u20esmyl.jpg)

>点击右上角铅笔标识的按钮,就进入了我们的工作区

>**工作区**

>![](http://ww1.sinaimg.cn/mw690/8edca89bgw1f4nk91ejkpj20vp0tf425.jpg)

>如图,在这我们可以直接对文件修改

>**暂存区**

>如果修改完成,在上图中,填写commit信息,点击commit按钮后,我们的修改内容就会到我们的暂存区.

>2.在github desktop客户端中

>github desktop客户端其实也是一样的道理,只是有一些细微的差别,下面我们通过无暂存区和有暂存区的两种图对比看看,这些区别在什么地方

>注意:左图都是没有暂存区的情况,右图是有暂存区的情况.红色圈出来的地方就是他们之间的差别.

>![](http://ww1.sinaimg.cn/mw690/8edca89bgw1f4nkfr2w0zj20rt0dngqy.jpg)

>![](http://ww1.sinaimg.cn/mw690/8edca89bgw1f4nkfs4x5hj20sa0cbwh8.jpg)





