<!-- FULL REPOSITORY AUDIT | 16 Aug 2026 -->

# Repository Audit

*Everything that exists, what state it is in, what duplicates what, what is
missing, and what should never be shown to the public.*

**Totals: 66 markdown files. ~88,000 words. 75 commits. 21 tagged releases.**

---

## 1. What exists, by function

### A. THE BOOK — the only thing written for a reader
| File | Words | State |
|---|---|---|
| `Book/00_THE_BOOK.md` | 14,463 | **Complete draft, 23 chapters, voice-passed** |
| `Book/README.md` | 385 | Fine |

**This is 16% of the repository's words and 100% of what a stranger can
actually read.**

### B. THE BLUEPRINT — the technical layer (24 files, ~24,000 words)
8 chapters, 4 Parts, 12 sector briefs, plus the Playbook, Costing,
Constitutional Audit, Doctrine, Pilot Brief, Foundations, translations.

**Problem: this now overlaps the book heavily.** Blueprint chapters and Book
chapters cover the same eight subjects. One of them is redundant as a
*reader-facing* artefact — but the Blueprint carries the evidence statuses
and the "what we got wrong" notes the Book compresses.

### C. THE RESEARCH ENGINE — the machine (22 files, ~21,000 words)
9 node decisions, the skill (10 rules), Mistakes (16 entries), Assumptions,
Evidence Standard, Law Zero, Preamble, Publication Rule, Research Habit,
Investigation SOP, Scorekeeper Test, Real Terms, Manifest, Version History.

**State: coherent and complete.** This is the strongest-built part of the
repo and the least likely to be read by anyone.

### D. THE PLATFORM — the movement (6 files, ~5,400 words)
Founding document, membership standard, irreversibility design, syllabus,
legal route, README.

**State: drafted, never revised, and written in the OLD voice** — before the
plain-language pass. **This is the biggest quality gap in the repo.**

### E. PROCESS FILES — not for the public (3 files, ~4,600 words)
`WORKTREE.md` (the queue), `RED_TEAM.md` (self-attack), `FINDINGS.md` (index).

**`FINDINGS.md` and `RED_TEAM.md` are genuinely public-worthy.**
**`WORKTREE.md` is internal** — it contains task lists, "who does what,"
and items addressed to the founder personally.

---

## 2. Duplication — the same finding in up to 9 places

| Finding | Appears in |
|---|---|
| UBEC 78% vs 16% | 9 files |
| The scorekeeper test | 8+ files |
| Lagos 375/376 | 8+ files |
| ₦332bn undrawn | 8+ files |
| 40% borehole failure | 6 files |

**This is not accidental.** The engine records it, the sector brief records
it, the synthesis records it, the chapter uses it, Findings indexes it, the
book tells it. Each layer has a different job.

**But for a public repository it reads as repetition**, and a reader
encountering the same number six times in six voices will assume padding.

---

## 3. What exists in the research and NEVER made the book

Checked directly. These are in the corpus and absent from `Book/`:

| Finding | Where it lives | Why it matters |
|---|---|---|
| **UBEC 78% vs Niger Delta 16%** | 9 files | The single best anti-fatalism fact we have. Kills "it's culture" and "it's region" at once. |
| **Pay on verified output** (REA vs NDDC) | Playbook | The most portable idea in the corpus. Not one word in the book. |
| **17.66% capital budget spent; ₦5.71tn rolled over; 56,000 abandoned projects** | Sector 06 | The scale of non-delivery. |
| **Politicians = 3.41% of budget; debt service = 28.52%** | Sector 11 | Settles an argument every Nigerian is having, wrongly. |
| **$300bn dead capital; 90% of land untitled; 71.4% of landlords hold no document** | Sector 07 | Most emotionally direct finding in the corpus. |
| **Fertiliser 13kg/ha vs 200 recommended; all 44 stakeholders say demand outstrips supply** | Sector 01 | Nigeria subsidising a shortage that doesn't exist. |
| **9 litres/person/day vs 12–16 standard; 46m open defecation** | Sector 05 | |
| **Cross River: zero abandoned projects** | Sector 06 | The proof that a Nigerian state can execute cleanly. |
| **ProZorro / Ukraine savings** | Now in book ✔ | (added this session) |
| **The sequence — which sector must move first** | Interdependence Map | Answers "where do I start?" |

