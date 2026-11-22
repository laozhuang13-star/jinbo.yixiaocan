# 锦波智库 PWA

本压缩包用于通过 GitHub Pages 发布「锦波智库」PWA 启动外壳。

- App 名称：锦波智库
- 正式入口： https://jinbo.yixiaocan.cn
- 图标：使用本次上传的 logo 生成 32、180、192、512 像素图标

## 上传到 GitHub

1. 在 GitHub 打开你准备存放 PWA 的仓库。
2. 进入仓库首页，点击 **Add file → Upload files**。
3. 解压本压缩包，将里面的 `index.html`、`manifest.json`、`service-worker.js`、`apple-touch-icon.png`、`favicon-32.png` 和 `icons` 文件夹上传到仓库根目录。
4. 如果仓库已有旧版 PWA 文件，选择覆盖同名文件。
5. 点击 **Commit changes** 保存。
6. 打开仓库 **Settings → Pages**，设置 **Deploy from a branch**，Branch 选 `main`，目录选 `/(root)`，点击 Save。
7. 等待 GitHub Pages 部署完成后，打开 GitHub Pages 给出的网址测试。页面会自动跳转到 https://jinbo.yixiaocan.cn。

## 安装到手机

- iPhone：用 Safari 打开 GitHub Pages 网址 → 分享 → 添加到主屏幕。
- Android：用 Chrome 打开 GitHub Pages 网址 → 菜单 → 安装应用 / 添加到主屏幕。

## 说明

这是 PWA 网页启动外壳，不是原生 App。实际业务页面、登录和数据仍由 `jinbo.yixiaocan.cn` 提供，需要联网使用。请先确认该正式域名已在 Base44 中绑定并可正常打开。
