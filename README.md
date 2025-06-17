# My Tech Blog | 技术博客

[![Vercel Deployment](https://img.shields.io/badge/Deployed_on-Vercel-black?logo=vercel)](https://vercel.com)
[![Hugo Version](https://img.shields.io/badge/Hugo-0.125.7_Extended-ff4088?logo=hugo)](https://gohugo.io)
[![Content License](https://img.shields.io/badge/Content-CC_BY--NC--SA_4.0-lightgrey)](LICENSE_CONTENT)
[![Code License](https://img.shields.io/badge/Code-MIT-blue)](LICENSE)

> 基于 Hugo + Stack 主题构建的静态技术博客 | [在线访问](https://your-blog.vercel.app)

![](static/images/screenshot.png) <!-- 博客截图 -->

## ✨ 核心特性
- **技术栈**: Hugo (Stack 主题) + Vercel + Algolia 搜索
- **功能支持**: 代码高亮/LaTeX 公式/RSS 订阅/暗黑模式
- **内容方向**: 前端框架/云原生/算法/开发实践

## 🚀 快速开始
```bash
# 1. 安装 Hugo Extended 版本 (必需)
# macOS
brew install hugo

# Windows (管理员权限运行)
choco install hugo-extended -y

# 2. 克隆项目（含主题子模块）
git clone --recurse-submodules https://github.com/yourname/your-blog.git

# 3. 启动本地服务器
cd your-blog
hugo server -D --disableFastRender