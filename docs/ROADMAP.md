# Toolkit roadmap (v0.1 – initialized in part 4 of Graecum VN)

> The toolkit is one of the three Graecum VN repositories (see the [architecture ADRs](https://github.com/qtan-tran/graecum-vn/blob/main/docs/ARCHITECTURE.md)): the portal changes at the pace of lesson writing, the **toolkit changes at the pace of the outside world** (dead links, new tools, resource comparisons), and the future sentence-analysis platform changes at the pace of software.

## Principles (inherited from the portal, adapted for a global audience)

1. Only **free or public-domain** tools; sustainability over quantity.
2. Every link is **manually verified at the time of writing** (HTTP check) – no link goes in unopened.
3. For copyrighted resources: **link-only reviews**, no hosting, no quotation of contents.
4. The hub is **self-contained static HTML** (no build step, no required JavaScript) – opens in any browser, works offline.
5. Every entry in `tools.json` must answer "use it when…" – the hub is advisory, not just a directory.
6. **Language: bilingual (since 2026-11)** – a Vietnamese homepage at the repository root plus a full English edition under `en/`, cross-linked both ways. Standard grammatical terminology is kept in the English edition, which remains the reference copy: the audience is global, and tools (unlike lessons) serve readers who need stable, searchable terms.

## Done (v0.1 – initial release)

- Repository initialized with: `README.md`, `LICENSE` (CC BY-SA 4.0 for content + MIT for code), `CONTRIBUTING.md`, `.gitignore`, `index.html` (hub, 5 categories), `tools.json` (16 tools), `docs/COMPARISONS.md` (resource comparisons v1), `docs/ROADMAP.md` (this file).
- All 16 tool URLs HTTP-verified at the time of writing (Logeion, Perseus, Scaife, Theoi, Wiktionary, Wikisource, Diogenes, TypeGreek, Keyman, SIL Gentium, Anki, three PD copies of Smyth…).
- Two-way cross-links with the Graecum VN portal (the portal's `toolkit.md` stub updated to point here).
- GitHub Pages enabled and live: https://qtan-tran.github.io/ancient-greek-toolkit/ (verified HTTP 200).
- Terminology page added (`terminology.html`): the standard English grammatical terms for Ancient Greek – writing system & sounds, nouns & article, verbs, syntax, plus a Greek-vs-Latin only-features table – each entry cross-referenced with the Vietnamese terminology of the portal (`terminology.html` there mirrors this page in Vietnamese); linked from the hub and `tools.json` (17 tools).

- **Wiktionary entry enriched (owner request):** the lexica category already listed Wiktionary, but the entry undersold its killer feature for beginners – paste any inflected form (e.g. παιδεύεις) and the page parses it (2nd-person singular present active indicative of παιδεύω), links back to the lemma, and gives reconstructed IPA pronunciation. desc/use_when in `tools.json` and the hub row updated to lead with form-parsing + IPA; a `.gk` style rule added to the hub so inline Greek matches the portal. Still 17 tools; Wiktionary URL unchanged (already HTTP-verified).

- **Vietnamese homepage + English edition (owner request, 2026-11):** the hub homepage at the repository root is now in Vietnamese (`index.html`), with the English edition moved to a full mirror at `en/index.html`; both pages cross-link to each other. A **YouTube category** was added (6 categories, 22 tools): @LearnAncientGreek (David Luchford), the Kosmos Society "Learn Ancient Greek" course by Leonard Muellner (Brandeis), Alpha with Angela (Koine comprehensible input), ScorpioMartianus (restored-pronunciation readings), and fig tree @underthefigtreee (culture & mythology long-forms); all five channel URLs HTTP-verified at the time of writing.

- **Satzanalyse VN added to Practice & review (2026-11):** the project's own sentence-analysis platform (live on GitHub Pages, HTTP-verified 200) now has a row in the Practice & review category of both editions (`index.html` + `en/index.html`) and an entry in `tools.json` (23 tools). Two-way cross-links: the hub links to the platform, and the platform's site links back to the hub and the portal. The Anki row's deck pointer was refreshed while editing the table (blocks 1–20 published).

## Plans

1. **Smyth mapping:** a table mapping each Graecum VN lesson to the relevant Smyth index subjects (subjects via the index; no section numbers until each is verified).
2. **Per-lesson quizzes:** if the portal grows standalone quizzes, add a "quizzes by lesson" category to the hub and `tools.json`.
3. **Anki cross-links:** when part 6 of the portal roadmap ships the decks, update the Anki entry to link the decks directly.
4. **Periodic link checks:** a manual checklist on every update (curl each URL); a small script if it ever becomes a chore – but the repository must never *require* a build.

## Checklist for accepting a new tool (issue triage)

- Free or PD? (paid → not accepted)
- Stable for years / widely used by the academic community?
- Genuinely useful for **self-taught learners** (not only for teachers)?
- "Use it when…" expressible in 1–2 sentences?
- Link verified?
