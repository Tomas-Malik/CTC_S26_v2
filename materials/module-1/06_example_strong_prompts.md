# Strong Example Prompts (Facilitator Reference)
*Ties to slide 11 (Pass One activity), slide 14 (Pass Two activity), and the
skeletons on slide 23. Use these as your own calibration, to answer "what does a
good version of this actually look like?", or to read aloud/project **after**
learners have tried their own first — not as a starting script to hand out before
they've attempted it themselves.*

---

## Pass One: example-anchored prompting

**Context:** learner has last month's report (`02_predecessor_template.md`) and
this month's raw inputs (`01_messy_inputs.md` / the three companion docs).

### A strong first prompt

> I'm writing this month's version of a monthly program update for my manager
> Dana. I'm giving you last month's report as a structural example, and this
> month's raw inputs below it.
>
> Match last month's structure and professional tone, but:
> - If any message corrects or updates something said earlier in the week (for
>   example, a number gets revised in a later message), use the most recent
>   version — not the first one you come across.
> - Don't assume this month's report needs the same sections filled the same way
>   last month's did. If something is genuinely unresolved and needs Dana's
>   input, put it under "Needs a Decision," even if that section was empty last
>   month.
> - If anything sounds unconfirmed, secondhand, or like a rumor, flag it
>   explicitly as such rather than stating it as settled fact.
> - Keep the professional tone, but don't apply "calm" uniformly — if something
>   this month is genuinely urgent or unresolved, let the report reflect that.
> - Leave out anything that isn't relevant to Dana or a board audience (internal
>   logistics, etc.).
>
> Last month's report:
> [paste `02_predecessor_template.md`]
>
> This month's raw inputs:
> [paste the Slack scrollback, Marcus's email, and Priya's notes]

### Why this prompt works

Every line maps to one of the five landmines in `03_pass_one_diagnostic.md`:
correcting earlier facts (the 19→18 trap), not assuming empty sections stay empty
(the "Needs a Decision" trap), flagging unconfirmed information (the Hendricks
rumor), preserving real urgency instead of flattening tone (the Denise item), and
an explicit filter instruction (printer/parking lot — usually the easy one
anyway).

Worth naming out loud to learners: this prompt is *longer* than their first
instinct, and that's the point. A one-line prompt asks AI to guess your judgment
calls. This one makes the judgment calls explicit instead of hoping AI infers
them.

---

## Pass Two: structure-first prompting

**Context:** learner has the same raw inputs, but no template — first the
structuring conversation, then generation.

### A strong opening prompt (structure conversation)

> I'm a team lead at a nonprofit, and I need to send my manager Dana a monthly
> program update by end of day — but I don't have a template to work from this
> time. Before we write anything, I want to figure out the right structure
> together.
>
> Here's who's reading this and why: Dana scans these updates to see what needs
> her decision versus what's routine good news, ahead of a board packet going out
> tomorrow.
>
> Given that, what sections would make sense for a report like this? I want
> structure that separates what needs action from what's just informational, and
> leaves room for things that are genuinely unresolved — not categories that
> assume everything wraps up neatly.
>
> Don't generate the report yet. Once we agree on a structure, I'll share this
> month's raw inputs so we can check whether the structure actually holds up
> against the real data before you write anything.

### A strong follow-up prompt (after the structure is agreed, before generating)

> Here's the real input — Slack scrollback, an email, and a colleague's call
> notes, all from this week. Before generating the report: does the structure we
> landed on actually fit this data, or does anything here not have an obvious
> home in it? If something doesn't fit, tell me rather than forcing it into the
> closest category.
>
> [paste the raw inputs]

### Why this works

This maps to the three checks in `04_pass_two_diagnostic.md`: giving AI context
about the reader before asking for structure, deliberately building in room for
unresolved things rather than only positive-framing categories, and — critically
— checking the structure against the real data *before* generating, rather than
designing in the abstract and forcing the inputs to fit afterward.

The two-step shape (agree on structure, *then* share data, *then* generate) is
itself the lesson. A learner who pastes everything in at once and asks for "a
report" has skipped the structuring conversation entirely, even if they used
thoughtful language.

---

## How this maps to the slide 23 skeletons

Slide 23 gives learners two portable skeletons to take with them. These prompts
above are those skeletons filled in for the Riverside scenario — useful if a
learner wants to see the abstract skeleton made concrete:

- **Skeleton 1 (have a template)** → the Pass One prompt above.
- **Skeleton 2 (no template)** → the two-step Pass Two prompts above.

If a learner is stuck mid-activity, walking from their attempt toward the
relevant skeleton is usually more useful than handing them this document
outright — the durable skill is *writing* a prompt like this, not reading one.
