<!-- markdownlint-disable MD033 MD041 -->

<p align="center">
  <img alt="LOGO" src="assets/resource/image/logo.png" width="180" height="180" />
</p>

<div align="center">

# MaaAshEchoes

MaaAshEchoes，基于全新架构的 白荆回廊 小助手。图像技术 + 模拟控制，解放双手！

本项目由 **[MaaFramework](https://github.com/MaaXYZ/MaaFramework)** 强力驱动！

本项目使用 **[MFAWPF](https://github.com/SweetSmellFox/MFAWPF)** 作为 GUI 界面！（仅限 win-x86_64 用户可用）

</div>

---

# 🎮 功能分类与说明

## 💪 清体力
### 同调者培养
- 🎯 指定同调者、技能、目标等级
- 🔄 自动使用体力进行培养（不使用体力药）

### 外勤作战
- 🗺️ 指定关卡名称
- ⚔️ 自动消耗体力进行作战（不使用体力药）

## 📅 日常/周常任务
- 🎁 领取好友赠礼
- 👍 俱乐部点赞与奖励领取
- ☕ 午后茶憩（支持多个角色）
  - 通过`resource/image/edit/午后茶憩_茶憩角色*.png`配置
  - 或直接选择排第一位的角色
  - 支持使用通用邀请函
  - 可解放双手反复喝茶提升角色默契值
- 🏰 白荆穹顶资源收取
- ⬆️ 烙痕升级（自动尝试升级低等级烙痕）
- 🎪 活动日常任务（随版本更新）
- 🔄 周常拟合回归（支持队伍选择）

## 🌟 漫巡
### 置顶刻印漫巡
- 🎯 使用置顶刻印配置
- 🔄 支持自动刷新支援烙痕
- 📋 使用上次编组基点
- 🔀 支持选择路线分支
- 💡 自动点亮推荐技能

## 🎁 奖励与福利
### 奖励领取
- 📅 日常/周常任务奖励
- 🌿 叶脉联结奖励

### 福利系统
- 🛍️ 每日外勤赠礼购买
- 🎲 每日免费烙痕抽取
- 📬 邮箱物品签收

## ⚙️ 基础功能
- 🚀 开始唤醒（需提前登录账号）
- 🔚 关闭游戏

## 📝 注意事项
1. 使用前安装好了必要的运行库：
   - [VC++运行时库 (vc_redist)](https://aka.ms/vs/17/release/vc_redist.x64.exe)
   - [.NET 8 SDK 或运行时](https://dotnet.microsoft.com/zh-cn/download/dotnet/8.0)

2. 茶憩功能需要确保：
   - 角色可以"再来一杯"
   - 所有茶憩对话已完成
   - 如需自定义，正确配置角色头像图片
   
3. 拟合回归注意：
   - 必须启用自动战斗
   - 1-4号位不能有支援角色

4. 漫巡功能使用前：
   - 请先调整好全自动选项
   - 设置合适的最大深度

5. 详见下方的“使用说明”章节。

还有想要的功能？欢迎在 [Issue](https://github.com/moulai/MaaAshEchoes/issues) 中提出建议或加 **QQ 群 865686593** 进行交流！请在 issue 标题中以 `[功能建议]` 开头。

**注意：请勿在各种白荆回廊官方动态下提到本软件/MAA等字眼，谢谢！**

![GUI界面展示](https://github.com/user-attachments/assets/9012466e-946b-4867-97bf-544ba37a6118)

## 下载及安装说明

### 下载地址

前往 [Releases 页面](https://github.com/moulai/MaaAshEchoes/releases) 下载适合您设备的版本。

### Windows 用户

Windows 用户可以通过以下简单步骤安装和使用：

1. 下载 `MaaAshEchoes-win-x86_64-vXXX.zip`。
2. 解压缩文件到任意位置。
3. 双击运行 `MaaAshEchoes.exe` 即可启动程序，享受便捷的图形化界面操作！

**注意**：

- 如果您的设备是 ARM 架构（极为罕见），请下载 `MaaAshEchoes-win-aarch64-vXXX.zip`，解压后运行 MaaPiCli.exe 即可。默认情况下，请优先选择 x86_64 版本。

### macOS 用户

如果您使用的是 macOS，请根据您的设备处理器类型选择合适的版本：

- 使用 Intel 处理器，请下载 `MaaAshEchoes-macos-x86_64-vXXX.zip`。
- 使用 M1、M2 等 ARM 处理器，请下载 `MaaAshEchoes-macos-aarch64-vXXX.zip`。

下载后，按照以下步骤运行：

```bash
chmod a+x MaaPiCli
./MaaPiCli
```

### Linux 用户

~~用 Linux 的大佬应该不需要我教~~

### 必要运行库

若运行时遇到错误提示，例如 “应用程序错误”，可能是缺少运行库。请安装以下组件：

- [VC++运行时库 (vc_redist)](https://aka.ms/vs/17/release/vc_redist.x64.exe)
- [.NET 8 SDK 或运行时](https://dotnet.microsoft.com/zh-cn/download/dotnet/8.0)

## 使用说明

### 使用前说明

在使用工具前完成以下工作：

1. 确保游戏可以在模拟器上流畅运行，没有严重的卡顿和延迟。

2. 完成所有游戏资源的下载，登录好账号，启用自动战斗。

3. 完成必要运行库的下载安装：  
  [VC++运行时库 (vc_redist)](https://aka.ms/vs/17/release/vc_redist.x64.exe)  
  [.NET 8 SDK 或运行时](https://dotnet.microsoft.com/zh-cn/download/dotnet/8.0)

### 模拟器设置要求

1. **分辨率要求**：使用 **16:9 分辨率**，推荐设置为 **1280×720**。  
   经测试，**2560×1440** 分辨率下也能正常运行。
   若出现识别问题，请优先调整分辨率为 1280×720 后重试。

2. **ADB 调试**：请确保已经打开模拟器的 ADB 调试选项。

3. **其它设置**：请确保关闭后台挂机时保活运行。

4. **游戏图像设置**：一般对运行没有影响。如果修改分辨率后识别问题仍然存在，请提 [Issue](https://github.com/moulai/MaaAshEchoes/issues)。

### 程序运行注意事项

1. **任务执行顺序**：
   - 请合理调整任务顺序，例如，建议将“领取奖励”相关的任务放在流程的最后。
   - 如果不确定任务执行顺序，请保持默认的执行顺序，并勾选您需要的任务。
   
2. **茶憩任务特别说明（重要）**：

   - **茶憩角色设置（图片素材准备）**：  
     直接看图（注意图片素材的文件名里没有空格）：  
     **如果找不到 GUI 中的“编辑任务”按钮，请先将`config/config.json`中的`EnableEdit`设置为`true`。**  
     ![茶憩角色选择说明](https://github.com/user-attachments/assets/91e01dba-a562-47a0-aa6e-003a8dbfa45b)

     详细说明：  
     1. 茶憩任务中，**通过创建或修改头像图片的方式设置茶憩角色**，任务“茶憩角色 1/2/3”分别对应的图片文件如下（数字编号前没有空格）：

        - `resource/image/edit/午后茶憩_茶憩角色1.png`
        - `resource/image/edit/午后茶憩_茶憩角色2.png`
        - `resource/image/edit/午后茶憩_茶憩角色3.png`  
          请参考 `resource/image/edit/午后茶憩_茶憩角色.png` 创建或修改上述图片文件，**文件名必须完全一致**。

     2. **图片要求**：

        - 使用 **无损原图缩放到 720p** 后裁剪茶憩角色选择页面的角色头像中心区域。
        - 若使用安卓模拟器，务必使用模拟器自带截图功能，不可直接对模拟器窗口截图。

     3. **推荐工具**：  
        除非您完全了解 MaaFramework 的图片处理机制，否则请使用以下推荐工具获取截图：

        - **GUI 自带截图工具**  
          使用方式：
          - 点击 GUI 主界面任务列表上方的“编辑任务”按钮（一个灰色的编辑图标）。
          - 如果找不到 GUI 中的“编辑任务”按钮，请先将`config/config.json`中的`EnableEdit`设置为`true`。
          - 在任务编辑器右上角点击“裁剪图片”按钮（一个灰色的图片图标）。
          - 在弹出的图片浏览器中截图并保存。
        - [MFA ImageCropper](https://github.com/MaaXYZ/MaaFramework/tree/main/tools/ImageCropper)
        - [MFATools](https://github.com/SweetSmellFox/MFATools)

     4. **头像截取要求**：
        - 截取头像中心部分即可，**不要包含头像框**。

### 更新方式

#### Windows 用户

~~直接运行程序目录中的 `updater.exe` 即可自动更新。~~

**[MFAWPF](https://github.com/SweetSmellFox/MFAWPF)** 支持自动更新及手动更新资源，使用【设置】→【软件更新】→检查资源/资源更新/自动更新资源即可。注意，这里“软件更新”指的是 MFAWPF 这个 GUI 的更新，不是 MaaAshEchoes 的更新。“资源更新”才是 MaaAshEchoes 的更新。

若使用 MFAWPF 更新资源失败，可以尝试使用 `updater.exe` 进行更新。

更新后可能会出现配置文件不兼容的问题，导致程序无法正常运行。此时请删除 `config` 目录下的 `config.json` 文件，重新打开程序即可。

#### macOS/Linux 用户

请重新下载最新版本并解压缩到原目录，覆盖原有文件即可。

## 定时运行

### Windows 用户

Windows 用户可以使用 Windows 任务计划程序来定时运行本工具。方法如下：

1. 在 GUI 高级设置中，设置“启动后操作”为“启动脚本”，勾选“启动MFA后启动模拟器”，设置好模拟器路径。对于Mumu模拟器，可以通过设置启动参数“-v 0”来选择需要启动的模拟器编号。建议将“结束后操作”设置为“关闭MFA”或“关闭MFA和模拟器”。

2. 打开 Windows 任务计划程序，在“任务计划程序库”下新建一个文件夹，名字如“MaaAshEchoes”。

3. 在新建的文件夹下新建一个基本任务，根据“创建基本任务向导”指示完成设置。设置触发器为您需要的时间（例如每日一次），操作为“启动程序”，“程序或脚本”选择 `MaaAshEchoes.exe` ，**注意**需要将“起始于”设置为 `MaaAshEchoes.exe` 所在的文件夹，否则可能会出现“找不到模拟器”错误。

4. 通过右键任务→运行，测试任务是否正常运行。

5. 享受自动收菜的快乐！

### macOS 用户

macOS 用户可以使用 `launchd` 或 `cron` 来定时运行 `MaaPiCli`。相关方法请自行搜索。

### Linux 用户

Linux 用户可以使用 `cron` 来定时运行 `MaaPiCli`。相关方法请自行搜索。

## 常见问题

### 1. 程序启动时报“应用程序错误”或无法运行

**原因**：缺少必要的运行时库。  
**解决方法**：请安装以下运行时库后重试：

- [VC++运行时库 (vc_redist)](https://aka.ms/vs/17/release/vc_redist.x64.exe)
- [.NET 8 SDK 或运行时](https://dotnet.microsoft.com/zh-cn/download/dotnet/8.0)

### 2. 茶憩任务运行异常，无法正确选择想要的角色

**原因**：图片素材设置错误。  
**解决方法**：请确保按照“茶憩任务特别说明”中的要求设置角色图片素材，确保文件名正确（数字编号前没有空格），并使用推荐工具进行截图。

### 3. 茶憩任务运行异常，无法正常开始或结束茶憩

**原因**：可能是任务设置选择了“只能使用免费邀请次数”但免费茶憩邀请次数已用完，或角色没有“再来一杯”选项，或仍存在未完成的茶憩对话。  
**解决方法**：请检查任务设置，确保已经为角色设置好了茶憩配方，即已经在设备上完成过至少一次茶憩，能够正常弹出“再来一杯”按钮，且所有茶憩对话已经完成。

### 4. 识别错误或程序无法正确执行任务

**原因**：一般是因为分辨率或图片素材不符合要求。  
**解决方法**：确保模拟器分辨率设置为 **16:9（推荐 1280×720）**。

### 5. 无法找到问题的解决方案

请附上以下信息提交 [Issue](https://github.com/moulai/MaaAshEchoes/issues)，或加 QQ 群 865686593 提问：  
- **日志文件**：位于 `debug/maa.log`。  
- **截图**：请包含任务出错时的界面截图和问题描述。

## 已知问题

### 1. 特定界面启动任务问题

**问题**：如果在一些特殊界面启动小助手，任务可能无法正常执行（无法正常返回主界面）。  
**解决方法**：请手动返回主界面后重试。

## 反馈

### 问题反馈

如果在使用过程中遇到问题，欢迎提交 [Issue](https://github.com/moulai/MaaAshEchoes/issues)，或加入 QQ 群 865686593 进行反馈。

反馈时请尽量提供以下信息：

- 日志文件（位于 `debug/maa.log`）。
- 问题发生时的模拟器界面截图。
- 简要描述问题出现的情况。

## 软件声明

- 本软件免费开源，仅供学习和交流使用。
- 本项目基于 [MaaFramework](https://github.com/MaaXYZ/MaaFramework) 构建，开发者对框架功能进行了进一步扩展。
- **使用须知**：
  - 本软件仅通过游戏提供的用户界面与游戏程序进行交互，不会读取或修改游戏的文件或代码。
  - 任何因使用本软件产生的问题或后果均与本软件及开发者团队无关。
  - 任何商家利用本软件提供代练等商业服务所产生的任何问题或后果，与本软件及开发者团队无关。

下载并使用本软件即表示您已阅读并同意上述声明。

## 开发者相关

### 开发文档

- [MaaFramework 开发文档](https://github.com/MaaXYZ/MaaFramework/blob/main/docs/zh_cn/1.1-%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B.md)：快速上手指南。
- [Pipeline 流水线协议](https://github.com/MaaXYZ/MaaFramework/blob/main/docs/zh_cn/3.1-%E4%BB%BB%E5%8A%A1%E6%B5%81%E6%B0%B4%E7%BA%BF%E5%8D%8F%E8%AE%AE.md)：任务编排机制的详细说明。
- 更多文档请参考 [MaaFramework 主仓库](https://github.com/MaaXYZ/MaaFramework)。

## 鸣谢

本项目由 **[MaaFramework](https://github.com/MaaXYZ/MaaFramework)** 强力驱动！

本项目使用 **[MFAWPF](https://github.com/SweetSmellFox/MFAWPF)** 作为 GUI 界面！

感谢以下开发者对本项目作出的贡献:

<a href="https://github.com/moulai/MaaAshEchoes/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=moulai/MaaAshEchoes" />
</a>

## Join us

闲聊/反馈/交流/开发群 QQ 群：865686593
