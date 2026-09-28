---
type: Feature
title: Product monorepo
description: Single repository for iOS client and macOS agent node.
tags: [pocket-agent, ios, macos, monorepo]
timestamp: 2026-09-28T00:00:00Z
---

| Path / link | Responsibility |
|-------------|----------------|
| **`src/app-ios/`** | Chat UI; smallest practical on-device model for offline use; optional secure link to a Mac node |
| **`src/app-macos/`** | Agent node host; tools and heavier models; Telegram bridge; admin and custom roles for shared access |
| **`specs/app-ios/`**, **`specs/app-macos/`** | OKF feature specs per platform |
| **`website/`** | Public landing page (iOS / macOS toggle) — [pocket-agent.pages.dev](https://pocket-agent.pages.dev) |
| **App Store** | [PocketAgent: Chatbot](https://apps.apple.com/us/app/pocketagent-chatbot/id6816867795) — one listing for iPhone, iPad, and Mac |

Repository: **[github.com/pocket-agent/pocket-agent](https://github.com/pocket-agent/pocket-agent)**.
