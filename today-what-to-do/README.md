# 今天做什么？

一个无需安装、无需联网的中文随机小事生成器。打开 `index.html` 就可以使用。

## 功能

- 32 条轻松、有趣的日常灵感
- 按“出门走走、随手创作、温柔一下、满足好奇”筛选
- 收藏灵感；收藏内容会保存在当前浏览器
- 点击按钮或按空格键随机抽取

## 运行

直接在浏览器中打开 `index.html`，或在项目目录执行：

```bash
python3 -m http.server 8000
```

随后访问 <http://localhost:8000>。

## 安装到手机

### iPhone / iPad

把这个目录部署到任意 HTTPS 静态网站后，用 Safari 打开页面，点击“分享”→“添加到主屏幕”。它会以独立 App 的形式启动，并在首次打开后支持离线使用。iOS 不能安装 APK；其原生安装包格式是 IPA，发布或侧载都需要 Apple 开发者签名。

### Android

仓库内的 `android/` 是一个离线原生 WebView 工程，可在 Android Studio 中打开并构建。GitHub Actions 工作流也会在每次改动时生成 `app-debug.apk` 构建产物：进入仓库的 **Actions** 页面、选择“Build 今天做什么 APK”，下载 `today-what-to-do-debug-apk`。

调试 APK 可直接安装到 Android 手机。正式分发前，请在 Android Studio 为 release 构建配置你自己的签名密钥。
