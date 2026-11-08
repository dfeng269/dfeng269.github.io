# 网站内容更新指南（简单版）

这个网站已经设置为“内容与样式分开”。日常更新只需改 Markdown 或 YAML 文本，不需要修改 HTML、CSS。

## 1. 添加一条“最新动态”

打开 `_data/updates.yml`，复制下面内容并粘贴到文件最上方：

```yml
- date: "2026-11"
  title: "这里写动态标题"
  description: "这里写一句补充说明"
  url: "https://doi.org/或其他链接"
  image: "/images/publications/图片文件名.png"
  image_alt: "用一句话描述图片内容"
  image_caption: "论文图形摘要"
```

先把论文图片放入 `images/publications/` 文件夹，再填写 `image`。如果没有链接或图片，删除对应行即可。首页最多自动显示最新 5 条。

## 2. 修改首页介绍

打开 `_pages/about.md`，直接修改对应的中文段落。保留文件最上方两条 `---` 之间的设置。

## 3. 修改研究方向

打开 `_pages/research.md`。新增研究方向时，复制下面格式：

```md
## 新的研究方向

用一段话介绍研究问题、采用的方法和希望解决的问题。
```

## 4. 添加代表论文

打开 `_pages/publications.md`，把新论文放在相应标题下方：

```md
作者. (年份). **论文标题.** *期刊名*, 卷(期), 页码. [DOI](https://doi.org/xxxxx)
```

## 5. 发布

在 GitHub 网页中编辑文件后点击 **Commit changes**。等待 Actions 构建完成，网页会自动更新。

建议每次只改一种内容，提交说明可写“更新动态”或“添加论文”。
