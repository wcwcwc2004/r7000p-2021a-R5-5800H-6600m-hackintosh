# r7000p-2021a-R5-5800H-6600m-hackintosh


黑苹果肌本完美在13.5系统下 整体功能没啥问题 亮度可调 必须切换bios独立显卡模式  插电盒盖能秒唤醒 不插电盒盖必黑死
14系统也能用需要更换w驱动  但是有一个坑就是 bcm94360网卡13.5系统不免驱 用不了用不了 可能是amd本子的锅 
解决不了 加了驱动没用 重制nv没用 加pcie地址没用 放弃了 买了ax210 网卡 回头再测试一下dw1830网卡 

Hello everyone, the Monterey kernel panic problem has been solved for AMD R7 5800H notebook installation. It is a great thing that the CPU can now run on 8 cores. Thank you guys very much.Thank them for discovering the problem and providing kernel patches @ExtremeX@Visual

Brand: Lenovo
Model: Legion 5 6th Gen
CPU: AMD Ryzen 7 5800h
GPU: AMD Radeon RX 6600m 8GB ( Separate GPU mode)
HDD: Samsung SSD 970 EVO Plus 1TB (1000 GB, PCI-E 3.0 x4)
WDS500G3X0C-00SJG0 (500 GB, PCI-E 3.0 x4)
Network: RealTek Semiconductor RTL8168/8111 PCI-E Gigabit Ethernet NIC
Intel(R) Wi-Fi 6E AX210 160MHz
Ram: x2 8GB 3200mhz ddr4
Display: 15.6 1080p 165HZ

Updated October 5, 2023
Problems solved:
1. You do not need to disable XHCI
2. The microphone problem is rectified
3. Monitor brightness can be adjusted, only in Ventura

Unresolved issues:
Failure to wake from sleep



form this ：https://forum.amd-osx.com/threads/amd-rayon-r7-5800h-install-monterey-kernel-panic.2725/
