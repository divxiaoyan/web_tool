# 个人前端工程师开发工具记录

标签（空格分隔）： 前端 工具 总结
------
我们前端,每个人都有自己的开发工作环境,工具等,所以我写了这一篇文章,为自己方便把自己常用的**`前端工具`**记录下来,以便到时候在新的电脑上可以快速搭建自己熟悉的工作环境和使用自己熟悉的工具,同时可能也会对你有少少的帮助吧!

前端环境软件安装
> *  [node.js][2]  很多东西都需要它
> *  [npm][3] , [cnpm][4] , [spm][5] 安装可以更换淘宝的安装包地址([淘宝镜像][6])
> *  [Ruby][7](git依赖) , [msysgit][8] / [SourceTree][9][win7以上]
> *  [gulp][10] 下面会列出常用插件 , [ F.I.S (百度前端工具框架)][11]
> *  [sass][12] [教程][13]/ [less][14]
> * `git`还有另外一个工具(在xp,win7上可用还是图形的哦,还有文章) [点我][15]

安装顺序
先安装`node` --> `npm ` --> `gulp` 
[使用 gulp 构建工程][16]
先安装`ruby` --> `git`,`sass`,`compass`
[window 安装 sass compass 记录][17]

常用工具列表：

> * [WebStrom][18]  我个人比较喜欢这个软件,功能非常强大已经更新到第九版([点我下载注册机和配色方案][19]) ,[sublime_text][20]([文章介绍][21]),[HBuilder][22]
> * [cmder(类似cmd的命令提示符,有自带git版本)][23]  [配置教程][24]
> * [koala考拉][25](Less、Sass、Compass、CoffeeScript编译) ----免费
> * [Mark 马克鳗][26] (设计图测量) 
> * [小苹果服务器][27](手机调试专用win7以上)
> * [F5][28] 自动刷新浏览器
> * [Notepad++][29] 不解释
> * Photoshop CS4/CS6 不解释,PS插件?建议去 [设计优][30]
> * 计算器 不解释
> * 右键助手1.0 ([我自己开发的,详细点这里][31]) ,彗星小助手（取色） , W3Cfuns前端开发工具箱 ([到百度分享查看下载地址][32])
> * AdobeDreamweaverCS4 写表格,热点图
> * [CSS Sprites 样式生成工具][33]
> * WampServer 搭建PHP环境服务器
> * MyWebServer 迷你型服务器
> * FlashFXP (ftp上传工具)
> * Regex Match Tracer 2.1 (正则工具)
> * [SETUNA2][34] (图片裁剪对比)

火狐浏览器插件 
> * Firebug 
> * YSlow 性能检测
> * JSONView 在页面查看那json数据
> * CSSUsage 检测无效css
> * Dust-Me Selectors 检测页面css沉余
> * FireQuery jq语法高亮
> * FireRainbow js语法高亮
> * HtmlValidator html文档标准检测
> * NoScript 控制页面和浏览器js
> * [FireGestures][35] 用鼠标手势命令
> * [Adblock Edge][36] 广告过滤
> * webDeveloper1.2.2-(zh-cn) 中文版,[点我][37]

除了最后一个网上可能找不到中文版

谷歌浏览器插件 --用到谷歌插件其实很少(其实我自己用的蛮多),为了方便,因为谷歌插件下载很多问题,我直接发到网盘,有需要的可以自己下载(360,猎豹应用市场也有好多应用)
> * [Web Developer][38] (居然被我找到谷歌版的,不过是英文的,不错了)
> * [Window Resizer][39] (允许你快速调整浏览器窗口分辨率)
> * [CSSViewer][40] (浮动面板简单显示CSS属性)
> * [Wappalyze][41] (分析网站使用什么技术,优化的时候可以看人家网站使用什么技术)
> * [IE Tab][42] (直接在Chrome中使用IE渲染引擎模仿IE,IE6、IE7、IE8和IE9,扩展目前仅适用于Windows系统,感觉有点不靠谱)
> * [Clear Cache][43](能让你从工具栏中清除缓存)
> * [Image Downloader][44] (批量下载图片)
> * 谷歌加速插件 替换一些需要翻墙才能链接的js替换为国内链接
> * JetBrains IDE Suport (配合WS 在浏览器同步刷新,似乎在谷歌高版本已经无效,如果你不使用ws,可以配合gulp的插件,也可以实现同步更新)
> * [ReRes][45] 开发的时候替换测试路径为本地,实际是上线后的地址
> * Enable Copy 去除右键限制
> * JSON View 查看json格式数据
> * WEB前端助手(FeHelper)_v5.8 
> * 有道云笔记网页剪报 (保存页面到有道笔记本)
> * Firebug Lite 谷歌用火狐插件(哈哈,开发者用火狐提供的ie火狐js搞的吧)
> * [网址转二维码][46] (手机测试中有用,扫描就打开测试地址了)
> * ScriptSafe汉化版 (可以控制页面的js脚本)
> * Word Count 是一款用来统计选中网页的字数，支持中文的扩展。

