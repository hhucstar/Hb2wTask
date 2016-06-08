## 小组信息
- 小组名称：12组 一林雪
- 组长：雷一
- 组员：雪夜流星、林志培

----
## 本周认领任务清单
- 问题1: 说说自己可以用 Github 做些什么，不少于 6 条。
- 问题2: 用实例介绍如何使用 Github Pages 的 User or organization site 及 Project site 建立独立站点？
- 问题4: 如果要用 200 字向一个对 Github 完全陌生的人介绍它，要如何介绍？

-----
## 作业详情
### 问题1：说说自己可以用 Github 做些什么，不少于 6 条。
答案：
1. 查找别人写好分享出来的代码、项目，避免重复造车轮；
2. 托管自己的代码、项目；
3. 做学习笔记；
4. 做数据备份，如配置文件；
5. 搭建个人博客；
6. 与开源程序作者交流；

### 问题2：用实例介绍如何使用 Github Pages 的 User or organization site 及 Project site 建立独立站点？
答案：
**User/Organization Pages 个人或公司站点:**
1. 使用自己的用户名，每个用户名下面只能建立一个；
2. 资源命名必须符合这样的规则username/username.github.com；
3. 主干上内容被用来构建和发布页面

**Project Pages 项目站点:**
1. gh-pages分支用于构建和发布；
2. 如果user/org pages使用了独立域名，那么托管在账户下的所有project pages将使用相同的域名进行重定向，除非project pages使用了自己的独立域名；
3. 如果没有使用独立域名，project pages将通过子路径的形式提供服务username.github.com/projectname；
4. 自定义404页面只能在独立域名下使用，否则会使用User Pages 404；

**User/Organization Pages 创建方法：**
1. 创建一个新的repository，地址：[https://github.com/new]
2. Repository name 必须为 github用户名.github.io
3. 创建成功后，按照提示，初始化版本库
4. 在版本库中添加index.html
5. 访问http://github用户名.github.io即可，如我自己的：[http://jesonray.github.io/]

**Project Pages 创建方法：**
1. 在任意repository下，点击setting
2. 在GitHub Pages部分，点击 Launch automatic page generator ，设置，选择主题，然后发布
3. 会自动生成网页，通过http://github用户名.github.io/仓库库即可访问，如我的：[http://jesonray.github.io/gb.upwith.me/]

如需绑定域名，在仓库下简历CNAME文件，文件里面一行填写一个要绑定的域名，可以绑定多个。
**注意：User/Organization Pages在master分支下创建CNAME，Project Pages需要在gh-pages分支下创建CNAME才会有效。**

### 问题6：如果要用 200 字向一个对 Github 完全陌生的人介绍它，要如何介绍？
答案：
1. Github是一个网站，域名为 github.com
2. Github是一个开源软件源码集中地，出名的开源项目基本都能在上面找得到，可以自由下载研究。它已超过了前辈SourceFroge，GoogleCode，成为最流行，最大的开源软件集中地。
3. Github也是技术牛人的聚集地，上面很多大神。
4. Github和git紧密联系在一起，可以很方便的进行源码发布、管理、查看、交流，而且，托管公开项目免费！这些特点是它流行起来的主要原因。
5. Github可以帮助我们更方便的远程协作，尤其是写作相关的工作。
6. 由于免费，使用很方便，很多非程序项目也托管在上面，发挥想象，甚至可以做一些别的事情，如：做备份空间（非私密内容），在上面写一本书，搭建一个博客！

