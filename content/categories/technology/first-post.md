+++
date = '2025-10-02T14:44:08+08:00'
draft = false
title = 'First Post'
categories = ["technology"]
tags = ["Hugo", "博客"]
+++

吆西www

> 💡 PaperMod 支持 TOC（目录）、代码高亮、数学公式（KaTeX）、表格等，Markdown 写作体验非常完整。

---

### ✅ 2️⃣ 推荐使用的编辑器
| 编辑器 | 优点 |
|--------|------|
| **VS Code** | 支持 Markdown 预览、YAML FrontMatter 高亮、Git 集成；推荐安装插件：*Markdown All in One*、*Front Matter CMS* |
| **Typora** | 极简实时预览写作体验 |
| **Obsidian** | 如果你有大量笔记，可用它组织 Markdown 知识库，写完后复制或同步到 Hugo 博客目录 |

---

## ⚙️ 三、Hugo 常用操作命令

| 功能 | 命令 |
|------|------|
| 启动本地服务器 | `hugo server -D` |
| 构建网站（生成静态文件） | `hugo` |
| 新建文章 | `hugo new posts/xxx.md` |
| 指定主题运行 | `hugo server -t PaperMod -D` |
| 清理 public 目录 | `rm -rf public` |

> ⚠️ 注意：Hugo 默认不会覆盖 public 下的旧文件，发布前可清理干净。

---

## 🧱 四、PaperMod 主题使用技巧

### 1️⃣ 首页信息配置
在 `config.toml` 中添加：

```toml
[params.homeInfoParams]
Title = "Hi there 👋"
Content = "欢迎来到我的技术博客，记录 Java 后端、算法与系统设计思考。"
