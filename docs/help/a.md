# 会战

## yobot

| 关键词   | 说明                           |
| -------- | ------------------------------ |
| 登录     | 登录进入 Web 模式              |
| 重置密码 | 随机重置一个新密码             |
| 手册     | 获取yobot手册                  |
| 退出此群 | (管理员)命令机器人退出当前群聊 |
| version  | 查看yobot版本                  |

## 合刀挂树提醒

| 关键词        | 说明                                         |
| ------------- | -------------------------------------------- |
| 挂树/取消挂树 | 带计时的挂树功能,按55分钟算                  |
| 合刀 A B C    | 三个字母分别是刀1伤害/刀2伤害/剩余血量(国服) |


## 公会排名

| 关键词                   | 说明                                                         |
| ------------------------ | ------------------------------------------------------------ |
| 查询排名 公会名 (会长名) | 查询指定公会排名,如有重名需要附加会长名                      |
| 查询分段                 | 查询分段信息                                                 |
| 查询关注                 | 查询关注的公会信息                                           |
| 添加关注 公会名 (会长名) | (需要管理员权限)将指定公会加入关注列表,如有重名需要附加会长名 |
| 删除关注 公会名          | (需要管理员权限)将指定公会从关注列表中删除                   |
| 清空关注                 | (需要管理员权限)清空关注列表                                 |

使用 [wiki.biligame.com](https://wiki.biligame.com/pcr/团队战分数查询工具) API获取数据

项目[地址](https://github.com/zyujs/clanbattle_rank)

公会战期间本插件将定时推送关注信息, 分别为前6天的5:15和第6天的23:55


## 公会排名2

| 关键词          | 说明           |
| --------------- | -------------- |
| 会战锁定 公会名 | 锁定一个公会   |
| 会战解锁 公会名 | 解锁一个公会   |
| 公会排行        | 查询锁定的公会 |

※最好不要和公会排名同时开启

## 会战报告

| 关键词                         | 说明                                         |
| ------------------------------ | -------------------------------------------- |
| 生成会战报告 [@用户] [API地址] | 生成会战报告                                 |
| 生成离职报告 [@用户] [API地址] | 生成离职报告                                 |
| 设置工会api API地址            | (需要管理员权限)为本群设置默认的Yobot工会API |
| 查看工会api                    | (需要管理员权限)查看本群设置的Yobot API      |
| 清除工会api                    | (需要管理员权限)清除本群设置的Yobot API      |

使用Yobot API数据生成离职报告和会战报告的HoshinoBot插件,由用户自行指定API地址，可使用任意远程服务器的Yobot数据生成报告

项目[地址](https://github.com/zyujs/clanbattle_report)



## BOX统计

| 关键词                                                       | 说明                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 一键box统计 [补录]                                           | 在配置完box统计参数后使用此指令，机器人会自动私聊公会成员统计其box。如果填写参数"补录"，则会开启补录模式，只让成员填写他们还没录入的角色星级和Rank |
| 设置box统计 <数据库名> <统计对象> <备注> <统计的角色名(逗号分隔,需要统计Rank的角色请在角色名后加上"R")> | 统计对象参数目前支持填写"all"(全部成员) 或"allE@xxx@yyy"(全部成员除去xxx和yyy) 或"@xxx@yyy"(xxx和yyy) |
| 查看box统计 [数据库名]                                       | 查看指定数据库的统计情况                                     |
| 查看box统计 [数据库名] <@qq>                                 | 查看指定用户录入的所有角色星级Rank                           |
| 查看box统计 [数据库名] <角色名>                              | 查看数据库中指定角色的星级Rank分布                           |
| 查看box统计 [数据库名] <@qq> <角色名>                        | 指定用户指定角色, 查看其星级Rank                             |
| 删除box数据 [数据库名] <@qq>                                 | 删除指定用户的box信息                                        |
| 删除box数据 [数据库名] <角色名>                              | 删除数据库中指定角色的所有录入信息                           |
| 查看box数据库名 [数据库名]                                   | 查看所有存放box的数据库的名称                                |
| 查看已统计角色 [数据库名]                                    | 查看已经录入数据库的所有角色名称                             |
| 导出box统计表 [数据库名]                                     | 从数据库中导出csv格式的box统计表格到后台                     |
| 发送box统计图 [数据库名]                                     | 机器人发送图片形式的box统计表格到群里                        |

## pcr轴

| 关键词                                    | 说明               |
| ----------------------------------------- | ------------------ |
| 录入轴  A/B <1/2/3/4/5>                   | <伤害> <说明> <轴> |
| 查找轴  A/B [1/2/3/4/5]                   |                    |
| 查找轴 [编号]                             |                    |
| 更新轴 <编号> <伤害> <说明> <轴>          |                    |
| 删除轴 <编号>                             |                    |
| 赞同轴 <编号> [赞同数,非管理员只能填1/-1] |                    |
| 查看轴库名                                |                    |
| 切换轴库 <新轴库名>                       |                    |

