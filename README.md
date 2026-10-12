# Awesome-Collaborative-Document-Workspace

# Awesome-Collaborative-Document-Workspace

# Top Collaborative Document Workspace Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Real-Time Co-Editing, Knowledge Bases & Team Documentation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Collaborative Document Workspaces**. These tools enable teams to write, edit, comment, and organize documents together in real time — combining docs, wikis, spreadsheets, and lightweight databases into a shared workspace.

**Examples** include Salesforce Quip, Notion, Coda, Google Docs, Microsoft 365, Dropbox Paper, Slite, Craft, ClickUp Docs, and Basecamp (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom real-time collaboration backends, and open knowledge management — ideal for teams, researchers, and developers seeking transparent, data-sovereign documentation platforms.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Quip](https://quip.com/)**  
  Collaborative productivity suite integrating docs, spreadsheets, and chat. Deep Salesforce CRM integration for embedding live records and driving account-based collaboration.

- **[Notion](https://www.notion.so/)**  
  All-in-one workspace combining docs, wikis, databases, and project management. Highly flexible block-based editor with templates and Notion AI.

- **[Coda](https://coda.io/)**  
  Doc-platform hybrid blending documents with spreadsheet-like tables and automation. Known as "docs that can do things" with buttons, formulas, and integrations.

- **[Google Docs](https://workspace.google.com/products/docs/)**  
  Real-time collaborative word processor with commenting, suggestions, version history, and deep integration across Google Workspace.

- **[Microsoft 365](https://www.microsoft.com/microsoft-365)**  
  Suite including Word, Excel, PowerPoint, and Loop with real-time co-authoring, Microsoft Teams integration, and Copilot AI assistance.

- **[Dropbox Paper](https://www.dropbox.com/paper)**  
  Collaborative document tool with lightweight formatting, to-do lists, and media embeds. Integrated with Dropbox file storage.

- **[Slite](https://slite.com/)**  
  Knowledge base and documentation platform for remote teams. Features AI-powered "Ask" search, templates, and verification workflows.

- **[Craft](https://www.craft.do/)**  
  Document editor with native apps across Apple platforms, block-based editing, and publishing to web. Strong visual design focus.

- **[ClickUp Docs](https://clickup.com/)**  
  Documents embedded within ClickUp's project management platform, with real-time collaboration, task linking, and nested pages.

- **[Basecamp](https://basecamp.com/)**  
  Project management and team communication platform with Docs & Files, message boards, and simple collaborative writing tools.

## Open-Source GitHub Projects

- **[AppFlowy](https://github.com/AppFlowy-IO/AppFlowy)**  
  Open-source Notion alternative (AGPL-3.0) built with Flutter and Rust. Features a kanban board, rich-text editor, database views, and self-hosting capability. Prioritizes data privacy and native cross-platform performance. 60k+ GitHub stars.

- **[AFFiNE](https://github.com/toeverything/AFFiNE)**  
  Open-source knowledge base (MIT/AGPL dual license) positioning itself as a Notion + Miro alternative. Combines docs, whiteboards, and databases in one workspace with local-first architecture and real-time collaboration.

- **[Outline](https://github.com/outline/outline)**  
  Fast, collaborative knowledge base and wiki (BSL 1.1) for growing teams. Features real-time editing, Markdown support, Slack integration, and a polished UI. Widely used as a self-hosted Notion/Confluence alternative. 30k+ GitHub stars.

- **[Docmost](https://github.com/docmost/docmost)**  
  Open-source collaborative wiki and documentation software (AGPL-3.0) — an alternative to Confluence and Notion. Built with TypeScript, React, and PostgreSQL. Supports real-time collaboration, diagrams (Draw.io, Excalidraw, Mermaid), permissions, and spaces. Docker deployment available.

- **[Huly](https://github.com/hcengineering/platform)**  
  Open-source all-in-one project management and collaboration platform (EPL-2.0). Combines documents, wikis, issues, and virtual office. Positioned as an open-source alternative to Notion, Slack, and Jira combined.

- **[Wiki.js](https://github.com/requarks/wiki)**  
  Modern, lightweight wiki engine (AGPL-3.0) built on Node.js. Supports Markdown, visual editing, granular permissions, and multiple database backends. 25k+ GitHub stars.

- **[BookStack](https://github.com/BookStackApp/BookStack)**  
  Simple, self-hosted documentation platform (MIT) with a books/chapters/pages hierarchy. Excellent WYSIWYG editor, built-in diagrams, and multi-language support. Ideal for internal wikis and knowledge bases.

- **[Etherpad](https://github.com/ether/etherpad-lite)**  
  Highly customizable open-source collaborative real-time editor (Apache-2.0). Supports rich text, plugins, and hundreds of concurrent users. One of the earliest and most battle-tested real-time collaboration tools.

- **[CryptPad](https://github.com/cryptpad/cryptpad)**  
  Privacy-focused, end-to-end encrypted collaboration suite (AGPL-3.0). Includes rich text docs, spreadsheets, slides, kanban, and whiteboards. Zero-knowledge architecture with no plaintext data on servers.

- **[Nextcloud Office / Collabora](https://github.com/nextcloud/richdocuments)**  
  Self-hosted document editing via Collabora Online (LibreOffice-based). Provides real-time collaborative editing of documents, spreadsheets, and presentations within Nextcloud.

- **[Rocket.Chat](https://github.com/RocketChat/Rocket.Chat)**  
  Open-source team communication platform (MIT) with integrated document sharing, video calls, and collaborative features. Often paired with wikis and file storage for full workspace functionality.

### Additional Strong Open-Source Options

- **[Logseq](https://github.com/logseq/logseq)** — Local-first, privacy-focused outliner and knowledge base with block references and graph view.
- **[Obsidian](https://obsidian.md/)** — Local Markdown knowledge base with extensive plugin ecosystem (note: core is closed-source, but file format is open).
- **[Trilium Notes](https://github.com/zadam/trilium)** — Hierarchical note-taking application with strong organization features.
- **[Joplin](https://github.com/laurent22/joplin)** — Open-source note-taking and to-do app with end-to-end encryption and sync.
- **[Mattermost](https://github.com/mattermost/mattermost)** — Open-source Slack alternative with boards, playbooks, and file sharing.
- **[ONLYOFFICE Docs](https://github.com/ONLYOFFICE/DocumentServer)** — Self-hosted collaborative office suite compatible with Microsoft formats.
- **[HedgeDoc](https://github.com/hedgedoc/hedgedoc)** — Open-source, real-time collaborative Markdown editor (formerly CodiMD).
- Community **Yjs** and **Automerge** libraries for building custom CRDT-based collaborative editors.

**Frameworks for building custom systems**: Combine **AppFlowy** or **AFFiNE** as the workspace frontend with **Yjs** for real-time CRDT synchronization, **Outline** or **Docmost** for wiki/knowledge base functionality, **Nextcloud + Collabora** for office document editing, and **PostgreSQL** for persistence — creating a fully self-hosted, enterprise-grade collaborative document workspace.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Document data must comply with data protection regulations (GDPR, CCPA, HIPAA, etc.).
- Self-hosted open-source solutions require proper security hardening, backup strategies, and ongoing maintenance.

---

**Made for teams, knowledge workers, researchers, and developers building transparent collaboration solutions.**  
Let's make collaborative document workspaces more open, data-driven, and efficient.
