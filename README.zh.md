<div align="center">

<a href="https://weread.qq.com/r/weread-skills"><img src="https://rescdn.qqmail.com/node/wr/wrpage/style/images/independent/appleTouchIcon/apple-touch-icon-144x144.png" width="48" alt="微信读书" /></a>

# 微信读书 SKILLS

## 让 AI 成为你的阅读搭档

[![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-自动同步-blue?logo=github-actions)](.github/workflows/sync.yml)
[![Agent Skills](https://img.shields.io/badge/Agent-Skills-purple)](https://skills.sh/gandli/weread-skills)
[![English](https://img.shields.io/badge/README-English-blue)](README.md)

---

连接微信读书账号，让 AI 助手随时查阅你的阅读记录。  
本仓库是微信读书官方 Agent Skills 的镜像，通过 GitHub Actions 自动同步更新。

</div>

## 安装

```bash
npx skills add gandli/weread-skills
```

## 快速配置

安装 Skill 后，即可通过 API Key 获取你的个人阅读信息。

1. 复制 Skill 安装指令，发送给你的 AI 助手即可自动安装
2. 前往 [微信读书官方页面](https://weread.qq.com/r/weread-skills) 获取 API Key 连接你的账号

*API Key 用于连接你的微信读书账号，数据仅你可见*

## 功能特性

### 可用 Skills

#### WeRead

微信读书官方 Skill，提供全面的阅读管理功能。

**使用场景：**

- "帮我搜索关于人工智能的书籍"
- "显示我的书架"
- "查看我的阅读统计"
- "导出《人类简史》的所有笔记"
- "根据我的阅读偏好推荐好书"

### 功能列表

| 功能 | 描述 |
|-----|------|
| 📚 **查阅书架** | 浏览你的个人书架，快速了解藏书全貌 |
| 📊 **阅读统计** | 时长、天数、偏好深度分析，量化你的阅读习惯 |
| 📝 **笔记和划线** | 查看个人划线和想法，导出笔记，回顾阅读中的思考 |
| 🔍 **书籍搜索** | 在书城搜索任意书籍，快速获取书名、作者、评分等关键信息 |
| 📖 **书籍详情** | 查看书籍详情、章节目录、阅读进度，了解你的阅读旅程 |
| ✨ **推荐好书** | 基于你的阅读偏好，个性化推荐或相似书籍推荐 |
| 💬 **书评与想法** | 管理你的书籍评论和阅读感想 |
| 👤 **个人资料** | 访问你的阅读档案和统计数据 |

## 使用方法

Skills 安装后自动可用，Agent 会在检测到相关任务时自动使用。

**使用示例：**

```
帮我搜索关于人工智能的书籍
```

```
查看我本周的阅读统计
```

```
导出《人类简史》的所有笔记
```

```
显示我的书架并推荐相似的书籍
```

## 目录结构

```
weread-skills/
├── skills/
│   └── weread/               # Skill 子目录 (名称 = weread)
│       ├── SKILL.md          # 主技能文件（包含 frontmatter）
│       ├── book.md           # 书籍相关功能
│       ├── search.md         # 搜索相关功能
│       ├── shelf.md          # 书架相关功能
│       ├── notes.md          # 笔记相关功能
│       ├── review.md         # 书评相关功能
│       ├── profile.md        # 个人资料
│       ├── readdata.md       # 阅读数据统计
│       ├── discover.md       # 发现与推荐
│       ├── SKILL-README.md   # Skill 说明文档
│       └── metadata.json     # 元数据
├── README.md                 # 英文文档（主）
├── README.zh.md              # 中文文档
├── CHANGELOG.md              # 更新日志
└── .github/workflows/
    └── sync.yml              # 自动同步工作流
```

## 自动同步

本仓库通过 GitHub Actions 每日自动从 [微信读书官方源](https://weread.qq.com/r/weread-skills) 同步最新的 SKILLS 文件。

同步时间：每日 UTC 0 点（北京时间 8 点）

## 官方资源

- 🌐 **官方网站**：[https://weread.qq.com/](https://weread.qq.com/)
- 📖 **Skill 介绍页**：[https://weread.qq.com/r/weread-skills](https://weread.qq.com/r/weread-skills)
- ⬇️ **官方下载地址**：`https://cdn.weread.qq.com/skills/weread-skills.zip`

## 免责声明

本仓库仅用于技术研究和学习目的。所有 SKILLS 文件的版权归微信读书所有。

---

*注：这是社区维护的微信读书 Skills 镜像。如需最新版本，请始终查看 [官方网站](https://weread.qq.com/r/weread-skills)。*
