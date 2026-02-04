# 我是小卢想睡觉的博客

## 关于

[telegram](https://www.t.me/wsxiaolu666)

[X](https://x.com/wsxiaolu?s=21)

[YouTube](https://www.youtube.com/@wsxiaolu)

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

![封面](https://dw.jichun29.cn/img/resource/2025/11/16464b9df3a8838f6ca850dad10cfa0d_691d217724b41.jpeg)

IDM终生激活版是一款经过完整激活的Internet Download Manager（IDM）软件版本，提供终身授权，免除反复注册和付费的困扰。使用前需先卸载旧版本IDM，并运行附件中的“IDM卸载后执行.bat”脚本，彻底清理以往安装残留文件，确保后续安装干净无误。

安装步骤如下：首先前往IDM官网下载最新版安装包并完成安装。安装完成后，完全退出IDM程序，执行附件内的“IDM_6.4x_Crack_v19.7”破解文件，以实现软件的永久激活。破解成功后，打开IDM，点击“注册”菜单并选择“注册”，即可在注册状态中确认已成功授权，享受全部高级功能。

如果遇到浏览器集成失败的问题，导致浏览器扩展未自动安装，可以手动解决。进入IDM的安装目录，找到对应浏览器的插件文件，例如使用Chrome浏览器时，找到名为IDMGCExt.crx的扩展文件（Google Chrome扩展）。打开Chrome浏览器的扩展程序页面，启用开发者模式，将该crx文件拖入扩展程序页面完成安装，即可恢复浏览器与IDM的完美集成，保证下载管理功能正常工作。

该版本激活后，IDM具备完整的下载加速、断点续传、多线程下载、浏览器深度集成等核心功能，极大提升下载效率和体验。通过清理旧版残留、确保软件最新版本安装和手动修复浏览器插件等多重步骤，保证软件环境的稳定和使用的顺畅，是资深用户和下载需求量大用户的理想选择。

------

📦 资源下载地址

🔗 [点击这里下载资源](https://yun.139.com/shareweb/#/w/i/2qidZUhg0qtja)

------

📸 资源图片展示

![资源图片1](https://dw.jichun29.cn/img/resource/2025/11/9NSHDJe_691d216f1e3df.webp)

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
