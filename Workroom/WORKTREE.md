<!-- WORKTREE | The live queue and the handover document | Updated: 30 Oct 2026 -->

# Worktree

This file is two things at once. It is the queue of everything owed, and it
is the handover document a new session reads first. If you are a fresh
session, read this file, then `Workroom/AUDIT.md`, then the book.

**This folder is public, deliberately.** It was called `.internal/` until
30 Oct 2026 on the assumption that it was private. It never was — the repo
is public and the folder was tracked in git. Rather than hide it, the
founder's decision is that it stays open: Nigerians are meant to read this
work, and a project whose first rule is *no claim above its evidence* is not
damaged by publishing its own audit. The folder was renamed `Workroom/` so
the name stops lying, and `README.md` now links to it.

One file was pulled out rather than published: `Translations_DRAFT.md`, the
Hausa, Yoruba and Igbo doctrine lines, all marked unusable pending
native-speaker review. It is held outside the repo until the review happens
(founder item 2 below). It remains in the pre-30-Oct git history, so anyone
who cloned before that date has it.

---

## READ FIRST — the state of the repo on 30 Oct 2026

**Repo:** `github.com/omoefeomoejie/nigeria-blueprint`, branch `main`.
82 commits, 70 tracked files (one more commit lands with this update), latest
pushed tag `v0.23` — tag pushes are blocked by some sandbox proxies, so tags
may lag the commits.

**Structure — five buckets, one front door.** `README.md` points at the book
first. Everything else sits under one of five directories:

| Bucket | What it is | State |
|---|---|---|
| `Book/` | `00_THE_BOOK.md` — 33 chapters, 6 parts, ~19,800 words | Complete first draft. Never read end to end by the founder. |
| `Movement/` | Why join, how to join, what survives us, becoming a party, the nine lines, for a governor | Rewritten in the book's voice (commit 19edf0b) |
| `Syllabus/` | `00_SYLLABUS.md` — 32 Level 1 items, 10 Level 2, 3 Level 3 tasks, each naming its chapter | Derived from the book, re-derived after renumbering (2df495c) |
| `Exams/` | Level 1 question bank (40 Q with answers), Level 2 paper (10 structured, answer any 6), Level 3 specimen (3 tasks with marking notes) | Exist as of b7d8a4a. Never sat by anyone. |
| `Evidence/` | 9 node investigations, 9 sector briefs plus a synthesis and an interdependence map (brief 08, trade & investment, was never written), the method layer, findings, red team, mistakes, scorekeeper test, costing, constitutional audit, absorption playbook, the older Blueprint chapters | Stable. This is the load-bearing research. |

**The chain that governs all of it:** the book is written from the evidence;
the syllabus is derived from the book; the exams are derived from the
syllabus. The rule, stated in the syllabus itself and non-negotiable:

> **If it is not in the book, it cannot be on the exam.**

That rule is why the book had to become complete. Part Four (how to check
anything) was written specifically so Level 2 would be studiable.

**Starting a fresh session:**

1. The sandbox filesystem resets between sessions. The repo must be cloned
   again each time, and **the GitHub token must be supplied again by the
   founder** — do not expect to find it on disk. The token in use as of
   this writing is a fine-grained PAT scoped to this one repo,
   Contents read/write only, 90-day expiry from mid-Aug 2026. It has
   appeared in chat history and **should be rotated at expiry rather than
   renewed.**
2. `git clone`, then read this file, then `Workroom/AUDIT.md`.
3. `Evidence/MISTAKES.md` before making any claim — it records every
   reversal and why it happened. Mistake 9.1 is the one to internalise: *a
   figure that makes the argument neat deserves more scrutiny, not less.*

---

## Publication decision — recorded 30 Oct 2026

The repository is public by intent. The founder's words: *"it is meant to be
public, because I want Nigerians to read it."* So there is no quarantine
layer in this repo and nothing should be added on the assumption of privacy.
If something genuinely cannot be published, it does not live here at all.

What that decision covers and does not cover:

