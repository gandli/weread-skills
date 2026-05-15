# 微信读书 SKILLS / WeRead SKILLS

[中文](#中文) | [English](#english)

---

## 中文

微信读书官方 Agent Skills 集合，通过 GitHub Actions 自动同步。

[![](https://skills.sh/b/gandli/weread-skills)](https://skills.sh/gandli/weread-skills)

### 安装

```bash
npx skills add gandli/weread-skills
```

### 可用 Skills

#### WeRead

微信读书官方技能，包含书籍搜索、书架管理、笔记查看、阅读数据等功能。

**使用场景：**

- 「搜索关于 React 的书籍」
- 「显示我的书架」
- 「查看我的阅读数据」
- 「导出我的读书笔记」

**功能覆盖：**

- 书籍搜索与详情
- 书架管理
- 笔记与标注
- 阅读数据统计
- 书评与想法
- 个人资料

### 使用

Skills 安装后自动可用。Agent 会在检测到相关任务时自动使用。

**示例：**

```
帮我搜索人工智能相关的书籍
```

```
查看我本周的阅读统计
```

### 结构

```
weread-skills/
├── skills/
│   ├── SKILL.md              # 主技能文件
│   ├── book.md               # 书籍相关功能
│   ├── search.md             # 搜索相关功能
│   ├── shelf.md              # 书架相关功能
│   ├── notes.md              # 笔记相关功能
│   ├── review.md             # 书评相关功能
│   ├── profile.md            # 个人资料
│   ├── readdata.md           # 阅读数据
│   ├── discover.md           # 发现相关
│   ├── README.md             # Skill 说明
│   └── metadata.json         # 元数据
├── CHANGELOG.md              # 更新日志
└── .github/workflows/
    └── sync.yml              # 自动同步工作流
```

### 自动同步

本仓库通过 GitHub Actions 每日自动从微信读书官方源同步最新的 SKILLS 文件。

### 免责声明

本仓库仅用于技术研究和学习目的。所有 SKILLS 文件的版权归微信读书所有。

---

## English

Official WeRead Agent Skills collection, automatically synced via GitHub Actions.

[![](https://skills.sh/b/gandli/weread-skills)](https://skills.sh/gandli/weread-skills)

### Installation

```bash
npx skills add gandli/weread-skills
```

### Available Skills

#### WeRead

Official WeRead skill with book search, shelf management, note viewing, reading data, and more.

**Use when:**

- "Search for books about React"
- "Show my bookshelf"
- "View my reading data"
- "Export my book notes"

**Features covered:**

- Book search and details
- Bookshelf management
- Notes and highlights
- Reading statistics
- Reviews and thoughts
- Profile information

### Usage

Skills are automatically available after installation. The agent will use them when relevant tasks are detected.

**Examples:**

```
Search for books about artificial intelligence
```

```
View my weekly reading statistics
```

### Structure

```
weread-skills/
├── skills/
│   ├── SKILL.md              # Main skill file
│   ├── book.md               # Book related functions
│   ├── search.md             # Search related functions
│   ├── shelf.md              # Shelf management
│   ├── notes.md              # Notes and highlights
│   ├── review.md             # Reviews and thoughts
│   ├── profile.md            # Profile information
│   ├── readdata.md           # Reading statistics
│   ├── discover.md           # Discovery related
│   ├── README.md             # Skill documentation
│   └── metadata.json         # Metadata
├── CHANGELOG.md              # Changelog
└── .github/workflows/
    └── sync.yml              # Auto-sync workflow
```

### Automatic Sync

This repository automatically syncs the latest SKILLS files from the official WeRead source daily via GitHub Actions.

### Disclaimer

This repository is for technical research and learning purposes only. All SKILLS files are copyrighted by WeRead.
