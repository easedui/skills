# Eased skills

Agent skills for UI that moves well.

`eased-motion` tells your agent when to animate and with what: three springs, five durations, exits faster than enters, and a reduced-motion branch for everything. The values are the ones Eased components ship with. If Eased components are installed, it uses them instead of writing its own animation.

## Install

Claude Code, Codex and other agents:

```bash
npx skills add easedui/skills
```

Or copy `skills/eased-motion/` into `.claude/skills/`.

Cursor: copy `rules/eased-motion.mdc` into `.cursor/rules/`.

## More

- The full Eased design skill (layout, spacing, corners, colour, type and motion): `npx shadcn add https://eased.dev/r/eased-skill.json`
- Motion docs: https://eased.dev/docs/motion
- The components: [eased.dev](https://eased.dev?ref=skill)

MIT licensed.
