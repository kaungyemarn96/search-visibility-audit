# Search Visibility Audit

[![Downloads](https://img.shields.io/github/downloads/kaungyemarn96/search-visibility-audit/total?label=downloads&color=2f6f4e)](https://github.com/kaungyemarn96/search-visibility-audit/releases/latest)
[![Latest release](https://img.shields.io/github/v/release/kaungyemarn96/search-visibility-audit?label=release&color=2f6f4e)](https://github.com/kaungyemarn96/search-visibility-audit/releases/latest)

A free, complete audit workflow. It establishes where a site actually stands in search before anything is agreed or changed, and it ends in a document with the client's name on it: letter grades across five categories, a score across three dimensions with a target, a keyword gap matrix against named competitors, and every finding triaged to a severity, a week and an owner.

It is a complete procedure, not a trimmed sample of one. Every step it names, it also tells you how to run.

**Version 1.0.1 · Current as of October 2026 · Free, no expiry, no signup**

**Changes in 1.0.1.** Reworded how the five crawler files are described, so that `robots.txt` and the schema are shown as real controls and the rest as low-cost groundwork, and updated the date. The procedure, the scoring and the licence terms are unchanged.

---

## Who it is for

Whoever owns the decision about search on a site and needs a defensible answer to "how bad is it, and what do we do first". A marketing lead about to write a brief, a founder about to hire, an agency inheriting an estate they did not build, or a writer who has been told to "do SEO" and wants a starting position rather than a tool subscription.

It assumes you can crawl a site and read analytics. It does not assume you have done this before.

## What it will not do

**It does not score AI and answer visibility.** A fourth dimension exists for presence and accuracy in answer-engine responses, and it is not scored here, which is why the score totals 75 rather than 100. The report template keeps the row and marks it **Not measured** rather than dropping it, because an unmeasured dimension is not a failing one and a reader is entitled to know a fourth exists. If you need that number, it takes a standing prompt set run against each engine, which this package does not include.

**It does not fix anything.** There is no foundation build here: no schema set, no five crawler files, no metadata rewriting. The audit tells you what is wrong and in what order. Doing the work is separate.

**It does not run a cycle.** No weekly pulse, no quarterly sweep. This is the one-off establishing measurement, not the operating rhythm.

**It does not handle multilingual estates properly.** Locale duplicates distort on-page counts in both directions, and the pairing checks that resolve that are out of scope here.

**It is not legal, financial, or ranking advice, and it promises no rank.** Targets follow the deliverables in scope, never the reverse.

## What it contains

| File | What it is | When it is used |
| --- | --- | --- |
| `workflows/audit.md` | The procedure, eight steps, with gates and a done-when test | Start here. It drives everything else |
| `references/scoring-rubric.md` | Both scoring systems: the five-category letter grade for the proposal stage, the three-dimension score for delivery | Steps 3 and 4 |
| `references/three-layer-model.md` | Why search, answers and declarations are one problem rather than three | Read once, before the first audit |
| `templates/audit-report.md` | The report shape, ready to fill | Step 8 |
| `templates/keyword-gap-matrix.md` | Keywords as rows, competitors as columns | Step 5 |
| `engagement.md` | What to capture during delivery so it can be proven later | Step 1, and throughout |
| `core/stack.md` | The adapter. Your tools, properties and approvers. Fill in once | Before the first run |
| `core/engagement-record.md` | The shared record-keeping rules `engagement.md` extends | With `engagement.md` |
| `core/always-true.md` | The rules that hold on every engagement | Read once |

Twelve files, and **every reference in them points at another file in this list.** Nothing here tells you to open something that is not in the download.

## How to run it

1. Fill in `core/stack.md`. It is the only configuration, and the workflows read their nouns from it.
2. Read `references/three-layer-model.md` once.
3. Follow `workflows/audit.md` from step 1. Do not skip step 1: once a fix lands the before-state is gone, and the before-state is what the engagement is measured against.
4. Write it up with `templates/audit-report.md`.

It is plain markdown, so it runs by hand in any tool, or as a skill in Claude Code by pointing the assistant at `workflows/audit.md`.

Licence: `LICENCE.md`. Free inside your own company, not to resell or offer as a service.
