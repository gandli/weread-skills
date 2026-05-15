# WeRead SKILLS

Official WeRead Agent Skills collection, automatically synced via GitHub Actions.

[![](https://skills.sh/b/gandli/weread-skills)](https://skills.sh/gandli/weread-skills)
[![中文](https://img.shields.io/badge/README-%E4%B8%AD%E6%96%87-green)](README.zh.md)

## Installation

```bash
npx skills add gandli/weread-skills
```

## Available Skills

### WeRead

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

## Usage

Skills are automatically available after installation. The agent will use them when relevant tasks are detected.

**Examples:**

```
Search for books about artificial intelligence
```

```
View my weekly reading statistics
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
│       ├── discover.md       # Discovery related
│       ├── SKILL-README.md   # Skill documentation
│       └── metadata.json     # Metadata
├── README.md                 # English documentation (main)
├── README.zh.md              # Chinese documentation
├── CHANGELOG.md              # Changelog
└── .github/workflows/
    └── sync.yml              # Auto-sync workflow
```

## Automatic Sync

This repository automatically syncs the latest SKILLS files from the official WeRead source daily via GitHub Actions.

## Disclaimer

This repository is for technical research and learning purposes only. All SKILLS files are copyrighted by WeRead.
