<div align="center">

# CyberPsych Kids
## Cyber Psychology Educational Content System for Children

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude_Code-Plugin-blue.svg)]()
[![Age Groups](https://img.shields.io/badge/Age_Groups-10-orange.svg)]()
[![Commands](https://img.shields.io/badge/Commands-27-purple.svg)]()

**A comprehensive system for creating creative educational content about cyber psychology for children and young adults**

[Arabic / العربية](README.md) | [Usage Guide](guide.html)

</div>

---

## What is this project?

**CyberPsych Kids** is a complete content creation system powered by Claude Code, designed to protect Arab children and youth in the digital world. The project delivers awareness content grounded in cyber psychology research, aligned with Islamic values and Arab culture. **Default theme: Egyptian Arabic Islamic**.

The system covers **10 age groups** from age 2 through 40, and provides **27 specialized commands** for generating stories, games, video scripts, lesson plans, interactive activities, a full project management system, and more. Core characters: Youssef, Mariam, Omar, Habiba.

---

## Features

- **10 age groups** covering all developmental stages from early childhood to digital parenting
- **27 specialized commands** for creating diverse educational content
- **Project management system** with full lifecycle: Discussion > Planning > Implementation > Review > Publish
- **Egyptian theme by default** (Egyptian Arabic Islamic) with support for other themes via `--theme`
- **`--theme` parameter** for all content commands (egyptian, gulf, levantine, maghreb, universal-arabic, universal)
- **10 ready-made templates** to accelerate content production
- **14 knowledge files** forming the scientific foundation of the system
- **Evidence-based methodology** rooted in cyber psychology research
- **Islamic values integration** with Arab cultural sensitivity
- **Multiple output formats** including HTML, Markdown, JSON, and AI prompts
- **Story-Lesson-Activity pattern** ensuring effective and enjoyable learning
- **Bilingual support** for Arabic and English
- **AI tool integrations** with Freepik, Blender MCP, and more

---

## Supported Age Groups

| Age Range | Name (Arabic) | Level | Primary Approach |
|:---:|---|---|---|
| 2-4 years | The Magic Screen World | Introductory | Simple colors and shapes, short songs |
| 4-6 years | Internet Adventures | Early Basic | Short picture stories, simple games |
| 6-8 years | Digital Safety Team | Basic | Interactive stories, hands-on activities |
| 8-10 years | Internet Detectives | Early Intermediate | Investigation adventures, brain challenges |
| 10-12 years | Digital World Heroes | Intermediate | Group projects, realistic scenarios |
| 12-14 years | Smart Digital Life | Early Advanced | Discussions, case studies, critical analysis |
| 14-16 years | Digital Age Leaders | Advanced | Peer leadership, community projects |
| 16-18 years | The Responsible Digital Citizen | Near-Adult | Independent research, personal initiatives |
| 18-28 years | Conscious Digital Living | Young Adults | Professional content, digital mental health |
| 28-40 years | Digital Parenting & Leadership | Parents | Guidebooks, mindful monitoring tools |

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/IbrahimBadawy/cyberpsych-kids.git
cd cyberpsych-kids
```

### 2. Open with Claude Code

```bash
claude
```

Claude will automatically read the `CLAUDE.md` configuration file and activate all commands and templates.

### 3. Start creating content

```bash
/story cyberbullying --age 8-10 --output html --lang ar
```

---

## Available Commands

| # | Command | Description | Output |
|:---:|---|---|---|
| 1 | `/research` | In-depth research on a specific cyber topic with scientific sources | Markdown Report |
| 2 | `/story` | Create an educational story about a cyber concept | HTML / Markdown |
| 3 | `/video-script` | Write an educational video script with storyboard | Markdown + JSON |
| 4 | `/game-design` | Design an educational game (digital or tabletop) | Game Design Document |
| 5 | `/lesson` | Prepare a complete lesson plan with activities and assessment | Lesson Plan (HTML) |
| 6 | `/quiz` | Create an interactive quiz to measure understanding | HTML Interactive Quiz |
| 7 | `/infographic` | Design an awareness infographic | Prompt + Instructions |
| 8 | `/social-post` | Create content for social media platforms | Multi-Platform Content |
| 9 | `/character` | Design a new character for the series | Character Sheet (JSON) |
| 10 | `/series-plan` | Plan an integrated content series | Series Blueprint |
| 11 | `/parent-guide` | Prepare a parental guidance document | PDF-Ready Markdown |
| 12 | `/workshop` | Design a training workshop | Workshop Kit |
| 13 | `/activity` | Design a standalone interactive activity | Activity Sheet |
| 14 | `/song` | Write an educational song/nasheed | Lyrics + Notes |
| 15 | `/freepik` | Generate a prompt for Freepik AI image design | Image Prompt |
| 16 | `/blender-scene` | Create a 3D scene in Blender | Blender Scene |
| 17 | `/age-adapt` | Adapt existing content for a different age group | Adapted Content |
| 18 | `/review` | Review content against quality criteria | Review Report |
| 19 | `/export` | Export content in the requested format | Multiple Formats |
| 20 | `/therapy-plan` | Prepare a therapy plan for cyber-related issues | Therapy Plan |
| 21 | `/family-game` | Design a family game about digital safety | Family Game Kit |
| 22 | `/tool-guide` | Guide for safely using a digital tool | Tool Guide |
| 23 | `/project-new` | Create a new content project | Project Folder |
| 24 | `/project-discuss` | Start a discussion about a project idea | Discussion Document |
| 25 | `/project-plan` | Convert discussion into an execution plan | Project Plan |
| 26 | `/project-start` | Start project implementation | Content Files |
| 27 | `/project-status` | Show current project status | Status Report |

### General Command Syntax

```
/command [topic] --age [age-group] --output [output-type] --lang [language] --theme [cultural-theme]
```

> **Note:** The default theme is `egyptian` (Egyptian Arabic Islamic). Available themes: `egyptian`, `gulf`, `levantine`, `maghreb`, `universal-arabic`, `universal`

---

## Project Management

The system provides a full project management system with a complete lifecycle:

```
💬 Discussion → 📋 Planning → 🔄 Implementation → ✅ Review → 📦 Publish
```

| Phase | Command | Description |
|---|---|---|
| Discussion | `/project-discuss` | Brainstorm and discuss the idea |
| Planning | `/project-plan` | Convert discussion into an execution plan |
| Implementation | `/project-start` | Start content production |
| Tracking | `/project-status` | Show project status |
| Creation | `/project-new` | Create a new project directly |

### Example: Creating a Story Series Project

```bash
# 1. Create a new project
/project-new digital-safety-series --age 8-10

# 2. Discuss ideas
/project-discuss episode ideas for the series

# 3. Create the plan
/project-plan

# 4. Start implementation
/project-start

# 5. Check status
/project-status
```

---

## Usage Examples

### Create a story about digital privacy
```bash
/story digital-privacy --age 6-8 --output html --lang ar
```

### Design a game about strong passwords
```bash
/game-design strong-passwords --age 8-10 --output json --lang ar
```

### Prepare a lesson plan about cyberbullying
```bash
/lesson cyberbullying --age 10-12 --output html --lang both
```

### Write a video script about digital footprint
```bash
/video-script digital-footprint --age 14-16 --output markdown --lang ar
```

### Create a story with Gulf theme
```bash
/story digital-privacy --age 6-8 --output html --lang ar --theme gulf
```

### Create a new project
```bash
/project-new internet-heroes-series --age 8-10
```

---

## Project Structure

```
cyberpsych-kids/
├── CLAUDE.md                  # Main system configuration file
├── README.md                  # Arabic README
├── README_EN.md               # This file (English)
├── guide.html                 # Interactive usage guide
├── LICENSE                    # MIT License
├── CHANGELOG.md               # Change log
├── CONTRIBUTING.md            # Contribution guide
├── knowledge/                 # Knowledge files (14 files)
│   ├── 01-what-is-cyber-psychology.md
│   ├── 02-core-theories.md
│   ├── 03-digital-problems.md
│   ├── 04-age-frameworks.md
│   ├── 08-color-psychology.md
│   ├── 09-gamification-guide.md
│   └── 10-character-bible.md
├── templates/                 # Templates (10 templates)
│   ├── story-template.md
│   ├── video-script-template.md
│   ├── game-design-doc-template.md
│   ├── lesson-plan-template.md
│   └── workshop-template.md
├── projects/                  # Content projects (project management system)
├── output/                    # Generated content
│   ├── stories/
│   ├── videos/
│   ├── games/
│   ├── lessons/
│   ├── activities/
│   └── social-media/
└── docs/                      # Additional documentation
```

---

## Required Tools

### Required (Core)

| Tool | Usage |
|---|---|
| **Claude Code** | Core engine - content creation, analysis, and programming |

### Optional (Extended Capabilities)

| Tool | Usage | Type |
|---|---|---|
| **Freepik** | AI-powered image and illustration design | Paid |
| **Gemini** (Google) | Advanced search, video analysis, translation | Paid |
| **ChatGPT** (OpenAI) | Brainstorming, review, additional content creation | Paid |
| **Blender MCP** | 3D scenes, characters, and environments | Free |
| **Canva** | Infographic and visual material design | Free/Paid |
| **Scratch** | Visual game programming (ages 6-14) | Free |
| **GDevelop** | No-code game development (ages 10-18) | Free |

---

## Contributing

Contributions are welcome! Please read the [Contributing Guide](CONTRIBUTING.md) before submitting changes.

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Areas Where Contributions Are Welcome

- Adding new knowledge files
- Improving existing templates
- Translating content to other languages
- Suggesting new topics
- Educational or cultural content review
- Developing interactive tools and activities

---

## License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">

**CyberPsych Kids** - Building a digitally aware generation, one piece of content at a time.

</div>
