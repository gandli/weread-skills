<div align="center">

[![WeRead Official](https://rescdn.qqmail.com/node/wr/wrpage/style/images/independent/appleTouchIcon/apple-touch-icon-60x60.png)](https://weread.qq.com/r/weread-skills)

# WeRead SKILLS

**Let AI be your reading partner**

[![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-Auto--Sync-blue?logo=github-actions)](.github/workflows/sync.yml)
[![Agent Skills](https://img.shields.io/badge/Agent-Skills-purple)](https://skills.sh/gandli/weread-skills)
[![中文文档](https://img.shields.io/badge/README-%E4%B8%AD%E6%96%87-green)](README.zh.md)

---

Connect your WeRead account, let AI assistant access your reading records anytime.  
This is the official WeRead Agent Skills collection, automatically synced via GitHub Actions.

</div>

## Installation

```bash
npx skills add gandli/weread-skills
```

## Quick Setup

After installing the Skill, you can access your personal reading information via API Key.

1. Copy the Skill installation command and send it to your AI assistant
2. Get API Key from [WeRead Official](https://weread.qq.com/r/weread-skills) to connect your account

*API Key is used to connect your WeRead account, data is visible only to you.*

## Available Skills

### WeRead

Official WeRead skill with comprehensive reading management capabilities.

**Use when:**

- "Search for books about AI"
- "Show my bookshelf"
- "View my reading statistics"
- "Export my book notes and highlights"
- "Get book details and table of contents"
- "Recommend books based on my preferences"

## Features

| Feature | Description |
|---------|-------------|
| 📚 **Bookshelf Access** | Browse your personal bookshelf, get a complete overview of your collection |
| 📊 **Reading Statistics** | In-depth analysis of duration, days, and preferences to quantify your reading habits |
| 📝 **Notes & Highlights** | View personal highlights and thoughts, export notes, review your thinking |
| 🔍 **Book Search** | Search any book in the library, quickly get title, author, rating, and more |
| 📖 **Book Details** | View book details, table of contents, reading progress, understand your reading journey |
| ✨ **Smart Recommendations** | Personalized or similar book recommendations based on your reading preferences |
| 💬 **Reviews & Thoughts** | Manage your book reviews and reading thoughts |
| 👤 **Profile Information** | Access your reading profile and statistics |

## Usage

Skills are automatically available after installation. The agent will use them when relevant tasks are detected.

**Examples:**

```
Search for books about artificial intelligence
```

```
View my weekly reading statistics
```

```
Export all notes from "Sapiens"
```

```
Show my bookshelf and recommend similar books
```

## Structure

```
weread-skills/
├── skills/
│   └── weread/               # Skill subdirectory (name = weread)
│       ├── SKILL.md          # Main skill file with frontmatter
│       ├── book.md           # Book related functions
│       ├── search.md         # Search related functions
│       ├── shelf.md          # Shelf management
│       ├── notes.md          # Notes and highlights
│       ├── review.md         # Reviews and thoughts
│       ├── profile.md        # Profile information
│       ├── readdata.md       # Reading statistics
│       ├── discover.md       # Discovery and recommendations
│       ├── SKILL-README.md   # Skill documentation
│       └── metadata.json     # Metadata
├── README.md                 # English documentation (main)
├── README.zh.md              # Chinese documentation
├── CHANGELOG.md              # Changelog
└── .github/workflows/
    └── sync.yml              # Auto-sync workflow
```

## Automatic Sync

This repository automatically syncs the latest SKILLS files from the [official WeRead source](https://weread.qq.com/r/weread-skills) daily via GitHub Actions.

Sync schedule: Daily at UTC 00:00 (Beijing time 08:00)

## Official Resources

- 🌐 **Official Website**: [https://weread.qq.com/](https://weread.qq.com/)
- 📖 **Skill Introduction**: [https://weread.qq.com/r/weread-skills](https://weread.qq.com/r/weread-skills)
- ⬇️ **Official Download**: `https://cdn.weread.qq.com/skills/weread-skills.zip`

## Disclaimer

This repository is for technical research and learning purposes only. All SKILLS files are copyrighted by WeRead.

---

*Note: This is a community-maintained mirror of the official WeRead Skills. For the most up-to-date version, always check the [official website](https://weread.qq.com/r/weread-skills).*
