# /roundtable-inner-team

Your head is not one voice. It's a committee.

A Claude Code command that facilitates your **Inner Team** — the competing voices inside you that make hard decisions feel impossible. Based on Friedemann Schulz von Thun's [Inner Team model](https://en.wikipedia.org/wiki/Friedemann_Schulz_von_Thun), it gives each voice a seat at the table, maps the tensions between them, and builds a resolution that doesn't pretend the trade-offs don't exist.

Not therapy. Not coaching. A structured process that turns "I don't know what to do" into "here's what I'm doing and why."

## How it works

```
You describe a dilemma
         ↓
You name your inner voices (3-7)
         ↓
Each voice speaks: their view, needs, fears, proposed solution
         ↓
Tension map: where do the voices pull in opposite directions?
         ↓
Integrated resolution: concrete action plan that names what gets priority and what gets sacrificed
         ↓
Next steps you can act on tomorrow
```

## Install

```bash
cp commands/roundtable-inner-team.md ~/.claude/commands/
```

Then in any Claude Code session:

```
/roundtable-inner-team
```

Or pass the dilemma directly:

```
/roundtable-inner-team [Describe situation, the more detail the better] Voices: The CEO, The Friend, The Mentor, The Pragmatist.
```

## Output structure

```
# Inner Team Roundtable: [Short title]

## 1. The Dilemma
## 2. The Inner Team Speaks
### The CEO
### The Friend
### ...
## 3. Tension Map
## 4. Integrated Resolution
## 5. Next Steps
```

## What makes this different

- **No sugarcoating.** Each voice says what it actually thinks — especially the uncomfortable parts.
- **No voice is dismissed.** Even a recognized bias gets heard. It's contextualized, not silenced.
- **No middle-ground mush.** The resolution makes actual calls and names what gets lost.
- **Quieter voices get amplified.** The ones you usually override often carry the real insight.
- **Action-oriented.** Every next step starts with a verb and maps to a specific voice's need.

## The Inner Team model

Friedemann Schulz von Thun's "Inneres Team" proposes that each person contains multiple inner voices with their own perspectives, values, and needs. In difficult decisions, these voices create internal conflict — not because something is wrong with you, but because the situation genuinely pulls in multiple directions.

The skill casts you as the **team leader** of your inner team. The goal is not to silence voices or find a bland average, but to hear each one fully and then make an integrated decision as the leader who holds the whole picture.

## Companion skills

- [/roundtable-review](https://github.com/matlugert/roundtable-review) — Multi-expert critique to find what's wrong with an artifact.
- [/roundtable-perspectives](https://github.com/matlugert/roundtable-perspectives) — Multi-stakeholder synthesis to find shared ground across perspectives.

## Author

[Matthias Lugert](https://github.com/matlugert)

## License

MIT
