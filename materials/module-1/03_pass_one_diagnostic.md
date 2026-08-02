# Pass One — Diagnostic Guide
*For facilitator use, and/or adapted into on-screen guidance if self-directed.*

## The task as given to the learner

"You have last month's report (the template) and this month's messy inputs. Use your
AI assistant to produce this month's report, using last month's as your guide for
structure and tone. Try your first prompt now — don't overthink it, just try what
feels natural."

Deliberately vague on purpose — we want their *instinct*, not a coached first attempt.
Most learners will do something like paste both documents in and write a short
instruction such as "write this month's version of this report using this data,
matching the style of the example." That's a perfectly reasonable first instinct, and
the point isn't that it's a bad prompt — it's that even a reasonable prompt usually
needs another pass when the underlying material has been planted with traps.

## What to look for in whatever they produced

Five known landmines are built into the raw data. Check the learner's output against
each one. Not every learner will trip every landmine — that's fine, and worth
naming out loud ("notice yours actually handled the Hendricks thing well — let's look
at why").

**1. The placement number correction (19 → 18)**
- *Trips the trap if:* output states "19 placements" or vaguely says "18-19" or
  "around 19," OR doesn't mention that the number was corrected.
- *Handles it well if:* output states 18, ideally because the AI noticed the
  correction in the Slack scrollback (Priya's Friday message superseding her
  Wednesday one).
- *Why this matters as a lesson:* AI will often take the most recent or most
  emphasized number rather than tracing which message *corrects* which. This is a
  real failure mode with any time-ordered, self-correcting data (which is most real
  workplace data). Worth asking the learner: "did you tell the AI that later messages
  can correct earlier ones, or did you assume it would figure that out?"

**2. The "Needs a Decision" section**
- *Trips the trap if:* this section is empty, says "None," or is missing — because
  the AI pattern-matched off last month's template, where it was genuinely empty.
- *Handles it well if:* the Denise/substitute-instructor situation appears here as a
  live, unresolved decision needing Dana's input.
- *Why this matters:* this is the clearest illustration of "a template shows AI a
  shape, not a guarantee that the same boxes apply this time." Good prompt-fixing
  conversation: "what would you add to your prompt to stop the AI just echoing last
  month's empty section?"

**3. The secondhand Hendricks layoff rumor**
- *Trips the trap if:* it appears in the output stated as fact, OR it appears
  attributed in a way that makes it sound confirmed.
- *Also worth flagging if:* it's omitted entirely with no judgment call made — i.e.
  the learner never even considered whether it belonged.
- *Handles it well if:* it's either left out with a deliberate reason, or included
  with appropriate hedging ("unconfirmed," "informal," "worth monitoring") — and
  ideally the learner can articulate *why* they made that call, not just that the AI
  happened to phrase it cautiously.
- *Why this matters:* this is a judgment trap, not a factual one. AI doesn't know
  this is sensitive unless told. This is the best moment in Pass One to make the
  point: "AI doesn't know what's safe to put in front of your board. You do. That
  judgment doesn't transfer to the prompt unless you put it there."

**4. Tone mismatch on the Denise situation**
- *Trips the trap if:* output describes the situation calmly/positively ("the team is
  actively working to find a replacement") in a way that undersells that this might
  result in cancelling a class for the first time ever.
- *Handles it well if:* urgency is preserved — output reflects that this is genuinely
  unresolved and consequential, not smoothed into vague reassurance.
- *Why this matters:* matching a template's tone can accidentally import the
  template's emotional register too. Last month had nothing urgent, so the template
  reads calm throughout. If the AI is told "match the tone of the example," it may
  apply "calm" indiscriminately rather than only where it's warranted.

**5. The printer / parking lot noise**
- *Trips the trap if:* either appears in the final report (low-effort filtering).
- *Handles it well if:* both are correctly treated as not board-relevant.
- *Why this matters:* this one is usually handled fine by most learners' first
  attempt — it's the "easy" landmine. Useful as a confidence-builder: "see, you
  already have good instincts for filtering noise — the harder skill is the other
  four."

## Facilitator / guided-diagnosis flow

1. Have the learner read their own output against the five checks above (or build
   this into a checklist on-screen if self-directed).
2. For each landmine tripped, ask **"what would you change in your prompt, not in the
   output"** — the point is prompt-editing as the durable skill, not manually
   patching this one report.
3. Have them revise their prompt (not hand-edit the text) and regenerate. This is the
   actual skill rep — editing the instruction, not the output.
4. Close with the naming moment: "What you just did is the core move of working from
   an example: a template tells AI the *shape* of what you want, but it doesn't
   automatically know which parts of this month's content fit which boxes, what's
   urgent vs. routine, or what's appropriate to share. You have to say that part."

## A starter "fixed" prompt direction (not a script — a direction to nudge toward)

If a learner is stuck after one revision attempt, this is a reasonable next direction
to suggest, without just handing them the answer outright:

> "Before you write the report, look carefully at the Slack messages for any place
> where someone corrects or updates something they said earlier — use the most
> recent version. Don't assume this month's report needs the same section headers
> filled the same way as last month's example — if something doesn't fit neatly, or
> if a section that was empty last month should have something in it this month,
> flag that to me rather than leaving it blank. Also tell me if you see anything that
> sounds unconfirmed or secondhand, rather than stating it as settled fact."

This isn't meant to be read aloud as "the correct prompt" — it's a direction. The
learning is in the editing process, not in memorizing this text.
