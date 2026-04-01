# Contributing to covfefe

The product is the prompt in `SKILL.md`. That's where the magic happens.

## What We Want

- **Better jokes.** Funnier reactions to coding events.
- **New event types.** What happens when someone runs `docker build`? When a migration fails? When they `npm audit`?
- **Evergreen templates.** More Trump-isms that work in coding contexts.
- **Bug reports.** If Trump breaks character or says something unfunny, that's a bug.

## How to Contribute

1. Fork the repo
2. Edit `SKILL.md` (that's the product)
3. Test it by installing your fork: `git clone YOUR_FORK ~/.claude/skills/covfefe`
4. Start a Claude Code session and code for 30+ minutes
5. Did you actually laugh? If yes, open a PR.

## Rules

- **PG-13.** No exceptions.
- **No real political commentary.** This is comedy about coding, not politics.
- **No personal attacks.** On real people, that is. Roasting code is encouraged.
- **Keep token budget under 2000.** The entire SKILL.md should stay lean.
- **Test your changes.** Run a real session. If it's not funny in practice, it doesn't ship.

## What NOT to Change

- `config.yaml` structure (breaking change for users)
- Kill switch phrases (users have muscle memory)
- The core personality (Trump narrating code as reality TV)

## The Real Test

Open a PR. We'll install your fork and code with it. If we laugh, it ships.
