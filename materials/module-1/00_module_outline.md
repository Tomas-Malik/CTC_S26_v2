# Module 1: From Mess to Message
### Turning Everyday Inputs into Reports AI Can Actually Help With

**Format:** Self-paced website with live facilitator support
**Target length:** 100–130 minutes
**Audience:** Mixed white-collar employees, no prior AI experience assumed
**Companion files:** `01_messy_inputs.md`, `02_predecessor_template.md`,
`03_pass_one_diagnostic.md`, `04_pass_two_diagnostic.md`

**Tool note:** All prompt language below is written tool-agnostic ("your AI
assistant"). Once the delivery tool is confirmed, do a find-and-replace pass to name
it specifically and, if useful, add real screenshots of that tool's interface.

---

## The throughline (keep this visible to facilitators throughout)

Everything in this module teaches one transferable distinction:

> **When you have an example to show AI, use it deliberately — don't just hand it
> over and hope. When you don't have an example, build the structure with AI as a
> separate step before asking it to generate anything.**

Both passes use the *same* messy raw material. The only thing that changes is which
of those two moves the learner is practicing. If a learner only remembers one
sentence from this module, it should be the throughline above — everything else is in
service of making that sentence land through experience rather than being told.

---

## Section 1 — Setup (10–15 min)

**Goal:** Establish the scenario, the stakes, and surface the learner's untouched
instincts before any AI framing.

- Present the scenario: they're a team lead at a mid-size nonprofit, just back from a
  few days off, manager needs the monthly update by end of day for a board packet.
- Show the raw messy inputs (`01_messy_inputs.md`) in full — Slack scrollback, the
  email from Marcus, Priya's meeting notes.
- **Before introducing AI at all**, ask: "If you had to do this the way you'd
  normally do it — no AI — what would your first move be?" Let a few answers surface
  (skim and summarize each person, start drafting in a doc, etc.). Don't critique
  these; they're a baseline for contrast later, not a thing to fix.
- Frame the two passes coming up: "You're going to do this twice. First with a
  template from last month. Then again, pretending that template never existed."

## Section 2 — Pass One: You have a template (25–30 min)

**Goal:** Teach example-anchored prompting through a live, unscripted first attempt
and guided diagnosis.

1. Reveal `02_predecessor_template.md` — last month's report. Let them read it.
2. Task: "Use your AI assistant to produce this month's version, using this as your
   guide, from the messy inputs you already have. Try your first prompt now — don't
   overthink it."
3. Let them run it live. This is unscripted — you don't know what they'll get.
4. Run the diagnosis using `03_pass_one_diagnostic.md` — the five landmines
   (placement correction, empty "Needs a Decision" section, the Hendricks rumor,
   tone mismatch on Denise, printer/parking-lot noise). Check their output against
   each, not against one fixed "correct" version.
5. Have them **revise the prompt** (not hand-edit the output) and regenerate.
6. Name the lesson explicitly: a template shows AI the *shape*, not which content
   goes where, what's urgent, or what's safe to share. That judgment has to be in the
   prompt.

## Section 3 — Pass Two: No template (25–30 min)

**Goal:** Teach structure-first thinking through the same live-attempt-and-diagnose
pattern, with a built-in fork depending on whether they jump to generation or
structure first.

1. Tell them to set the template aside: "Pretend you're brand new, nobody left you an
   example. Same messy inputs. Figure out what should even go in this report before
   you generate anything."
2. Let them run it live — genuinely unscripted on whether they structure first or
   generate first.
3. Use `04_pass_two_diagnostic.md` to diagnose whichever path they took:
   - If they generated first: compare against what a structuring-first attempt
     produces. The side-by-side comparison is the lesson.
   - If they structured first: check whether the structuring conversation gave AI
     real context (who's reading, why), left room for unresolved/ambiguous items,
     and was checked against the actual messy data before generating.
4. Reinforce explicitly: there is no single right structure. Different valid
   structures are a feature of this exercise, not noise to converge away.
5. Name the lesson: without an example, AI is still useful — but only as a
   structuring partner *first*, separately from generation.

## Section 4 — Bridge: naming the pattern (10 min)

**Goal:** Pull the lesson out of the specific story so it survives outside this one
report.

- Facilitator-led discussion (or reflective writing prompt if self-paced):
  "What did Pass One and Pass Two have in common, despite looking different?"
- Land on the throughline explicitly. Make it sound like a tool they'll reach for
  again, not a moral of this particular story: *"Bring an example when you have one
  and use it deliberately. Build the structure with AI when you don't, before you
  generate anything."*
- Optional: briefly preview that this exact pattern applies to other recurring work
  (meeting prep, recurring client updates, etc.) — sets up future modules without
  committing to them yet.

## Section 5 — Bring your own (20–30 min) — *this is the evaluable part*

**Goal:** Transfer the skill to the learner's real work, and produce something
assessable.

- Two paths, learner's choice:
  - **Real data:** bring an actual recurring or templated task from their own job —
    a real report, update, or summary they produce — and run through whichever of
    Pass One / Pass Two fits (do they have a template or not?).
  - **Safe fallback:** if they're not ready to use real work data, provide a second
    built-in messy scenario (different domain — e.g. a small business inventory/
    sales update, or a school administrator's parent-communication digest — so it
    doesn't just feel like a re-skin of the nonprofit story) as a like-for-like
    substitute.
- This is the part to actually evaluate: did they bring an example deliberately or
  hand it over passively? Did they structure first when no example existed? Did they
  catch the kind of judgment traps (sensitive info, false resolution, stale data)
  this module trained them to look for?
- Capture this output (however the website is built to do so) for whoever's giving
  feedback afterward.

## Section 6 — Wrap (5–10 min)

- Quick recap of the throughline.
- Hand them a short keep-able cheat sheet: two prompt skeletons —
  1. **Example-anchored skeleton:** "Here's an example of [output type]. Here's
     [messy input]. Use the example for structure and tone, but check: does
     everything from this month's input actually fit the same categories, or does
     something need its own space? Flag anything uncertain, corrected, or sensitive
     rather than stating it as settled."
  2. **Structure-first skeleton:** "I need to produce [output type] for [specific
     reader] who cares about [specific thing]. Before generating anything, help me
     figure out what structure would actually serve that. Here's the real input I'll
     be working from — check the structure holds up against it before we finalize."
- Note (if relevant): this scenario is one of several this pattern applies to;
  flag the meeting-prep variant as a likely next module if this pilot lands well.

---

## Notes for whoever evaluates Section 5 submissions

Use the same lens as the diagnostic guides, generalized:

- **Did they use an example deliberately, or hand it over and hope?** (Pass One
  skill, applied to their own task.)
- **Did they structure before generating, when no example existed?** (Pass Two
  skill, applied to their own task.)
- **Did they catch the kind of traps this module trained for** — stale/corrected
  information, sensitive content that shouldn't be stated as fact, false resolution
  of things that are genuinely unresolved, irrelevant noise?
- **Could they articulate *why* they made a structural or content choice**, not just
  that the AI's output happened to look fine?

The goal of feedback at this stage is the same throughline, applied to their actual
job: did the skill transfer, or did they revert to "paste everything in and hope"
once the training-wheel scenario was gone?
