# MCDR插件
## [Quick Backup Multi](https://mcdreforged.com/zh-CN/plugin/quick_backup_multi "多槽位备份/回档插件")  
- ### Usage
  `!!qb` 显示帮助信息  
  `!!qb list` 显示各槽位的存档信息  
  `!!qb confirm` 确认是否进行回档  
  `!!qb abort` 中断回档  
  `!!qb reload` 重新加载配置文件

  ---
  以下指令推荐用`!!qb list`后手动操作
  > `!!qb make [<comment>]` 创建一个储存至槽位`1`的备份，并将后移已有槽位，`<comment>`为可选存档注释  
  > `!!qb back [<slot>]` 回档为槽位 <slot> 的存档  
  > `!!qb del <slot>` 删除槽位`<slot>`的存档，默认为槽位1  
  > `!!qb rename <slot> <comment>` 修改槽位`<slot>`的注释  
  

- ### [Config](https://github.com/KiiiLin/Redstone_Survival_Quarter/blob/main/mcdr_plugin/config/QuickBackupM.json)  

## [Timed QBM](https://mcdreforged.com/zh-CN/plugin/timed_quick_backup_multi "一个QuickBackupM插件的扩展，用于定时触发QBM从而进行自动备份")  
- ### Usage
  `!!tqb` 显示帮助信息  
  `!!tqb status` 查看状态  
  `!!tqb enable` 启动备份定时器  
  `!!tqb disable` 关闭备份定时器  
  `!!tqb set_interval <minutes>` 设置备份定时器时间间隔，单位分钟  
  `!!tqb reset_timer` 重置备份定时器  
 

- ### [Config](https://github.com/KiiiLin/Redstone_Survival_Quarter/blob/main/mcdr_plugin/config/timed_quick_backup_multi.json)  

## [Where2go](https://mcdreforged.com/zh-CN/plugin/where2go "一个功能强大的位置插件，包含共享坐标点、查询玩家位置等功能")  
- ### Usage  
- ### [Config](https://github.com/KiiiLin/Redstone_Survival_Quarter/blob/main/mcdr_plugin/config/where2go/config.json)  

## [Bot](https://mcdreforged.com/zh-CN/plugin/bot "最好用的地毯模组假人管理器！")  
- ### Usage  
- ### [Config](https://github.com/KiiiLin/Redstone_Survival_Quarter/blob/main/mcdr_plugin/config/bot/config.json)  

## [Seed](https://mcdreforged.com/zh-CN/plugin/seed "在没有op权限的情况下获取种子")  
- ### Usage  
- ### [Config](https://github.com/KiiiLin/Redstone_Survival_Quarter/blob/main/mcdr_plugin/config/seed/config.json)  

## [LoginProxy](https://mcdreforged.com/zh-CN/plugin/loginproxy "Minecraft 服务器登录代理兼白名单插件")  
- ### Usage  
- ### [Config](https://github.com/KiiiLin/Redstone_Survival_Quarter/blob/main/mcdr_plugin/config/loginproxy/config.json)  

## [Join MOTD](https://mcdreforged.com/zh-CN/plugin/join_motd "当玩家加入游戏时向其发送欢迎信息")  
- ### Usage  
- ### [Config](https://github.com/KiiiLin/Redstone_Survival_Quarter/blob/main/mcdr_plugin/config/joinMOTD.json)  

## [Crash Restart](https://mcdreforged.com/zh-CN/plugin/crash_restart "在服务端崩溃后自动重启服务器的插件")  
- ### Usage  
- ### [Config](https://github.com/KiiiLin/Redstone_Survival_Quarter/blob/main/mcdr_plugin/config/CrashRestart.json)  
