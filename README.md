<div align="center">

# uniapp-skills

**uni-app cross-platform development skills**

[![GitHub](https://img.shields.io/badge/github-full--statck--skills%2Funiapp-skills-green.svg)](https://github.com/full-statck-skills/uniapp-skills)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Compatible-purple.svg)](https://agentskills.io)

English | [简体中文](./README.zh-CN.md)

[Introduction](#-introduction) · [Install](#-install) · [Skills](#-skills) · [Supported Agents](#-supported-agents) · [Ecosystem](#-ecosystem)

</div>

---

## 📖 Introduction

**uni-app Skills** is a curated collection of Agent Skills for AI coding agents, part of the [Full Stack Skills](https://github.com/partme-ai/full-stack-skills) ecosystem maintained by [PartMe.AI](https://github.com/partme-ai).

This package includes **13 skills**. Each skill is a self-contained `SKILL.md` file that AI agents load on-demand.

## 📦 Install

```bash
npx skills add full-statck-skills/uniapp-skills
```

Or install specific skills: `npx skills add full-statck-skills/uniapp-skills --skill <skill-name>`

## 🎯 Skills (13)

| Skill | Description |
|-------|-------------|
| `uniapp-ad` | A comprehensive skill for uni-ad monetization in uni-app. Use this skill to integrate ads, configure ad types, handle... |
| `uniapp-cloud` | A comprehensive skill for uniCloud cloud development in the uni-app ecosystem. Use this skill when you need uniCloud ... |
| `uniapp-mini` | A comprehensive skill for uni-app mini program development. Use when building uni-app mini programs, configuring mini... |
| `uniapp-native-app` | A comprehensive skill for uni-app native app offline packaging. Use this skill to package uni-app as native Android/i... |
| `uniapp-native-plugin` | A comprehensive skill for developing native plugins for uni-app. Use this skill when building Android/iOS native plug... |
| `uniapp-plugin` | A comprehensive skill for the uni-app plugin market and automatic plugin installation. Use this skill to browse plugi... |
| `uniapp-project-creator` | Provides one-command project creation for uni-app using the official quickstart CLI, including project initialization... |
| `uniapp-project` | Provides comprehensive uni-app component and API integration guidance. Use when the user needs official uni-app compo... |
| `uniapp-ucharts` | A comprehensive skill for integrating and using uCharts with UniApp projects. This skill focuses on UniApp-specific i... |
| `uniapp-uview` | A comprehensive skill for integrating and using uView UI with UniApp projects. This skill focuses on UniApp-specific ... |
| `uniappx-project-creator` | Provides one-command project creation for uni-app-x including Vue 3 + TypeScript + Vite setup, configuration, and tem... |
| `uniappx-project` | Provides comprehensive uni-app-x component and API integration guidance. Use when the user needs official uni-app-x c... |
| `uniappx-uview-pro` | A comprehensive skill for integrating and using uView Pro with UniAppX projects. This skill focuses on UniAppX-specif... |

## 🤖 Supported Agents

Works with [Claude Code](https://code.claude.com), [Codex](https://developers.openai.com/codex), [Cursor](https://cursor.com), [OpenCode](https://opencode.ai), [Gemini CLI](https://geminicli.com), [GitHub Copilot](https://github.com/features/copilot), [Windsurf](https://codeium.com/windsurf), and [70+ others](https://agentskills.io/clients).

### Claude Code Installation

**Option 1: npx skills CLI (Recommended)**

```bash
npx skills add full-statck-skills/uniapp-skills
```

**Option 2: Manual Installation**

```bash
git clone https://github.com/full-statck-skills/uniapp-skills.git
cp -r uniapp-skills/skills/* .claude/skills/
```

For more details, see the [Claude Code Skills Guide](https://code.claude.com/docs/en/skills) and [Agent Skills Spec](https://agentskills.io/).

## 🌐 Ecosystem

| Resource | Link |
|----------|------|
| **Full Stack Skills** | [github.com/partme-ai/full-stack-skills](https://github.com/partme-ai/full-stack-skills) |
| **All Skill Groups** | [github.com/full-statck-skills](https://github.com/full-statck-skills) |
| **Agent Skills Spec** | [agentskills.io](https://agentskills.io) |
| **Skills CLI** | [github.com/vercel-labs/skills](https://github.com/vercel-labs/skills) |

## 📄 License

Apache 2.0 — see [LICENSE](LICENSE).
