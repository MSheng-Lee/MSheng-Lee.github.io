# mingshengli_new

可直接部署到 GitHub Pages 的静态个人主页。

## 本地预览

直接双击 `index.html`，或用任意静态服务器打开目录。

## GitHub Pages 部署步骤

1. 在 GitHub 创建仓库（建议仓库名：`<你的用户名>.github.io`）。
2. 把本目录全部文件上传到仓库根目录（至少包含 `index.html` 与 `.nojekyll`）。
3. 进入仓库 `Settings` -> `Pages`。
4. 在 `Build and deployment` 中选择：
   - Source: `Deploy from a branch`
   - Branch: `main`（或 `master`）/`root`
5. 保存后等待 1-3 分钟，访问：
   - 若仓库是 `<用户名>.github.io`，地址通常是 `https://<用户名>.github.io/`
   - 否则是 `https://<用户名>.github.io/<仓库名>/`

## 自定义建议

- 改头像/视频：替换 `Gallery` 区块内容即可。
- 改文案：直接编辑 `index.html` 中各 section 文本。
- 绑定自定义域名：在仓库根目录新增 `CNAME` 文件，写入你的域名。
