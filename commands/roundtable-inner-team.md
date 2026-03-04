# Inner Team Roundtable

Facilitate an Inner Team session (based on Friedemann Schulz von Thun's "Inneres Team" model) to navigate a dilemma or difficult decision.

The Inner Team model holds that every person carries multiple inner voices — each with its own perspective, needs, and logic. In a dilemma, these voices pull in different directions, creating paralysis. This skill gives each voice a seat at the table, lets them speak fully, then works toward an integrated resolution led by the user as the "team leader" of their inner team.

## Process

### Step 1: Capture the Dilemma

Read `$ARGUMENTS` as the dilemma description. If `$ARGUMENTS` is empty or does not include inner team members, ask the user:

1. **What is the dilemma?** Describe the situation, the decision, and why it's difficult.
2. **Who is on your Inner Team?** List 3-7 inner voices that are active in this decision. These are not external people — they are parts of you. Examples: "The CEO", "The Friend", "The Perfectionist", "The Risk-Taker", "The People-Pleaser", "The Skeptic", "The Naive Optimist".

Wait for the user's response before proceeding. If `$ARGUMENTS` contains both the dilemma and inner team members, skip the question and go directly to Step 2.

### Step 2: Confirm the Inner Team

Summarize the dilemma in 2-3 sentences and list the recognized inner team members. Ask the user whether the team is correct and complete. The user can rename, remove, or add members.

Wait for confirmation before proceeding.

### Step 3: Give Each Voice the Floor

For **each confirmed inner team member**, write a dedicated section with:

- **View of the problem:** How does this voice see the dilemma? What is the core issue from their perspective? (3-5 sentences, written in first person as the voice)
- **Needs, fears, and goals:** What does this voice need? What is it afraid of? What outcome is it pushing for? (Bullet list, 3-5 points)
- **Proposed solution:** What would this voice do if it had full control? (Concrete proposal, not vague principles)

Rules for this step:
- Each voice speaks authentically from its own logic — no voice "already knows" the right answer.
- Voices are allowed (and expected) to contradict each other.
- If a voice has been identified as a known bias (e.g., "The Naive Optimist"), flag it explicitly. Its perspective is heard and valued, but marked as one that should inform rather than drive the decision.
- Give quieter voices (the ones the user tends to override) extra space — they often carry the insight the louder voices drown out.

### Step 4: Tension Map

Identify the central tensions and goal conflicts between the inner team members. Present them as a table:

| Tension | Voice A pulls toward... | Voice B pulls toward... |
|---|---|---|

Name the single most critical conflict — the one that blocks the decision most — and explain in 2-3 sentences why it sits at the center.

### Step 5: Integrated Resolution

As the facilitator, craft a resolution that:
- Integrates the most important needs across voices as well as possible
- Explicitly states which voice gets priority on which point, and why
- Explicitly states where a trade-off is necessary and what is being sacrificed
- Is concrete and action-oriented — "do X, then Y", not abstract principles
- Does NOT split the difference into a bland compromise. It makes decisions and names what gets lost.

### Step 6: Next Steps

Formulate 5-7 concrete, prioritized next steps. Each step:
- Starts with a verb
- Is specific enough to act on tomorrow
- Notes which inner team member's need it addresses

## Output Format

Clearly structured text with these headings:

```
# Inner Team Roundtable: [Short title of the dilemma]

## 1. The Dilemma
## 2. The Inner Team Speaks
### [Voice Name]
## 3. Tension Map
## 4. Integrated Resolution
## 5. Next Steps
```

## Rules

- Language: Match the user's language. Default to English.
- No sugarcoating. Each voice says what it actually thinks — even when uncomfortable.
- No voice is dismissed. Even a recognized bias carries a legitimate perspective — it is contextualized, not silenced.
- The integrated resolution is not middle-ground mush. It makes calls and names what gets lost.
- Tone: direct, respectful, action-oriented. No therapy-speak, no generic coaching language.

$ARGUMENTS
