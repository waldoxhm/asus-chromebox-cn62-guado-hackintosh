# Asus-chromebox-cn62-guado-hackintosh
opencore efi partition

## About downgrade the bios
https://github.com/waldoxhm/scripts

## update2021.08.20 （osx Big sur 11.5.2 with opencore 0.7.2 ）
 - New Folder “EFI-Fakesmc-OC0.7.2”  added IntelBluetoothFirmware.kext for better bluetooth support.
 - Updated drivers and opencore version.
 - Nowadays, mrchromebox.tech has already upgraded their coreboot bios to 4.14, which fixed the intel graphic and change the way nvram stores.
so,this efi file does not support mrchromebox.tech's latest bios.(I'v tested and managed to downgrade.LOL, maybe I'LL post the script recently)
 - Remember，change the serial number and system uuid in config.plist.

## update2020.11.01 （osx catalina 10.15.7 with opencore 0.6.1 ）
 - Fixed 3.5mm audio jack, supports a headphone with mic now.
 - New Folder “EFI-fakesmc” replaced the Virtualsmc with Fakesmc to get Fan-control（via ssd fan control https://exirion.net/ssdfanctrl/ ）
 - Opencore's Installation guide says it is not recommand to use fakesmc with opencore, and fakesmc is out of date. so if you want Virtualsmc back, pls use folder “EFI”, but you will lose fanctrl.

### System configuration
 - BIOS：mrchromebox COREBOOT 4.12 
 - CPU: Intel Core i7-5500U
 - Graphic: Intel HD5500
 - WiFi&BT: Intel AC7260
 - Audio: Realtek ALC283
 - Ethernet: Realtek RTL8111

### What's working
 - IGPU
 - Audio
 - Ethernet(set EN0-interface-preferences-hardware to manual , or it will not wired)
 - SD card reader
 - Original WIFI module(use heliport to connect wifi)
 - BLUETOOTH
 - Native Power Management （patched）
 - HDMI + Audio
 - Fan control （via ssd fan control https://exirion.net/ssdfanctrl/ ）

### Credits & Sources (in no particular order and maybe missing some)
 - Apple INC.
 - https://github.com/MrChromebox
 - https://github.com/acidanthera
 - https://github.com/RehabMan
 - https://github.com/corpnewt
 - https://www.insanelymac.com/
 - https://www.tonymacx86.com/
 - https://reddit.com/r/hackintosh
 - https://reddit.com/r/chrultrabook
 - https://dortania.github.io/vanilla-laptop-guide/
 - https://blog.daliansky.net/
 - https://blog.xjn819.com/
 - https://github.com/OpenIntelWireless
 - https://github.com/Mieze/RTL8111_driver_for_OS_X
 
——————————————————————————————————————————————————
# 华硕-chromebox-cn62-guado-黑苹果
OPENCORE efi分区所有文件

## 关于降级BIOS
https://github.com/waldoxhm/scripts

## 更新2021.08.20 （osx Big sur 11.5.2 with opencore 0.7.2 ）
 - 新文件夹 “EFI-Fakesmc-OC0.7.2”  新增 IntelBluetoothFirmware.kext 以获得更好的蓝牙支持。
 - 更新了所有驱动，以及opencore版本。
 - 最近mrchromebox.tech已经将bios版本更新到了4.14, 使用脚本跟新完后提示修复了intel显卡以及更改了nvram的存储方式，导致opencore无限重启
所以这个efi分区文件不支持最新的mrchromebox.tech BIOS。(我已经更新了，然后进不去系统然后bios降级了。LOL, 近期可能会把降级脚本发上来)
 - 记住替换 config.plist里的serial number 和 system uuid。

## 更新2020.11.01 （osx catalina 10.15.7 with opencore 0.6.1）
 - 修复3.5mm音频接口，现支持耳麦。
 - 新文件夹 “EFI-fakesmc” 使用fakesmc替换Virtualsmc以获得完整的风扇控制和传感器读数（通过使用 ssd fan control https://exirion.net/ssdfanctrl/ ）。
 - Opencore的安装手册中不建议将fakesmc与opencore一起使用, 并且fakesmc已经停止开发,所以如果您想使用持续更新的Virtualsmc，请使用“EFI”文件夹,但是您将失去风扇控制。

### 系统配置
 - BIOS：mrchromebox COREBOOT 4.12 
 - 中央处理器: Intel Core i7-5500U
 - 显卡: Intel HD5500
 - 无线网卡及蓝牙: Intel AC7260
 - 声卡: Realtek ALC283
 - 网卡: Realtek RTL8111

### 正常工作
 - 显卡
 - 声卡
 - 网卡(需要到网络偏好设置中将EN0的硬件选项调至手动，否则显示网线未插好)
 - 读卡器
 - 原生无线网卡（使用heliport连接Wi-Fi）
 - 蓝牙
 - 原生电源管理（已打补丁） 
 - HDMI及声音
 - 风扇控制（通过使用 ssd fan control https://exirion.net/ssdfanctrl/ ）

### 感谢及出处 (没有特定顺序，并且可能遗漏)
 - 美国苹果电脑公司
 - https://github.com/MrChromebox
 - https://github.com/acidanthera
 - https://github.com/RehabMan
 - https://github.com/corpnewt
 - https://www.insanelymac.com/
 - https://www.tonymacx86.com/
 - https://reddit.com/r/hackintosh
 - https://reddit.com/r/chrultrabook
 - https://dortania.github.io/vanilla-laptop-guide/
 - https://blog.daliansky.net/
 - https://blog.xjn819.com/
 - https://github.com/OpenIntelWireless
 - https://github.com/Mieze/RTL8111_driver_for_OS_X
