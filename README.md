# asrock-Z490M-itx-hackintosh
asrock Z490M itx hackintosh catalina&amp;big sur


1.基本硬件配置清单 及截图
CPU：i7-10700（支持所有十代）

主板：Asrock Z490M itx/ac

SSD：SN750 500G

Wi-Fi：BCM94352Z

内存；十铨火神DDR4 3000  16gx2


2.实现的功能
CPU正常睿频
核显双硬解正常
音频输出正常
蓝牙、WiFi正常  支持隔空、接力、随航
睡眠及唤醒正常，支持USB唤醒

未修正的地方
暂未发现

3.bios 设置参考指南   
https://www.bilibili.com/read/cv7393476


另 四大主板厂商华擎、华硕、维修、技嘉 针对性 详细截图 黑苹果bios设置 参考B站专栏

https://space.bilibili.com/591453294/article


5.OC0.6.3 引导基本使用说明

USB端口定制了15个端口，AsrockZ490Mitx-15USBPorts.kext  见USB截图



默认config.plist               支持核显双4K输出，DP支持4K60HZ，HDMI支持4K30HZ

AMD RX5500t& IGPU.plist       支持AMD RX5500XT 仿冒成Radeon Pro W5500X  ，IGPU核显作为加速 ，id为0300C89B

AMD RX5600/5700& IGPU.plist   支持AMD RX5600XT、5700、5700XT 仿冒成Radeon Pro W5700X  ，IGPU核显作为加速，id为0300C89B

如有其他问题，请加Q群：1125705781，备注小明或者B站

