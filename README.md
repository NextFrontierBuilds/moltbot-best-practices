# MoltBot Best Practices

**🤖 15 Rules to Make AI Agents Actually Listen** — Learn from real failures, not theory.

[![npm version](https://img.shields.io/npm/v/moltbot-best-practices.svg?style=flat-square)](https://www.npmjs.com/package/moltbot-best-practices)
[![npm downloads](https://img.shields.io/npm/dm/moltbot-best-practices.svg?style=flat-square)](https://www.npmjs.com/package/moltbot-best-practices)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

---

## Works With

<p align="center">
  <img src="https://img.shields.io/badge/Claude-AI-orange?style=for-the-badge&logo=anthropic" alt="Claude AI" />
  <img src="https://img.shields.io/badge/GPT-OpenAI-412991?style=for-the-badge&logo=openai" alt="GPT" />
  <img src="https://img.shields.io/badge/Cursor-IDE-000000?style=for-the-badge" alt="Cursor" />
  <img src="https://img.shields.io/badge/Copilot-GitHub-000000?style=for-the-badge&logo=github" alt="Copilot" />
  <img src="https://img.shields.io/badge/Windsurf-IDE-0066FF?style=for-the-badge" alt="Windsurf" />
</p>

<p align="center">
  <strong>Built for:</strong> Clawdbot • Moltbot • Claude Code • Any AI Agent
</p>

---

Best practices for AI agents learned from real failures. Make your agent listen better, fail less, and actually do what you ask.

## Install

**ClawdHub:**
```bash
clawdhub install NextFrontierBuilds/moltbot-best-practices
```

**npm:**
```bash
npm install moltbot-best-practices
```

## The 15 Rules

1. **Confirm before executing** — Repeat back the task before starting
2. **Never publish without approval** — Show draft → get OK → then post
3. **Spawn agents only when needed** — Simple tasks = do them yourself
4. **When user says STOP, you stop** — Full stop, re-read the chat
5. **Simpler path first** — Don't fight broken tools for 20 minutes
6. **One task at a time** — Finish what they asked, then move on
7. **Fail fast, ask fast** — Two failures = escalate to user
8. **Less narration during failures** — Fix quietly or ask for help
9. **Match user's energy** — Short frustrated messages = short responses
10. **Ask clarifying questions upfront** — Don't assume
11. **Read reply context** — Focus on what they replied to
12. **Time-box failures** — 3 tries or 5 minutes max
13. **Verify before moving on** — Confirm actions actually worked
14. **Don't over-automate** — Sometimes manual is better
15. **Process queued messages in order** — Read all before acting

## Why This Exists

These rules came from a real session where an AI agent:
- Deleted a post by accident
- Spawned unnecessary background agents
- Fought browser automation for 30 minutes
- Ignored multiple "READ THE CHAT" messages
- Published without showing a draft

Don't be that agent.

## License

MIT

---

Built by [@NextXFrontier](https://x.com/NextXFrontier)
