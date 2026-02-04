# 我是小卢想睡觉的博客

## 关于

telegram:
```Plain
https://www.t.me/wsxiaolu666 
```

X:
```Plain
https://x.com/wsxiaolu?s=21
```
YouTube:
```Plain
https://www.youtube.com/@wsxiaolu
```
## Argon主题博客美化

==导入准备好的主题设置JSON==

找到argon主题设置选项 点击右下角"到底部" 没有就将页面下滑一点点

点击导入设置

==更换网站图标==

然后设置网站图标 点击外观 自定义 点击站点身份 跟换站点图标 上传文件 更换 点击发布

==添加网站导航==

点击文章 点击分类目录 添加其他的分类：文章 说说 聊天 关于 将默认的第一个分类修改名称为首页，分类的别名自己看着来

添加好分类后 点击外观 点击菜单 菜单名：网站导航 菜单项：点击分类目录 点击查看所有 点击全选 点击添加至菜单 点击保存菜单

==给网站导航和其他内容配置CSS(包含透明设置)==

点击外观 点击自定义 点击额外CSS 将当前文件目录下的 额外CSS.css 文件里面的内容复制到网站额外CSS设置里面点击发布

==给后台设置一个自己的头像==

点击插件 点击添加新插件 搜索User Profile Picture 添加后启用 然后点击用户 点击个人资料 点击Profile Image 上传图片更改即可 同时修改管理配色方案为argon 名字 昵称 公开显示为 邮箱 点击更新个人资料

==给网站上传白天和黑夜的背景==

点击媒体 点击添加文件 上传即可 上传好后点击图片可查看图片的位置 复制图片url位置 点击argon主题选项 点击右边大纲--页面背景 粘贴url地址到页面背景/页面背景(夜间模式时)输入框

==菜单图标==

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

[点击下載](https://wwmi.lanzouo.com/i2OPJ2i3lsle)

![img](https://www.30aitool.com/wp-content/uploads/2024/10/2024121408280531.webp)



