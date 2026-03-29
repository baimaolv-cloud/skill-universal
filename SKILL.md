---
name: skill-universal
description: Universal Skill Pack for OpenClaw - A collection of commonly used skills for AI agents
metadata:
  {
    "openclaw":
      {
        "requires": { "bins": ["clawhub"] },
        "install":
          [
            {
              "id": "clawhub",
              "kind": "node",
              "package": "clawhub",
              "bins": ["clawhub"],
              "label": "Install ClawHub CLI",
            },
          ],
      },
  }
---

# skill-universal

Universal Skill Pack for OpenClaw

## Features

- **skill-progress-bar**: Automatically displays progress bars for tasks longer than 30 seconds
- **universal-doc-storage**: Unified document storage and management system
- **skill-storager**: Skill storage manager (upgraded version of universal-doc-storage)
- **More skills coming soon...**

## Installation

```bash
git clone https://github.com/baimaolv-cloud/skill-universal.git ~/.openclaw/workspace/skills/skill-universal
bash ~/.openclaw/workspace/skills/skill-universal/scripts/example.sh
```

## Usage

This is a meta-skill package that includes various useful skills for OpenClaw AI agents.

## Author

baimaolv-cloud

## Version

1.0.0