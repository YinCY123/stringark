# 生命科学笔记

使用 [Quarto](https://quarto.org/) 构建的生物科普与技术笔记网站。

## 网站结构

```
bio-science-site/
├── _quarto.yml          # 网站配置
├── index.qmd            # 首页
├── about.qmd            # 关于页面
├── posts.qmd            # 生物科普列表
├── linux.qmd            # Linux 技术笔记
├── r-lang.qmd           # R 语言笔记
├── cpp.qmd              # C++ 笔记
├── posts/               # 博客文章
│   ├── first-post.qmd   # CRISPR 科普
│   └── second-post.qmd  # 加拉帕戈斯群岛
├── styles/              # 自定义样式
│   ├── bio-theme.scss   # 主题 SCSS
│   └── bio-theme.css    # 额外 CSS
└── .gitignore
```

## 内容方向

- DNA 生物科普 — 分子生物学、进化论、生态学、神经科学
- 计算机 技术笔记 — Linux、R 语言、C++

## 本地预览

```bash
quarto preview
```

## 部署到 GitHub Pages

```bash
quarto render
git add .
git commit -m "更新网站"
git push
```

在 GitHub Settings > Pages 中选择 `docs` 文件夹作为发布源。

## 自定义

- 修改 `_quarto.yml` 调整网站配置
- 编辑 `styles/bio-theme.scss` 自定义颜色和布局
- 在 `posts/` 添加新的科普文章
- 在 `linux.qmd`, `r-lang.qmd`, `cpp.qmd` 添加技术笔记

## 技术栈

- [Quarto](https://quarto.org/)
- [Bootstrap 5](https://getbootstrap.com/)
- [Noto Serif SC / Noto Sans SC](https://fonts.google.com/)
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/)

## 许可证

CC BY-NC-SA 4.0
