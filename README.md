# prior-art

Look for existing solutions before writing your own software tools or engineering workflows.

This skill looks for current evidence of real human use, not just newer tools. It searches for people who have had the same engineering problem in relevant communities like Reddit or Twitter, then checks important claims against primary sources, so you dont catastrophically miss an obvious solution because your agent has adhd and overthought the hell out of a simple question.

## Install

For Copilot, Claude Code, and other supported agents:

```bash
npx skills add Yuncun/prior-art --skill prior-art
```

The optional plugin package is named `prior-art`, matching the skill. It is not
the separate `research-evidence` package. Choose a standalone skill or a plugin
installation for a client, rather than loading both copies.

Copilot can also install the single file directly:

```bash
copilot skill add https://raw.githubusercontent.com/Yuncun/prior-art/main/skills/prior-art/SKILL.md
```

## License

MIT
