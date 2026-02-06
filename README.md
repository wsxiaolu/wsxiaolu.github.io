# 我是小卢想睡觉的博客

## 关于
[X](https://x.com/wsxiaolu?s=21)

[telegram](https://www.t.me/wsxiaolu666)

[YouTube](https://www.youtube.com/@wsxiaolu)

[Facebook](https://www.facebook.com/share/185ZidcNWw/?mibextid=wwXIfr)

[Threads](https://www.threads.com/@wsxiaolu666?igshid=NTc4MTIwNjQ2YQ==)

## Argon主题博客美化

==导入准备好的主题设置JSON==

------

找到argon主题设置选项 点击右下角"到底部" 没有就将页面下滑一点点

点击导入设置

==更换网站图标==

------

然后设置网站图标 点击外观 自定义 点击站点身份 跟换站点图标 上传文件 更换 点击发布

==添加网站导航==

------

点击文章 点击分类目录 添加其他的分类：文章 说说 聊天 关于 将默认的第一个分类修改名称为首页，分类的别名自己看着来

添加好分类后 点击外观 点击菜单 菜单名：网站导航 菜单项：点击分类目录 点击查看所有 点击全选 点击添加至菜单 点击保存菜单

==给网站导航和其他内容配置CSS(包含透明设置)==

------

点击外观 点击自定义 点击额外CSS 将当前文件目录下的 额外CSS.css 文件里面的内容复制到网站额外CSS设置里面点击发布

==给后台设置一个自己的头像==

------

点击插件 点击添加新插件 搜索User Profile Picture 添加后启用 然后点击用户 点击个人资料 点击Profile Image 上传图片更改即可 同时修改管理配色方案为argon 名字 昵称 公开显示为 邮箱 点击更新个人资料

==给网站上传白天和黑夜的背景==

------

点击媒体 点击添加文件 上传即可 上传好后点击图片可查看图片的位置 复制图片url位置 点击argon主题选项 点击右边大纲--页面背景 粘贴url地址到页面背景/页面背景(夜间模式时)输入框

==菜单图标==

------

首页

```Plain
<i class="fa fa-home"></i>
```

文章

```Plain
<i class="fa fa-book" aria-hidden="true"></i>
```

说说

```Plain
<i class="fa fa-comment-o" aria-hidden="true"></i>
```

关于

```Plain
<i class="fa fa-question-circle" aria-hidden="true"></i>
```

聊天

```Plain
<i class="fa fa-comments" aria-hidden="true"></i>
```

bilibili主页

```Plain
<i class="fa fa-youtube-play" aria-hidden="true"></i>
```

归档

```Plain
<i class="fa fa-clock-o" aria-hidden="true"></i>
```

==年度倒计时显示==

------

点击外观 在左侧栏里面添加工具--简码

```Plain
<div class="progress-wrapper" style="padding: 0">
<div class="progress-info">
<div class="progress-label">
<span id="yearprogress_yearname"></span>
</div>
<div id="yearprogress_text_container" class="progress-percentage">
<span id="yearprogress_progresstext"></span>
<span id="yearprogress_progresstext_full"></span>
</div>
</div>
<div class="progress">
<div id="yearprogress_progressbar" class="progress-bar bg-primary"></div>
</div>
</div>
<script no-pjax="">
function yearprogress_refresh() {
let year = new Date().getFullYear();
$("#yearprogress_yearname").text(year);
let from = new Date(year, 0, 1, 0, 0, 0);
let to = new Date(year, 11, 31, 23, 59, 59);
let now = new Date();
let progress = (((now - from) / (to - from + 1)) * 100).toFixed(7);
let progressshort = (((now - from) / (to - from + 1)) * 100).toFixed(2);
$("#yearprogress_progresstext").text(progressshort + "%");
$("#yearprogress_progresstext_full").text(progress + "%");
$("#yearprogress_progressbar").css("width", progress + "%");
}
yearprogress_refresh();
if (typeof yearProgressIntervalHasSet == "undefined") {
var yearProgressIntervalHasSet = true;
setInterval(function () {
yearprogress_refresh();
}, 500);
}
</script>
<style>
#yearprogress_text_container {
width: 100%;
height: 22px;
overflow: hidden;
user-select: none;
}
#yearprogress_text_container > span {
transition: all 0.3s ease;
display: block;
}
#yearprogress_text_container:hover > span {
transform: translateY(-45px);
}
</style>
```

==添加嘉然看板娘==

------

主题设置页脚

添加代码

```Plain
</script>
<!--live2d--> 
<script src="/wp-content/themes/argon/argon/live2d/TweenLite.js"></script> 
<script src="/wp-content/themes/argon/argon/live2d/live2dcubismcore.min.js"></script>
<script src="/wp-content/themes/argon/argon/live2d/pixi.min.js"></script> 
<script src="/wp-content/themes/argon/argon/live2d/cubism4.min.js"></script> 
<link href="/wp-content/themes/argon/argon/live2d/pio.css" rel="stylesheet" type="text/css"/> 
<script src="/wp-content/themes/argon/argon/live2d/pio.js"></script> 
<script src="/wp-content/themes/argon/argon/live2d/pio_sdk4.js"></script> 
<script src="/wp-content/themes/argon/argon/live2d/load.js"></script>
```

## IDM激活工具

IDM终生激活版是一款经过完整激活的Internet Download Manager（IDM）软件版本，提供终身授权，免除反复注册和付费的困扰。使用前需先卸载旧版本IDM，并运行附件中的“IDM卸载后执行.bat”脚本，彻底清理以往安装残留文件，确保后续安装干净无误。

安装步骤如下：首先前往IDM官网下载最新版安装包并完成安装。安装完成后，完全退出IDM程序，执行附件内的“IDM_6.4x_Crack_v19.7”破解文件，以实现软件的永久激活。破解成功后，打开IDM，点击“注册”菜单并选择“注册”，即可在注册状态中确认已成功授权，享受全部高级功能。

如果遇到浏览器集成失败的问题，导致浏览器扩展未自动安装，可以手动解决。进入IDM的安装目录，找到对应浏览器的插件文件，例如使用Chrome浏览器时，找到名为IDMGCExt.crx的扩展文件（Google Chrome扩展）。打开Chrome浏览器的扩展程序页面，启用开发者模式，将该crx文件拖入扩展程序页面完成安装，即可恢复浏览器与IDM的完美集成，保证下载管理功能正常工作。

该版本激活后，IDM具备完整的下载加速、断点续传、多线程下载、浏览器深度集成等核心功能，极大提升下载效率和体验。通过清理旧版残留、确保软件最新版本安装和手动修复浏览器插件等多重步骤，保证软件环境的稳定和使用的顺畅，是资深用户和下载需求量大用户的理想选择。

------

📦 资源下载地址

🔗 [点击这里下载资源](https://yun.139.com/shareweb/#/w/i/2qidZUhg0qtja)

## 视频播放器

------

💻介绍

- 支持多种视频、音频格式，无需额外解码器
- 播放流畅不卡顿，且能进行多种画面优化调整

[点击下载](https://wwmi.lanzouo.com/i2OPJ2i3lsle)

![img](https://www.30aitool.com/wp-content/uploads/2024/10/2024121408280531.webp)

## 专业卸载工具

**HiBit Uninstaller（适用性最强）**

------

🏆优点

- 免费免安装，功能齐全
- 批量卸载、强制删除基础功能都有，并且支持创建恢复点

🥷缺点

- （待补充）

**特别注意点**：如果你电脑没下载过太多的流氓软件，就不要过渡的清理注册表！要不然有小概率会误删，从而导致系统部分驱动缺失（最稳妥的还是使用火绒的垃圾清理即可），当然也不用太过担心，在清理的时候记得勾选上备份就可以了，基本出问题就是实时反馈的，到时候在恢复注册表即可，以及也可以在重新装对应的驱动，但是对于小白用户而言

切记！不要过渡清理注册表，因为Windown电脑环境比较复杂**，特别是win7！如果你电脑是win7，那么就不要乱动，很容易出现驱动丢失，win7我只建议使用火绒清理**；其他的也是切记不要过度操作，简单干净稳当使用才是最重要的

[点击下载](https://wwmi.lanzouo.com/b00oczjopg)

[官网下载](https://www.hibitsoft.ir/Uninstaller.html)

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025050905063611.webp)

如果遇到这种选择选那个都可以，**只是存储位置不同，小白就直接选第一个即可**

![img](https://www.30aitool.com/wp-content/uploads/2025/10/1767103884-7e1b3ac2b520224fe4b40b535bd6e5a0569150588.png)



**‎‎‎‎‎‎‎ㅤIObit Uninstaller（功能齐全）**

------

🏆优点

- 更加全面的功能、操作简单、页面UI美观

🥷缺点

- 满血功能需要购买才能解锁

[点击下载](https://wwmi.lanzouo.com/b00oczjoxe)

[官网下载](https://www.iobit.com/en/advanceduninstaller.php)

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025050905154794.webp)

**‎‎‎‎‎‎‎ㅤGeek Uninstaller（小而精悍）**

------

🏆优点

- 2M大小无需安装、便携使用、该有的功能都有

🥷缺点

- 有误删注册表的风险
- 若是十分小白的用户，不太推荐使用

[点击进入](https://wwmi.lanzouo.com/b00oczjptg)

[官网下载](https://geekuninstaller.com/)

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025051004250937.webp)

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025051900494621.png)

‎‎‎‎‎‎‎ㅤ其他软件（适合进阶玩家）

------

**Total Uninstall**

**💻简述：**可直观的看见软件相关文件夹和注册表位置

[点击下载](https://wwmi.lanzouo.com/b00oczjp4b)

[官方地址](https://www.martau.com/zh-CN/)

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025050910105386.webp)

**BCUninstaller**

💻**简述**：Github著名卸载工具项目，功能十分的齐全

[点击下载](https://wwmi.lanzouo.com/iuVj42wl5gvi)

[官方地址](https://github.com/Klocman/Bulk-Crap-Uninstaller)

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025051815440320.webp)

**卸载软件知识点**

**‎‎‎‎‎‎‎ㅤ软件安装和卸载**

------

**常见误区：直接删除桌面图标**

很多人第一次尝试"卸载"软件时，会简单地将桌面图标拖入回收站。这种方式实际上只是删除了软件的快捷方式，并不会卸载软件本身。

快捷方式本质上只是一个"指向器"，它指向软件的实际安装位置。我们可以右击桌面图标，选择"属性"，在"快捷方式"选项卡中看到"目标位置"——这才是软件真正的安装位置。删除快捷方式对软件本体没有任何影响。

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052709174738.webp)

**为什么直接删除软件文件夹也不够？**

有人可能会想：既然知道了软件的安装位置，直接删除整个文件夹不就解决问题了吗？

实际上，这种方式依然不够彻底。因为软件安装时，除了在指定目录安装主程序外，通常还会：

- 在系统盘创建配置文件
- 在注册表中添加信息
- 在其他位置存储缓存和数据文件
- 可能安装系统服务或驱动程序

**系统自带的卸载功能**

Windows的"程序和功能"(控制面板)或"应用和功能"(设置)提供的卸载功能是较为标准的卸载方式，其实对于大部分人是够用的，就用于卸载一些常见的通用软件

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052709193871.webp)

然而，某些流氓软件，在卸载后可能仍会留下配置文件、缓存或注册表残留。这也是为什么有些软件卸载后还能"死灰复燃"的原因之一。

**专业卸载软件的优势**

使用第三方专业卸载工具通常能提供更彻底的卸载体验，它们的优势包括：

- 卸载完成后自动扫描并清理相关残留文件
- 提供批量卸载功能，节省时间
- 针对顽固软件的强制卸载功能
- 更直观的用户界面，便于操作

对于重要系统或需要彻底清除的流氓软件，使用专业卸载工具是最佳选择

**‎‎‎‎‎‎‎ㅤ常见的流氓软件**

------

**‎‎‎‎‎‎‎传奇系列**

这类就不用多说了，看到直接卸载，我相信大部分的人都是被迫下载的，而不是真的想玩这类游戏

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052709212083.webp)

**360系列**

视频里面说到，360安全卫士，其实说不上是流氓软件，360的杀毒技术是世界第一梯队的，但是360 安全卫士最好还是卸载，因为说对于大部分用户都驾驭不了它，或者说没必要，现在 win 自带的防护其实是就够用了，电脑很少会出现中病毒的情况（正常使用情况下），而更多是被流氓软件干扰

这里也包括腾讯的电脑管家、金山毒霸等，基本都是处于一个“过度保护“（对于普通人），电脑若要安装第三方的防护，这里我这里推荐一个火绒这个产品，纯净没弹窗，该有的功能都有

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052709253687.webp)



**2345系列**

如果说360系列是普通人不好驾驭，那么2345则是适合三体人用

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052709275556.webp)

**AI软件**

**每个时代都有每个时代的流氓软件**，这类软件核心就打信息差和大量的广告轰炸，例如像之前网络很火的deepseek本地部署，关于本地部署是需要钱的，但是就有一些厂家进行一个包装就收取费用（主要还垃圾）；还有AI对话、写作这些，基本都是接一个api就拿出来卖钱，真正的体验远远不如大厂的产品，而且大厂的是免费的呀

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052709440028.jpg)

**收费工具**

像图片压缩、格式转化、音频转换、PDF编辑这些工具基本都是有开源免费的，就还是一个信息差的问题，我网站上也基本整理了常见的各种工具的免费网站以及免费的本地软件了

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052709522632.webp)

**ㅤ卸载软件注意事项**

------

在讲 geek 那里的时候我提到卸载微软组件会导致问题发生，**当然用其他的卸载也不行，切记小白不要去卸载微软自带的一些组件，特别是 v++**

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052709590277.webp)

在卸载一些比较大型的生产力软件，例如 adobe 或者大学里的专业软件，在卸载的时候，记得最好使用可以进行注册表备份的产品，避免导致连带误删的情况



卸载流氓软件的时候要拿出考试审题的态度来卸载

**补充延申**

------

欢迎你在抖音或者B站评论区留言遇到的更具体的问题和不同的情况，我看到会进行补充在网站这里，让更多人可以少走弯路！

ㅤ之前没卸载干净怎么办？

![img](https://www.30aitool.com/wp-content/uploads/2025/10/1766645277-image.png)

这种情况可以可以使用上面提到的[hibit](https://www.30aitool.com/3886.html#H3-1)右上角的工具＞注册表清理程序（纯小白不建议，建议用火绒就可以）

也可以实用[火绒](https://www.30aitool.com/4031.html#H3-9)里面的垃圾清理功能也是可以清理掉注册表垃圾的，在搭配上其他的漏洞修复和系统扫描，来个电脑大检查下

![img](https://www.30aitool.com/wp-content/uploads/2025/10/1766645016-image-347.png)

![img](https://www.30aitool.com/wp-content/uploads/2025/10/1766645192-image_348.webp)

## 浏览器插件

**起始页优化**

------

以点右上角的设置，然后按照图片这样把能关的都关了，起始页就会十分的简洁

![img](https://www.30aitool.com/wp-content/uploads/2025/10/image-56.webp)

如果是360页面，**就是被360和鲁大师给劫持了**，可以按下面的修改掉，但是我还是建议直接卸载掉！360如果说想留还有点理由，鲁大师这家伙一定要卸载了，具体可查看这篇文章[“捉迷藏”式收割：撕开鲁大师为首系列企业流量劫持黑幕！-技术文章-火绒安全](https://www.huorong.cn/document/tech/vir_report/1858)总结一句话就是:“让我感觉恶心”

![img](https://www.30aitool.com/wp-content/uploads/2025/10/1766856466-%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20251228012702.jpg)

**使用系统自带的卸载 360 和广告大师，主页被篡改的问题往往依然存在，必须清理相关掉注册表才行**，所以建议使用第三方专业卸载工具。如果你已经直接卸载了，也不用担心，可以使用 Hibit 或其他清理工具，专门扫描并清理残留的注册表。关于清理流氓软件的详细内容，如果没看过本系列的第一课

**起始页插件****

------

👉[i**Tab新标签页**](https://microsoftedge.microsoft.com/addons/detail/itab新标签页/inedkoakiaeepjoblbiiipedngonadhn?hl=zh-CN)

我的预设👉[预设下载](https://lz.qaiu.top/parser?url=https://share.feijipan.com/s/aqZAbwQ4)

其他起始页：[青柠起始页](https://microsoftedge.microsoft.com/addons/detail/青柠起始页/pcpnigdkpcgemocnjhebmajldpjlbeom?hl=zh-CN)、[infinity](https://microsoftedge.microsoft.com/addons/detail/infinity-新标签页-pro/hajlmbnnniemimmaehcefkamdadpjlfa?hl=zh-CN)

一个好的浏览器首页可以帮你快速启动常用的网站提高工作效率，以及页面的样式可以高度自定义成自己喜欢的样式；设置好一个浏览器主页+视频里面提到的收藏夹整理技巧，基本就可以让你从此打开网址十分的友谊了

![img](https://www.30aitool.com/wp-content/uploads/2025/05/PixPin_2025-10-02_16-17-01.webp)

**收藏夹整理技巧**

- 改写：改写收藏夹上面的网站标题，不仅能节省收藏栏空间，还能使用相关关键词进行搜索

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052804232599.png)

- 拖拽：直接拖动到收藏栏的目标位置 这种方法让您能够精确控制新收藏的位置，无需事后再调整排序

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052804294324.gif)

- 分段：利用空白logo 网站进行分段，网站地址👉[空白logo网站](https://separator.mayastudios.com/?horz#bookmark-differentiator--234fd716-90a2-493e-a7bc-923fcc337323)

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052804380181.webp)

**‎‎‎‎‎‎‎ㅤ通用插件**

------

👉[**AdGuard**](https://microsoftedge.microsoft.com/addons/detail/adguard-广告拦截器/pdffkfellgipmhklpdmokmckkkfcopbh?hl=zh-CN)

核心功能就是进行网站弹窗广告的拦截，也是被誉为最好的电脑浏览器广告拦截，下面是案例图，可以拦截任何网页上面的广告

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052105231849.webp)

👉[**沉浸式翻译**](https://microsoftedge.microsoft.com/addons/detail/沉浸式翻译-网页翻译插件-pdf翻译-/amkbmndfnliijdhojkpoglbnaaahippg?hl=zh-CN)

提供翻译模型选择、支持对网站、视频、文章、PDF、漫画进行翻译；还有其独特的双语对照翻译模式、简便的操作方式也是被大量网友誉为最好的浏览器翻译插件；我个人用的比较多除了悬浮球点击翻译，**以及快速敲三下空格键就可以进行翻译成英文，这个除了搜索框，在其他页面也是可以的**

我个人是建议下载好后，进入设置页面里面看下里面的[官方说明书](https://immersivetranslate.com/zh-Hans/docs/faq/)，这个浏览器插件可以是说是功能集大成的代表之一，在翻译这个了领域做到头了

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052105342059.webp)

👉[**AIX智能下载器**](https://microsoftedge.microsoft.com/addons/detail/aix智能下载器图片视频音乐文档/pljfekbkmmbkdfhddpebdlmfngigcohc?hl=zh-CN)

可以从网站上下载在线视频、音乐、MP3、图片等

**注意点**

- 1、这个插件并不是什么图片、视频、音频、文件都可以被可以被下载到! 例如像一些传统的电影平台、网课、知识付费平台等这些都是不能的（尊重知识版权）
- 2、下载B站视频最高只能下载720p的视频，若想下载原画质则是需要专门的B站下载软件，在我网站里面👉[视频下载30aitool](https://www.30aitool.com/397.html#H3-2)
- 3、若对于视频下载的需求比较重，可以再下载一个叫“[猫抓](https://microsoftedge.microsoft.com/addons/detail/猫抓/oohmdefbjalncfplafanlagojlakmjci?hl=zh-CN)”的拓展这个的视频获取能力会比aix下载器强，猫抓甚至还有直接录屏功能

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052105524419.webp)

[👉**视频速度控制**](https://microsoftedge.microsoft.com/addons/detail/global-speed-视频速度控制/mjhlabbcmjflkpjknnicihkfnmbdfced?hl=zh-CN)

网站通用，自动应用于所有网站上播放的全部视频和音频，倍**速自定义并且支持快捷操作,推荐设置下快捷键，体验感会十分的好**；但是在设置自定义快捷键的时候，要注意是否与其原本的有冲突

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052105565196.webp)

**‎‎‎‎‎‎‎ㅤ其他推荐**

------

👉**[获取B站字幕文件](https://microsoftedge.microsoft.com/addons/detail/bilibili-字幕提取器/piefbmcaopkgkcdimjlegiacighgoinb?hl=zh-CN)**
获取后，在发给AI就可以针对性整理笔记了
但是记得并不是所有的视频都有字幕文件

![img](https://www.30aitool.com/wp-content/uploads/2025/10/image-54.webp)

👉[**跳过B站恰饭片段**](https://microsoftedge.microsoft.com/addons/detail/小电视空降助手/khkeolgobhdoloioehjgfpobjnmagfha?hl=zh-CN)
从此再也没有看过转转和妙界了

![img](https://www.30aitool.com/wp-content/uploads/2025/10/image-55.webp)

👉**[豆瓣评分趋势](https://www.crxsoso.com/webstore/detail/mompgifjlbbfcmgfgpfjdhhaibnmamki)**
图一乐这块

![img](https://www.30aitool.com/wp-content/uploads/2025/10/image-53.webp)

👉[**豆瓣跳转其他平台**](https://microsoftedge.microsoft.com/addons/detail/douban-book/kfdimcpljilcbhmlogkagbbjpjkdihom?hl=zh-CN)
可跳转微信读书、zlibrary

![img](https://www.30aitool.com/wp-content/uploads/2025/10/image-1.png)

👉**[找类似网站](https://microsoftedge.microsoft.com/addons/detail/edge-的类似网站/gcadmjofigcidaecpelabbdhdkkgkbko?hl=zh-CN)**
根据当前网站推荐同类型的网站

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052109125917.webp)

👉[**高清长截图当前网页**](https://microsoftedge.microsoft.com/addons/detail/gofullpage-full-page-sc/hfaciehifhdcgoolaejkoncjciicbemc?hl=zh-CN)
可跳转微信读书、zlibrary

![img](https://www.30aitool.com/wp-content/uploads/2025/10/image-2.png)

👉**[批量AI搜索的](https://microsoftedge.microsoft.com/addons/detail/学术资源全网搜索/jinddgjhfchibbpdohnllegfjllidhpk?hl=zh-CN)**
除了AI搜索还有其他的资源批量搜索

![img](https://www.30aitool.com/wp-content/uploads/2025/10/image-3.png)

👉**[小红书笔记下载助手](https://microsoftedge.microsoft.com/addons/detail/小红书笔记下载助手/aajfehiicohpgdimepmpjgeajecagdgb)**
可批量采集笔记

![img](https://www.30aitool.com/wp-content/uploads/2025/10/image-4.png)

‎‎‎‎‎‎‎**寻找扩展**

------

[👉**CRX扩展商店**](https://www.crxsoso.com/)

crx网站聚合了各种浏览器扩展程序，收录了大量谷歌插件市场的插件。由于谷歌插件市场需要魔法上网才能访问，CRX提供了更便捷的下载方式，用户可以直接下载插件文件进行手动安装

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025052214441635.webp)

关于浏览器扩展，剩下的最好就是根据自己的职业或者日常习惯来做配置，这里我推荐使用 crx 浏览器插件这个网站，简单来说是一个整合了大量的浏览器插件的平台，可以根据**自己的需求和职业搜索关键词**

**注意要点**

- 若电脑配置一般不建议多装插件，够用就行，edge本身就是很吃电脑内存的，若在装了过多的浏览器插件就会导致电脑卡顿了

**🚀快捷操作**

------

**关闭网页**：我个人用最多的就是关闭其他页，因为大部分都会有打开一堆网页的情况，这个还是很实用的（可以绑定快捷手势），若想保留特定的两个就可以拖到下位置选择关闭右侧标签页，以及使用鼠标的滚轮键关闭，也可以用ctrl+w的快捷键关闭

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025062604313931.webp)

**快捷手势**：视频我演示的案例，是绑定了一个关闭其他页，大家也可以自行研究下其他的手势使用

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025062605120623.webp)

**拖拽逻辑**：文件基本都是可以被拖拽添加的，不一定要按照上传文件，这对于绝大多数网站软件是都用的逻辑

**收藏夹启动**：如果是打工人，应该每天上班都有几个是固定要打开的网页后台数据、邮箱之类的，这时候就可以放在一个收藏夹里面，只需要右击就可以一键打开

![img](https://www.30aitool.com/wp-content/uploads/2025/05/2025062605155049.webp)



**软件下载教程**

**软件搜索下载**

我个人建议使用必应或者谷歌（有条件的话）直接搜索下载，基本都排列在第一个。如果你确实习惯使用国内搜索引擎，那就安装一个广告拦截插件，并且认准有"官网"二字标识的！这样就基本不会下载错了。常被下载错的Steam，官方地址是"[store.steampowered.com/](https://store.steampowered.com/about/)"。

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025062813493032.webp)

有人会问："我用电脑的xx市场下载可以吗？"我个人对于软件下载还是建议直接进官网下载，这是最直接的方式。第三方软件市场并不是什么软件都有，每个人的电脑都不同自带的商店也不同，这里我不好做判断

**‎‎‎‎‎‎‎安装注意项**

- 软件下载好后，安装时要查看安装路径。一般软件的安装路径默认都是C盘，建议安装到其他盘符。有些软件也会安装的时候就同时让你选择缓存文件的存放位置，也尽量也不要放到C盘。

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025062814212627.png)

- 软件安装的目录名称，最好设置为英文，不要用中文以及不要有空格。有些软件会因为目录是中文而导致运行不了，为了避免后期不必阳的麻烦，软件路径要设置为英文。

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025062814125127.png)

- 软件安装完成后，要注意检查是否有捆绑软件软件！

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025062814243130.png)

**‎‎‎‎‎‎‎缓存文件设置**

软件安装后要养成好习惯，先进入设置修改下文件缓存位置，因为基本都是默认在C盘的，若你已经有软件是缓存在C盘的了，你也可以切换文章，基本都会进行文件的迁移的

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025070209505627.png)

电脑缓存文件大头基本是微信(以及QQ），快去检查下你的微信缓存文件设置吧

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025070209520167.png)

**‎‎‎‎‎‎‎ㅤPCDN关闭**

PCDN详细科普内容推荐：

简单来说电脑里面装有：腾讯视频、爱奇艺、优酷、QQ音乐这四个的客户端就要小心了（当然其他的像手机和电视端也有，这里欢迎大家补充），按照下面的图进行关闭掉这个所谓的“加速付费”

![img](https://www.30aitool.com/wp-content/uploads/2025/10/Frame_484.webp)

如果电脑里面装有火绒的话，可以使用里面的流量监控进行查看，最好是进行上传速度限制，根据网上有人反馈，即使关闭了加速服务的选项依旧会偷偷上传

![img](https://www.30aitool.com/wp-content/uploads/2025/10/Frame_490.webp)

**‎‎‎‎‎‎‎下载被拦截**

如果你在其他第三方平台下载软件的时候，可能会出现下面的样式，这是被微软自带的Microsoft Defender 拦截了

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025070208585573.png)

点击被禁止文件旁边的三个点，就可以点击保留就可以了；也可以进入浏览器的设置把Microsoft Defender SmartScreen这个选项给关闭之后就再也不会出现了

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025070209032330.png)

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025070209004177.png)

Microsoft Defender是win电脑自带的安全防护，但是也经常被吐槽“过度保护”，遵循着宁可误杀也不放过的原则，有时候甚至会直接给把它认为的风险文件给直接删除了，下面讲下如何关闭

（但是关闭有风险，纯小白谨慎操作，若你已经掌握了我上面提到的下载软件进官网下载，以及电脑还有第三方的防护软件，例如下面提到的火绒，则基本就不会有问题）

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025070209443973.jpg)

操作步骤：直接在win哪里搜索安全两个字，进入到win安全中心，点击病毒和威胁防护，刷到最下面把下面的那个“MicrosoftDefender防病毒选项”给关了

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025070209483187.png)

**‎‎‎‎‎‎‎ㅤ软件版本选择**

对于普通用户：Windows 11 系统直接盲选 x64 版本，这是当前最主流的架构，99% 的情况都适用。遇到架构选择的情况并不多见：主流软件通常会自动识别系统或只提供单一版本，其实只有部分开源工具、开发软件才会列出多个架构选项。

32位系统基本已接近淘汰，除非你使用 2015 年前的老旧电脑或仍在坚守 Windows 7 系统，否则基本不会遇到 32 位系统，而ARM64 普通 Windows 电脑用户暂时无需关注。

![img](https://www.30aitool.com/wp-content/uploads/2025/06/%E5%AF%B9%E6%A0%87.webp)



软件的免安装便携版和安装版怎么做选择呢？一句话：临时用选免安装，常用选安装版。

![img](https://www.30aitool.com/wp-content/uploads/2025/06/PixPin_2025-10-08_08-16-50.webp)



**必装软件**

**‎‎‎‎‎‎‎ㅤNDM（下载器）**

------

NDM是一款免费开源的下载管理器，体积小巧不到1MB，安装后会自动接管浏览器的下载功能。它不仅能提升下载速度，还能智能嗅探网页中的视频、音频等资源，让下载内容更加方便

[点击下载](https://wwmi.lanzouo.com/iLlwQ24qij2h)

[官网下载](https://neatdownloadmanager.com/index.php/en/)

<video height="1080" width="1920" controls="" src="https://www.30aitool.com/wp-content/uploads/2024/10/2024101308283314.mp4" style="max-width: 100%; height: auto; vertical-align: middle; width: 878px; aspect-ratio: 1920 / 1080;"></video>

使用注意事项：若出现下载错误的情况以及若下载速度很慢的情况，就点击插件即可暂停使用，这是小概率情况；绝大多数情况NDM在下载这方便还是很省心好用的

延伸：提到下载器，肯定会有人提到IDM，虽然知名度更高，但需要付费买断使用。虽然有不少网上的破解版，但存在稳定性问题，且对于普通用户来说操作相对复杂，学习成本较高，我还是推荐NDM这样开箱即用的免费方案

**‎‎‎‎‎‎‎ㅤ火绒（安全防护）**

------

具备广告拦截、杀毒防护和垃圾清理等基础功能。我个人觉的它最大的优势“安静”，不会有任何弹窗打扰，就在默默后台守护你的电脑，这在充斥着各种弹窗广告的安全软件市场中堪称一股清流

当然没有软件是完美的，在我收集资料的时候发现有些用户装火绒会导致部分文件误删或者黑屏的情况（小概率），因为win的环境本来就复杂，而且不同的win版本号也不会不同的情况；若你电脑也出现这种情况就卸载掉就好了

延伸内容：[C盘清理思路and工具](https://www.30aitool.com/990.html)

[官网下载](https://www.huorong.cn/)

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025062813280778.webp)

**‎‎‎‎‎‎‎ㅤPotplayer（播放器）**

------

支持几乎所有主流音视频格式，内置强大的解码能力和硬件加速功能。最主要自定义能力特别强，你想的到和想不到的设置它都有

图2常用设置，potplayer还是要设置一下才会更顺手使用，大家也可以自行研究下
图3常用快捷键，我这里仅总结了几个较高频的使用的

Potplayer还可以通过安装：madVR、LAV Filters、xy-VSFilter三大插件获得更好的画质、解密、字幕但仅推荐进阶玩家进行研究；以说到播放器肯定绕不过：VLC、MPV这两个同类型竞品，但是我还是推荐Potplayer很主要一个原因是它使用人群是最多的，这样找对应的教程和经验分享相对比较方便（以及我自己也是从高中用到现在了）

[官网下载](https://potplayer.tv/)

[点击下载](https://wwmi.lanzouo.com/iCvzy2zuwnoh)

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025062813340715.webp)

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025070314450025.webp)

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025070315002634.png)

**ㅤ360zip（解压软件）**

------

👉[压缩软件#解压#7zip#‎‎‎‎‎‎‎Bandizip#360国际版#winraw ](https://www.30aitool.com/982.html)👈

**ㅤ图吧工具箱（检测合集）**

------

集成了几十种常用硬件检测工具，一个软件包解决所有检测需求

[点击下载](https://wwmi.lanzouo.com/iV5l12ztb14d)

[官网下载](https://www.tbtool.cn/)

![img](https://www.30aitool.com/wp-content/uploads/2025/06/2025062813354139.webp)

------

**网易云ncm转mp3**

网易云音乐文件格式转换，ncm 转 mp3，批量转换，速度飞快

![](https://s41.ax1x.com/2026/02/06/pZoMOud.jpg)

[点击进入](https://www.ncm2mp3.com/)

## 搜索

**线上处理**

------

**AI搜索**

------

利用AI搜索找资源时，可以优先考虑接入平台的大模型，例如豆包接入的是抖音，秘塔的针对性搜索也做得比较好。市面上总有一些大模型特别擅长搜索找资源，可以多问问AI。

不过以我的经验来看，还是有点抽卡属性——每个主流模型其实差别不大，可能这次它给的质量高，下次是另一个高。所以我个人觉得最好的办法还是使用交叉搜索，多搜索几个，然后取交集。

需要注意的是，AI搜索结果来源仍然是互联网上的公开内容，且更偏向权重高、传播广的文章。这意味着许多小众、新上线或仅在特定圈子流传的优质工具，基本不会被收录。这种情况就需要去即刻（用手机体验感会比较好）V2EX、Reddit等垂直社区寻找。

[即刻](https://web.okjike.com/following)

[V2EX](https://www.v2ex.com/)

[Reddit](https://www.reddit.com/)

![img](https://www.30aitool.com/wp-content/uploads/2025/10/image-51.webp)

一次性调用多个AI搜索用到的插件叫[学术资源全网搜索](https://microsoftedge.microsoft.com/addons/detail/学术资源全网搜索/jinddgjhfchibbpdohnllegfjllidhpk?hl=zh-CN)（点击即可跳转下载）

![img](https://www.30aitool.com/wp-content/uploads/2025/10/1766665114-image.png)

**‎‎‎‎‎‎‎ㅤ插件&脚本**

------

只要是在网页上用的,我都建议你优先考虑浏览器插件。因为浏览器插件真的足够简单、足够轻量化,而且大部分都是免费的,用起来也比较丝滑,最关键是选择多、生态完整,基本上你想要的功能都能找到。

另外如果你本身就在用Quicker这个工具的话,（还是很推荐的）,因为Quicker里面有很多现成的动作库,特别是那种需要流程化操作的场景,触发起来就很快，就很丝滑，就很适合微高频的需求

[CRX扩展商店](https://www.crxsoso.com/)

[Quicker动作库](https://getquicker.net/)

![img](https://www.30aitool.com/wp-content/uploads/2025/10/%E6%89%BE%E8%BD%AF%E4%BB%B61018%EF%BC%88%E4%B8%8A%E5%AD%97%E5%B9%95%EF%BC%89.00_03_01_12.Still002.webp)

**‎‎‎‎‎‎‎ㅤAI“手搓”**

------

现在AI手搓工具的门槛是越来越低了，随着AI能力的提升，你基本上就是把需求说给它听就行（当然你也别提太逆天的需求）尽量控制在一些简单的批量操作上，比如图片处理、文本处理，或者生成一些网页小工具，这些AI都能帮你搞定。

关于提问技巧，我常用的方法是先把简单的需求发给AI，然后再补一句"你觉得还有什么要补充的吗"，让AI反过来问你。因为其实大部分人对自己的需求都是模糊的，但AI做程序需要十分清晰的指令，所以让它来帮你梳理需求会更高效。基本的口令就是"生成一个可以在线运行的HTML小工具"，关于这块因为迭代太快了，你可以直接在小红书或B站上搜"AI生成HTML小工具"，能找到很多案例。我真的强烈建议每个人都去尝试一下，因为你能感受到那种创造的快乐，没有人能拒绝创造的快乐

![img](https://www.30aitool.com/wp-content/uploads/2025/10/image.png)

**‎‎‎‎‎‎‎ㅤ在线方案总结**

------

（待补充完善）

![img](https://www.30aitool.com/wp-content/uploads/2025/10/%E5%9C%A8%E7%BA%BF%E6%80%BB%E7%BB%93%E6%88%AA%E5%9B%BE.webp)

**💻本地处理**

**‎‎‎‎‎‎‎ㅤ吾爱破解**

------

你可以在上面找到很多有意思或者实用的工具。但其实对于小白而言，我更推荐先在吾爱破解上搜索，再去GitHub上找。因为吾爱上面真的有很多大神在分享精炼的小众产品，其实很多资源本身也是来自GitHub的，但上面的大神们会把它们汉化、修改、优化等，以及会有很多大神手搓的应用。包括我自己在找一些本地小工具的时候，可能还是更偏向去吾爱找——门槛更低一点，毕竟是国内的平台。

[点击进入](https://www.52pojie.cn/)

![img](https://www.30aitool.com/wp-content/uploads/2025/10/image-52.webp)

**‎‎‎‎‎‎‎ㅤGithub**

------

很多人觉得它是一个代码相关的平台，跟并非程序员的人没什么关系。其实不是滴！你可以理解为，程序员们秉持着互联网的开源精神，会在上面分享很多优质好用的工具、产品，或者资料整合包。一般来说，极客们会在那边分享很多有意思的好东西。

关于GitHub的具体使用，我这里就不做过多介绍了，因为UP主痕迹做的那两期视频（）已经讲得很好了，，那两期视频对于大家入门是完全够用的。我可能后面会分享一些其他github项目，或者一些进阶用法，但入门的话先看他的教程就行，记得给他一键三连，好教程值得

[点击进入](https://github.com/)

![img](https://www.30aitool.com/wp-content/uploads/2025/10/eb6mwB9p2oLX45QaMGxYtg.webp)

‎‎‎‎‎‎‎**ㅤ在线方案总结**

------

（待补充完善）

![img](https://www.30aitool.com/wp-content/uploads/2025/10/%E6%9C%AC%E5%9C%B0%E6%80%BB%E7%BB%93.webp)
