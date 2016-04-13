

#FlowGeek
FlowGeek是基于MVP架构的、遵循Material Design设计规范的开源中国社区客户端。

开源中国社区客户端自面世开源以来，	给很多初学者到来了很多帮助，感谢@火蚁 的工作。现在技术革新很厉害，而我们开源中国的社区app还一直停留在原始的样子，不断的收集大家的意见和issue，改改bug什么的，并没有做改版。其实到这，改版的理由已经很充足了，技术落后、界面难看、代码臃肿...但是各位老司机都应该清楚，改版这种事情是件工作量具大的，理解业务逻辑、UI设计、架构设计、开源组件选择...所以，内部也是停留在想想的阶段。所幸来到开源中国，工作量（暂时）不大，还是比较轻松的，最近业界也津津乐道过MVP、Material Design一阵子，闲来无事，怀着一颗我不入地狱谁入地狱的决心，我就入坑了...

##技术架构

###MVP

<img src="http://git.oschina.net/uploads/images/2016/0310/133601_cf3c9118_116508.png" width="700"/>


###类图
Activity    

<img src="http://git.oschina.net/uploads/images/2016/0310/145150_7129b37b_116508.png" width="600"/>

Fragment    

<img src="http://git.oschina.net/uploads/images/2016/0310/133607_6191b5fe_116508.png" width="700"/>

Presenter    

<img src="http://git.oschina.net/uploads/images/2016/0310/133609_5518d6b3_116508.png" width="700"/>

我发现我还是很敬业的

##主要开源组件
- [RxJava/RxAndroid](https://github.com/ReactiveX/RxJava)：Java的响应式编程的库，相当强大且相当赞！！推荐大家深入到源码，体会设计的强大。

- [Retrofit](https://github.com/square/retrofit)：优雅的HTTP请求开源库，使用动态代理实现，也很赞！推荐你深入源码。

- [Picasso](https://github.com/square/picasso)：强大的图像加载库，Square公司真是业界良心。

- [ButterKnift](https://github.com/JakeWharton/butterknife)：告别findViewById

- [RxLifecycle](https://github.com/trello/RxLifecycle)：在Acvitity和Fragment中管理订阅者/观察者的生命周期。

- [Nucleus](https://github.com/konmik/nucleus)：MVP框架基础库，我使用的MVP基础类就是来源于他，感谢这位开发者。

- [Gson](https://github.com/google/gson)：Google的json解析库。



##推荐Document
- [RxReactive](http://reactivex.io/)

- [Retrofit](http://square.github.io/retrofit/#contributing)

- [Retrofit技术博文](https://futurestud.io/blog/retrofit-getting-started-and-android-client)

- [MVP](http://www.tuicool.com/articles/uIjEJj7)

- [Material Design中文版](http://wiki.jikexueyuan.com/project/material-design/)
 
- [RxJava技术博文](http://gank.io/post/560e15be2dca930e00da1083)

- [MVP入坑文](https://github.com/bboyfeiyu/android-tech-frontier/blob/master/issue-12%2FAndroid%E4%B8%8AMVP%E7%9A%84%E4%BB%8B%E7%BB%8D.md#使用mvp)

##Feture

- **2016.03.13更新**: 添加用户首页,优化一些地方, 添加TODO. 不好意思,现在开始忙起来了,开发进度放缓. 做到这里,常用的几个地方我已经做好了,每天看看资讯,发发动弹还是没什么问题的,
最近我发现app老是不稳定,希望高手能手帮我看看. 明天我就要开始学习React Native做毕业设计了,到时候我会做一个React Native版本的开源中国社区,届时,希望大家多多关注
当然,这个版本我会坚持下去,一个人的力量有时穷,单凭我一个人做不知道什么时候才到反扑原版的时候,所以我在一些需要补充的功能的位置写了TODO,希望大家能够参与进来展现
我们GIT@OSC的开源力量!
    如果你想补充某一个TODO,请告诉我,免得大家做重复工作,做完提交PR和效果图给我就好了,审核代码质量,命名规范...之后我会添加到master ^_^

- **2016.03.10更新**：目前功能：登录、资讯（暂且只支持一些分类，其他太过复杂）、资讯评论、动弹列表、我的动弹、发表动弹（文字or有图像）、动弹评论


##效果图一览

### 夜间主题

<img src="http://git.oschina.net/uploads/images/2016/0310/140319_0b00d52d_116508.png" height="550"/> <img src="http://git.oschina.net/uploads/images/2016/0310/140333_50142400_116508.png" height="550"/> <img src="http://git.oschina.net/uploads/images/2016/0310/140336_b459238f_116508.png" height="550"/> <img src="http://git.oschina.net/uploads/images/2016/0310/140338_5dee381c_116508.png" height="550"/> <img src="http://git.oschina.net/uploads/images/2016/0310/140340_621e5059_116508.png" height="550"/> <img src="http://git.oschina.net/uploads/images/2016/0310/140342_1c1dd7b1_116508.png" height="550"/><img src="http://git.oschina.net/uploads/images/2016/0313/173028_4630f6c6_116508.png" height="550"/>
 
### 日间主题
<img src="http://git.oschina.net/uploads/images/2016/0310/140356_9403ffcd_116508.png" height="550"/> <img src="http://git.oschina.net/uploads/images/2016/0310/140427_e8e3fcaf_116508.png" height="550"/> <img src="http://git.oschina.net/uploads/images/2016/0310/140435_c73abe4d_116508.png" height="550"/> <img src="http://git.oschina.net/uploads/images/2016/0310/140437_0effd45f_116508.png" height="550"/> <img src="http://git.oschina.net/uploads/images/2016/0310/140438_f37f37e1_116508.png" height="550"/> <img src="http://git.oschina.net/uploads/images/2016/0310/140440_c5e114a0_116508.png" height="550"/> <img src="http://git.oschina.net/uploads/images/2016/0310/140442_3d2414e2_116508.png" height="550"/> <img src="http://git.oschina.net/uploads/images/2016/0310/140450_6f4611e7_116508.png" height="550"/><img src="http://git.oschina.net/uploads/images/2016/0313/173038_47f608ee_116508.png" height="550"/>


##Note
- 本人技术和见识都有限，自己认为好的不一定是被认可的，可取的，我希望大家不吝赐教，发挥开源的力量。

- 我一直在自己的小米手机上开发的，版本是5.1，回过头看了下4.4的样子，发现有些地方匪夷所思，暂且Design Support向下兼容得并不好，很多地方不相通，如果你想看最佳的效果，请用Android5.0以上。

- 没有正式完成前改动都会比较大，希望大家watch me, star me and fork me :)。

- 恩，我可以去当设计师了╭∩╮（︶︿︶）╭∩╮