**Roughly 40% of the strongest material never reached a reader.**

---

## 4. Quality inconsistency

| Layer | Voice | Status |
|---|---|---|
| Book | Plain, scenario-led, jargon-free | **Current standard** |
| Platform | Technical, jargon present | **Two revisions behind** |
| Blueprint chapters | Semi-technical, part-passed | One revision behind |
| Sector briefs | Technical | Not reader-facing, acceptable |
| Research Engine | Deliberately technical | Correct as is |

**The Platform files are the problem.** They are the recruitment layer — the
documents a person reads when deciding to join — and they are written in the
voice we abandoned.

---

## 5. Structural problems

**5.1 Two front doors.** `README.md` points at the evidence; `Book/README.md`
points at the book. A stranger does not know which is the front.

**5.2 The Blueprint is now ambiguous.** Is it the book's evidence base, or a
second book? Currently it reads as a second, worse book.

**5.3 Numbering collides.** Book has "Chapter 13a" (inserted health).
Sectors run 00–11 with 08 missing. Blueprint has Parts I–V and Chapters 1–8
that do not map to Book chapters 1–23.

**5.4 The syllabus examines documents that a reader cannot easily find**, and
references the Blueprint's structure rather than the book's.

**5.5 No exam actually exists.** The syllabus describes three levels. There
is no question bank, no specimen paper, no marking scheme.

**5.6 Version headers are stale** in files not touched since v0.23.

---

## 6. What is genuinely missing

| Missing | Consequence |
|---|---|
| **Land chapter in the book** | $300bn finding invisible to readers |
| **Water chapter** | Self-supply finding invisible |
| **Agriculture chapter** | Fertiliser/extension findings invisible |
| **Absorption chapter** ("pay after delivery") | Best portable idea unused |
| **Cost-of-governance correction** | Readers keep blaming the 3.41% |
| **The actual exam** | Platform has a standard and no instrument |
| **Pidgin edition** | Stated as required; not started |
| **Hausa/Yoruba/Igbo review** | Drafts exist, unreviewed, quarantined |

---

## 7. What should NOT be public

- `WORKTREE.md` — internal task queue, addresses the founder directly
- Version headers and engine bookkeeping — meaningless to outsiders
- `Blueprint/Doctrine_Translations_DRAFT.md` — explicitly marked unusable

**Everything else can be public**, including `RED_TEAM.md` and the Mistakes
file. Those are assets, not liabilities.

---

## 8. Recommendation: four buckets

The categories proposed — book / movement / syllabus / exams — are right, and
the audit suggests a fifth for the evidence.

```
1. THE BOOK        Book/                    the thing people read
2. THE MOVEMENT    Movement/                why join, what we promise, how to join
3. THE SYLLABUS    Syllabus/                what a member must know
4. THE EXAMS       Exams/                   the instrument (does not yet exist)
5. THE EVIDENCE    Evidence/                everything a skeptic checks
   ├── Findings, Red Team, Mistakes
   ├── Nodes (the 9 investigations)
   ├── Sectors (the 12 briefs)
   └── Method (Law Zero, Evidence Standard, etc.)
```

**Consolidation moves this implies:**

- Blueprint chapters **merge into the book** (they are the same eight
  subjects) and their evidence notes move to Evidence.
- Sector briefs stay whole in Evidence; their best findings become **book
  chapters** (land, water, agriculture, absorption).
- Platform files move to Movement and are **rewritten in the book's voice.**
- Research Engine becomes Evidence/Method — unchanged content, clearer home.
- `WORKTREE.md` moves out of public view.
- One README at root, pointing at the book first.

**Estimated result: ~30 files instead of 66, no lost content, one obvious
reading path.**
