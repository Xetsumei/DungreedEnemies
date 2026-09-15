# DungreedEnemies 1.1.0

[한국어](README_ko.md) · [English](README_en.md) · [日本語](README_jp.md) · [中文](README_zh.md)

将Dungreed的90种普通怪物与8类BOSS移植到塞菲莉亚俯视战斗中的AddOn。普通怪物会从各层候选中自然出现。德瓦娜仍不在自然出现候选中。

## 主要功能

- 每个普通生成位置以50:50概率选择原版敌人或本层Dungreed敌人，并不保证每个房间恰好各占一半。
- 没有独立设置窗口。安装EM后可在其列表中禁用这些敌人。EM、QoL、ModMaker均非必需。
- 普通怪物、BOSS及附属实体共107个名称支持韩语、英语、日语、简体中文，并跟随游戏语言。
- F8测试功能已关闭。

## 安装

将ZIP解压至`Sephiria/AddOns/DungreedEnemies`，将`metadata.json`、DLL与`Libs`保存在同一文件夹。 同时保留`DungreedEnemies.pak`。

## 自动更新

进入游戏后会检查新版本，并在大厅提供［立即更新・稍后提醒・跳过此更新］。点击立即更新后会下载并重启游戏。冒险中不会自动弹窗或关闭游戏。

用`/de update`手动检查，`/de update off`关闭自动检查，`/de update on`重新开启。手动检查也会显示已跳过的版本。

文件通过验证后才会安装，现有设置会保留。若新版本更改了Libs，请下载ZIP并关闭游戏后覆盖安装。

没有此功能的旧版本需要先手动安装一次新ZIP。

[更新记录](patchlog_zh.md)
