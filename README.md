# asrock-Z490M-itx-hackintosh  opencore0.6.3
===============================================

asrock Z490M itx hackintosh Catalina 10.15.x &   big sur 11.0.1


# 1.基本硬件配置清单 及基本截图

CPU：i7-10700（支持所有十代）

主板：Asrock Z490M itx/ac

SSD：SN750 500G

Wi-Fi：intel wifi 更换为 BCM94352Z

内存；十铨火神DDR4 3000  16gx2



# 2.macOS 状况

OC0.6.3 支持Catalina 10.15.x 和Big Sur 11.0.1 支持OTA升级

## PC截图

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/%E5%85%B3%E4%BA%8E%E6%9C%AC%E6%9C%BA.png)

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/CPU%20geekbench.png)

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/IGPU%20DP%25HDMI.png)

## 基本功能
CPU正常睿频
核显双硬解正常
音频输出正常（alcid=50）
有线双网卡设置
蓝牙、WiFi正常  支持隔空、接力、随航
睡眠及唤醒正常，支持USB唤醒

未修正的地方
暂未发现

# 3.bios 设置参考指南   
https://www.bilibili.com/read/cv7393476


另 四大主板厂商华擎、华硕、维修、技嘉 针对性 详细截图 黑苹果bios设置 参考B站专栏

https://space.bilibili.com/591453294/article


# 4.OC0.6.3 引导使用指南

##基本驱动及对应版本

Lilu.kext---------------------------1.4.9

VirtualSMC.kext--------------------1.1.8 

WhateverGreen.kex----------------1.4.4

AppleALC.kext---------------------1.5.4

IntelMausi.kext---------------------1.0.4

LucyRTL8125Ethernet.kext---------1.0.0

NVMeFix.kext-----------------------1.0.4




## USB端口定制了15个端口，AsrockZ490Mitx-15USBPorts.kext  见USBports截图

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/USBports.png)


### USB具体分布如下图

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/%E4%B8%BB%E6%9D%BFUSB%20%26%E6%9C%BA%E7%AE%B1%E5%89%8D%E7%BD%AEUSB.png)

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/%E5%90%8E%E7%BD%AEUSB.png)



## 如何使用2.5G有线网卡
 
 联网设置：系统偏好设置—-网络—以太网—高级——硬件—配置有自动改为手动，速率手工设置为1000 全双工（或100，取决于网线链接路由器的端口速率），见图


![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/2.5G%E7%BD%91%E5%8D%A1%E8%AE%BE%E7%BD%AE.png)


### config.plist使用

情景NO.1 无独显默认config.plist               支持核显双4K输出，DP支持4K60HZ，HDMI支持4K30HZ

情景NO.2 AMD RX5500t& IGPU.plist       支持AMD RX5500XT 仿冒成Radeon Pro W5500X  ，IGPU核显作为加速 ，id为0300C89B

情景NO.3 AMD RX5600/5700& IGPU.plist   支持AMD RX5600XT、5700、5700XT 仿冒成Radeon Pro W5700X  ，IGPU核显作为加速，id为0300C89B




# 若有其他问题请加Q群：1125705781，备注小明或者B站