| File | Status |
|---|---|
| `AUDIT.md` | Public. Our own assessment of where the work is weakest. Publishing it is the argument working. |
| `WORKTREE.md` | Public. Includes item E — that our largest structural weakness is having no human sources. Stated plainly, on purpose. |
| `MANIFEST.md`, `VERSION_HISTORY.md` | Public. Harmless. |
| `Foundations_pre_evidence.md` | Public. Pre-evidence framework material, kept for provenance, superseded in substance. |
| `Translations_DRAFT.md` | **Removed from the repo.** Three languages the founder cannot verify, marked unusable. Publishing lines nobody has checked, in languages we do not speak, is not transparency — it is a claim above its evidence, in Hausa. It returns in one commit once reviewed. |

The folder name was `.internal/` and is now `Workroom/`, because the old
name told a future contributor something false.

---

## FOUNDER ONLY — the two things I cannot do

These have been sitting unassigned for weeks and a new session would not
know they are yours. They are not research tasks. They need a human with a
phone.

1. **Find a named external examiner.** A person or body outside the
   movement, paid whether candidates pass or fail. Without this, Level 3
   fails our own scorekeeper test — and the scorekeeper test is the single
   finding the whole project rests on. We rejected the CCP model on exactly
   this ground: the CCP sets, marks and audits its own exam, which is the
   same structure that produced 375 seats out of 376 in Lagos in July 2025.
   If we mark our own exam we have reproduced the thing we are against.
   Governance should come from the professional-institute model (ICAN and
   similar), not the party model.
2. **Get native speakers to check the Hausa, Yoruba and Igbo doctrine
   lines.** Drafts are in `Translations_DRAFT.md` (held outside the repo), all marked
   unusable. One speaker per language. They are judging rhythm and whether
   the line lands, not literal accuracy. Until this happens the lines cannot
   be published in any form.

A third, smaller, also yours: **decide whether sharing the podcast name
("Hand of Nigeria") is right.** The risk is that the founder becomes the
product, and a movement whose doctrine is "if it lives in one man, it dies
with him" is embarrassed by that.

---

## The book — highest priority work

| # | Item | Who |
|---|---|---|
| B5 | **Read the full book end to end.** It has never had one complete read. Mark anything that stops the reader. This is the highest-value hour available. | Founder |
| B3 | **Pidgin edition, written fresh** — not translated from English | Founder + me |
| B6 | **Second specificity pass.** The rule is: name the state, the date, the party, the agency. The book mostly obeys it now. Mostly is not a standard. | Me |

## Offered, not yet accepted

**A script system for short-form video.** The founder is camera-shy and
currently uses Google Veo via YouTube Shorts plus CapCut. The proposal was a
repeatable format drawn from the book's 33 chapters and the 40 Level 1
questions, turning the channel into a recruitment funnel for the exam. Never
accepted or declined. Still available.

## From the red team — ranked by damage if found first

| # | Item | Tier |
|---|---|---|
| A2 | **Found or fund an external scorer in an unscored domain** — cheapest high-leverage intervention the scorekeeper test surfaced; nobody has proposed it | new |
| D | **Second civic auditor to triangulate BudgIT** — source concentration is real | 2.4 |
| E | **Human sources** — the single largest structural weakness; not mine to do | 1.1 |

See `Evidence/RED_TEAM.md` for the full pass. Items A, A3, B, C and C2 are
closed and listed under Done.

## Platform work still open

| # | Item | Who |
|---|---|---|
| P3 | **Cost party registration end to end** — 24 offices, fees, compliance. No Nigerian party publishes this; another missing scorekeeper. | Me, 2 drills |
| P4 | **The supporter tier** — how a person who cannot sit a written exam participates without speaking in the movement's name. Risk 2 in the membership standard is unsolved. | Both |
| P6 | **Oral examination protocol for Level 1** — follows from P4. A written-only gate excludes people the movement needs. | Me |
| P5 | **Confirm the name against s.222** — must not reflect ethnic, religious or sectional identity. "Hand of Nigeria" appears to pass; it has not been checked against INEC's actual refusals. | Founder + me |

## Research still owed

