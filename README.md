# -root-
小白写给自己手机root指南

所有工具在master分支

设备：

Redmi Note 12T pro

Redmi Note 10 pro

ROOT步骤:
-----------------------------------------------------------------------------------------------------------------------------
一、解BL：

官方解锁：

打开开发者选项，打开OEM引导，解锁设备（按官方要求登录小米社区绑定手机和账号，完成内测申请，大约需要半个月刷积分）

使用小米官方解锁工具 http://www.miui.com/unlock/index.html   

强解：

（联发科MTK 天玑1100以前的芯片可强解）

1.下载强解MTK工具包：

2.安装驱动路径：   （之后删除驱动时不要断开手机连接，否则可能找不到andriod设备信息，无法删除）
            
            a.MTK工具等3个文件\MTK工具\MTK工具箱\MTK工具箱\驱动  5个驱动，按需安装
      
            b.MTK工具等3个文件\MTK工具\AUTO_MTK_UNBL_TOOL.V.07.10.21\AUTO_MTK_UNBL_TOOL.V.07.10.21\AUTO_MTK_UNBL_TOOL.V.07.10.21.exe（密码在同路径文件中）

3.MTK_Client解锁：

按照工具中的提示 （关机，接线，同时按住两个音量键，找到点击unlock bootloader，成功后拔线重启，或连续点击电源强制重启）

            MTK工具等3个文件\MTK工具\MTK工具箱\MTK工具箱\MTK_Client.exe



----------------------------------------------------------------------------------------------------------------------------

二、Root: 

刷机包下载 官方版：https://xiaomirom.com/series/

系统更新版：在系统更新里下载到100%断网找到boot.img

部分root版：

使用官方的miflash 刷机包

suroot版：

Magisk下载  https://github.com/topjohnwu/Magisk

打开magisk修复boot.img,获取到新img传给电脑

秋之盒下载 https://atmb.top/

打开秋之盒，点击fastboot

点击刷入boot(img)，选择之前传到电脑上的img文件

成功后点击重启，查看magisk情况

                
