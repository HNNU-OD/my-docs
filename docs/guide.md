
# 使用指南

## 环境准备

运行本项目需要以下工具：

- Python 3.12
- Git
- VS Code

## 安装依赖

在项目根目录执行：

```bash
python -m pip install -r requirements.txt
```

## 本地预览

执行以下命令：

```bash
python -m mkdocs serve
```

在浏览器访问 http://127.0.0.1:8000/ 查看文档网站。

## 构建网站

```bash
python -m mkdocs build --strict
```

构建完成后，生成的静态网页保存在 site 目录中。

## 更新网站

1. 修改 docs 目录中的文档。
2. 使用 MkDocs 检查本地效果。
3. 使用 Git 提交修改。
4. 将修改推送到 GitHub 的 main 分支。
5. 查看 GitHub Actions 的运行状态。
6. 访问 GitHub Pages 网站检查更新结果。

[返回首页](index.md)
