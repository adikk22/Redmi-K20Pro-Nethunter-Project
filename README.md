Redmin-K20-Pro Nethunter-Project
=====
警告：该内核仅在用于黑客技术的学习和交流，禁止非法使用，期间发生和导致的任何责任问题都与本人无关！
该内核基于UtsavBalar1231内核源码和android-linux-stable并进行修改，适用于MIUI_Q,基本上实现了Nethunter官网支持手机的全部功能并且已解决所有已知问题

+ 支持otg外接网卡 MTKMT7601U rt28xx/3070l ar9170等
+ HID模拟键盘鼠标攻击，完美支持DuckyHID
+ SYSVIPC支持 (现在你可以开启PostgreSQL数据库)
+ DriveDroid支持
+ USB RNDIS 模拟网卡
+ USB/UART 蓝牙设备支持
+ RTL-SDR, AirSpy, Hackrf 支持
+ USB RTL8150/2/3 based 有线网卡支持
+ USB serial (目前支持CH341和pl2303接口)
+ 支持高通内置网卡开启监听, 现在你可以使用手机自身的"wlan0"网卡来开启监听模式了(暂不支持注入)

如果你想开启手机内置网卡wlan0的监听功能, [请看这里](https://github.com/kimocoder/qualcomm_android_monitor_mode)

内核自身功能
====
+ Update to 4.14.178
+ Merge tag 'LA.UM.8.1.r1-14700-sm8150.0'
+ 添加 830mhz gpu freq
+ BBR2 and set default
+ 升级 qcacld3 wlan driver 到最新
+ 升级 wireguard 到最新
+ Zram: 默认lz4压缩算法

感谢名单
====
<br> Thanks [UtsavBalar1231](https://github.com/UtsavBalar1231)
<br> Thanks [shandongtlb](https://github.com/shandongtlb)
<br> Thanks [android-linux-stable/](https://github.com/android-linux-stable/msm-4.14/tree/kernel.lnx.4.14.r4-rel)
<br> Thanks [simonpunk](https://forum.xda-developers.com/oneplus-5/development/burgerhunter-t3638810)
<br> Thanks [kimocoder](https://github.com/kimocoder)
