# Stack adapter

Fill this in once, at the start of an engagement. Every bundle reads its nouns from here.

This file is the reason a bundle fits more than one client. The workflows, gates and failure modes never change. The names of the tools, teams and properties always do. Keeping them in one file means a workflow can say "publish to the help desk" and be correct everywhere, instead of naming one vendor and being wrong everywhere else.

Leave a line as `not used` rather than deleting it. A workflow that expects a canonical layer needs to know the client has none, which is different from the question never being asked.

---

## Organisation

| Field | Value |
| --- | --- |
| Organisation name | |
| What it sells, in one line | |
| Primary market | |
| Languages published | |
| Default language | |

## Layers

Most content operations have two: a place where work happens while it is still moving, and a place where the agreed version lives. Some clients have one. Some have three. Name what exists.

| Layer | Tool | Who can write | Notes |
| --- | --- | --- | --- |
| Working layer | | | Where drafts and tasks live |
| Canonical layer | | | The agreed version. Wins on conflict |
| Public layer | | | Anything a customer can reach |

**Contract between layers.** State plainly which one wins when they disagree, because they will. Without this line, two people fix the same page in two places and neither knows.

## Platforms

| Function | Tool | Who applies changes |
| --- | --- | --- |
| Website CMS | | |
| Help desk | | |
| Email platform | | |
| Analytics | | |
| Search console | | |
| SEO plugin | | |
| Task tracker | | |
| Design tool | | |

The **who applies changes** column is not decoration. Where the writer determines a value but someone else enters it, the workflow ends at handover and the done-when test belongs to that handover, not to the live site. Getting this wrong produces a deliverable nobody applies.

## Properties

Every distinct site, subdomain or app the work covers. Reporting bundles iterate this list.

| Property | URL | Language(s) | Tracked |
| --- | --- | --- | --- |

## Product lines

| Product | What it is | Who owns it | Ships releases |
| --- | --- | --- | --- |

## Contributing teams

Teams that supply material, sign off, or receive work. Reporting and documentation bundles iterate this list, so a missing row becomes a missing section later.

| Team | Supplies | Confirms | Lead |
| --- | --- | --- | --- |

## Answer engines tracked

Which assistants the client wants to be cited by. Order matters: the first is the one reported on when time is short.

| Engine | Tracked | Notes |
| --- | --- | --- |

## Approval gates

Who has to say yes before something goes out, and to what. One row per gate. A gate with no named holder is not a gate.

| What | Held by | Applies to |
| --- | --- | --- |

## Sensitive topics

Subjects that stop and wait for a named person rather than being drafted and reviewed. Not the same as an approval gate: these are the ones where drafting first is itself the risk.

| Topic | Cleared by |
| --- | --- |

## Cadence

| Activity | Frequency | Day |
| --- | --- | --- |

---

## Filling this in is billable work, not admin

Half the findings in a first engagement come from this table rather than from any audit. A client who cannot say which layer wins, or who applies a CMS change, or who signs off on pricing claims, has just told you where their content operation breaks. Record those answers as findings.
