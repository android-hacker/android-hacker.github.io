# 发布日志

# 0.10.1

[下载](http://files.git.oschina.net/group1/M00/03/C9/PaAvDFsPVTGAZ6oDAGjZ4ArO67o005.apk?token=042a78915be6b72cc24dd35dad9aeb78&ts=1527731511&attname=VirtualXposed_0.10.1.apk)

1. 现在可以去掉恼人的常驻通知栏了。
2. 设置界面添加Xposed模块管理的入口，更加便捷（设置-模块管理）。
3. 允许安装没有签名的应用到 VirtualXposed（设置-高级设置）。
4. 修复Xposed模块声明多个入口时只会生效一个的BUG。
5. 修复Xposed接口调用原函数直接崩溃的BUG。
6. 初步支持 x86。
7. 修复非中文系统上安装必定闪退的问题。

What's new ?

1. You can hide the resident notification of VirtualXposed now.
2. new Xposed Module manage UI in settings.
3. Allow to install apk without signatures.
4. fix bug of Xposed module with multiple entries.
5. fix bug of Xposed when invoke orignal method.
6. add initial support for x86.
7. fix crash when add app to VirtualXposed.



2018/5/31

# 0.9.9

[下载](http://p229bylfv.bkt.clouddn.com/VirtualXposed_0.9.9.apk)

1. Xposed底层调整，提升对插件的兼容性。
2. 保守模式默认开启，如果你使用没问题；需要主动前往高级设置关闭。
3. 新增常用模块的功能，推荐一些VXP使用稳定的模块。
4. QQ群/微信群反馈隐藏，请使用邮件反馈。
5. 修复若干Xposed相关的Bug。

What's new?

1. improve the compatbiility with some Xposed module.
2. keep conservative mode default on, you need to switch it off manally when necessary.
3. new feature: Recommended Xposed Module.
4. hide the qq group & wechat group.
5. fix some bug about Xposed.

2018/5/9

# 0.9.8

[下载](http://p229bylfv.bkt.clouddn.com/VirtualXposed_0.9.8.apk)

更新说明：

1. 提高 Android 7.0/7.1系统上的稳定性。
2. 解决某些应用界面跳转时闪动的问题。
3. 兼容全面屏（支持18:9屏幕）
4. 新增“保守模式”（设置-高级设置）

What's new?

1. Improve the stability on Android 7.0 & 7.1.
2. fix the screen flashing when switch UI.
3. Support 18:9 screen.
4. New Feature: Conservative Mode(Settings -> Advance Settings)

# 0.9.7

[下载](http://p229bylfv.bkt.clouddn.com/VirtualXposed_0.9.7.apk)

更新说明：

1. 尝试修复微信经常需要重新输入密码登陆的问题。
2. 继续部分机型改善后台收发消息的问题。
3. 同步Pixel桌面的最新代码。
4. 添加Telegram群组/文件复制等UI。
5. 部分细节调整。
6. 华为用户看这里：http://vxposed.com/zhongchou.html

Release Notes:

1. Improve the message sending & receiving of IM.
2. Merge the source code of Rootless Pixel Launcher.
3. You can find Telegram group in about page.
4. minar UI fix.

2018/4/18

# 0.9.4

[下载](http://p229bylfv.bkt.clouddn.com/VirtualXposed_0.9.4.apk)

更新说明：

1. 修复音量增强器在 Android 8.0上无法使用的问题。
2. 修复部分插件在Android 8.0上不生效的问题。
3. 添加西班牙语支持。
4. 华为用户看这里：http://vxposed.com/zhongchou.html

New Features:

1. Language support for Spanish, Thanks @JMVS.
2. fix some Xposed module can not work in Android 8.0.
3. fix for UnblockCloudMusic163.

2018/4/16

# 0.9.1

[下载](http://p229bylfv.bkt.clouddn.com/VirtualXposed_0.9.1.apk)

更新说明：

1. 修复微信收发消息的问题。
2. 修复GG修改器无法使用的问题。

2018/4/13

# 0.9.0

[下载](http://p229bylfv.bkt.clouddn.com/VirtualXposed_0.9.0.apk)

更新说明：

1. 修复三星8.0上无法使用的问题。
2. 改善后台接受消息的问题。
3. 修复闪退，提升稳定性。
4. 修复某些情况下微信频繁自杀的问题。

2018/4/12

# 0.8.5

[下载](http://p229bylfv.bkt.clouddn.com/VirtualXposed_0.8.5.apk)

更新说明：

1. 新功能：支持从外部系统分享内容到VirtualXposed内部。
2. 新功能：支持从外部系统直接安装应用到Virtual Xposed。
3. 新功能：支持直接从内部APP退回到系统桌面（设置－高级设置）。
4. 新功能：支持隐藏主页设置按钮（可以通过菜单键和长按主界面进入设置）。
5. 新功能：更完善的IO重定向（本次升级后会有缓存被清的情况，属正常现象，以后不会了）。
6. 大量界面改进。
7. 修复闪退，提升稳定性。

2018/3/20

## 0.7.3

[下载](http://p229bylfv.bkt.clouddn.com/VirtualXposed_0.7.3.apk)

更新说明：

1. 添加了升级/降级安装应用的功能。（添加APP时单选即可）
2. 添加了更换壁纸的功能（设置－桌面设置－更换壁纸。
3. 添加了修复应用的功能（设置－应用管理），APP无法打开时可以尝试使用。
4. 修复了微信，QQ图片和视频保存无法及时看到的问题。
5. 修复了内部应用无法创建快捷方式的问题（如微信小程序等）
6. 添加APP界面改进，APP顺序按拼音排列，方便查找。
7. 修复了任务管理界面图标偶尔不显示的问题。
8. APP添加时显示apk的路径。
9. 紧急修复打开任务管理界面闪退的问题。

## 0.7.1

[下载](http://p229bylfv.bkt.clouddn.com/VirtualXposed_0.7.1.apk)

更新说明：

1. 修复闪退。
2. 提升稳定性。

## 0.7.0

[下载](http://p229bylfv.bkt.clouddn.com/VirtualXposed_0.7.0.apk)

更新说明：

1. 修复闪退。
2. 修复某些系统上安装不上的问题。
3. 修复某些APP图标霸屏的问题。
4. 修复多开快捷方式无法创建的问题。
5. 提供给XP模块开发者使用的接口，详细见 [Utilities-For-Xposed-Module-Developer](https://github.com/android-hacker/VirtualXposed/wiki/Utilities-For-Xposed-Module-Developer)。

## 0.6.8

[下载](http://p229bylfv.bkt.clouddn.com/VirtualXposed_0.6.8.apk)

在新年的鞭炮声中完成了 VirtualXposed 的更新，先给大家拜个年，祝大家新年快乐，狗年旺旺！然后说说更新了啥：

1. 新年新名字：VAExposed已经正式更名为 VirtualXposed。
2. 新年新界面：VirtualXposed 的UI已经完全重写，内部的交互更像是一个沉浸式的虚拟空间，希望大家喜欢！
3. 新年新功能：应用管理 & 任务管理。
4. 新年新版本号：0.6.8 只为图个吉利 :)

辞旧迎新，也有的东西已经要成为过去式了：

VirtualXposed 不再支持 Android 5.0 以下的系统；新版本无法安装在4.4及以下的设备上。

新年快乐！

## 0.4.7

[下载](http://p229bylfv.bkt.clouddn.com/VAExposed_0.4.7.apk)

修复0.4.6引入的一些稳定性问题

## 0.4.6

[下载](http://p229bylfv.bkt.clouddn.com/VAExposed_0.4.6.apk)

更新说明：

1. 支持从文件选择器选择文件安装。
2. 支持模拟位置。
3. 支持微信巫师最新版。
