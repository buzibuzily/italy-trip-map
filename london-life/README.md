# 伦敦生活模拟器 · GitHub Pages 版本

无需构建工具，纯 HTML/CSS/JS 静态网页，可直接部署到 GitHub Pages。

## 快速发布
1. 在 GitHub 创建一个 **Public** 仓库，例如 `london-life`。
2. 把此文件夹中的 `index.html`、`assets/`、`.nojekyll` 上传到仓库根目录。不要只上传压缩包。
3. 打开仓库 **Settings → Pages → Build and deployment**，Source 选 **Deploy from a branch**，Branch 选 `main`，Folder 选 `/ (root)`，保存。
4. 发布成功后访问 `https://你的用户名.github.io/london-life/`。具体 URL 以 GitHub Pages 显示为准。

## 图片与动态素材
- `assets/advisor.jpg`：合照静态封面。
- `assets/advisor-live.mp4`：合照 Live Photo 导出的动态视频。点击图片在原位播放，结束后恢复封面。
- `assets/edinburgh.jpg`：爱丁堡旅行照片。
- 其余照片在 `index.html` 的 `ASSETS` 配置中填写路径即可。

提示：移动端浏览器可能限制自动有声播放；本网页在用户点击后调用播放，遇到限制时视频自带控制栏可手动播放。GitHub Pages 公开仓库部署后，图片和视频是公开可访问的，上传他人合照或录音前请确认分享范围。
