**VirtualXposed** 是基于[VirtualApp](https://github.com/asLody/VirtualApp) 和 [epic](https://github.com/tiann/epic) 在**非ROOT**环境下运行Xposed模块的实现（支持5.0~8.1)。

[点击下载][latest_version]

## 使用

<video width="320" controls preload> 
    <source src="video.webm"></source> 
</video>

### 准备

首先在 [下载页面](download.md) 下载最新的 VirtualXposed 安装包安装到手机。

- [最新版][latest_version]
- [历史版本](download.md)

### 安装模块

打开 VirtualXposed，在里面安装要使用的APP，以及相应的Xposed模块即可。

注意：**所有的工作（安装Xposed模块，安装APP）必须在 VirtualXposed中**进行，否则Xposed模块不会有任何作用！比如，将微信直接安装在系统上（而非VirtualXposed中），防撤回安装在VirtualXposed中；或者把微信安装在VirtualXposed上，防撤回插件直接安装在系统上；或者两者都直接安装在系统上，**均不会起任何作用**。

在VirtualXposed中安装App有三种方式：

1. 直接复制已经在系统中安装好的APP，比如如果你系统中装了微信，那么可以直接复制一份。
2. 通过外置存储直接安装APK文件；点主界面底部按钮——添加应用，然后选择后面两个TAB即可。
3. 点击右边的浮动按钮，从第三方文件选择器选择安装

在VirtualXposed中安装Xposed模块，可以跟安装正常的APK一样，以上两种安装App的方式也适用于安装Xposed模块。不过，你也可以通过VirtualXposed中内置的XposedInstaller来安装和管理模块，跟通常的XposedInstaller使用方式一样；去下载页面，下载安装即可。 

## 已经支持的模块

- [微X模块][wx]: 微信模块，功能全面；但与VXP兼容性一般。
- [微信巫师][wxws]: 微信模块，项目开源，代码优秀。
- [MDWechat][mdwechat]: 微信美化模块，可以把微信整成MD风格。
- [应用变量][yybl]: 可以用来进行机型修改，比如王者荣耀高帧率；QQ空间修改小尾巴等。
- [音量增强器][ylzqq]: 网易云音乐模块，非常好用，低调。
- [微信学英语][wxxyy]: 自动把微信消息翻译为英语，非常实用。
- [冲顶助手][cdzs]: 答题辅助模块。
- [情迁抢包][qqqb]: 抢红包模块，兼容性一般。
- [微信跳一跳助手][ttzs]: 微信跳一跳游戏辅助模块。
- [步数修改器][bsxg]: 运动步数修改模块。
- [模拟位置][mnwz]: 虚拟定位模块，稳定好用。
- [指纹支付][zwzf]: 对不支持指纹支付但系统本身有指纹的手机开启指纹支付的模块。
- [QQ精简模块 2.0][qqjj]: QQ模块，不仅可以精简QQ，还能防撤回，防闪照。VXP不支持QX，推荐用这个。
- [微信增强插件][wxzqcj]: 微信模块，VXP内最稳定的微信模块；如无特殊需求建议用这个。
- [QQ斗图神器][qqdtsq]: 各种表情，斗图神器。
- [微信斗图神器][wxdtsq]: 斗图神器，微信用的。
- [大圣净化][dsjh]: 去广告神器，推荐使用。

或许还有很多，自行测试。

## 已知问题

1. 由于暂不支持资源HOOK，因此资源钩子不会起任何作用；使用资源HOOK的模块，相应的功能不会生效。
2. 部分插件的兼容性有问题，比如QX模块。

## 支持和加入

目前VirtualXposed 还不完善，如果你对非ROOT下实现Xposed感兴趣；欢迎加入！你可以通过如下方式来支持：

1. 直接贡献代码，提供Feature，修复BUG！
2. 使用你拥有的手机，安装你常用的Xposed模块，反馈不可用情况；协助帮忙解决兼容性问题！
3. 提出体验上，功能上的建议，帮助完善VirtualXposed！

## 致谢

1. [VirtualApp](https://github.com/asLody/VirtualApp)
2. [Xposed](https://github.com/rovo89/Xposed)
    
[latest_version]: http://p229bylfv.bkt.clouddn.com/VirtualXposed_0.9.9.apk
[wx]: https://pan.baidu.com/s/1hrOzCnq#list/path=%2Freleases%2Fapk&parentPath=%2Freleases
[wxws]: https://github.com/Gh0u1L5/WechatMagician/releases
[yybl]: https://www.coolapk.com/apk/com.sollyu.xposed.hook.model
[ylzqq]: https://github.com/bin456789/Unblock163MusicClient-Xposed/releases
[wxxyy]: https://www.coolapk.com/apk/com.hiwechart.translate
[cdzs]: https://www.coolapk.com/apk/com.gy.xposed.cddh
[qqqb]: http://repo.xposed.info/module/cn.qssq666.redpacket
[ttzs]: http://repo.xposed.info/module/com.emily.mmjumphelper
[mnwz]: https://www.coolapk.com/apk/com.rong.xposed.fakelocation
[zwzf]: https://github.com/android-hacker/Xposed-Fingerprint-pay/releases
[bsxg]: https://www.coolapk.com/apk/com.specher.sm
[mdwechat]: https://github.com/Blankeer/MDWechat
[wxzqcj]:https://github.com/firesunCN/WechatEnhancement
[qqjj]: https://www.coolapk.com/apk/me.zpp0196.qqsimple
[qqdtsq]: https://www.coolapk.com/apk/x.hook.qqemoji
[wxdtsq]: https://www.coolapk.com/apk/x.hook.emojihook
[dsjh]: https://wiki.ad-gone.com/archives/32/
