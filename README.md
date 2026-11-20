# ADAM 的学习笔记

[打开在线笔记](https://adam-cheng666.github.io/adam-learning-notes/)

## 目录结构

```text
index.html                    首页目录
notes/
  megatron-qwen38/
    index.html                Megatron 新模型接入
  transformer/
    index.html                Transformer 架构图谱
```

## 新增一篇网页笔记

1. 在 `notes/` 下新建一个简短的英文目录，比如 `notes/attention/`。
2. 将网页命名为 `index.html` 放进去。图片、CSS 和 JavaScript 可以和这篇笔记放在同一个目录，页面里用相对路径引用。
3. 在根目录 `index.html` 的笔记列表里补一条链接，比如 `notes/attention/index.html`。
4. 将这篇笔记及目录更新提交到 `main`。GitHub Pages 会从该分支的根目录重新部署。上例在站点下的相对访问路径是 `notes/attention/`。

[GitHub Pages 发布来源说明](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
