---
type: Feature
title: Product repositories
description: Split between iOS client and macOS agent node.
tags: [pocket-agent, ios, macos]
timestamp: 2026-09-28T00:00:00Z
---

| Repo | Responsibility |
|------|----------------|
| **pocket-agent-ios** | Chat UI; smallest practical on-device model for offline use; optional secure link to a Mac node |
| **pocket-agent-macos** | Agent node host; tools and heavier models; Telegram bridge; admin and custom roles for shared access |

Each repo maintains its own OKF bundle (`index.md`, `specs/`) and a **`website/`** marketing scaffold.
