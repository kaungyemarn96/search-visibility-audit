---
name: search-visibility-audit
description: Run a one-off search visibility audit on a website and write it up as a client-ready report. Use for a site audit, an SEO health check, a first-pass search assessment, a keyword gap analysis against named competitors, letter grades across on-page, links, performance, social and usability, or a triaged list of what to fix first. Triggers include "audit this site", "how bad is our SEO", "where do we stand in search", "what should we fix first", "SEO health check", "keyword gap", "site grade". Do NOT promise a rank; targets follow the deliverables in scope. Do NOT score AI or answer-engine visibility, it is not covered by this package and must be reported as not measured rather than as zero. Do NOT present a score without its biggest specific finding. Do NOT skip the before-state capture in step 1.
---

# Search Visibility Audit

The free audit. One establishing measurement of where a site stands, written up so a non-technical reader can act on it.

Load `core/always-true.md` first. Read `core/stack.md` before running anything: every property, tool and owner comes from there, and an audit run against unfilled fields is an audit of nothing.

## What this package is

A complete one-off audit procedure. It does not score AI and answer visibility, and it does not build, fix or maintain anything. `README.md` states the boundary in full and `LICENCE.md` states the terms. Read the boundary before scoping any work against this.

## Run it

Follow `workflows/audit.md` in order. Eight steps, two gates, and a done-when test that someone who did not run it can check.

The two shapes it produces are in `references/scoring-rubric.md`: letter grades across five categories for the proposal stage, and a score across three dimensions for delivery. Run both. Running only one costs either the sale or the report.

`references/three-layer-model.md` explains why search, answers and crawler declarations are one problem. Read it once before the first audit; it is not a step.

## The rules that carry it

**Capture the before-state first.** Step 1, before anything else. Once a fix lands the evidence is gone, and the before-state is what the whole engagement is measured against. Everything to capture is in `engagement.md`, which extends `core/engagement-record.md`.

**Never present a score without its biggest specific.** A number tells someone where they are. A finding tells them what to do. Only the second is worth anything.

**A finding with no week attached is a complaint.** Every finding carries a severity, a week and an owner, or it does not go in the report.

**Report the failing category first.** One failing category and four good ones is a clear decision. Five middling grades is none.

**Record the tool, the date and the settings**, never just the number. A score from a different tool, or the same tool six months on, is not comparable.

**The fourth dimension is absent, not zero.** This package does not measure AI and answer visibility. Record it as not measured and leave the total at 75. Scoring it zero would be a false measurement, and rescaling to 100 would make it look comparable to a score that includes it.

## Done when

Every finding carries a severity, a week and an owner. Every grade carries a specific. Every target names the deliverables behind it. The before-state is captured and stored. The reader can finish the first page and know what the worst problem is.

## Where it ends

An audit ends in a scope. Where the audit is free, that scope is a proposal and the report should say so plainly rather than implying the work is already agreed.