建议访问 [360云盘共享][47] 文件多,有点乱,自己翻  
访问密码 a505

其他软件工具
> * [Flux][48] 调整屏幕亮度,暖色调
> * [ADSafe][49] 过滤广告
> * [Everything][50] 快速查询
> * [Wise Registry Cleaner][51] 注册表清理
> * [Clover][52] 让你的Windows资源管理器拥有像谷歌浏览器一样好用的多标签页
> * [360云盘][53] 同步数据文件
> * [有道云笔记][54] 协作同步开发
> * Proxy SwitchySharp 代理工具,翻墙用的,需要自己找账号信息填写哦

####其他一些网上工具
> * [中国开源在线工具][55]
> * [熊猫png压缩][56]
> * [智图(多种图片压缩)][57]
> * [雪碧图坐标查询][58]
> * [cssanimate动画制作工具][59]
> * [在线切图工具][60] (最近找到的,不知道如何,欢迎大家测试)
> * [配色方案][61](美工的工具)

##gulp常用插件

整理了在自己工作当中常用的一些gulp 插件
> * 编译Sass (gulp-ruby-sass)
> * 编译Map文件          (gulp-sourcemaps)
> * 自动添加css前缀            （gulp-autoprefixer）
> * 压缩css                    （gulp-minify-css）
> * 压缩css使用的                gulp-mini-css[国产.配合清除沉余css插件后的压缩插件,跟上面的不一样哦] 
> * js代码校验                  （gulp-jshint）
> * 合并js文件                  （gulp-concat）
> * 压缩js代码                  （gulp-uglify）
> * 压缩图片                    （gulp-imagemin）
> * 自动刷新页面                 （gulp-livereload）//不建议配合WS一起用(WS的自动保存,然后你懂的,但如果你不是用less或者sass开发,还是建议使用的)
> * 图片缓存，只有图片替换了才压缩  （gulp-cache） //我也没用过
> * 更改提醒                    （gulp-notify） //我也没用过
> * 清除文件                    （del）
> * 替换内容,需自定义范围内容,支持正则[常用于替换上线后的js,css文件路径]                    （gulp-replace）
> * 同上,更加智能 ([gulp-rev-collector][62])
> * 智图图片处理插件     ([gulp-imageisux][63])
> * 将文件转成utf8编码的gulp插件([gulp-utf8-convert][64])
> * 合并按模块引入的html文件([gulp-content-includer][65])
> * 压缩html ([gulp-minify-html][66])

##帮助文档
> * [css手册][67] 在线(里面可以下载,感谢作者:飘零雾雨)
> * [jQuery手册][68] ，　[其他版本][69] 
> * [Zepto手册][70]
> * [Less.js 中文文档][71]
> * [Bootstrap 中文文档][72]
> * [Underscore.js (1.8.2) 中文文档][73]
> * [Backbone.js(1.1.2) API中文文档][74]
> * [其他在线手册][75] 自己看吧,应该有的都有了

##谷歌搜索地址(不用翻墙)
> * [地址1][76] [地址2][77] [地址3][78]

------

再一次感谢您花费时间阅读这篇文章,如果你有更好的工具,可以给我留言,其他资料还在整理当中,感谢你的阅读!

