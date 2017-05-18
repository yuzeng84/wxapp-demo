# wxapp-demo
#微信小程序完整商城类demo：灵动云商（含PHP后端）
项目下载地址： 
 - 前端：http://git.oschina.net/dotton/lendoo-wx 
 - 前端下载： <a href="http://www.wxapp-union.com/forum.php?mod=attachment&aid=OTkxOXw0ZWQ0MGFhOHwxNDk1MDk2MTgwfDE0MTAxfDQ3MTg%3D">dotton-lendoo-wx-master.zip</a> (150.34 KB, 下载次数: 1277) 
 - 后端：http://git.oschina.net/dotton/lendoo-web 
 - 后端下载；http://pan.baidu.com/s/1pLbNPhx 
 - 后端演示地址（自带账号密码）：http://lendoo.leanapp.cn/manager/login

项目详情：http://www.wxapp-union.com/forum.php?mod=viewthread&tid=4718&utm_source=githup-wxapp-demo

项目简介： 
Codeigniter是一个老牌的php框架，零配置，文档极其丰富，国内的流利程度上看github的start数，让人觉得不可思议，是国外流行比较流行吧。它没有ORM，没有模板引擎，用它，只是因为够用了，LeanCloud自身就是ORM，而PHP天生就是模板语言，所以CI有没有ORM与模板引擎也无所谓。 
使用LeanCloud后端云帮我省去了90%以上的后端接口，没有比小程序端用JS直接操作数据库更方便的了，所以直到小程序写完，再来写后台也完全来得及。后台只为了发布商品以及订单发货状态而已。当然Bmob也是一个不错的选择，现在也推出了小程序端sdk了。 
后台界面，使用了Admin-LTE，它是基于Bootstrap的一套UI，打包了太多现成的组件，菜单目录树，表格，下拉框，颜色选择器，编辑器，日历，报表，聊天窗口，具体可以下载它的demo来看。基本一套后台能想到能使用到的，都在这里了。 
在登录与修改页面，其实还用到零星的vue+element-ui，取dom的最高境界就是不用取dom，数据双向绑定确实方便实惠；还有就是bootstrap没有自带MessageBox很让人抓狂，于是就上了element-ui。说不准以后就让admin-lte与jQuery下岗了，让vue+ele全职来做吧。 
最后就是2个工具，composer与bower，分别用来安装php与js库，有了这些包管理工具，安装第三方依赖库，直接敲上bower install bootstrap就达目的了，日后update还是那么的方便，再也不用搜索官网，下载解压，复制到项目等一切繁琐步骤；就跟git一样，一旦用上，就再也回不去了，严重推荐。

编辑者：<a href="http://www.wxapp-union.com/" target="_blank">微信小程序开发</a> <a href="http://www.wxapp-union.com/" target="_blank">微信小程序</a>
