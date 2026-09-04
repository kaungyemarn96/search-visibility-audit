# Scoring

Two scoring systems, used at different moments for different audiences. Running only one is a common mistake and it costs either the sale or the report.

---

## 1. The live-crawl grade — proposal stage

Letter grades across five categories, produced by crawling the site before any engagement is agreed. Fast, legible to a non-technical buyer, and it converts.

| Category | What it covers |
| --- | --- |
| On-page | Titles, descriptions, headings, alt text, canonical tags |
| Links | Internal linking, broken links, orphan pages, redirect chains |
| Performance | Load behaviour, image formats, render-blocking resources |
| Social | Open Graph and card tags, share preview correctness |
| Usability | Mobile layout, tap targets, viewport, contrast |

| Grade | Meaning |
| --- | --- |
| A+ | Nothing to fix in this category |
| A | Sound, minor items only |
| B | Working, with a pattern worth fixing |
| C | Multiple defects affecting outcomes |
| D | Broken in ways a visitor notices |
| F | Not functioning |

**A category can be A+ and still hide the worst finding on the site.** A site with an excellent social presence can score A+ on Social while having no Open Graph tags at all, meaning every share posts without an image. The grade reflects the category as a whole; the finding under it is what gets sold. Always pair a grade with its single most important specific.

**Report the F first.** A buyer with one failing category and four good ones has a clear decision. A buyer handed five middling grades has none.

---

## 2. The three-dimension score — delivery stage

Out of 75, with a stated target after implementation. This is the one that appears in reports and gets re-run to show movement.

**Why 75 and not 100.** A fourth dimension, AI and answer visibility, carries a weight of 25 and is not scored by this package. The total therefore stops at 75 rather than being rescaled, because rescaling would make a three-dimension score and a four-dimension one look comparable when they measure different things. Record the fourth as absent, not as zero: an unmeasured dimension is not a failing one.

| Dimension | What it measures | Weight |
| --- | --- | --- |
| On-page | Meta completeness and quality across the tracked estate | 30 |
| Technical | Crawlability, speed, structure, correctness of markup | 25 |
| Content authority | Depth, coverage of the topic space, entity clarity | 20 |

### Scoring each dimension

**On-page.** Percentage of tracked pages with a present, unique, correctly-lengthed title and description, a single H1, and topic-specific tags rather than a shared boilerplate set. Straight proportion.

**Technical.** Start at 100. Deduct per defect class present, not per instance: broken internal links, redirect chains, missing canonicals, duplicate H1s, absent sitemap, sitemap not referenced in robots, unvalidated schema, failing core performance thresholds, missing alt text as a pattern. Weight by whether it affects crawling, rendering, or neither.

**Content authority.** Proportion of the mapped topic space with a page that could plausibly be the best answer, weighted by whether entity terms are used consistently and whether a definition block exists for each core entity.

### Targets

Every audit states a target per dimension after implementation, not a promise of rank. Targets are what the deliverables in scope can reasonably achieve, and they are what the next report is measured against.

State the target as a number and the deliverables that produce it. A target with no mechanism behind it is a forecast, and forecasts are not sold here.

---

## Rules for both

**Record the tool, the date and the settings**, not just the number. A score from a different tool, or the same tool six months on, is not comparable. This is in `engagement.md` for a reason.

**Re-run with identical settings.** Desktop against mobile, logged in against out, one page against the estate. A comparison across changed settings is not a comparison.

**Never present a score without its biggest specific.** A number tells a client where they are. A finding tells them what to do. Only the second one is worth paying for.

**Report anything that moved the wrong way.** A dimension that dropped, said plainly with a reason, buys more credibility than four that rose.
