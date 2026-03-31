# PM Interview Skill for Claude Code

A structured mock interview coaching skill for product management roles — from APM to CPO. It researches your target company, builds a candidate profile from your background, generates role-calibrated questions, runs realistic mock interviews, and coaches you toward interview-ready answers.

---

## What it does

1. **Orient** — Establishes role level, target company, focus areas, session mode (Interviewer vs Coach), and practice medium (voice recommended)
2. **Candidate Context** *(Phase 1.5)* — Ingests your resume, LinkedIn, GitHub, and past work to build a personalised profile and map your experience to 7 producteer story types
3. **Company Research** — Produces a Strategic Context Brief (5-7 insights) + Interview Process Map (round-by-round breakdown with prep weighting)
4. **Question Generation** — Creates 8–12 company-specific questions with deep dives for product sense, analytical, execution, and builder mindset rounds
5. **Mock Q&A** — Runs in two modes (see below); includes follow-up probes, pacing coaching, and per-answer scorecards
6. **Session Debrief** — Synthesises patterns across answers, delivers a hire-signal summary, and maintains a gap coverage tracker across sessions
7. **Exports** — Interview prep brief (.docx), answer bank (.md), or session-over-session progress report (.md)

---

## Two coaching modes

| Mode | When to use | How it works |
|---|---|---|
| **Interviewer Mode** *(recommended)* | Sessions 3+, pressure practice | Claude stays in character as an interviewer — no coaching preamble, realistic follow-ups, debrief only after the full pass |
| **Coach Mode** | Early prep, new question types | Frames each question with coaching context before you answer, then gives structured feedback |

For multi-session prep, the recommended arc is: Coach Mode for sessions 1–2, Interviewer Mode from session 3 onward.

---

## Role coverage

| Level | Question focus | AI fluency expectation |
|---|---|---|
| APM | Frameworks, user empathy, basic prioritisation, learning agility | Understands what LLMs and AI APIs can/can't do; can identify where AI fits without hand-waving |
| PM | Execution, metrics, cross-functional collaboration, delivery under ambiguity | Can scope AI features with realistic constraints (data, latency, cost); understands probabilistic UX |
| Senior PM | Product strategy, roadmap ownership, stakeholder influence, trade-off reasoning | Can articulate AI trade-offs (accuracy vs. speed, automation vs. human-in-the-loop, build vs. buy) |
| Group PM / Director | Multi-team leadership, org design, platform thinking, build vs. buy, M&A | Can set AI strategy for a product area; structure ML-PM collaboration |
| VP / CPO | Vision, company-level strategy, board communication, culture, talent | Can articulate company-level AI positioning and competitive dynamics of foundation models |

---

## Producteer story bank

After collecting your materials, the skill maps your experience to 7 high-signal story types increasingly expected at growth-stage and AI-native companies:

1. **"I built it to prove it"** — prototype-driven conviction
2. **"I killed it with data"** — evidence over opinion
3. **"I shipped AI and learned the hard way"** — AI in production
4. **"I made the build vs. buy call"** — AI capability sourcing
5. **"I bridged the gap"** — PM-to-engineering translation for AI
6. **"I used AI to work differently"** — personal workflow transformation
7. **"I navigated the responsible AI question"** — ethics in practice

Missing stories are flagged and built into question generation and mock Q&A.

---

## AI fluency as a cross-cutting lens

Across all question types, the skill evaluates whether you naturally consider AI as part of the product toolkit — scoping it realistically, naming constraints and failure modes, and reasoning about trade-offs including:

- Deterministic vs. probabilistic UX
- Automation vs. human-in-the-loop
- Personalisation vs. privacy
- Accuracy vs. latency vs. cost
- Generalisation vs. domain specificity
- AI transparency vs. simplicity

---

## AI-assisted problem solving

The skill also preps you for companies that allow or evaluate AI tool use during interviews (including Meta's AI product sense rounds). It coaches problem decomposition before prompting, prompt quality, critical evaluation of AI output, and narration of AI usage — and can simulate AI-assisted rounds where Claude evaluates both your answer and how you use it.

---

## Feedback structure

Each answer gets feedback across four areas:

- **What's landing** — specific strength and why it works
- **What's missing** — the exact gap and what the interviewer will think if it stays
- **Sharpening suggestions** — a concrete rewrite, not just a direction
- **Polished version** — written in your voice, in spoken cadence

## Scorecard

| Dimension | Rating |
|---|---|
| Strategic clarity | ✅ Excellent / ✅ Strong / ⚠️ Needs sharpening / ❌ Missing |
| Use of concrete examples | … |
| Metrics grounding | … |
| Trade-off reasoning | … |
| AI fluency | … |
| Structure & pacing | … |

---

## Session debrief & progress tracking

After every 4–5 questions, the skill delivers a session debrief covering:

- **Pattern recognition** — recurring strengths and gaps across answers
- **Hire signal summary** — an honest read on where you'd land in a real debrief
- **Top 3 actions** — one structural fix, one content gap, one delivery improvement

Progress is tracked in a **gap coverage tracker** by question type (product sense, strategy, metrics, behavioral, execution, estimation, builder). An **Answer Bank** accumulates your best polished answers as reference material for future sessions.

---

## How to use

1. Install [Claude Code](https://claude.ai/code)
2. Add this skill to your Claude Code skills directory
3. Start a session — the skill will ask for your role, company, focus areas, session mode, and practice medium
4. Optionally share your resume or LinkedIn URL for personalised coaching
5. Work through the phases at your own pace

---

## Coaching philosophy

1. **Lead with what's landing** before what's missing — name it specifically
2. **Distinguish instinct from structure** — "Your instinct is right — what's missing is the structure around it"
3. **Push for the concrete** — vague answers at Director level are disqualifying
4. **Failure stories are highest signal** — a candidate who only shares successes signals they haven't built anything hard
5. **Track the through-line** — coherence across answers separates Director candidates from Senior PMs
6. **Don't shortcut the thinking** — push candidates to complete the answer before filling the gap
7. **The interviewer tests three things at once** — surface question, what's underneath, and the meta-signal

---

## Contributing

Issues and pull requests welcome. The entire skill is defined in [`SKILL.md`](./SKILL.md).