| # | Item | Why | Who |
|---|---|---|---|
| 2 | **What a bandit foot soldier actually earns** | The ₦5,000 figure failed corroboration; the ransom economy is what corroborated. Nobody has published what a participant nets from a ransom share — the number a livelihood programme must actually compete with. | Me, 2 drills |
| 3 | **Independent verification of UBEC's self-reported figures** | 95% procurement completion, 8.7m learners, ₦100bn mobilised — all self-reported. The absorption playbook rests partly on them. | Me, 2 drills |
| 4 | **Sector Brief 08 — trade & investment** | Last unwritten brief. Assessed as unlikely to yield a ninth finding; available on request. | Me, 1 session |
| 5 | **Middle-case test of the absorption playbook** | We have the top (78%), the captured bottom (16%), and the results-based middle (65%). Untested: an honest, low-capacity body with no donor scaffolding. | Me, 2 drills |

### Opened by Node 9 (external constraint)

- **Illicit financial flows and transfer pricing out of Nigeria** — genuinely
  unexamined, plausibly large, and the channel most likely to shift Node 9's
  balance if investigated.
- **The historical causal chain** — colonial extraction → rentier structure →
  the 1999 Constitution drafted under military rule. Saying today's failure
  is domestic is not the same as saying the structure producing it was.
- **Has any African state funded a domestic verification agent independent
  enough to fail its own government?** The most direct sovereignty
  intervention in the corpus, and we do not know if it has ever been done.
- **Arms proliferation** — cross-border dimensions of the security node,
  never investigated.
- **Land Use Act reform** — the audit covered titling cost, not tenure
  security. A Certificate of Occupancy is a leasehold from the governor, not
  freehold. Different question, unanswered.

### Opened by the costing work

- **The 2024 capex reversal.** Capital exceeded recurrent by ₦1.26tn for the
  first time in the series. Either states turned a corner, or windfall
  revenue flowed into capital budgets that went unexecuted (Sector 06 found
  17.66% implementation to Q3 2025). Both stories fit the same number and
  nobody has separated them. **Large question, genuinely open.**

### Owed per node

From the node decisions themselves. Several have been searched and not
found, which is itself a finding.

- **Node 1:** Kwara layers 2–3 (capex share, conversion); within-non-tax
  decomposition beyond 2024
- **Node 2:** any Nigerian selection reform with measured service outcomes;
  any that survived succession
- **Node 3:** CJTF mechanism below existential threat; the demobilisation
  endgame
- **Node 4:** any measured Nigerian leakage-reduction figure — *searched
  three times, not found. Probably has to be built rather than found.*
- **Node 5:** whether any president signs a self-constraining s.162(2)
  amendment
- **Node 6:** NYSC effect below graduate level; direct evidence on Pidgin as
  unifier; a religion mechanism beyond capture-prevention
- **Node 7:** any Nigerian learning-linked transfer instance
- **Node 8:** the operative §60(3) text as gazetted, read directly

## Watch items — time resolves these, not searching

| Item | What would change | Where recorded |
|---|---|---|
| **2027 elections** (presidential 16 Jan, governorship 6 Feb) | The only real test of whether the 2026 Act produces real-time upload | Node 8 |
| **RMAFC formula transmission** | If transmitted, Node 5's central finding weakens — revise by commit | Node 5 v1.1 |
| **Enugu 2024 audited accounts** | Publication settles whether the gap is delay or avoidance | Node 1 v1.5 |
| **155 Host Community Development Trusts** | If HCDT funds show NDDC's abandonment pattern within 3 years, statutory spending rules are insufficient without independent verification | Sector 09 |
| **NDDC forensic audit report** | Submitted 2021, declared missing 2025, still unpublished. Highest-value single disclosure available. | Absorption Playbook |
| Federal funding-certainty directive (2026) | If 2026–27 abandonment falls, procurement rules can move absorption | Sector 06 §4 |
| Enugu FY2025 independent corroboration | Node 1's newest figures are ESIRS-sourced | Node 1 v1.4 |
| National Learning Assessment quality | If credible and state-disaggregated, Ch.7's baseline step already exists | Ch.7 correction |

