# Nolan Vale

Independent developer building practical open-source CLI tools for AI coding agents, search automation, browser automation, and Russian-language text processing.

## Google NotebookLM

Complete terminal toolkit for Google NotebookLM — Chrome-based auth and full programmatic access.

| Project | What it does | Install |
|---|---|---|
| [notebooklm-cdp](https://github.com/nolan-vale/notebooklm-cdp) | CDP auth from Chrome Beta + chat, sources, generation, Studio notes from terminal | `uv tool install notebooklm-cdp` |

## Search & Research

CLI tools for web search, URL crawling, and AI-powered research from the terminal.

| Project | What it does | Install |
|---|---|---|
| [exa-search-cli](https://github.com/nolan-vale/exa-search-cli) | Exa neural search, URL crawling, and deep research from terminal | `uv tool install exa-search-cli` |
| [yandex-search-cli](https://github.com/nolan-vale/yandex-search-cli) | Yandex Search API and YandexGPT from terminal | `uv tool install yandex-search-cli` |

## Browser Automation

Real browser automation for AI agents — visible Chrome with a dedicated agent profile and Chrome DevTools Protocol.

| Project | What it does | Install |
|---|---|---|
| [browser-agent-cli](https://github.com/nolan-vale/browser-agent-cli) | Launch Chrome Beta with agent profile + CDP control layer. No headless. Persistent logins. | `git clone` + `bash install.sh` |

## Russian Text AI Skills

AI instruction files (skills) for removing AI writing markers from Russian text. Work with Claude, ChatGPT, Gemini, and any LLM that accepts a system prompt.

| Project | What it does | Use case |
|---|---|---|
| [humanizer-ru](https://github.com/nolan-vale/humanizer-ru) | Removes 21 AI writing patterns from Russian text | Social media, ads, short content |
| [humanizer-ru-pro](https://github.com/nolan-vale/humanizer-ru-pro) | 52 patterns, quad-pass audit, author voice calibration | Business writing, Habr, long-form |
| [ru-academic-editor](https://github.com/nolan-vale/ru-academic-editor) | Academic editor for dissertations and journal articles | Thesis, ВКР, scientific papers |

## Focus

- NotebookLM terminal automation and AI knowledge workflows
- Search automation and AI-agent CLI tools
- Real browser automation via Chrome DevTools Protocol
- Russian-language AI text processing
- JSON output for scripts and coding agents
- Terminal-first utilities

## How these tools are built

Each project starts as a written spec and a plan, then gets implemented with AI coding agents (Claude Code, Codex). Every diff is reviewed before merge, and each release goes through tests and basic security checks before it ships. The agents write the code; the design decisions and the review are not automated.

Clear tools. Simple workflows. Less friction.
