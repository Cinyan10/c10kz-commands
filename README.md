# 服务器指令


## 服务器相关指令
 * `!list` - 在游戏内显示服务器列表

## 皮肤类指令
 * `!skins` - 打开模型选择菜单
 * `!cw` - 打开自定义武器设置菜单（仅6-9服）
 * `!ws` - 打开武器皮肤设置菜单
 * `!knife` - 打开刀型选择菜单

## 娱乐类指令
 * `!dance` - 跳舞
 * `!pts` - 打开喷图设置菜单
 * `!pt` - 喷图

## GOKZ指令

### gokz-core

 * `!options`/`!o` - 打开设置菜单.
 * `!checkpoint` - 设置存点.
 * `!gocheck` - 传送到存点.
 * `!prev` - 上一个存点.
 * `!next` - 下一个存点.
 * `!undo` - 撤回传送.
 * `!start`/`!restart`/`!r` - 传送回起点.
 * `!searchstart` - 寻找并传送到起点. 用法: `!searchstart <main/#course>`
 * `!end` - 传送到终点. 用法: `!end <main/#course>`.
 * `!setstartpos`/`!ssp` - 自定义起始位置.
 * `!clearstartpos`/`!csp` - 清除自定义起始位置.
 * `!main`/`!m` - 传送到主关卡的起点.
 * `!bonus`/`!b` - 传送到奖励关的起点. 用法: `!b <#bonus>`
 * `!pause`/`!resume` - 暂停/重启计时.
 * `!stop` - 终止计时.
 * `!virtualbuttonindicators`/`!vbi` - 开关计时器指示器(圈).
 * `!virtualbuttons`/`!vb` - 切换锁定计时器,防止其移动.
 * `!mode` - 打开模式选择菜单.
 * `!vanilla`/`!vnl`/`!v` - 切换到VNL模式.
 * `!simplekz`/`!skz`/`!s` - 切换到SKZ模式.
 * `!kztimer`/`!kzt`/`!k` - 切换到KZT模式.
 * `!nc` - 开关飞行.
 * `!ncnt` - 开关忽略触发器的飞行 (不会被板子传送) (noclip-notrigger).
 * `+noclip` - 飞行 (绑键使用).
 * `+noclipnt` - 忽略触发器的飞行 (绑键使用).

### gokz-hud

 * `!menu`/`!cpmenu` - 开关显示存点菜单.
 * `!adv` - 切换高级/简易存点菜单.
 * `!panel` - 开关中心面板的显示.
 * `!timerstyle` - 切换计时器文本显示的样式.
 * `!timertype` - 计时器是否显示NUB/PRO.
 * `!speed` - 开关速度显示.
 * `!hideweapon` - 隐藏手臂.

### gokz-tips

 * `!tips` - 开关小贴士发送.

### gokz-quiet

 * `!hide` - 隐藏其他玩家.
 * `!stopsound` - 关闭所有声音,例如地图音乐声音.

### gokz-pistol

 * `!pistol` - 打开手枪选择菜单.

### gokz-measure

 * `!measure` - 打开距离测量菜单.
 * `+measure` - 开始测量 (绑键使用)
 * `!measureblock` - 测量到板子的距离.

### gokz-goto

 * `!goto` - 传送到其他玩家. 用法: `!goto <player>`

### gokz-saveloc

 * `!saveloc` - 储存一个位置. 用法: `!saveloc <name>`
 * `!loadloc` - 加载位置. 用法: `!loadloc <#id OR name>`
 * `!locmenu` - 打开位置菜单.
 * `!nameloc` - 命名位置. 用法: `!nameloc <#id> <name>`

### gokz-paint

 * `!paint` - 喷涂标记
 * `+paint` - 喷涂标记 (绑键使用)
 * `!paintoptions` - 打开标记设置
 * `r_cleardecals` - 清除标记 (控制台输入或者绑键使用)

### gokz-spec

 * `!spec` - 观察其他玩家. 用法 `!spec <player>`
 * `!specs`/`!speclist` - 显示有哪些玩家在偷偷观察.

