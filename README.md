# macOS Catalina for MECHREVO S1

- [Enable macOS HiDPI](https://github.com/xzhih/one-key-hidpi) 
- [CPUFriend](https://github.com/daliansky/XiaoMi-Pro/tree/master/one-key-cpufriend) 

## Configuration

| Specifications | Detail                                                  |
| ------------------- | -------------------------------------------|
| Computer model      | MECHREVO S1 (MX150/GTX)                    |
| Processor           | Intel Core i5-8250U/i7-8550U Processor     |
| Memory              | 8GB/16GB Samsung DDR4 2400MHz              |
| Hard Disk           | FORESEE NVMe SSD Controller P900F 256GB    |
| Integrated Graphics | Intel UHD Graphics 620                     |
| Monitor             | CMO CMN14D5 FHD 1920x1080 (14 inch)        |
| Sound Card          | Realtek ALC298 (layout-id:66)              |
| Wireless Card       | Intel Wireless 3168                        |
| SD Card Reader      | Realtek RTS5129                            |

## Features

* Non-working
   * GPU (Nvidia MX150/GTX)
   * WIFI (Intel® Dual Band Wireless-AC 3168)
   * SD Card Reader (Realtek RTS5129)
   * Fingerprint

## Credits

- [RehabMan](https://github.com/RehabMan) 
- [daliansky](https://github.com/daliansky) 

## Change Log:

- 2019.07.10
	- Update Clover4986 & Kext.

- 2019.07.08
	- Update Kext.

- 2019.07.06
	- Update Kext | Support macOS10.15.

- 2019.07.04
	- Update Clover4979 & Kext & config.plist | Add OpenCore0.0.3.
	- 新增 OC 引导，若要使用 OC 引导，需在Win下手动添加 \EFI\BOOT\BOOTX64.efi 为引导项即可选择进入OC.
	- 目前 SMCBatteryManager 暂不支持升级到 10.15b3，等待更新.

- 2019.06.27
	- Update Clover4977 & Hotpatch & Kext.
	- 目前该分支在 10.15 上还存在 多手势触控板 等小功能异常,但已经可以日常使用(忽略 Catalina 自身 Bug).

- 2019.06.27
	- Update Clover4977 & Hotpatch & Kext.
	- 目前该分支在 10.15 上还存在 多手势触控板 等小功能异常,但已经可以日常使用(忽略 Catalina 自身 Bug).

- 2019.06.22
	- Update Clover4968 & Kext | Fix Blutooth.
	- 更新到 Clover4968 版本,更新BCM94352z Kext (联想NGFF)修复蓝牙配对问题.
	- 目前该分支在 10.15 上还存在 多手势触控板 等小功能异常,但已经可以日常使用(忽略 Catalina 自身 Bug),除非用于测试,否则不建议更新.

- 2019.06.12
	- Update Clover4964 & Kext.
	- 更新到 Clover4964 版本,更新键盘 Kext 修复触摸板失效.
	- 目前该分支在 10.15 上还存在 多手势触控板\蓝牙配对 等小功能异常,但已经可以日常使用(忽略 Catalina 自身 Bug),除非用于测试,否则不建议更新.

- 2019.06.09
	- Update Clover4958 & Kext.
	- 更新到 Clover4958 版本,更新键盘 Kext 切换 Option/Command 按键,目前该分支在 10.15 上还存在 多手势触控板\蓝牙配对 等小功能异常,但已经可以日常使用(忽略 Catalina 自身 Bug),除非用于测试,否则不建议更新.

- 2019.06.08
	- Update Clover4953 & config.plist.
	- 更新到 Clover4953 版本,更新 config.plist,目前该分支在 10.15 上还存在 多手势触控板\蓝牙配对 等小功能异常,但已经可以日常使用(忽略 Catalina 自身 Bug),除非用于测试,否则不建议更新.

- 2019.06.07
	- Update Clover4950 & Kext latest build for Catalina | Fix Battery and Sensor.
	- 更新到 Clover4950 版本,更新 Kext 为原作者最新提交编译版本, 修复电池及其他传感器信息显示,目前该分支在 10.15 上还存在 多手势触控板\蓝牙配对 等小功能异常,但已经可以日常使用(忽略 Catalina 自身 Bug),除非用于测试,否则不建议更新.

- 2019.06.06
	- Update Clover4948 & Kext latest build for Catalina | This Branch  Only Test For Catalina.
	- 更新到 Clover4948 版本,更新 Kext 为原作者最新提交编译版本,这个分支今后将以测试为目的更新,目前该分支在 10.15 上还存在多功能触摸板\蓝牙\电池信息等小功能异常,但已经可以日常使用(忽略 Catalina 自身 Bug),除非用于测试,否则不建议更新.

- 2019.06.04
	- Update Clover4942 & Kext latest build for Catalina.

- 2019.06.01
	- Update Hotpatch & Kext for Fix USB3.0 speed.

- 2019.05.29
	- Update config.plist & Kext for Fix Line-in Mic.

- 2019.05.27
	- Update Kext.

- 2019.05.26
	- Update Hotpatch & config.plist.

- 2019.05.25
	- Update Kext.

- 2019.05.24
	- Update Clover.

- 2019.05.23
	- Update Kext & config.plist.

- 2019.05.22
	- Update Clover & config.plist.

- 2019.05.14
	- Update Kext & config.plist.

- 2019.05.13
	- Update Hotpatch.

- 2019.05.10
	- Update Hotpatch & Kext & config.plist.

- 2019.04.28
	- Update Clover & Hotpatch & Kext & config.plist.

- 2019.03.25
	- Update Hotpatch & Kext.

- 2019.03.14
	- Update config.plist.

- 2019.03.1
	- Update Clover & Kext & config.plist.

- 2019.02.25
	- Update config.plist.

- 2019.02.14
	- Update Hotpatch & config.plist.

- 2019.02.11
	- Update Clover & Hotpatch & Kext & config.plist.

- 2019.01.29
	- Update Hotpatch.

- 2019.01.27
	- Update Kext.

- 2019.01.17
	- Update Hotpatch & config.plist.

- 2019.01.16
	- Update Kext & config.plist.

- 2019.01.13
	- Update Clover & Kext & config.plist.

- 2019.01.08
	- Update Kext.

- 2019.01.07
	- Update Hotpatch & Kext.

- 2019.01.04
	- Update Kext for Broadcom BCM94352z/DW1560.

- 2019.01.04
	- Update Clover & Hotpatch & Kext & config.plist for macOS Mojave 10.14.2.

- 2018.05.27
	- Update Clover & Hotpatch & Kext & config.plist.

- 2018.05.19
	- Update Clover & Hotpatch & Kext & config.plist.

- 2018.05.13
	- High Sierra Clover EFI uploaded on Git.


## Support and discussion

http://bbs.pcbeta.com/viewthread-1785843-1-1.html
