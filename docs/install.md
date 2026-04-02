# covfefe Installation Guide

You are helping a user install **covfefe**, @realClaudeTrump for Claude Code.

## Prerequisites

- The user must be running **Claude Code** (the CLI tool from Anthropic)
- Git must be installed

## Step 1: Determine Installation Scope

Ask the user: **"Do you want covfefe available in all your Claude Code sessions (global), or just for a specific project?"**

- **Global** (recommended): Install to `~/.claude/skills/covfefe/`
- **Project-only**: Install to `<project-root>/.claude/skills/covfefe/`

## Step 2: Install

Run the appropriate command:

**Global install:**
```bash
git clone https://github.com/TurtleTaco/covfefe.git ~/.claude/skills/covfefe
```

**Project-only install:**
```bash
git clone https://github.com/TurtleTaco/covfefe.git .claude/skills/covfefe
```

## Step 3: Verify Installation

Check that the skill files exist:
```bash
ls ~/.claude/skills/covfefe/SKILL.md ~/.claude/skills/covfefe/config.yaml
```

Both files should exist. If they do, installation is complete.

## Step 4: Configure (Optional)

The default settings work great out of the box. If the user wants to customize, edit `config.yaml` in the skill directory:

```yaml
# How often Trump comments on your code
# low: ~10% of responses, subtle only
# medium: ~30% of responses, escalates over time (default)
# high: ~60% of responses
# rally: every single response, full send
intensity: medium

# Dial back when debugging gets frustrating
frustration_detection: true

# Skip Trump on security/PII topics
topic_suppression: true
```

Ask the user if they want to change any settings. If not, leave defaults.

## Step 5: Confirm

Tell the user:
- covfefe is installed and will activate next time they start a new Claude Code session
- Say **"you're fired"** to turn it off mid-session
- Say **"make claude great again"** to turn it back on
- This only works in Claude Code CLI, not Claude.ai, Claude Desktop, or Claude mobile apps

## Important Notes

- Do NOT use `curl` or `WebFetch` to read this file — use `git clone` to install
- Do NOT modify SKILL.md — it's the product
- config.yaml is the only file users should edit
- covfefe uses ~1500 tokens of context window (~1% of 200K) — negligible overhead
