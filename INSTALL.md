# 安装与更新 / Installation and Updates

## 中文

World Ascension 是 WorldBox 的社区代码模组，需要 NeoModLoader（NML）。目前确认兼容 Windows、WorldBox 0.51.2（Steam build 19962337）和 NML 1.2.0.1。

### 安装

1. 按 [NML 安装说明](https://worldboxopenmods.gitbook.io/mod-tutorial-en/player-manual/install)安装与游戏版本匹配的 NeoModLoader，并开启 WorldBox 的 Experimental Mode。
2. 关闭 WorldBox。
3. 解压下载包，把其中整个 `WorldAscension` 文件夹放进游戏目录的 `Mods` 文件夹。
4. 检查最终路径为 `worldbox/Mods/WorldAscension/mod.json`；`WorldAscension.dll` 应与 `mod.json` 同级。
5. 启动游戏，在 NML 模组列表中确认 **World Ascension** 已启用。
6. 建议先用新世界或已有世界的副本游玩。入口是 **世界飞升 → 总览 → 国家面板**。

不要把整个ZIP直接放进 `Mods`，也不要同时启用手动安装和 Steam Workshop 订阅的两个副本。

### 语言

模组跟随 WorldBox 的语言设置。中文语言使用简体中文界面，English 使用英文界面。切换语言后，已打开的国家面板和说明窗口会自动刷新，无需重开窗口或重启游戏。

### 更新与移除

- 更新前关闭游戏，并备份重要世界。
- 把旧 `WorldAscension` 文件夹移出游戏扫描目录，再放入新版本；不要在游戏运行时覆盖 DLL。
- 移除时关闭游戏，再移走模组文件夹或取消订阅。包含自定义建筑、装备或特质的世界可能依赖本模组，返回纯原版时优先使用安装前的世界备份。
- 日志位于 `worldbox/Logs/WorldAscension/worldascension.log`。

## English

World Ascension is a community code mod for WorldBox and requires NeoModLoader (NML). The verified environment is Windows, WorldBox 0.51.2 (Steam build 19962337), and NML 1.2.0.1.

### Install

1. Follow the [NML installation guide](https://worldboxopenmods.gitbook.io/mod-tutorial-en/player-manual/install) to install a NeoModLoader version compatible with your game, then enable Experimental Mode in WorldBox.
2. Close WorldBox.
3. Extract the download and place the entire `WorldAscension` folder inside the game's `Mods` folder.
4. Confirm the final path is `worldbox/Mods/WorldAscension/mod.json`; `WorldAscension.dll` must be next to `mod.json`.
5. Start the game and confirm **World Ascension** is enabled in the NML mod list.
6. Start with a new world or a copy of an existing one. Open **World Ascension → Overview → National Panel**.

Do not place the ZIP itself in `Mods`, and do not enable both a manual copy and a Steam Workshop subscription at the same time.

### Language

The mod follows the WorldBox language setting. Chinese uses the Simplified Chinese interface, and English uses the English interface. Open National Panel and guide windows refresh automatically after a language switch; reopening the window or restarting the game is unnecessary.

### Update or remove

- Close the game and back up important worlds before updating.
- Move the old `WorldAscension` folder outside the game's scan path, then install the new copy. Do not overwrite the DLL while the game is running.
- To remove the mod, close the game and move the folder away or unsubscribe. Worlds containing custom buildings, equipment, or traits may depend on the mod; use a pre-install backup when returning to vanilla.
- The log is at `worldbox/Logs/WorldAscension/worldascension.log`.

When reporting a problem, include the WorldBox, NML, and World Ascension versions, other enabled mods, reproduction steps, and the relevant log lines.
