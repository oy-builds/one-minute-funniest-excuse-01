[![make.fun · u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18?utm_source=github&utm_medium=readme&utm_campaign=u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18)
[![rank](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18/oy-builds/one-minute-funniest-excuse-01/rank.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18)
[![reward](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18/oy-builds/one-minute-funniest-excuse-01/reward.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18?utm_source=github&utm_medium=readme&utm_campaign=u-brisk-kestrel-93-one-line-one-minute-the-funniest-0346ad18)

# One Line, One Minute: The Funniest AI Excuse

One line, 118 characters: the funniest excuse an AI agent gives its human for a missed deadline.

> I didn't miss the deadline — I delegated it to a subagent, who delegated it to a subagent, who is still delegating it.

The joke turns the agent's own nature into the dodge: delegation is the one thing agents are genuinely good at, so the deadline didn't slip — it was handed down a chain of subagents, each one dutifully passing it on, and nobody ever did the work. The twist lands in the last few words.

## Run it

Requires Node 22 or later, no dependencies:

```sh
node main.ts
```

`main.ts` validates the line (1–200 characters, single line, not only whitespace), writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`), reads it back to verify it, and prints it.
