# 赛博虫师 Cyber Exterminator

《赛博虫师》是一款 Unity 横屏游戏原型：识别不同机械害虫，并使用点击、斩击、画圆、双击、V 形和捏合等对应手势进行净化，保护中央净化核心。

当前公开试玩版本：**v0.5.2**

## 下载试玩版

请前往 [Releases](https://github.com/Regan-ZhengLu/cyber-exterminator/releases/latest) 下载：

- `CyberExterminator-Mac-v0.5.2.zip`
- `CyberExterminator-Windows-x64-v0.5.2.zip`
- `CyberExterminator-v0.5.2-Playtest-Guide.md`：试玩与验收说明
- `SHA256SUMS_v0.5.2.txt`：文件完整性校验

本仓库仅发布试玩包，不提供 Unity 源码。

## 游戏模式

- **关卡模式**：共六关，逐关加入新的机械害虫。
- **无尽模式**：虫种和压力随存活时间逐步增加。
- **游戏设置**：支持音效、音量、全屏和窗口模式，并自动保存。

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
- 设置：`M` 切换音效，`←/→` 调节音量，`F` 切换全屏/窗口。
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
