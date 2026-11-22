# The Channel Practice

A beginner guide to starting and growing a YouTube channel, long-form videos and Shorts, from your first upload to the basics of growth, with a source for every claim.

Written for **complete beginners to YouTube**: every term is defined ([glossary](docs/glossary.md)), every step is small, and every external claim links to a source checked on 22 Nov 2026 ([sources](docs/sources.md)). The worked example is **Maya Sen**, the fictional beginner from *The Content Practice*, in a second season: her short videos elsewhere have traction, and now she is trying long-form YouTube and Shorts ([meet her](docs/meet-maya.md)). Three real creators are cited from their own public videos about process ([real creators](docs/real-creators.md)).

Companion to [The Content Practice](https://github.com/brenotreviso/content-practice) (short videos on any platform) and [The Coded Motion Guide](https://github.com/brenotreviso/coded-motion) (pictures made with code). You need neither to use this guide.

## Start here

| If you want to… | Go to |
|---|---|
| Upload your first long video and Short this week | [0 · Start here (7-day path)](docs/00-start-here.md) |
| Read the guide | [docs/index.md](docs/index.md) (also builds as a website, see below) |
| Check YPP thresholds or Shorts rules | [Platform snapshot](docs/platform-snapshot.md) (dated; refresh quarterly and after 1 Feb 2027) |
| Work with an AI agent | [AGENTS.md](AGENTS.md) + [the skill](.agents/skills/channel-practice/SKILL.md) |

## What's inside

```
channel-practice/
├── README.md · AGENTS.md · CLAUDE.md · CHANGELOG.md
├── LICENSE (CC BY-NC-SA 4.0, text) · LICENSE-CODE (MIT, templates and scripts)
├── docs/                 14 chapters (00-13) + meet-maya, real-creators, platform-snapshot, glossary, sources
├── templates/            video plan, long-video script, Shorts script, upload calendar, analytics review
├── checklists/           channel setup, first video, title and thumbnail, before you upload, 48-hour review, YPP readiness
├── scripts/              mkdocs_hooks.py
├── .agents/skills/channel-practice/SKILL.md   (symlinked into .claude/skills and .grok/skills)
├── .github/workflows/docs.yml                 (builds and deploys the site to GitHub Pages)
└── mkdocs.yml            docs website (Material for MkDocs)
```

## Run the docs site

```bash
pip install mkdocs-material
mkdocs serve        # http://127.0.0.1:8000
mkdocs build --strict
```

## Notes

- **Windows + symlinks:** the skill lives in `.agents/skills/channel-practice/` and is symlinked into `.claude/skills/` and `.grok/skills/`; the docs website links `docs/templates` and `docs/checklists` the same way. On Windows, enable symlinks before cloning (`git config --global core.symlinks true` plus Developer Mode), or copy the folders.
- **Maya Sen** is made up for teaching. She is not a real person. Do not cite her as a creator, client or data point.
- **Money:** chapter 11 (*The Partner Program, and why it isn’t your goal yet*) is a short, deliberate departure from *The Content Practice*’s no-money stance: today’s YouTube Partner Program thresholds and revenue shares from official pages, with the finer 2027 detail in the platform snapshot. Brand deals, sponsorships, affiliate links, selling products and tax are out of scope.
- **Name:** YouTube’s developer branding guidelines say not to use “YouTube” in the name of an app, product or service; describing it as being *for* YouTube is allowed. The guide is named accordingly.

## Licence

- Text, images and docs: [Creative Commons Attribution-NonCommercial-ShareAlike 4.0](LICENSE) (CC BY-NC-SA 4.0).
- Code, scripts and fill-in templates: [MIT](LICENSE-CODE).

© 2026 Breno Bergamin (Breno Treviso)
