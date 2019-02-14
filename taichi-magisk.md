# TaiChi·Magisk

[中文版](https://github.com/tiann/EXposed/wiki/taichi-magisk-zh)

## What is TaiChi·Magisk？

**TaiChi·Magisk is the enhanced version of TaiChi**。

The normal TaiChi can not hook into system process, and it must uninstall the original app when create new app.TaiChi·Magisk can overcome these shortcomings. TaiChi·Magisk hooks into system process via a magisk module, it can intercept all processes in system, so it can do all which Xposed Framework can do.

To be specific, what are the differences between TaiChi·Magisk and TaiChi?

1. TaiChi·Magisk can hook system process, so more modules are supported, such as Xposed Edge/Greenify.
2. TaiChi·Magisk don't need to modify app, it is very fast to create apps.
3. TaiChi·Magisk has more control over system, so it is more stable than the normal version.

And what are the differences between TaiChi·Magisk and Xposed Framework?

1. TaiChi·Magisk fully supports Android Pie.
2. TaiChi·Magisk does not effect the android system and it does not hook all apps in system. Only the apps you want to apply Xposed modules are hooked. Other apps in system run in a completely clean environment.
3. TaiChi·Magisk doesn't need to reboot sysytem in most cases.
4. TaiChi·Magisk is hard to detect. TaiChi doesn't modify the libart and app_process, it has nearly no noticeable characteristics.

## How to use ?

In simple terms, follow the steps:

1. Install Magisk.
2. Flash the magisk provided by TaiChi.
3. Install TaiChi App. 

Here are more informations in detail:

[**Notice**](https://github.com/tiann/EXposed/wiki/%E5%87%86%E5%A4%87%E4%BA%8B%E9%A1%B9)

[**Usage**](https://github.com/tiann/EXposed/wiki/%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8)

[**FAQ**](https://github.com/tiann/EXposed/wiki/%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)

[Known Issues](https://github.com/tiann/EXposed/wiki/%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9%E5%92%8C%E5%B7%B2%E7%9F%A5%E9%97%AE%E9%A2%98)

**Please read every instructions carefully**.