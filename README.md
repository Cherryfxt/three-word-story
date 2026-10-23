# 三词成故事

三个意想不到的词，一个有头有尾的故事。

## 在线体验

https://cherryfxt.github.io/three-word-story/

## 玩法

点击开始揭晓三个词，先准备 5 秒，再进行 60 秒讲述。准备阶段可以换词，换词后重新计时。讲述可提前结束；自然到时播放简短提示音，结束后保留本轮词语，再开始下一轮。

词库共 250 个词，分为物品、人物、生物、场景、形容词等五组（具体分类以词库为准）。用于想象与表达练习，没有唯一正确答案。

## 项目隔离

这是独立仓库，独立使用 GitHub Pages，从 `main` 分支的根目录发布。不依赖、导入或修改“出发吧”的代码、发布配置或数据。

运行文件仅为 `index.html`、`style.css`、`words.js`、`game.js`。无服务器、登录、数据库、用户数据收集、Service Worker 或跨项目本地存储。GitHub Pages 的不同项目路径仍位于同一域名下；本项目当前不使用共享域名存储。将来新增存储时须使用独立命名空间。

## 本地运行

直接打开 `index.html`，或在本目录运行 `python3 -m http.server 8080` 后访问 `http://127.0.0.1:8080/`。

## 发布

GitHub 仓库 Settings → Pages → Deploy from a branch → `main` → `/ (root)`。

`.preview/`、本地发布压缩包与系统文件不上传。`.nojekyll` 保持静态文件直接发布。
