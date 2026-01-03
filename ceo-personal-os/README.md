# CEO Personal OS

**A private productivity system for founders, CEOs, and operators who want clarity without bureaucracy.**

This is not software. This is a system — a set of practices, prompts, and frameworks designed to help you reflect, decide, and move forward with intention. Everything here runs in plain text. No dashboards. No analytics theater. Just you, your thoughts, and a structured way to think clearly about what matters.

---

## What This System Does

- **Daily check-ins** (5 minutes) — track energy, wins, friction, and tomorrow's priority
- **Weekly reviews** (20 minutes) — separate signal from noise, spot patterns, adjust course
- **Quarterly reviews** (1-2 hours) — evaluate goals, detect misalignment, correct strategy
- **Annual reflection** (3-4 hours) — deep reflection on the past year and clear intent for the next
- **Guided self-interviews** — coach-like prompts to surface insights you wouldn't find in a spreadsheet
- **Framework-based thinking** — borrowed from Dr. Anthony Gustin, Tim Ferriss, Tony Robbins, Alex Lieberman
- **Pattern extraction** — upload past reviews and notes; the system finds repeated themes, blind spots, and strengths
- **Long-term goal tracking** — 1-year, 3-year, 10-year visions that actually inform daily decisions

---

## How to Use This System

### First-Time Setup (15 minutes)

1. **Read `principles.md`** — understand the philosophy behind this system
2. **Fill out `north_star.md`** — define your current context (stage of life, role, priorities)
3. **Complete one interview** — start with `interviews/past_year_reflection.md` or `interviews/identity_and_values.md`
4. **Set your first goal** — open `goals/1_year.md` and write what matters most this year
5. *Optional:* Upload past annual reviews or notes to `uploads/` and run a pattern extraction (instructions below)

That's it. You're ready.

---

### Daily Practice (5 minutes)

Every morning or evening, create a new file in `reviews/daily/` using this naming convention:

```
reviews/daily/2026-01-15.md
```

Copy the template from the first daily check-in file, answer the five prompts, save, and close. No more than five minutes. The point is consistency, not perfection.

**What you'll track:**
- Energy level (1-10)
- One meaningful win
- One friction point
- One thing to let go of
- Tomorrow's single priority

---

### Weekly Practice (20 minutes)

Every Friday or Sunday, create a new file in `reviews/weekly/`:

```
reviews/weekly/2026-W03.md
```

Use the weekly review template. This is where you separate what moved the needle from what was noise. You'll spot patterns (energy leaks, strategic insights, time traps) and make one adjustment for next week.

**What you'll evaluate:**
- What actually moved the business forward?
- What felt busy but didn't matter?
- Where did time leak?
- One strategic insight
- One adjustment for next week

---

### Quarterly Practice (1-2 hours)

At the end of each quarter (March, June, September, December), create a file in `reviews/quarterly/`:

```
reviews/quarterly/2026-Q1.md
```

Use the quarterly review template. This is a deeper checkpoint: Are your goals still relevant? Is your energy aligned with your output? What needs to course-correct?

**What you'll assess:**
- Progress on 1-year goals
- Energy vs. output analysis
- Strategic misalignments
- Wins, failures, lessons
- Course corrections for next quarter

---

### Annual Practice (3-4 hours)

Once a year (ideally late December or early January), complete the full annual review process:

1. Run the **Past Year Reflection Interview** (`interviews/past_year_reflection.md`)
2. Complete the **Annual Review Framework** (`frameworks/annual_review.md`)
3. Update your **Life Map** (`frameworks/life_map.md`)
4. Refresh your **Vivid Vision** (`frameworks/vivid_vision.md`)
5. Recalculate your **Ideal Life Costing** (`frameworks/ideal_life_costing.md`)
6. Set new goals in `goals/1_year.md`, `goals/3_year.md`, `goals/10_year.md`
7. Save the completed review in `reviews/annual/2026.md`

This is your North Star reset. You'll leave with total clarity on what the past year meant and what the next year demands.

---

## The Frameworks (What They Are and Why They Matter)

This system uses proven frameworks adapted for CEO-level thinking:

