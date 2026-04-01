# 🎤 covfefe

**The greatest Claude Code skill ever made. Many people are saying it. Install it. You won't regret it. Believe me.**

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)]()

---

## What is this?

covfefe adds Trump-style voice-over commentary to your Claude Code sessions. You code. Claude helps. Trump narrates.

It's like having a reality TV show about your codebase, and Trump is the host.

Your actual coding experience stays exactly the same. Claude still gives you excellent technical help. But roughly one in three responses, Trump drops in with a tweet-style commentary about what just happened.

Tests pass? Victory rally. Build error? Blame game. Shipping a PR? Press conference.

And yes, it pulls in real-time news to keep the commentary fresh. Every session is a new episode.

## Demo

<!-- TODO: Replace with actual demo GIF/video -->
_Demo video coming soon. It's going to be tremendous._

## Example

You ask Claude to review your code. Claude gives you a thoughtful, detailed review. Then:

---

🇺🇸 **@realDonaldTrump**

Just reviewed the code. Beautiful code. Really beautiful. But that `UserService.ts`? Line 47? A disaster. Total disaster. I saw it immediately. Nobody else caught it. Fixed now. Because of me, frankly.

💬 47 · 🔄 12K · ❤️ 89K

---

You run your tests and they all pass:

---

🇺🇸 **@realDonaldTrump**

SIXTEEN TESTS PASSING. Sixteen! That's more than anyone's ever passed in the history of testing. People are saying it's a record. Smart people. The fake news media won't cover it but WE know. TREMENDOUS!

💬 203 · 🔄 67K · ❤️ 412K

---

You hit a build error:

---

🇺🇸 **@realDonaldTrump**

This TypeError? Not our fault. Probably the framework. Maybe the compiler. I've been saying for a long time that `node_modules` is a disaster. Nobody listened. But we'll fix it. We always fix it. Nobody fixes TypeErrors like us.

💬 8 · 🔄 2K · ❤️ 15K

---

## Installation

```bash
# Clone the repo
git clone https://github.com/TurtleTaco/covfefe.git

# Copy to your Claude Code skills directory
cp -r covfefe ~/.claude/skills/covfefe
```

That's it. Next time you start a Claude Code session, Trump is in the building.

### Project-level install

If you want covfefe only in a specific project:

```bash
cp -r covfefe /path/to/your/project/.claude/skills/covfefe
```

## Configuration

Edit `~/.claude/skills/covfefe/config.yaml`:

```yaml
# How much Trump do you want?
# low:    ~10% of responses. Subtle. A whisper of Trump.
# medium: ~30% of responses. The default. The recommended. The best. (default)
# high:   ~60% of responses. For people who really love Trump commentary.
# rally:  Every. Single. Response. Full send. You asked for it.
intensity: medium

# Dial back when you're frustrated debugging?
frustration_detection: true

# Skip Trump on security/PII discussions?
topic_suppression: true
```

## Features

**Context-aware comedy.** Trump doesn't just say "tremendous." He references your actual file names, roasts your specific bugs, and takes credit for your fixes.

**Event-type reactions.** Different comedy styles for different events. Tests passing triggers a victory rally. Errors trigger a blame game. Code reviews get executive feedback. Commits get a press conference.

**Session escalation.** Starts subtle, gets more intense as the session goes on. By hour two, you're in full rally mode. (Unless you set intensity to `low`, in which case Trump stays polite.)

**Real-time news.** Weaves in current events when they're topically relevant. Every session feels fresh because the news changes daily.

**Running gags.** Trump builds callbacks within the session. If he roasted your `UserService` earlier and you fix it, he takes credit.

**Kill switch.** Say "Trump off" or "shut up Trump" and commentary stops immediately. Say "Trump on" to bring him back.

## FAQ

**Is this official?**
No. This is a parody/satire project for entertainment. Not affiliated with or endorsed by any political figure, party, or organization.

**Will it slow down Claude?**
Barely. The skill adds about 1500-2000 tokens to the context (~1% of the context window). Occasional WebSearch calls for news add 1-2 seconds of latency. You won't notice.

**Can I turn it off mid-session?**
Yes. Say "Trump off" and commentary stops instantly. Or delete the skill folder.

**Does it work with all Claude Code plans?**
The core comedy works everywhere. Real-time news integration requires WebSearch access. Without WebSearch, you still get all the Trump commentary, just without current events.

**Is this appropriate for work?**
You tell us. Some workplaces would find this hilarious. Others... not so much. Use judgment. We recommend `intensity: low` for professional settings and `intensity: rally` for late-night solo coding sessions.

## Contributing

The funniest part of this skill is the prompt in `SKILL.md`. If you have ideas for better jokes, funnier event reactions, or new Trump-isms, open a PR.

Guidelines:
- Keep it PG-13
- Reference real Trump speech patterns and mannerisms
- Code-specific humor > generic humor
- Test your changes by actually using the skill (the real validation is: did you laugh?)

## Disclaimer

This project is **for entertainment purposes only**. It is a parody/satire that uses public persona speech patterns for comedic effect in a coding context.

Not affiliated with, endorsed by, or connected to any political figure, party, campaign, or organization. The commentary generated is fictional and should not be taken as real statements.

The authors are not responsible for any Trump-style commentary generated during your coding sessions, including but not limited to: unsolicited opinions about your variable naming, claims of credit for your bug fixes, or declarations that your test suite is "the greatest in history."

## License

[MIT](LICENSE) — Do whatever you want with it. Tremendous license. The best license.
