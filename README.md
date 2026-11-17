# NEXUS ANDROID 9 SETTINGS V5.0

Android Studio 原生 Java 项目，目标 Android 9 / API 28，适配电视遥控器焦点操作。

## 项目源码包
请将 `NEXUS_ANDROID_9_SETTINGS_GITHUB_V5.zip` 上传到仓库根目录。ZIP 内含完整 Android Studio 项目和原始 GitHub Actions 工作流配置。

## 自动构建
仓库已配置 GitHub Actions：上传 ZIP 后，在 Actions 中运行 **Build NEXUS Android 9 Settings APK**。成功后从运行记录的 Artifacts 下载 `NEXUS-ANDROID-9-SETTINGS-V5-debug`，其中包含 `app-debug.apk`。

注意：普通第三方 APK 不能替代系统签名的 Android 设置应用。Wi-Fi / 蓝牙开关是否可用取决于电视 ROM。当前 workflow 尚未在此仓库执行构建验证。
