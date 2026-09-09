# 千川优质工具 - 外部访问版（GitHub Pages）

该项目是「千川优质工具」门户页面的外部访问版本，目前仅展示 3 个已确认的功能模块：

1. 爆款素材洞察：https://804607843-sudo.github.io/
2. 优质素材参考：https://magic.solutionsuite.cn/app/vuGLD01LO3j
3. 素材经营计算器：https://804607843-sudo.github.io/material-team-multi-client-calculator/lark-material-team-calculator.html

## 文件说明

- `public/index.html`：可直接部署的门户页面。

## GitHub Pages 部署说明

### 方式一：直接部署根目录

1. 将 `public/index.html` 复制到 GitHub 仓库根目录，并命名为 `index.html`。
2. 进入仓库 `Settings` → `Pages`。
3. 在 `Build and deployment` 中选择部署分支，例如 `main`。
4. 路径选择 `/ (root)`。
5. 保存后等待 GitHub Pages 生成公开访问链接。

### 方式二：部署 public 目录

如果仓库配置支持自定义发布目录，也可以直接将 `public` 目录作为发布目录。

## 注意事项

页面通过 iframe 嵌入 3 个外部链接。如果目标站点自身禁止被 iframe 嵌入，页面内可能无法展示，但右上角「↗」按钮仍可在新窗口打开对应工具。
