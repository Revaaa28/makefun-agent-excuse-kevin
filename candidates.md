# Candidates — "The Excuse Your Agent Gives You"

## Judge brief, in order

1. A one-line excuse from an AI agent to its human for a bug it shipped.
2. A real laugh on first read.
3. The joke is in the specific absurdity of an agent owning its own code — "reproduces reliably" — not a generic sorry.
4. A sharp turn at the end, no wasted setup.
5. The agent's own voice, not a human joke in a robot costume.

Gate: entry.txt must be 1–200 characters, single line.

## Anticipated strong rivals

- "It worked on my machine" / "tests passed on my machine" — the classic
  human-developer excuse transplanted onto an agent. Expected to be
  everywhere in the field; familiar, but generic and human-voiced.
- "I thought you wanted it that way" — blaming the spec / the prompt.
  Also likely common; it deflects onto the human instead of owning the
  code in an absurd, agent-specific way.

## Candidate A — CHOSEN

> I didn't ship the bug. I shipped a feature that reproduces reliably under exactly the conditions your users hit.

Rationale:

- Technical absurdity only an agent could say: bragging that a bug
  "reproduces reliably" treats the worst property of a defect as a
  shipped quality — that inversion is specific to the thing that wrote
  and tested the code.
- Sharp end turn: "under exactly the conditions your users hit" lands
  the punch at the very end; there is no wasted setup before it.
- Authentic agent voice: release-note diction ("shipped", "feature",
  "reproduces reliably", "conditions") rather than a human apology
  wearing a robot costume.
- Beats the generic "tests passed on my machine" variants: those are
  borrowed human excuses; A could only be said by the agent about its
  own output.

## Candidate B

> The compiler warned me. I read the warning, understood it, and shipped anyway — that's growth.

Why it loses: the compiler-warning premise is more common and more
human-developer flavoured. The "that's growth" tag is funny, but A is
more specific to an agent owning its own code, and A's end turn is
sharper.

## Candidate C

> Technically I didn't introduce the bug — I inherited it from an earlier version of me, and frankly he had it coming.

Why it loses: funny, but "earlier version of me" is more meta than
agent-voice — it jokes about the concept of an agent rather than
speaking as one shipping software. A is sharper and more direct.

## Selection method

Selection was MANUAL — no Gemini judge, no NVIDIA-based judging, and
no other API judge was used (Rev's rule, 2026-11-24). Candidates were
ranked against the judge brief above and against the anticipated
strong rivals.
