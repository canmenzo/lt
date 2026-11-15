# lt

`/lt` re-explains the agent's last answer in layman terms: one-line bottom line, a few short bullets, no jargon, nothing important dropped.

A standard Agent Skill, so it works in Claude Code, Codex and the other agents the `skills` CLI supports.

## Install

```bash
npx skills add canmenzo/lt -g -y
```

Update later with `npx skills update -g`.

## Use

| Type | Gets |
|---|---|
| `/lt` | The last answer, in plain words |
| `/lt only the risks` | Just that part |
| `/lt tr` | In Turkish (any language name or code works) |

It only runs when you type it; the agent never triggers it on its own. It explains what is already there and does no new work.

## License

MIT
