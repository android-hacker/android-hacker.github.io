## Download

- [Latest Version/最新版本下载][latest_version]
- [History Release/历史版本下载](download.md)

[Donate \| 支持我](donate.md)

## Usage

<video width="320" controls preload> 
    <source src="video.webm"></source> 
</video>

### Install APP and Xposed Module

Open VirtualXposed, Click on the **Drawer Button** at the bottom of home page(Or long click the screen), add your desired APP and Xposed Module to VirtualXposed's virtual environment.

Note: **All operations（installation of Xposed Module, APP）must be done in VirtualXposed**, otherwise the Xposed Module installed won't take effect. For example, if you install the YouTube app on your system (Your phone's original system, not in VirtualXposed), and then install YouTube AdAway (A YouTube Xposed Module) in VirtualXposed; or you install YouTube in VirtualXposed, and install YouTube AdAway on original system; or both of them are installed on original system, **neither of these three cases will work!**


There are three ways to install an APP or Xposed Module to VirtualXposed:

1. **Clone an installed app from your original system.** (Click Button at bottom of home page, then click Add App, the first page shows a list of installed apps.)
2. **Install via an APK file.** (Click Button at bottom of home page, then click Add App, the second page shows APKs found in your sdcard)
3. **Install via an external file chooser.** (Click Button at bottom of home page, then click Add App, use the floating action button to choose an APK file to install)

For Xposed Module, You can install it from Xposed Installer, too.

### Activate the Xposed Module

Open Xposed Installer in VirtualXposed, go to the module fragment, check the module you want to use:

### Reboot

You only need to reboot VirtualXposed, **There's no need to reboot your phone**; Just click Settings in home page of VirtualXposed, click `Reboot` button, and VirtualXposed will reboot in a blink. 

## Modules Tested by myself

- [XPrivacyLua][xpl]: Really simple to use privacy manager for Android 6.0 Marshmallow and later.
- [XInsta][xinsta]: Instagram module(Feed downing, stories downloading, etc).
- [Minminguard][minminguard]: Completely remove both the ads inside apps and the empty space caused by those ads.
- [YouTube AdAway][yta]:  Get rid of ads on the official YouTube App.
- [微X模块][wx]: 微信模块，功能强大。
- [微信巫师][wxws]: 微信模块，项目开源，代码优秀。
- [MDWechat][mdwechat]: 微信美化模块，可以把微信整成MD风格。
- [应用变量][yybl]: 可以用来进行机型修改，比如王者荣耀高帧率；QQ空间修改小尾巴等。
- [音量增强器][ylzqq]: 网易云音乐模块，非常好用，低调。
- [微信学英语][wxxyy]: 自动把微信消息翻译为英语，非常实用。
- [情迁抢包][qqqb]: 微信QQ抢红包模块。
- [微信跳一跳助手][ttzs]: 微信跳一跳游戏辅助模块。
- [步数修改器][bsxg]: 运动步数修改模块。
- [模拟位置][mnwz]: 虚拟定位模块，稳定好用。
- [指纹支付][zwzf]: 对不支持指纹支付但系统本身有指纹的手机开启指纹支付的模块。
- [QQ精简模块 2.0][qqjj]: QQ模块，不仅可以精简QQ，还能防撤回，防闪照。
- [微信增强插件][wxzqcj]: 微信模块，VXP内最稳定的微信模块；如无特殊需求建议用这个。
- [QX模块][qx]: QQ模块，防撤回抢红包斗图一应俱全。
- [QQ斗图神器][qqdtsq]: 各种表情，斗图神器。
- [微信斗图神器][wxdtsq]: 斗图神器，微信用的。
- [大圣净化][dsjh]: 去广告神器，推荐使用。

Supported modules are far more than above, you should test it by yourself.

    
[latest_version]: http://files.git.oschina.net/group1/M00/04/C3/PaAvDFuHe2GAPvFAAGoefrpztxQ420.apk?token=8ceb9531f8ac501c76cb34f0c2ce41d0&ts=1535605603&attname=app-aosp-release.apk
[wx]: http://repo.xposed.info/module/com.fkzhang.wechatxposed
[qx]: http://repo.xposed.info/module/com.fkzhang.qqxposed
[wxws]: https://github.com/Gh0u1L5/WechatMagician/releases
[yybl]: https://www.coolapk.com/apk/com.sollyu.xposed.hook.model
[ylzqq]: https://github.com/bin456789/Unblock163MusicClient-Xposed/releases
[wxxyy]: https://www.coolapk.com/apk/com.hiwechart.translate
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
[dsjh]: https://wiki.ad-gone.com/archives/32
[xpl]: https://github.com/android-hacker/VirtualXposed/wiki/Privacy-control(XPrivacyLua)
[minminguard]: http://repo.xposed.info/module/tw.fatminmin.xposed.minminguard
[yta]: http://repo.xposed.info/module/ma.wanam.youtubeadaway
[xinsta]: http://repo.xposed.info/module/com.ihelp101.instagram
