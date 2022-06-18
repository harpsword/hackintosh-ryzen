# Readme



![photo](https://github.com/harpsword/hackintosh-ryzen/raw/master/photo/f.png)



该仓库内的efi来自于[1]，该efi采用的是opencore，在使用之前请仔细阅读精解opencore[2]这篇文章，库内的propertree-master.zip为修改config.plist的工具软件。



我的机型为

1. CPU: AMD r7 3700x
2. 微星B450 mortar
3. GPU: XFX 5700XT
4. SSD: 三星 860 EVO

本人是先用clover安装了10.15，由于无法升级到10.15.1，所以采用了该efi；实测可以升级到macOS 10.15.1。使用前，请根据自身配置修改config.plist。当10.15.0升级到10.15.1的时候屏幕可能会出现花屏，但这只是暂时的，等一会儿就会升级好。

Big Sur 版本可以参考 feature-big-sur 分支.



[1] https://forum.amd-osx.com/viewtopic.php?f=61&t=9437

[2] https://blog.daliansky.net/OpenCore-BootLoader.html