作者 [@黑色技术][79]     
2015 年 3月 15日    
更新时间: 2015 年 4月 1日



  [2]: https://nodejs.org/download/
  [3]: https://www.npmjs.com/
  [4]: https://cnpmjs.org/
  [5]: http://docs.spmjs.org/doc/
  [6]: http://npm.taobao.org/
  [7]: https://www.ruby-lang.org/zh_cn/downloads/
  [8]: https://msysgit.github.io/
  [9]: http://www.sourcetreeapp.com/
  [10]: http://gulpjs.com/
  [11]: http://fis.baidu.com/
  [12]: http://www.w3cplus.com/sassguide/install.html
  [13]: http://www.w3cplus.com/sassguide/
  [14]: http://lesscss.net/
  [15]: http://backlogtool.com/git-guide/tw/intro/intro1_1.html
  [16]: http://www.u396.com/getting-started-with-gulp.html
  [17]: http://www.cnblogs.com/yyman001/p/install_sass_compass_for_window.html
  [18]: https://www.jetbrains.com/webstorm/
  [19]: http://pan.baidu.com/s/1iVZ20#path=%252Fwebstorm
  [20]: http://www.sublimetext.com/
  [21]: http://www.codeceo.com/article/sublime-text-usage.html
  [22]: http://www.dcloud.io/
  [23]: http://bliker.github.io/cmder/
  [24]: http://bg.biedalian.com/2014/09/11/cmder.html
  [25]: http://koala-app.com/index-zh.html
  [26]: http://www.getmarkman.com/
  [27]: http://www.xbole.com/
  [28]: http://getf5.com/
  [29]: http://notepad-plus-plus.org/
  [30]: http://www.uisdc.com/
  [31]: https://www.zybuluo.com/yyman001/note/78390
  [32]: http://pan.baidu.com/s/1pJFmnAN
  [33]: http://www.cssforest.org/blog/index.php?id=129
  [34]: http://www.clearunit.com/clearup/setuna2/
  [35]: http://www.xuldev.org/firegestures/
  [36]: https://bitbucket.org/adstomper/adblockedge/downloads
  [37]: http://pan.baidu.com/s/1pJFmnAN#path=%252F%25E5%2589%258D%25E7%25AB%25AF%25E5%25B7%25A5%25E5%2585%25B7%252F%25E7%2581%25AB%25E7%258B%2590%25E6%258F%2592%25E4%25BB%25B6
  [38]: https://chrome.google.com/webstore/detail/web-developer/bfbameneiokkgbdmiekhjnmfkcnldhhm
  [39]: https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh?hl=en%20
  [40]: https://chrome.google.com/webstore/detail/cssviewer/ggfgijbpiheegefliciemofobhmofgce?hl=en
  [41]: https://chrome.google.com/webstore/detail/wappalyzer/gppongmhjkpfnbhagpmjfkannfbllamg?hl=en%20
  [42]: https://chrome.google.com/webstore/detail/ie-tab/hehijbfgiekmjfkfjpbkbammjbdenadd?hl=en%20
  [43]: https://chrome.google.com/webstore/detail/clear-cache/cppjkneekbjaeellbfkmgnhonkkjfpdn?hl=en%20
  [44]: https://chrome.google.com/webstore/detail/image-downloader/cnpniohnfphhjihaiiggeabnkjhpaldj%20
  [45]: https://github.com/hanan198501/ReRes
  [46]: https://chrome.google.com/webstore/detail/%E4%BA%8C%E7%BB%B4%E7%A0%81%E7%94%9F%E6%88%90%E5%99%A8/ajaomcmkalmeeahjfdklkcjbljhbokjl?utm_source=chrome-ntp-icon
  [47]: http://yunpan.cn/cZdfChwFmEpYF
  [48]: http://www.iplaysoft.com/flux.html
  [49]: http://www.ad-safe.com/
  [50]: http://www.voidtools.com/
  [51]: http://www.wisecleaner.com/download.html
  [52]: http://clover.softonic.cn/
  [53]: http://yunpan.360.cn/
  [54]: http://note.youdao.com/
  [55]: http://tool.oschina.net/
  [56]: https://tinypng.com/
  [57]: http://image.tencent.com/
  [58]: http://www.spritecow.com/
  [59]: http://cssanimate.com/
  [60]: http://card.qdsay.com/
  [61]: http://card.qdsay.com/
  [62]: https://github.com/shonny-ua/gulp-rev-collector
  [63]: https://www.npmjs.com/package/gulp-imageisux
  [64]: http://segmentfault.com/blog/paopao/1190000000763005
  [65]: http://segmentfault.com/blog/paopao/1190000001500298
  [66]: https://www.npmjs.com/package/gulp-minify-html
  [67]: http://css.doyoe.com/
  [68]: http://hemin.cn/jq/
  [69]: http://jquery.js-ku.com/
  [70]: http://www.css88.com/doc/zeptojs_api/
  [71]: http://www.css88.com/doc/less/
  [72]: http://bootstrap.css88.com/
  [73]: http://www.css88.com/doc/underscore/
  [74]: http://www.css88.com/doc/backbone/
  [75]: http://www.css88.com/jqueryapi
  [76]: http://www.clonegoogle.com/?gws_rd=ssl
  [77]: http://ggss.so/
  [78]: http://www.gfsswy.com/
  [79]: http://weibo.com/yyman001