---
title: GitHub Trending Garden
---

# 🌿 GitHub Trending Garden

> AI 驱动的 GitHub 热门项目技术调研报告自动生成与发布平台

---

## 关于

本平台每周自动采集 GitHub Trending 仓库，通过 AI 深度分析生成中文技术报告。

| 项目 | 说明 |
|------|------|
| 📊 数据来源 | GitHub API (Weekly Trending) |
| 🤖 AI 分析 | MiniMax Text-01 模型 |
| 🏗️ 静态网站 | Quartz v4 |
| 🔄 自动部署 | GitHub Actions |

---

## 📂 最新报告

[浏览全部报告 →](/trending/)

---

## 🚀 使用方法

```bash
cd github-trend-analyzer
export MINIMAX_API_KEY="your-api-key"
python cli.py trending --language python --limit 5 --publish
```

---

*由 GitHub Trend Analyzer 自动生成*