### gokz-jumpstats

 * `!jso` - 打开jumpstats菜单.
 * `!jsalways` - 切换总是显示跳跃数据模式.

### gokz-replay

 * `!replay` - 打开回放菜单.
 * `!replaycontrols`/`!rpcontrols` - 打开回放机器人控制菜单.
 * `!replaygoto`/`!rpgoto` - 回放机器人跳转到指定时间. 用法: `!rpgoto hh:mm:ss`   例如:`!rpgoto 3:14` 回放机器人跳转到3分14秒

### gokz-race

 * `!accept` - 加入比赛.
 * `!decline` - 拒绝加入比赛.
 * `!surrender` - 比赛投降.
 * `!race` - 打开举办比赛菜单.
 * `!duel`/`!challenge` - 打开决斗菜单.
 * `!abort` - 放弃当前举办的比赛.

### gokz-localranks

其中大多数指令都需要指定模式.

 * `!top` - 打开服务器记录持有者排行榜
 * `!maptop` - 显示当前地图的排行. 用法: `!maptop <map>`
 * `!bmaptop` - 显示当前地图的奖励关排行. 用法: `!btop <#bonus> <map>`
 * `!pb` - 显示当前地图的个人最佳记录. 用法: `!pb <map> <player>`
 * `!bpb` - 显示当前地图奖励关的个人最佳记录. 用法: `!bpb <#bonus> <map> <player>`
 * `!wr` - 显示世界记录. 用法: `!wr <map>`
 * `!bwr` - 显示奖励关的世界记录. 用法: `!bwr <#bonus> <map>`
 * `!avg` - 显示当前地图的服务器平均用时. 用法 `!avg <map>`
 * `!bavg` - 显示当前地图奖励关的平均用时. 用法 `!bavg <#bonus> <map>`
 * `!pc` - 显示你在服务器的地图完成情况. 用法: `!pc <player>`
 * `!rr`/`!latest` -显示服务器最近刷新的记录.
 * `!jumptop`/`!jstop` - 显示跳跃数据排行.
 * `!jumpstats`/`!js` - 显示最佳跳跃数据. 用法: `!js <jumper>`
 * `!ljpb` - 显示LJPB. 用法: `!ljpb <jumper>`
 * `!bhpb` - 显示 Bunnyhop PB. 用法: `!bhpb <jumper>`
 * `!lbhpb` - 显示 Lowpre Bunnyhop PB. 用法: `!lbhpb <jumper>`
 * `!mbhpb` - 显示 Multi Bunnyhop PB. 用法: `!mbhpb <jumper>`
 * `!wjpb` - 显示 Weird Jump PB. 用法: `!wjpb <jumper>`
 * `!lwjpb` - 显示 Lowpre Weird Jump PB. 用法: `!lwjpb <jumper>`
 * `!lajpb` - 显示 Ladder Jump PB. 用法: `!lajpb <jumper>`
 * `!lahpb` - 显示 Ladderhop PB. 用法: `!lahpb <jumper>`
 * `!jbpb` - 显示 Jumpbug PB. 用法: `!jbpb <jumper>`

### gokz-global

 * `!globalcheck`/`!gc` - 检查记录能否上传到全球.
 * `!tier` - 显示当前地图难度 (非全球图难度显示不准确).
 * `!gr`/`!gwr` - 显示当前地图的全球记录. 用法: `!gr <map>`
 * `!gbr`/`!gbwr` - 显示当前地图奖励关的全球记录. 用法: `!bgr <#bonus> <map>`
 * `!gpb` - 显示当前地图全球的个人记录. 用法: `!gpb <map>`
 * `!gbpb` - 显示当前地图奖励关的全球个人记录. 用法: `!gbpb <#bonus>`
 * `!gmaptop` - 显示当前地图的全球排行. 用法: `!gmaptop <map>`
 * `!gbmaptop` - 显示当前地图奖励关的全球排行: `!gbmaptop <#bonus> <map>`