## Standing rules

1. Anything discovered and not immediately actioned lands here in the same
   commit.
2. Items are ranked by evidential value, not by ease.
3. A closed item moves to Done with its commit or tag — never deleted.
4. **This file is cleaned when it drifts.** It had duplicate rows on
   16 Aug 2026; it was two revisions behind the repo on 30 Oct 2026, listing
   neither the consolidation, nor the exams, nor the Movement rewrite.
   Corrected both times. It will drift again.
5. Reader-facing text carries no jargon of ours. "Absorptive capacity,"
   "stock and flow," "route-matching" are our words, not Nigeria's. The
   evidence layer may keep precise terms; nothing a citizen reads may.

## Done

| Item | Closed by |
|---|---|
| Osun mechanism (Contested since Node 1) | v0.16 |
| Node 1 replication proof | v0.12 (Kwara), v0.16 (three-way) |
| Enugu durability | v0.9, v0.11 |
| Skills & Education node (Vision 2050's admitted gap) | v0.14 |
| Blueprint structure (Parts I–V, Ch. 1–7) | 5fae4c2 |
| Sector axis, first six briefs + synthesis | e218eaa |
| Repo front door | d21b856 |
| Seventeen-states drill — redefined absorption as organisational; corrected our own overclaim | d213ef2 |
| UBEC practice audit → Absorption Playbook | 1d58bcc |
| Failure-side audit (NDDC) — incentive vs competence settled | 77bee7d |
| Node 8 (Elections) + Chapter 8 | v0.18 |
| SIEC extension — first measured boundary on units-first | v0.19 |
| Middle-case agency (REA) — pay-on-verified-output identified | d08e70d |
| Voice pass — Doctrine, Parts I–V, Chapters 1–8, sector briefs | 0178634 |
| Doctrine translation drafts (HA/YO/IG), quarantined | 321892e |
| Pay-on-output donor-dependence question answered | 9f2baae |
| Enugu integrity check — three qualifications, no collapse | v0.20 |
| Sector Brief 07 (Housing & Land) — $300bn dead capital | 834e043 |
| Sector Brief 09 (Oil & Gas) — the purest proof | 4ba30d4 |
| Sector interdependence map — the sequence a state should attack in | 573264e |
| Reverse dependency: insecurity→agriculture measured; map corrected to regionally conditional | 8377838 |
| Feedback loop closed: agriculture→insecurity; security-first shown self-defeating alone | 1226a99 |
| ₦5,000 corroboration attempt — FAILED; figure downgraded to Contested, design conclusion restated, Mistake 9.1 logged | v0.21 |
| Scorekeeper test across 16 domains — 5 failures | v0.22 |
| Real-terms restatement — Osun's magnitude claim retired, Enugu halved | v0.22 |
| All eight chapters costed; "no Nigerian state publishes what reform costs" logged as a missing scorekeeper | v0.22 |
| Findings index — twelve findings ranked by what they changed | FINDINGS.md |
| Full repo audit — 66 files, found the book was 16% of words and 100% of what a stranger could read | Workroom/AUDIT.md |
| Plain-language rewrite for a Nigerian lay reader; invented analogies replaced with real cases | multiple |
| Health chapter written (was absent) | a58d19e |
| Sector work brought into the book — absorption, land, water, agriculture, oil, sequencing | 31d825a |
| Part Four written (how to check anything) so Level 2 would be studiable | 31d825a |
| Consolidation into five buckets, one front door | a58d19e |
| Movement files rewritten in the book's voice | 19edf0b |
| Syllabus re-derived from the book after renumbering | 2df495c |
| Exams written — Level 1 bank, Level 2 paper, Level 3 specimen | b7d8a4a |
| Chapter-list error in the costing corrected (money, people, openness, schools — not land) | 31d825a |
| CCP governance model rejected using our own scorekeeper evidence | Movement/02 |
| Front-door counts corrected — README said twelve sector briefs (nine) and sixteen mistakes (nineteen) | 30 Oct 2026 |
| `.internal/` renamed `Workroom/` and published; translations draft pulled out | 30 Oct 2026 |
