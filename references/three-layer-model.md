# The three layers

One problem, three surfaces. Most of the underlying work serves all three, which is why they are sold together and run in the same sitting. Where they diverge, they diverge sharply.

---

## SEO — ranked by a search engine

A person types a query and picks from a list. What decides the list: crawlability, titles and descriptions, heading structure, internal linking, page speed, mobile behaviour, and whether the page answers the query it claims to.

**Delivered as:** meta values per page, heading fixes, internal link additions, redirect maps, technical defect lists.

**Measured by:** position, impressions, click-through rate, and the technical scores.

## GEO — cited by a generative answer

A person asks a question and reads a synthesised answer with sources attached. What decides whether the site is one of those sources: entity clarity, question-shaped content, structured data, and consistency of terms across the estate.

The mechanism is different from ranking. An answer engine is not choosing the best page, it is assembling a response from passages it trusts. A page can rank well and never be quoted, because it never states plainly what the thing is.

**Delivered as:** entity definition blocks, FAQ sets in plain question and answer form, schema that matches the page it sits on, consistent naming for every entity.

**Measured by:** whether the standing prompts return the site, what they cite, and whether what they say is correct.

## AEO — the crawler files

The layer most people skip. Five files that set out what the site covers, which pages are canonical, how it wants to be cited, and which crawlers may read it.

Be exact about what each one does. `robots.txt` and the schema snippet are controls that crawlers and search engines document and honour. `llms.txt`, the AI overview page and the AI sitemap are groundwork: cheap to write and harmless, read by people and by developer tools, but no major assistant has confirmed that it reads them, so none of this is promised to a client as a cause of citation.

This is infrastructure, not content. It is written once, revised when the site changes shape, and it is the cheapest of the three to deliver.

**Delivered as:** five crawler files at the site root. Writing them is out of scope here; this audit reports whether they are present and correct.

**Measured by:** crawler access in logs, and by the citation format actually used when the site appears in an answer. The effect is measured, not assumed.

---

## Why the separation matters commercially

A client asking for SEO usually means the first layer. The second is where their actual complaint lives, which is a competitor being named in an answer. The third is the one nobody else is doing, costs the least, and is the easiest to show.

Selling all three as "SEO" undersells two of them. Naming them separately makes the scope legible and the price defensible.

## Where they conflict

**Keyword density versus entity clarity.** Ranking rewards a page that covers a topic thoroughly. Being quoted rewards a page that states one thing unambiguously in one place. When these pull apart, favour clarity: a page that is quoted is also, increasingly, a page that ranks.

**Comprehensive pages versus answerable passages.** A long guide can rank on many terms and be quoted on none, because no single passage stands alone. Fix by adding a definition block and a FAQ set to the same page rather than splitting it.

**Locale duplicates.** Translated pages help the second and third layers and hurt the first if canonicals are wrong. Checking a multilingual estate properly is out of scope for this package.
