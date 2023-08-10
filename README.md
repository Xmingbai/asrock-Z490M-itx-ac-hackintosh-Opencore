===========================================================================
# asrock-Z490M-itx/ac-hackintosh  opencore0.9.0 beta（0303）
===========================================================================

1.更新至0.9.0最新测试版，支持Catalina 10.15.x、bigsur 11.x、Monterey 12.x、MacOS 13.x

2.更新Kexts至最新版本

3.默认config.plist 支持所有Navi核心独立显卡并支持其温度监控（需要自己去勾选RadeonSensor.kext和SMCRadeonGPU.kext，OS13已不需要）

4.如只有核显，IGPU-config.plist 可改名为config.plist来使用

5.引导默认支持（BCM94352Z、DW1560、DW1830、BCM94360NG、BCM94360Z3\Z4）博通无线网


===========================================================================
# asrock-Z490M-itx/ac-hackintosh  opencore0.8.2 
===========================================================================

1.更新至0.8.2正式版，支持Catalina 10.15.x、bigsur 11.6.x、Monterey 12.x、MacOS 13 beta

2.更新Kexts至最新版本，修复睡眠丢失核显DP或HDMI音频

3.默认config.plist 支持所有Navi核心独立显卡并支持其温度监控（需要自己去勾选RadeonSensor.kext和SMCRadeonGPU.kext，OS13已不需要）

4.如只有核显，IGPU.plist 可改名为config.plist来使用

5.引导默认支持（BCM94352Z、DW1560、DW1830、BCM94360NG、BCM94360Z3\Z4）博通无线网

===========================================================================
# asrock-Z490M-itx/ac-hackintosh  opencore0.8.0
===========================================================================

1.更新至0.8.0测试版，支持Catalina 10.15.x、bigsur 11.6.x、Monterey 12.x

2.更新Kexts至最新版本

3.默认config.plist 支持所有Navi核心独立显卡并支持其温度监控（需要自己去勾选RadeonSensor.kext和SMCRadeonGPU.kext）

4.如只有核显，IGPU.plist 可改名为config.plist来使用

5.引导默认支持（BCM94352Z、DW1560、DW1830、BCM94360NG、BCM94360Z3\Z4）博通无线网


===========================================================================
# asrock-Z490M-itx/ac-hackintosh  opencore0.7.8
===========================================================================
更新内容：

1.OC至0.8.0测试版，支持Catalina 10.15.x、bigsur 11.6.x、Monterey 12.x

2.更新Kexts至最新版本

3.默认config.plist 支持所有Navi核心独立显卡并支持其温度监控（需去config中手动启用）

4.如只有核显，IGPU.plist 可改名为config.plist来使用

5.引导默认支持（BCM94352Z、DW1560、DW1830、BCM94360NG、BCM94360Z3\Z4）博通无线网卡

===========================================================================
# asrock-Z490M-itx/ac-hackintosh  opencore0.7.8
===========================================================================
更新内容：

1.OC至0.7.8正式版，支持Catalina 10.15.x、bigsur 11.6.x、Monterey 12.x

2.更新Kexts至最新版本

3.默认config.plist 支持所有Navi核心独立显卡并支持其温度监控

4.如只有核显，IGPU.plist 可改名为config.plist来使用

5.引导默认支持（BCM94352Z、DW1560、DW1830、BCM94360NG、BCM94360Z3\Z4）博通无线网卡



# asrock-Z490M-itx/ac-hackintosh  opencore0.7.6
===========================================================================
☆ 升级kext驱动到最新正式版本

☆支持11.6正式版及12.x

☆支持核显HDMI&DP,需在config中启用

☆默认config支持5500/5600/5700/6600/6800/6900系列显卡

===========================================================================
# asrock-Z490M-itx/ac-hackintosh  opencore0.7.4
===========================================================================

☆ 升级kext驱动到最新正式版本

☆支持11.6正式版及12

☆支持核显HDMI&DP

☆默认config支持5500/5600/5700/6800/6900系列显卡

☆核显使用IGPU_config.plist改名为config.plist来使用


===========================================================================
# asrock-Z490M-itx/ac-hackintosh  opencore0.7.1
===========================================================================

☆ 升级kext驱动到最新正式版本

☆支持11.5.1正式版及12 beta

☆支持核显HDMI&DP

☆如果独显是RX5500/5600/5700/6800/6900系列 请加启动参数agdpmod=pikera





===========================================================================
# asrock-Z490M-itx/ac-hackintosh  opencore0.6.9
===========================================================================

☆ 升级kext驱动到最新正式版本

☆支持11.4正式版

☆支持核显HDMI&DP及核显音频输出

☆支持intel wifi，若是博通网卡请启用config中对应驱动

☆如果独显是RX5500/5600/5700/6800/6900系列 请加启动参数agdpmod=pikera


===========================================================================
# asrock-Z490M-itx/ac-hackintosh  opencore0.6.6
===========================================================================

更新部分

☆ 升级kext驱动到最新正式版本

☆ 音频输出 增加了核显（DP或者HDMI）显示器音频输出

☆ 精简ACPI ，添加系统判断，避大部分免OC引导windows蓝屏

