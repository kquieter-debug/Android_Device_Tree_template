# LineageOS 源码设备树模板
______
从此开启你的安卓开发之旅。借助此模板，可轻松为新设备构建设备树、移植自定义操作系统（ROM）与自定义恢复模式（Recovery）

研读模板以理解文件架构，随后从你的设备中提取启动镜像（Boot）或恢复镜像（Recovery），并运行mkvendor.sh脚本来生成初步的设备树，关于如何构建设备树，可参考谷歌的 [AOSP tutorial](https://source.android.com/setup/develop/new-device) 官方教程  关于这些文件的具体作用，也可查阅 [StackOverflow](https://stackoverflow.com/a/11353248) 上的详细解析

你需补充额外配置信息（例如BoardConfig.mk文件中的TARGET_BOARD_PLATFORM参数），设备树方可正常投入使用.
______

最后，祝你开发顺利！用安卓做出一些精彩的成果吧:)

请务必将你在教程中获取的信息，与 [LineageOS repositories](https://github.com/LineageOS?utf8=✓&q=android_device)中的其他设备树进行交叉比对, **切勿**向文件中添加已弃用的属性等内容 —— 因为相关教程可能已过时.

你可以为你的设备构建 [TWRP](https://twrp.me/) (第三方 Recovery) . 其官方编译教程可在此处查看 [here](https://forum.xda-developers.com/showthread.php?t=1943625) (由 [@Dees-Troy] (https://github.com/Dees-Troy)撰写).
______
###### 免责声明: 本内容按 “现状” 提供。对于因使用本仓库提供的数据或引用内容而引发的任何问题，我不承担任何责任.