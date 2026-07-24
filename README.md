# 美国圣诞行程地图

这是可直接部署到 GitHub Pages 的静态网页。

## 发布

1. 把本文件夹内的全部文件上传到 GitHub 仓库根目录。
2. 打开仓库的 **Settings → Pages**。
3. 在 **Build and deployment** 中选择 **Deploy from a branch**。
4. Branch 选择 `main`，目录选择 `/(root)`，然后保存。

GitHub Pages 生成网址后，打开仓库 Pages 页面显示的链接即可。

## 文件说明

- `index.html`：网站入口。
- `assets/`：行程数据、页面样式与交互脚本。
- `vendor/`：本地 Leaflet 地图库。

地图底图使用 OpenStreetMap 在线图块，因此访问时仍需联网。