☆ device properties 内包含RX55000xt\5600&5700优化信息，需要手工启用（去掉前置#就行）

☆ 更换OC主题包（支持OC UI 随意切换有三个背景选择，改名为Background.icns即可）

☆ 正常直升11.2 （支持11.3 beta x）

![](https://github.com/Xmingbai/hackintosh-opencore--UI-theme/blob/main/TipsBackground.png)


===========================================================================
# asrock-Z490M-itx/ac-hackintosh  opencore0.6.4
===========================================================================

更新部分

☆ 升级kext驱动到最新正式版本

☆ 新增一组配置文件 AMD RX5XX& IGPU.plist

☆ 更换OC主题包

☆ 正常直升11.1 20C69

![](https://github.com/Xmingbai/asrock-Z490M-itx-ac-hackintosh-Opencore/blob/main/11.1%2020C69.png)

![](https://github.com/Xmingbai/asrock-Z490M-itx-ac-hackintosh-Opencore/blob/main/%E6%96%B0OC%E4%B8%BB%E9%A2%98.png)






============================================================================

# asrock-Z490M-itx/ac-hackintosh  opencore0.6.3
============================================================================
asrock Z490M itx hackintosh Catalina 10.15.x &   big sur 11.0.1


# 1.基本硬件配置清单 及截图

CPU：i7-10700（可以支持所有十代）

主板：Asrock Z490M itx/ac

SSD：SN750 500G

Wi-Fi：intel wifi 更换为 BCM94352Z

内存；十铨火神DDR4 3000  16gx2

# 若有其他问题请加Q群：608352460，备注小明或者B站，也欢迎关注B站：小明和他的女朋友

此份操作指南 同步 发布于B站专栏，方便国内访问  

https://www.bilibili.com/read/cv8721205 

# 2.macOS 状况

OC0.6.3 支持Catalina 10.15.x 和Big Sur 11.0.1 支持OTA升级，支持直装

## PC截图

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/%E5%85%B3%E4%BA%8E%E6%9C%AC%E6%9C%BA.png)

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/CPU%20geekbench.png)

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/IGPU%20DP%25HDMI.png)

## 基本功能

CPU正常睿频

核显双硬解正常

核显支持双4K显示器，DP支持4K60HZ，HDMI支持4K30HZ

若使用独显5500、5600、5700 配置文件自带显卡性能优化

音频输出正常（alcid=50）

支持有线双网卡（1000M+2.5G）

蓝牙、WiFi正常  支持隔空、接力、随航

睡眠及唤醒正常，支持USB唤醒

支持开机启动音，支持双系统启动界面选择

未修正的地方 ：暂未发现

# 3.bios 设置参考指南   

https://www.bilibili.com/read/cv7393476


另 四大主板厂商华擎、华硕、微星、技嘉 针对性 详细截图 黑苹果bios设置 参考B站专栏


https://space.bilibili.com/591453294/article


# 4.OC0.6.3 引导使用指南 

## 4.1 基本驱动及对应版本

Lilu.kext----------------------------1.4.9

VirtualSMC.kext--------------------1.1.8 

WhateverGreen.kex----------------1.4.4

AppleALC.kext---------------------1.5.4

IntelMausi.kext---------------------1.0.4

LucyRTL8125Ethernet.kext---------1.0.0

NVMeFix.kext----------------------1.0.4


## 4.2 OC配置文件config.plist如何使用

### 情景NO.1  无独显默认config.plist      

支持核显双4K输出，DP支持4K60HZ，HDMI支持4K30HZ

### 情景NO.2  AMD RX5500t& IGPU.plist     

支持AMD RX5500XT 仿冒成Radeon Pro W5500X  ，IGPU核显作为加速 ，id为0300C89B

### 情景NO.3  AMD RX5600/5700& IGPU.plist 

支持AMD RX5600XT、5700、5700XT 仿冒成Radeon Pro W5700X  ，IGPU核显作为加速，id为0300C89B

### 情景NO.4  AMD RX5XX& IGPU.plist  

支持独显AMD RX560、570、580、590等  ，IGPU核显作为加速，id为0300C89B

### 根据自己实际情况，选择对应配置文件改名为config.plist，最好自己重新生成三码。


## 4.3 USB端口定制了15个端口，见USBports截图

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/USBports.png)

双网口附近的4个USB支持10G速率


### USB具体分布如下图

![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/%E4%B8%BB%E6%9D%BFUSB%20%26%E6%9C%BA%E7%AE%B1%E5%89%8D%E7%BD%AEUSB.png)


![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/%E5%90%8E%E7%BD%AEUSB.png)



## 4.4 如何使用2.5G有线网卡
 
 联网设置：系统偏好设置—-网络—以太网—高级——硬件—配置有自动改为手动，速率手工设置为1000 全双工（或100，取决于网线链接路由器的端口速率），见图


![](https://github.com/Xmingbai/asrock-Z490M-itx-hackintosh/blob/main/2.5G%E7%BD%91%E5%8D%A1%E8%AE%BE%E7%BD%AE.png)

# 若有其他问题请加Q群：608352460，备注小明或者B站

# 也欢迎关注B站：小明和他的女朋友

https://space.bilibili.com/591453294?spm_id_from=333.788.b_765f7570696e666f.2

