# V3 iteration notes / V3 迭代说明

## 简体中文

1. 录制首页标题栏移除四边框，仅保留底部分隔线。
2. 底部导航移除整圈边框，仅保留顶部细分隔线。
3. 底部导航加入 Android navigation bar / 手势区域 Insets，避免系统手势横条遮挡导航内容；背景延伸到系统导航区域。
4. 录制首页背景延伸到状态栏安全区域。
5. 设置 > 外观中新增“应用语言”，支持简体中文与 English，选择会被保存。
6. 移除“锁屏时停止录制”设置项。

## English

1. Removed the full border from the recorder app bar, keeping only its bottom divider.
2. Removed the full border from bottom navigation, keeping only its top divider.
3. Added Android navigation-bar / gesture-area insets so system gesture UI does not overlap navigation content; the background extends behind the system navigation area.
4. Extended the recorder screen background into the status-bar safe area.
5. Added a persistent Simplified Chinese / English language selector under Settings > Appearance.
6. Removed the “Stop when lock screen” setting.

## Build verification / 构建验证

The source package received static resource/XML and archive checks. An Android SDK / successful Gradle build was not available in the preparation environment; this note does not claim a reproducible build. The APK distributed with this iteration was supplied separately and is not claimed to be reproducibly built from this source package.
