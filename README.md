# 简述
本EFI配置文件使用**OpenCore 0.6.9**，并理论支持到**macOS 11.3.1**。经过初步测试暂无发现更多BUG。

# 本机配置
主板：微星 MPG Z390 GAMING PLUS

CPU：i9-9900K

显卡：AMD Radeon RX 5700 XT

RAM：DDR4 32GB

声卡：ALC892 (alcid=1)

有线网卡：Intel Ethernet Connection I219-V

无线网卡：Fenvi FV-T919 (BCM94360CD)

# BUG列表
- macOS 11.3 更新发布后，OpenCore的XhciPortLimit Quirk失效。本配置文件临时将此项关闭。但关闭后USB端口不能超过15个。待修复后定制USB。一劳永逸解决该问题。

# 感谢列表 （排名不分先后）
[Intel Coffee Lake平台完美黑苹果系统安装教程（Opencore+Catalina15.4）](https://www.bilibili.com/video/BV1hA411t7dr "Intel Coffee Lake平台完美黑苹果系统安装教程（Opencore+Catalina15.4）")

[Desktop Coffee Lake - OpenCore Desktop Guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html)

[黑果小兵的部落格](https://blog.daliansky.net/ "黑果小兵的部落格")
