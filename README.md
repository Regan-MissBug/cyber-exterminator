# 赛博虫师 Cyber Exterminator

[中文说明](#中文说明) · [English](#english)

## 中文说明

《赛博虫师》是一款 Unity 横屏游戏原型：识别不同机械害虫，并使用点击、斩击、画圆、双击、V 形和捏合等对应手势进行净化，保护中央净化核心。

当前公开试玩版本：**v0.6.0**

## 在线试玩

手机或电脑直接打开：[进入《赛博虫师》在线试玩](https://regan-missbug.github.io/cyber-exterminator/)

手机请横屏游玩。首次进入需要加载约 14 MB 游戏数据；微信中可直接点击链接打开，无需下载安装包。

## 下载试玩版

请前往 [Releases](https://github.com/Regan-MissBug/cyber-exterminator/releases/latest) 下载：

- `CyberExterminator-Mac-v0.6.0.zip`
- `CyberExterminator-Windows-x64-v0.6.0.zip`
- `CyberExterminator-v0.6.0-Playtest-Guide.md`：试玩与验收说明

本仓库仅发布试玩包，不提供 Unity 源码。

## 游戏模式

- **关卡模式**：共六关，逐关加入新的机械害虫。
- **无尽模式**：虫种和压力随存活时间逐步增加。
- **游戏设置**：支持音效、音量、全屏/窗口和四档难度，并自动保存。

## v0.6.0 新内容

- **四档难度**：简单、一般、中等、大师；难度只调整虫子的爬行速度和出现频率。
- **强化打击感**：正确净化增加白闪、冲击环、轻微镜头震动和冲击音层。
- **连击反馈**：评级文字和连击数字会短促回弹，每 5 连击触发额外光效与升调提示。
- **脉冲反馈**：脉冲蓄满和全域清场加入更明确的视听提示。

## 六类机械害虫

| 害虫 | 净化操作 |
| --- | --- |
| 机械蚊 | 点击 |
| 装甲蟑螂 | 直线斩击 |
| 毒液蜘蛛 | 画闭合圆 |
| 机械苍蝇 | 快速双击 |
| 机械蝗虫 | V 形斩击 |
| 机械白蚁 | 双指捏合；桌面支持右键或 Shift + 左键 |

## 桌面操作

- 主菜单：数字键 `1`–`4`，或鼠标点击。
- 设置：`M` 切换音效，`←/→` 调节音量，`F` 切换全屏/窗口，`D` 循环难度。
- 战斗：脉冲充满后按 `Space` 释放全域脉冲。
- 返回：`Esc`。

## 启动说明

### macOS

解压后运行 `CyberExterminator.app`。当前试玩包未进行 Apple 公证；如系统阻止首次启动，请按住 Control 点击应用，选择“打开”。

### Windows

完整解压后运行 `CyberExterminator.exe`，不要单独移动 EXE。当前试玩包未进行 Authenticode 签名，Windows 可能显示未知发布者提示。

## 系统与版本

- Unity 6000.5.4f1
- 横屏 16:9
- macOS：Universal，支持 Apple Silicon 与 Intel
- Windows：64 位

## 许可说明

本仓库未提供开源许可，试玩包仅用于游戏体验与展示。

---

## English

Cyber Exterminator is a landscape Unity game prototype. Identify different mechanical pests and purify them with the matching gesture—tap, slash, circle, double-tap, V-shape, or pinch—to defend the central Purification Core.

Current public playtest version: **v0.6.0**

### Play Online

Open the browser version on mobile or desktop: [Play Cyber Exterminator online](https://regan-missbug.github.io/cyber-exterminator/)

Use landscape orientation on mobile. The first launch downloads about 14 MB of game data; no installation is required.

### Download the Playtest

Visit [Releases](https://github.com/Regan-MissBug/cyber-exterminator/releases/latest) and download:

- `CyberExterminator-Mac-v0.6.0.zip`
- `CyberExterminator-Windows-x64-v0.6.0.zip`
- `CyberExterminator-v0.6.0-Playtest-Guide.md`: playtest and acceptance notes

This repository distributes playable builds only. The Unity source code is not included.

### Game Modes

- **Level Mode:** Six levels that introduce new mechanical pests one by one.
- **Endless Mode:** New pest types and increasing pressure are added as survival time increases.
- **Settings:** Sound effects, volume, fullscreen/windowed mode, and four difficulty levels are saved automatically.

### What's New in v0.6.0

- **Four difficulty levels:** Easy, Normal, Medium, and Master. Difficulty changes only pest movement speed and spawn frequency.
- **Stronger impact feedback:** Successful purification adds a white flash, impact ring, subtle camera shake, and a layered impact sound.
- **Combo feedback:** Rating and combo text briefly punch in; every fifth combo adds an extra visual and rising audio cue.
- **Pulse feedback:** Reaching full charge and clearing multiple targets now have clearer audiovisual cues.

### Mechanical Pests and Gestures

| Pest | Purification gesture |
| --- | --- |
| Mechanical Mosquito | Tap |
| Armored Cockroach | Straight-line slash |
| Venom Spider | Draw a closed circle |
| Mechanical Fly | Rapid double-tap |
| Mechanical Locust | V-shaped slash |
| Mechanical Termite | Two-finger pinch; right-click or Shift + left-click on desktop |

### Desktop Controls

- Main menu: number keys `1`–`4`, or mouse input.
- Settings: `M` toggles sound, `←/→` adjusts volume, `F` switches between fullscreen and windowed mode, and `D` cycles difficulty.
- Battle: press `Space` to release the Global Pulse when fully charged.
- Back: `Esc`.

### Launch Instructions

#### macOS

Extract the ZIP and launch `CyberExterminator.app`. The current build is not Apple-notarized. If macOS blocks the first launch, Control-click the app, choose **Open**, and confirm.

#### Windows

Extract the complete ZIP and launch `CyberExterminator.exe`. Do not move the EXE away from its companion folders. The current build is not Authenticode-signed, so Windows may show an unknown-publisher warning.

### System and Build Information

- Unity 6000.5.4f1
- Landscape 16:9
- macOS: Universal build for Apple Silicon and Intel
- Windows: 64-bit

### License Notice

No open-source license is provided. The playtest builds are intended for gameplay evaluation and showcase purposes only.
