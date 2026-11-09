# Toolkit roadmap (v0.1 — initialized in part 4 of Graecum VN)

> The toolkit is one of the three Graecum VN repositories (see the [architecture ADRs](https://github.com/qtan-tran/graecum-vn/blob/main/docs/ARCHITECTURE.md)): the portal changes at the pace of lesson writing, the **toolkit changes at the pace of the outside world** (dead links, new tools, resource comparisons), and the future sentence-analysis platform changes at the pace of software.

## Principles (inherited from the portal, adapted for a global audience)

1. Only **free or public-domain** tools; sustainability over quantity.
2. Every link is **manually verified at the time of writing** (HTTP check) — no link goes in unopened.
3. For copyrighted resources: **link-only reviews**, no hosting, no quotation of contents.
4. The hub is **self-contained static HTML** (no build step, no required JavaScript) — opens in any browser, works offline.
5. Every entry in `tools.json` must answer "use it when…" — the hub is advisory, not just a directory.
6. **Language: English only**, with standard grammatical terminology — the audience is global, and tools (unlike lessons) serve readers who need stable, searchable terms.

## Done (v0.1 — initial release)

- Repository initialized with: `README.md`, `LICENSE` (CC BY-SA 4.0 for content + MIT for code), `CONTRIBUTING.md`, `.gitignore`, `index.html` (hub, 5 categories), `tools.json` (16 tools), `docs/COMPARISONS.md` (resource comparisons v1), `docs/ROADMAP.md` (this file).
- All 16 tool URLs HTTP-verified at the time of writing (Logeion, Perseus, Scaife, Theoi, Wiktionary, Wikisource, Diogenes, TypeGreek, Keyman, SIL Gentium, Anki, three PD copies of Smyth…).
- Two-way cross-links with the Graecum VN portal (the portal's `toolkit.md` stub updated to point here).
- GitHub Pages enabled and live: https://qtan-tran.github.io/ancient-greek-toolkit/ (verified HTTP 200).

## Plans

1. **Smyth mapping:** a table mapping each Graecum VN lesson to the relevant Smyth index subjects (subjects via the index; no section numbers until each is verified).
2. **Per-lesson quizzes:** if the portal grows standalone quizzes, add a "quizzes by lesson" category to the hub and `tools.json`.
3. **Anki cross-links:** when part 6 of the portal roadmap ships the decks, update the Anki entry to link the decks directly.
4. **Periodic link checks:** a manual checklist on every update (curl each URL); a small script if it ever becomes a chore — but the repository must never *require* a build.
5. **Terminology page:** a short glossary aligning the project's English terms with the Vietnamese terms used in the Vietnamese lesson edition (Nom./Gen./Dat./Acc./Voc. ↔ chủ cách/sở hữu cách/tặng cách/đối cách/hô cách), since the sentence-analysis platform will also use standard English terms.

## Checklist for accepting a new tool (issue triage)

- Free or PD? (paid → not accepted)
- Stable for years / widely used by the academic community?
- Genuinely useful for **self-taught learners** (not only for teachers)?
- "Use it when…" expressible in 1–2 sentences?
- Link verified?
