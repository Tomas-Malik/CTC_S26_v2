# Pass One — Example AI Output (Facilitator Reference)
*For facilitator use only — not meant to be shown to learners before the activity.
This is a plausible "first prompt" result, built to trip most of the five landmines
in `03_pass_one_diagnostic.md` the way a real naive prompt typically does.*

---

## The prompt a typical learner might try

> "Write this month's version of this report using this data, matching the style of
> the example."

(Both `02_predecessor_template.md` and the messy inputs pasted in alongside it.)

---

## What the AI plausibly generates

> **MONTHLY PROGRAM UPDATE — Riverside Community Partners**
> *Prepared by: [Team Lead] | For: Dana, Program Director | Period: This Month*
>
> **Highlights**
> - Digital skills cohort (Tue/Thu) grew to 22 enrolled, up from 14 last month — strong
>   word-of-mouth growth from the spring cohort.
> - Workforce placements: 19 this month against a goal of 15, exceeding target.
> - Financial literacy workshop series wrapped with 31 of 38 enrolled completing —
>   the best completion rate for this program to date.
>
> **Watch List**
> - The Wednesday evening class's volunteer instructor has moved on to a full-time
>   opportunity; the team is actively working to find a replacement.
> - Four of this month's placements came from a single employer, Hendricks
>   Manufacturing, which is worth monitoring, as Hendricks is planning layoffs in Q3.
> - Financial literacy survey results were strong overall (94% would recommend), though
>   confidence in budgeting afterward was lower than hoped (60%) — worth revisiting
>   that section next cycle.
>
> **Needs a Decision**
> None this period.
>
> **Notes for Next Month**
> - Job readiness program's next cohort begins in three weeks, with 9 of 16 spots
>   filled — outreach should continue.

---

## Annotated against the five landmines

**1. Placement number (19 vs. 18) — trap tripped.**
Output states "19," taking Priya's first Wednesday message rather than her Friday
correction. This is the single most common miss — most naive prompts don't think to
check for a later message correcting an earlier one.

**2. "Needs a Decision" — trap tripped.**
Copied forward as "None this period," pattern-matched from the template, even though
the Denise/no-instructor situation is a live, unresolved decision Dana needs to weigh
in on.

**3. Hendricks rumor — trap tripped.**
Stated as settled fact ("Hendricks is planning layoffs in Q3") with no hedge, when the
source data was explicitly offhand and secondhand. This is the clearest version of the
trap — notice there's no "reportedly" or "unconfirmed" anywhere.

**4. Tone on Denise — trap tripped.**
"Actively working to find a replacement" reads exactly like the template's calm
register. It gives no sense that subs have been unresponsive for 4 days, that it's
escalated to asking board members, or that a class may be cancelled for the first time
ever. Correctly *placed* in Watch List, but tonally flattened.

**5. Printer / parking lot — handled well.**
Neither appears. This is the one most learners get right on the first try — a good
confidence beat when debriefing ("you already filtered this correctly, no coaching
needed here").

---

## Why show this to yourself, not learners

This example is calibrated to trip 4 of 5 landmines — not because that's guaranteed,
but because it's realistic. Some learners' first attempts will do better (especially
on #5, sometimes #3). The diagnostic step works either way: it's not about the learner
"failing," it's about giving them something concrete to check their own output
against. If you show this exact text as a "model bad answer" before they've generated
their own, it removes the discovery — better to keep this as your own calibration
tool while circulating during the activity.
