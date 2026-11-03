# 王子棋 · 架构设计 / 全栈开发 / AI 工程

此仓库更新自 2019 年个人博客，作为新版作品集的旧址兼容副本。

- **主站：** https://owenpi-alt.github.io/
- **本仓库访问地址：** https://owenpi-alt.github.io/WANGZIQI.github.io/
- **本仓库固定中文地址：** https://owenpi-alt.github.io/WANGZIQI.github.io/zh/
- **本仓库英文地址：** https://owenpi-alt.github.io/WANGZIQI.github.io/en/
- **主要源码与维护入口：** https://github.com/OwenPi-alt/owenpi-alt.github.io
- **项目合作：** https://github.com/OwenPi-alt/owenpi-alt.github.io/issues/new?template=project-inquiry.yml
- **公开业务邮箱：** [chuangzaoxingfuvip@gmail.com](mailto:chuangzaoxingfuvip@gmail.com)

网站包含合作服务、系统架构、全栈业务、AI / AIGC、量化研究案例，以及技术体系、交付流程和可打印职业简历。项目合作可通过公开业务邮箱联系，GitHub 需求统一在主站仓库收集。

## 发布与维护

本仓库的 GitHub Pages 来源为 `master` 分支根目录。页面使用相对资源路径，可以直接运行于本仓库的项目子路径。

主站是主要维护版本。更新主站后，如需同步旧地址，将 `.gitignore`、`.nojekyll`、`index.html`、`styles.css`、`portfolio.css`、`casebook.css`、`seo-pages.css`、`bilingual.css`、`language-preference.js`、`case-studies.js`、`case-studies.en.js`、`architecture-lab.js`、`architecture-lab.en.js`、`app.js`、`resume.html`、`projects/`、`zh/`、`en/` 与 `assets/` 同步到本仓库并提交。脚本与增量样式 URL 的版本值也需一起同步。两个仓库之间当前没有自动同步工作流。

canonical、Open Graph 地址和复制链接按钮保留主站地址；独立域名也在主站仓库配置。

通用入口按手动偏好、浏览器语言偏好、默认中文的顺序，进入本仓库下的 `/zh/` 或 `/en/`，保留查询参数与锚点。固定语言页面、案例和简历不会自动跳转。手动偏好仅保存在浏览器本地，主站与本仓库同源共用该偏好；存储被禁用时真实语言链接仍可正常使用。

独立案例页在主站生成后再同步；中英文各页 canonical 指向主站对应语言、对应内容的页面，语言切换在旧址下也保留对应页面。站点地图只列主站二十个固定语言网址，由主站根目录的 `robots.txt` 声明；不在旧址子目录重复配置 robots，也不阻止搜索引擎读取旧页面的 canonical。

## 保留的历史

旧博客的 Git 历史没有改写。覆盖前版本保留在历史提交 `8f976e9906dddf776e4370b55793ed1da950aff2`。

需要恢复时，可在干净工作区从该历史提交恢复文件并创建新的回退提交，无需强制推送。
