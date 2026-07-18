# 邢台学院新生必备手册（H5 静态站点）

基于草料二维码 H5 页面完整复制并本地化的纯静态网站，可离线打开，也可部署到 GitHub Pages。

## 目录结构
- `index.html` —— 首页
- `pages/col_*.html` —— 各栏目内容页
- `pages/placeholder.html` —— 招生网 / 小程序等外链的占位页
- `assets/` —— 首页的 CSS、字体、图片
- `pages/assets/img/` —— 栏目页图片
- `links.json` —— 栏目编号与标题映射表
- `.nojekyll` —— 关闭 GitHub Pages 的 Jekyll 处理，保证所有文件原样发布

## 本地预览
直接用浏览器打开 `index.html` 即可（全部为相对路径，可离线运行）。

## GitHub Pages 部署
1. 仓库 Settings → Pages
2. Source 选择 `Deploy from a branch`
3. Branch 选择 `main`，目录选 `/ (root)`，保存
4. 等待构建完成后访问：`https://plutolio777.github.io/xingtaixueyuan/`

## 说明
页面内容为抓取时的静态快照，原站更新不会自动同步。招生网与小程序栏目为占位页，不做跳转。
