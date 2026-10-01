# 8周居家力量训练 PWA

## 如何发布成可安装的手机 App
PWA 必须通过 HTTPS 网站打开，不能只在手机本地打开 HTML。

### 简单方案：GitHub Pages
1. 在 GitHub 创建一个新的公开仓库（Repository）。
2. 上传本文件夹内的 `index.html`、`manifest.json`、`sw.js`、`icon.svg` 四个文件（放在仓库根目录）。
3. 进入仓库 Settings → Pages。
4. 在 Build and deployment 选择 Deploy from a branch；选择 `main` 和 `/ (root)`，保存。
5. 等待 GitHub Pages 显示网址，格式通常为 `https://你的用户名.github.io/仓库名/`。
6. 用 Android 手机上的 Chrome 打开这个网址。点右上角菜单，选择“安装应用”或“添加到主屏幕”。

发布后，首次打开需要联网；之后 Service Worker 会缓存页面，支持离线打开。
训练打卡数据保存在当前浏览器的本机存储中。清除浏览器数据可能会删除记录。

## 内容说明
每周三练 A/B/C，动作使用自重或装书/水瓶的背包。动画是示意，不是精确真人教学视频。
