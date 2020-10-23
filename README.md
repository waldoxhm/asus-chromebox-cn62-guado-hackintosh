# asus-chromebox-cn62-guado-hackintosh
opencore efi partition（osx catalina 10.15.7 with opencore 0.6.1 ）

System configuration
BIOS：mrchromebox COREBOOT 4.12 
CPU: Intel Core i7-5500U
Graphic: Intel HD5500
WiFi&BT: Intel AC7260
Audio: Realtek ALC283
Ethernet: Realtek RTL8111

What's working
IGPU
Audio
Ethernet(set EN0-interface-preferences-hardware to manual or will not wired)
SD card reader
Original WIFI module(use heliport to connect wifi)
BLUETOOTH
Native Power Management （patched）

Not working
FAN control（fan runs at 2400 RPM ，does not change speed）

Not sure
HDMI + Audio(I'm using DP Display with BT speaker,test it yourself)

Credits & Sources (in no particular order and maybe missing some)
Apple
https://github.com/MrChromebox
https://github.com/acidanthera
https://github.com/RehabMan
https://github.com/corpnewt
https://www.insanelymac.com/
https://www.tonymacx86.com/
https://reddit.com/r/hackintosh
https://reddit.com/r/chrultrabook
https://dortania.github.io/vanilla-laptop-guide/
https://blog.daliansky.net/
https://blog.xjn819.com/
https://github.com/OpenIntelWireless
https://github.com/Mieze/RTL8111_driver_for_OS_X

————————————————————————————————————————————————————————————————————————————————
OPENCORE efi分区所有文件（osx catalina 10.15.7 with opencore 0.6.1）

系统配置
BIOS：mrchromebox COREBOOT 4.12 
中央处理器: Intel Core i7-5500U
显卡: Intel HD5500
无线网卡及蓝牙: Intel AC7260
声卡: Realtek ALC283
网卡: Realtek RTL8111

正常工作
显卡
声卡
网卡(需要到网络偏好设置中将EN0的硬件选项调至手动，否则显示网线未插好)
读卡器
原生无线网卡（使用heliport连接Wi-Fi）
蓝牙
原生电源管理（已打补丁） 

不正常工作
风扇控制（风扇一直匀速2400转左右，不会改变转速）

不确定
HDMI的声音(我用DP显示器和蓝牙音箱，HDMI声音需要自行测试)

感谢及出处 (没有特定顺序，并且可能遗漏)
美国苹果电脑公司
https://github.com/MrChromebox
https://github.com/acidanthera
https://github.com/RehabMan
https://github.com/corpnewt
https://www.insanelymac.com/
https://www.tonymacx86.com/
https://reddit.com/r/hackintosh
https://reddit.com/r/chrultrabook
https://dortania.github.io/vanilla-laptop-guide/
https://blog.daliansky.net/
https://blog.xjn819.com/
https://github.com/OpenIntelWireless
https://github.com/Mieze/RTL8111_driver_for_OS_X
