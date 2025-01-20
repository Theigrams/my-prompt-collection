# 我的提示词集合

这个仓库用于存储我使用的各种提示词（Prompts）和实用工具。

## 在线访问

你可以通过 GitHub Pages 访问我们的网站：<https://theigrams.github.io/my-prompt-collection/>

在线网站提供：

- 提示词分类浏览
- 在线工具使用
  - Markdown 公式转换器：将 LaTeX 公式转换为 Markdown 兼容格式

## 目录结构

提示词按类别组织在不同的文件夹中：

### 学术类 (`academic/`)

- [paper_analyzer.md](academic/paper_analyzer.md)
  - 提供全面的学术论文分析框架，包括元数据提取、关键要点总结等
- [paper_o1.md](academic/paper_o1.md)
  - 针对 o1 模型的论文解释工具，按章节详细解释论文内容，适合非专业人士理解

### 元提示词 (`meta/`)

- [o1-meta-prompt.md](meta/o1-meta-prompt.md)
  - o1 模型的提示词生成指南，使用 GWFC (Goal-Warnings-Format-Context) 框架

### 编程开发 (`programming/`)

- [github_explanation.md](programming/github_explanation.md)
  - GitHub 仓库分析工具，提供项目用途、功能和应用场景的简明概述

### 工具类 (`docs/tools/`)

- [md-equation-tool.html](docs/tools/md-equation-tool.html)
  - 在线 Markdown 公式转换工具，支持 LaTeX 到 Markdown 的转换
