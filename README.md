# my-docs

使用 MkDocs 构建的示例技术文档，通过 GitHub Actions 自动部署到 GitHub Pages。

## 本地预览

```bash
pip install mkdocs-material
mkdocs serve
```

## 部署

推送代码到 `main` 分支后，GitHub Actions 会自动构建并部署到 `gh-pages` 分支。
