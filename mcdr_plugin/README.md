# MCDR插件
## [Quick Backup Multi](https://mcdreforged.com/zh-CN/plugin/quick_backup_multi "多槽位备份/回档插件")  
- ### Usage
  `!!qb` 查看帮助  
  `!!qb list` 显示各槽位的存档信息  
  `!!qb confirm` 确认是否进行回档  
  `!!qb abort` 中断回档  
  `!!qb reload` 重新加载配置文件

  ---
  以下指令推荐用`!!qb list`后手动操作
  > `!!qb make [comment]` 创建一个储存至槽位`1`的备份，并将后移已有槽位，`[comment]`为可选存档注释  
  > `!!qb back [slot]` 回档为槽位`[slot]`的存档  
  > `!!qb del <slot>` 删除槽位`<slot>`的存档，默认为槽位1  
  > `!!qb rename <slot> <comment>` 修改槽位`<slot>`的注释  
  

- ### [Config](https://github.com/KiiiLin/Redstone_Survival_Quarter/blob/main/mcdr_plugin/config/QuickBackupM.json)  

## [Timed QBM](https://mcdreforged.com/zh-CN/plugin/timed_quick_backup_multi "一个QuickBackupM插件的扩展，用于定时触发QBM从而进行自动备份")  
- ### Usage  
  **至少需要`权限2`才能操作**  

  `!!tqb` 查看帮助  
  `!!tqb status` 查看状态  
  `!!tqb enable` 启动备份定时器  
  `!!tqb disable` 关闭备份定时器  
  `!!tqb set_interval <minutes>` 设置备份定时器时间间隔，单位分钟  
  `!!tqb reset_timer` 重置备份定时器  

- ### [Config](https://github.com/KiiiLin/Redstone_Survival_Quarter/blob/main/mcdr_plugin/config/timed_quick_backup_multi.json)  

## [Where2go](https://mcdreforged.com/zh-CN/plugin/where2go "一个功能强大的位置插件，包含共享坐标点、查询玩家位置等功能")  
- ### Usage  
  `!!wp` 查看帮助  
  `!!wp list [page]` 列出所有的坐标点,`[page]`为页数可选项，默认为1    
  `!!wp addhere <name>` 将玩家当前位置添加为名为`<name>`的坐标点  
  `!!wp addpos <x> <y> <z> <dimension> <name>` 添加名为`<name>`，坐标为(`<x>`, `<y>`, `<z>`)，位于`<dimension>`维度的坐标点，`<dimension>`可以为`overworld` `the_nether` `the_end`或分别简写为`o` `n` `e`  

  ---
  以下指令推荐用`!!wp list`后手动操作  
  >`!!wp info <id>` 查看坐标点`<id>`详情  
  >`!!wp remove <id>` 移除坐标点`<id>`  

  >tips:通过`[+X#]`可以添加坐标点到Xaero  
  >*高版本只能点击`#`部分发布坐标后，通过`[add]`手动添加到Xaero*  

  ---
  `!!here` 广播自身位置与100m内坐标点  
  `!!whereis <player>` 查询`<player>`的位置  
  >tips:使用`XXX在哪` `XXX在哪里` `XXX在哪里?`等语句也可以查询
- ### [Config](https://github.com/KiiiLin/Redstone_Survival_Quarter/blob/main/mcdr_plugin/config/where2go/config.json)  

## [Bot](https://mcdreforged.com/zh-CN/plugin/bot "最好用的地毯模组假人管理器！")  
- ### Usage  
  `!!bot` 查看帮助  
  `!!bot list [filters]` 显示假人列表  
  >`[filters]`选项  
  >`--index <index>`：页码，例如 `--index 1`，`<index>`默认为 0  
  >`--online`：显示在线假人  
  >`--saved`：显示保存的假人  
  >`--tag <tag>`：按标签过滤  
  
  `!!bot save <name> [position] [facing] [dimension]`  保存假人

- ### [Config](https://github.com/KiiiLin/Redstone_Survival_Quarter/blob/main/mcdr_plugin/config/bot/config.json)  

## [Seed](https://mcdreforged.com/zh-CN/plugin/seed "在没有op权限的情况下获取种子")  
- ### Usage  
  `!!seed` 获取服务器种子  
  ~~真的没有了~~  

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

---
# 创造服特供

## [Simple OP](https://mcdreforged.com/zh-CN/plugin/simple_op)  
- ### Usage  
  `!!op` 获取op  
  `!!restart` 重启服务器
  
