# 墙隙试验 B-09 · W-GATE 模拟恐怖实测档案

第一人称 3D 像素风非欧空间模拟恐怖网页游戏（纯前端单页应用，无需后端服务器）。

## 目录结构

| 文件 | 用途说明 |
| :--- | :--- |
| `index.html` | 游戏完整单文件入口（内联样式、着色器、程序化像素贴图与 Web Audio 合成音频，仅通过 CDN 加载 [Three.js r128](https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js)） |
| `.nojekyll` | 空白标记文件，用于指示 GitHub Pages 跳过默认 Jekyll 构建并直接托管静态资源（参见 [Creating a GitHub Pages site](https://docs.github.com/articles/creating-project-pages-manually)） |
| `README.md` | 仓库与部署说明文档 |

## 部署至 GitHub Pages 步骤

1. 登录 GitHub 新建一个公开仓库（参考 [GitHub Pages 快速入门](https://docs.github.com/en/pages/quickstart)）。
2. 将压缩包解压后的 `index.html`、`.nojekyll` 与 `README.md` 直接上传并提交至仓库默认分支（如 `main`）根目录。
3. 打开仓库顶部 **Settings** → 左侧栏 **Pages**，在 **Build and deployment** 下将 **Source** 设为 **Deploy from a branch**，分支选择 `main` 与 `/ (root)` 并保存（详见 [配置 GitHub Pages 发布源](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)）。
4. 等待部署完成后，访问页面顶部生成的 `https://<你的用户名>.github.io/<仓库名>/` 链接即可直接游玩（首次发布最长可能需要数分钟生效，参见 [GitHub Pages 快速入门](https://docs.github.com/en/pages/quickstart)）。

## 本地运行方式

直接用现代桌面或移动端浏览器双击打开 `index.html`（需要联网加载 [Three.js r128](https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js)），或通过任意本地静态文件服务预览。

## 基本操作

- **移动**：`W` `A` `S` `D` 或方向键（按住 `Shift` 快步移动，触屏设备可开启右上角【触控】虚拟按键）
- **环顾视角**：移动鼠标或拖拽画面（亦可用 `Q` / `R` 辅助转向）
- **展开墙面传送门**：鼠标左键 或 `F` 键
- **设施交互**：鼠标右键 或 `E` 键
- **员工守则**：`Tab` 或 `H` 键
- **头盔照明 / 静音切换**：`L` 键 / `M` 键
