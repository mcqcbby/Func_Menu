# Func_Menu MkDocs Material 完整导航版

这是 Func_Menu 的 MkDocs Material 文档项目。

## GitHub Pages 部署

上传到 GitHub 仓库根目录：

```text
mkdocs.yml
requirements.txt
docs/
.github/workflows/deploy.yml
README.md
```

GitHub Pages 设置：

```text
Settings → Pages → Source → GitHub Actions
```

然后运行：

```text
Actions → Deploy MkDocs Material to Pages
```

成功后访问：

```text
https://mcqcbby.github.io/Func_Menu/
```

## 本地预览

```bash
pip install -r requirements.txt
mkdocs serve
```
