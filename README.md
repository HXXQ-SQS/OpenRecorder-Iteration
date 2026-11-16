# OpenRecorder — Community Iteration

**An independent Android screen-recorder iteration based on [NoneBaiano/OpenRecorder](https://github.com/NoneBaiano/OpenRecorder).** This repository preserves attribution to the upstream project and its contributors. It is not the upstream repository and is not affiliated with or endorsed by the original maintainer.

**中文说明：** 本仓库是基于 [NoneBaiano/OpenRecorder](https://github.com/NoneBaiano/OpenRecorder) 继续开发的独立迭代版本。原项目及其贡献者的署名和 GPL-3.0-only 许可证均予以保留。本仓库不是原作者的官方仓库，也不代表原作者发布或背书。

[简体中文](#简体中文) | [English](#english)

---

## 简体中文

这是 OpenRecorder 的社区迭代版本，基于上游项目 [NoneBaiano/OpenRecorder](https://github.com/NoneBaiano/OpenRecorder) 修改。

### 本迭代版本的主要变化

- 重新整理录制首页布局，采用深色/浅色卡片式界面和绿色强调色。
- 优化顶部标题栏与底部导航栏边框，避免屏幕左右边缘出现多余竖线。
- 为底部导航处理 Android 手势导航区域 Insets，避免系统手势横条遮挡导航内容。
- 设置中加入简体中文 / English 应用语言切换，并保存用户选择。
- 移除设置中的“锁屏时停止录制”选项；Android 在锁屏时对屏幕录制的系统行为仍由系统版本和设备策略决定。
- 保留上游项目的原生录屏与内部音频采集架构。

### 上游项目与致谢

- 原始项目：**[NoneBaiano/OpenRecorder](https://github.com/NoneBaiano/OpenRecorder)**
- 本仓库是在该开源项目基础上继续修改的独立迭代，不会覆盖或替代上游仓库。
- 其他第三方组件和代码来源见 `NOTICE` 与 `LICENSES/`；请一并阅读相关许可证。

### 构建要求

- Android Studio / Android Gradle Plugin（版本见 `build.gradle`）
- JDK 17
- Android SDK：`compileSdk 37`
- 最低系统版本：Android 10（API 29）

在 Android Studio 中打开仓库根目录，等待 Gradle Sync 后构建 `app` 模块。

### APK 下载

APK 计划作为 GitHub Release 附件发布，文件名为 `OpenRecorder-v3-debug.apk`。该文件是用户提供的 debug 命名构建，不应视为上游官方签名版本。发布时请核对 Release 中公布的 SHA-256。

### 许可证

本项目按上游代码所附的 **GNU GPL v3.0 only (GPL-3.0-only)** 发布。请阅读 `LICENSE`。第三方代码仍受各自许可证约束，详见 `NOTICE` 和 `LICENSES/`。

---

## English

This is a community-maintained iteration of OpenRecorder, derived from the upstream project **[NoneBaiano/OpenRecorder](https://github.com/NoneBaiano/OpenRecorder)**.

### Highlights of this iteration

- Refined the recorder home screen with card-based dark/light styling and emerald accents.
- Cleaned up the top app bar and bottom navigation borders to remove unwanted vertical edge lines.
- Added Android navigation-bar insets to keep bottom navigation clear of the system gesture area.
- Added a persistent Simplified Chinese / English language selector in Settings.
- Removed the “Stop when lock screen” preference. Actual screen-capture behavior on lock is still governed by Android and device policy.
- Retained the upstream native screen-recording and internal-audio capture architecture.

### Upstream attribution

- Original project: **[NoneBaiano/OpenRecorder](https://github.com/NoneBaiano/OpenRecorder)**
- This repository is an independent derivative/iteration. It does not replace, modify, or claim ownership of the upstream repository.
- Other third-party components and adapted code are credited in `NOTICE` and `LICENSES/`.

### Build requirements

- Android Studio / Android Gradle Plugin (see `build.gradle`)
- JDK 17
- Android SDK `compileSdk 37`
- Android 10 (API 29) or newer

Open the repository root in Android Studio, sync Gradle, and build the `app` module.

### APK download

The APK is intended to be distributed as a GitHub Release asset named `OpenRecorder-v3-debug.apk`. It was supplied as a debug-named build and should not be represented as an official upstream-signed release. Verify the SHA-256 published alongside the release before installing.

### License

The project is distributed under **GNU GPL v3.0 only (GPL-3.0-only)** as indicated by the upstream source. See `LICENSE`. Third-party components remain subject to their respective licenses in `NOTICE` and `LICENSES/`.