### gokz-profile

 * `!profile`/`!p` - 打开某个玩家的个人资料. 用法: `!p <player>`
 * `!profileoptions`/`!pfo` - 打开个人资料设置.
 * `!ranks` - 显示段位所需积分.

## 工具类插件指令
 * `!mhud` - 打开MovementHUD设置菜单
 * `!showpos` - 显示位置角度信息
 * `!jt`/`jumpstool` - 打开lj可视化工具
 * `!lj` - 传送到LJ房
 * `!ztopwatch` - 打开区域计时器

### more-stats
 * `!morestats` - 在控制台显示morestats指令
 * `!pausesegment`/`!unpausesegment`/`!resumesegment`/`!togglesegment` - 切换片段录制
 * `!resetsegment` - 重置细分的所有统计信息
 * `!postrunstats` - 在运行结束时显示所有运行统计信息
 * `!bhopstats` - 显示bhop统计. 用法 `!bhopstats <s> <m>`
 * `!perfstreaks <s> <m>` - 显示性能条纹
 * `!scrollstats <s> <m>` - 显示滚动统计
 * `!chatscrollstats` - 在聊天中显示实时滚动统计信息
 * `!chatbhopstats <s> <m>` - 在聊天中显示bhop统计信息，类似于GOKZ的!bhopcheck
 * `!resetcount` / `!rcount <s/map> <c> <m>` - 显示重置计数
 * `!completioncount` / `!ccount <s/map> <c> <m>` - 显示重置和完成计数
 * `!procompletioncount1` / `!pccount <s/map> <c> <m>` - 显示重置和专业完成计数
 * `!chatairstats` - 在聊天中显示实时空中加速统计信息
 * `!airstats <s> <m>`- 显示空中加速统计数据

### Distbug
 * `!distbug` - 打开distbug数据显示
 * `!distbughudgraph` - 在屏幕中心和控制台可视化显示加速
 * `!distbugbeam` - 显示distbug跳跃光束
 * `!distbugveerbeam` - 显示distbug跳跃角度
 * `!distbugadvchat` - distbug高级聊天切换，以减少垃圾信息
 * `!distbugversion` - 显示distbug版本
 * `!strafestats` - 开关显示加速数据
 * `!distbughelp` - 在控制台显示distbug指令
 * `!perfstats` - 显示bhop数据统计

# 管理员指令

### 服务器

 * `!admin` - 打开管理员菜单
 * `!ban` - 封禁某人

### 分发武器
 * `!weapon <player/@me/@all> <weapon_name>` - 给某人分发武器


### gokz-anticheat

 * `!bhopcheck` - 显示bhop统计报告.

### gokz-localdb

 * `!savetimersetup`/`!sts` - 将当前计时器设置（开始位置和虚拟按钮）保存到数据库.
 * `!loadtimersetup`/`!lts` - 从数据库加载并锁定计时器设置（开始位置和虚拟按钮）.
 * `!setcheater` - 将某人设置为作弊者. 用法: `!setcheater <STEAM_1:X:X>`
 * `!setnotcheater` - 将某人设置为非作弊者. 用法: `!setnotcheater <STEAM_1:X:X>`
 * `!deletebestjump` - 删除某人的最佳跳跃数据. 用法: `!deletebestjump <STEAM_1:X:X> <mode> <jump type> <block?>`
 * `!deletealljumps` - 删除某人的所有跳跃数据. 用法: `!deletealljumps <STEAM_1:X:X>`
 * `!deletejump` - 通过jumpid删除跳跃数据. 用法: `!deletejump <id>`
 * `!deletetime` - 通过计时ID删除计时. 用法: `!deletetime <id>`

### gokz-localranks

 * `!updatemappool` - 更新位于`cfg/sourcemod/gokz/gokz-localranks-mappool`的地图池.cfg.

### LJ房传送
* `!setlj` - 设置LJ房
* `!dellj` - 删除设置的LJ房

### more-stats
 * `!morestatsdelete <UID> <all/bhop/reset/air>`- 删除所选玩家的统计信息。UID是玩家的SteamID3中的数字：[U:1:XXXXXXXXX]



