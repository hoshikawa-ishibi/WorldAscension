# 安装与更新

本包是 WorldBox 的社区代码模组，需要 NeoModLoader（NML）。目前仅验证 Windows、WorldBox 0.51.2（Steam build 19962337）、NML 1.2.0.1。不要为了安装本包直接更新一个正在使用的固定版本。

## 第一次安装 NML

1. 在 Steam 的 WorldBox 属性中选择“已安装文件 → 浏览”，找到包含 `worldbox.exe` 的游戏目录。
2. 按 [NML 官方安装说明](https://worldboxopenmods.gitbook.io/mod-tutorial-en/player-manual/install)取得与游戏匹配的加载器。首次安装需要手动放入 `worldbox_Data/StreamingAssets/mods/NeoModLoader.dll`；单纯订阅创意工坊不会完成这一步。
3. 开启游戏设置里的实验模式（Experimental Mode），退出后重新启动，让 NML 完成初始化。
4. 确认游戏里出现 NML 的模组列表，再正常关闭游戏。

本包不附带游戏本体、原版程序集或 NML。加载器与游戏版本不匹配时，请查对应版本说明，不要混装多个加载器。

## 安装 World Ascension

1. 关闭 WorldBox，把解压后的整个 `WorldAscension` 文件夹放入游戏目录的 `Mods` 文件夹。
2. 检查最终路径：`worldbox/Mods/WorldAscension/mod.json`。`WorldAscension.dll` 应与 `mod.json` 同级；避免多套一层文件夹。
3. 启动游戏，在 NML 模组列表中确认 **World Ascension** 已启用。若显示加载失败，先核对游戏、NML 和模组版本。
4. 用新世界或已有世界的副本开始游玩。入口是 **世界飞升 → 总览 → 国家面板**，然后点击一座城市。

只保留一个启用的 World Ascension 副本；手动安装与 Workshop 订阅版本不要同时加载。NML 的常规启用/停用操作通常需要重启游戏。[NML 使用说明](https://worldboxopenmods.gitbook.io/mod-tutorial-en/player-manual/howtouseit)

## 更新与移除

- **更新：** 先关闭游戏，将旧模组文件夹移到游戏扫描目录之外作为备份，再放入新版本文件夹。不要在游戏运行时覆盖 DLL。
- **世界备份：** 模组将科技、设施、分工、国家计划等保存在世界数据里。更新前保留一份未覆盖的世界副本。
- **移除：** 关闭游戏后移走模组文件夹或停用订阅。已有世界中的自定义建筑、装备、特质可能依赖本模组，因此不承诺移除后能无损继续。需要回到纯原版时优先使用安装前的世界备份。
- **日志：** 模组日志位于游戏目录的 `Logs/WorldAscension/worldascension.log`。反馈时附版本、复现步骤和相关错误片段；分享日志前检查其中是否含私人路径。

## 反馈时写什么

说明游戏版本、NML 版本、模组版本，以及使用的新世界或旧世界、发生前的操作、期望结果与实际结果。国家面板的原因提示能帮助区分条件未满足和程序故障。无需上传整个个人存档目录。
