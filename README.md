> [!NOTE]
> **This skill now lives in the main collection: [milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills/tree/main/skills/cost-cutter)**. Please ⭐ star it there; that's where updates land first.
> Docs: **https://milad-ahmd.github.io/agent-skills/skills/cost-cutter/** · Claude Code: `/plugin install all-skills --marketplace milad-ahmd/agent-skills`

<div align="center">

# 💸 cost-cutter

**Cut cloud, SaaS and LLM API bills with dollar estimates, effort, risk and exact fixes. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/cost-cutter)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/cost-cutter?style=social)](https://github.com/milad-ahmd/cost-cutter)
![Category](https://img.shields.io/badge/category-DevOps-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/cost-cutter/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- cost-cutter
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/cost-cutter /tmp/cost-cutter
mkdir -p ~/.claude/skills && cp -r /tmp/cost-cutter/skills/cost-cutter ~/.claude/skills/
```

**Per project:** copy `skills/cost-cutter` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/cost-cutter/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Why is our AWS bill so high?
Cut our OpenAI API costs
```

The full workflow, rules and output format are in [`SKILL.md`](skills/cost-cutter/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
