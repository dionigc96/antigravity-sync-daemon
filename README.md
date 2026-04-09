# antigravity-sync-daemon

A lightweight, cross-platform Rust daemon to sync Antigravity LLM chats in real-time using Neon DB.

## Overview

`antigravity-sync-daemon` is a background service built entirely in **Rust**, designed to run on multiple platforms (Linux, macOS, Windows) with minimal resource footprint. It keeps your Antigravity conversation history synchronized across devices in real-time using **[Neon DB](https://neon.tech/)** — a serverless PostgreSQL platform built for modern, cloud-native applications.

## Key Features

- ⚡ **Real-time sync** — Pushes and pulls chat changes as they happen
- 🦀 **Built in Rust** — Memory-safe, blazing-fast, and cross-platform from day one
- 🐘 **PostgreSQL-powered storage** — Backed by Neon DB for scalable, serverless PostgreSQL
- 🔌 **Daemon architecture** — Runs silently in the background, no UI required
- 🔒 **Secure by default** — End-to-end encryption for all synced data

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Rust |
| Database | Neon DB (PostgreSQL) |
| Sync Protocol | Custom binary protocol over WebSocket |
| Packaging | Cargo / cross-rs |

## Getting Started

> ⚠️ This project is in early development. Stay tuned.

```bash
git clone https://github.com/dionigc96/antigravity-sync-daemon.git
cd antigravity-sync-daemon
cargo build --release
```

## License

MIT