- **Annual Review** (Dr. Anthony Gustin) — structured reflection on the year: peaks, valleys, lessons, and forward intent
- **Vivid Vision** (Tony Robbins-style) — emotionally clear picture of your ideal life, not just business goals
- **Ideal Life Costing** (Tim Ferriss) — what does your dream life actually cost? (Usually less than you think)
- **Life Map** (Alex Lieberman) — balance across six domains: career, relationships, health, meaning, finances, fun

Each framework has its own document in `frameworks/` with instructions and prompts.

---

## Pattern Extraction (Optional but Powerful)

If you have past annual reviews, performance reviews, or personal notes, upload them to `uploads/past_annual_reviews/` or `uploads/notes/`.

Then, ask your assistant (Claude, ChatGPT, or any LLM) to:

> "Read all files in `uploads/`, extract recurring patterns, themes, repeated goals, failures, strengths, and blind spots. Summarize findings in a document called `Executive Pattern Summary` and update `memory.md` with key insights."

The system will spot things you can't see yourself: goals you set every year but never do, strengths you undervalue, energy drains you rationalize, decisions you avoid.

These insights feed into future check-ins. Your weekly and quarterly reviews reference `memory.md` to remind you of your own patterns.

---

## The Interviews (Guided Self-Reflection)

Three interview scripts are included in `interviews/`:

1. **Past Year Reflection** — what happened, what mattered, what drained you, what you'd never repeat
2. **Identity and Values** — who you are, what you stand for, what you won't compromise
3. **Future Self Interview** — where you're going, what success looks like, what you're building toward

These are not forms. They're conversations with yourself. Answer honestly. No one else will read this.

---

## Personalization (Make It Yours in 15 Minutes)

This system includes placeholders like `[YOUR COMPANY]`, `[YOUR ROLE]`, `[YOUR STAGE OF LIFE]`. Do a find-and-replace:

- Open `north_star.md`
- Replace placeholders with your actual context
- Do the same in any framework or goal document that feels generic

That's it. The system adapts to you.

---

## Rules of the System

1. **No productivity theater.** If a check-in feels performative, skip it. The system serves you, not the other way around.
2. **Consistency beats intensity.** A 5-minute daily check-in for 90 days is worth more than a 4-hour quarterly binge.
3. **This is private.** No one sees this but you. Be honest. The value is in the truth, not the story.
4. **Reflect, don't report.** You're not filing a status update. You're thinking clearly about what's working and what's not.
5. **Adjust as needed.** If a framework doesn't fit, change it. If a prompt feels wrong, rewrite it. You own this.

---

## What Success Looks Like

After 90 days of using this system, you should experience:

- **More clarity** on what actually matters vs. what just feels urgent
- **Less decision fatigue** because your priorities are explicit
- **Better energy management** because you're tracking what drains you
- **Fewer regrets** because you're reflecting before the year is over
- **Sharper strategy** because you're separating signal from noise weekly
- **Deeper self-awareness** because you're asking questions most people avoid

This system doesn't make you more productive. It makes you more intentional.

---

## File Structure Reference

```
ceo-personal-os/
├── README.md (you are here)
├── principles.md (system philosophy)
├── north_star.md (your current context and priorities)
├── memory.md (extracted patterns and insights)
├── frameworks/
│   ├── annual_review.md
│   ├── vivid_vision.md
│   ├── ideal_life_costing.md
│   └── life_map.md
├── interviews/
│   ├── past_year_reflection.md
│   ├── identity_and_values.md
│   └── future_self_interview.md
├── reviews/
│   ├── daily/ (one file per day: YYYY-MM-DD.md)
│   ├── weekly/ (one file per week: YYYY-Wnn.md)
│   ├── quarterly/ (one file per quarter: YYYY-Qn.md)
│   └── annual/ (one file per year: YYYY.md)
├── goals/
│   ├── 1_year.md
│   ├── 3_year.md
│   └── 10_year.md
└── uploads/
    ├── past_annual_reviews/
    └── notes/
```

---

## Start Here

1. Open `principles.md`
2. Fill out `north_star.md`
3. Run your first daily check-in tomorrow morning
4. Do your first weekly review this Sunday

That's the whole system. No apps. No subscriptions. Just you and a text editor.

Welcome to your personal operating system.
