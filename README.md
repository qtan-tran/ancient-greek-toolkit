# ancient-greek-toolkit – Curated tools & resource comparisons

**"grill me with ancient greek"** – a curated hub of tools for learners of Ancient Greek: lexica, primary-text libraries, typing, practice, and reference grammar. Every tool listed is **free or public domain**.

> All content: **CC BY-SA 4.0** · Code: **MIT** · Compiled by **Trần Quốc Tân** · No ads, no paywall, no data collection.

This repository is developed and maintained by **Quoc-Tan Tran**, **Postdoctoral Researcher** at the **Institute for Studies of Science, Bielefeld University**.

## Why a separate repository?

Per the three-repository architecture of Graecum VN ([ADR](https://github.com/qtan-tran/graecum-vn/blob/main/docs/ARCHITECTURE.md)): educational content (the portal) changes at the pace of lesson writing; **curated links (this toolkit) change at the pace of the outside world** – dead links, new tools, resource comparisons. Splitting keeps the "slow" portal from being dragged along by the "fast" toolkit, and vice versa. Since 2026-11 the toolkit is **bilingual**: the homepage at the repository root is in **Vietnamese**, with a full **English edition** at [`en/`](https://qtan-tran.github.io/ancient-greek-toolkit/en/). The English edition remains the reference copy for a global audience: tools need standard, searchable terminology (LSJ lemma, TLG abbreviation, Unicode keycap), and structure flows more naturally in English than in any single local language. The Vietnamese homepage mirrors it 1:1 so Vietnamese learners can navigate the same gears in their own language; both pages cross-link to each other.

## Where to start

- **Just use it:** open the hub at **https://qtan-tran.github.io/ancient-greek-toolkit/** (Vietnamese homepage) or the [English edition](https://qtan-tran.github.io/ancient-greek-toolkit/en/). The hub has six categories: lexica & morphology · primary-text libraries · typing & fonts · practice · reference grammar · YouTube channels.
- **Choose supplementary material:** [`docs/COMPARISONS.md`](docs/COMPARISONS.md) – comparisons of reference grammars (public-domain Smyth), introductory textbooks, and lexica.
- **Follow the roadmap:** the [Graecum VN portal](https://qtan-tran.github.io/graecum-vn/en/) – a complete 48-lesson course (Vietnamese main edition, English edition under way). This toolkit is the gear used alongside those lessons.

## Repository layout

```
├── index.html              # Hub portal (GitHub Pages) – Vietnamese homepage, start here
├── en/
│   └── index.html          # English edition of the hub
├── tools.json              # Meta index: id, url, category, "use it when…"
├── docs/
│   ├── COMPARISONS.md      # Resource comparisons (link-only policy for copyrighted works)
│   └── ROADMAP.md          # Toolkit roadmap + acceptance checklist for new tools
├── README.md               # This file
├── LICENSE                 # CC BY-SA 4.0 (content) + MIT (code)
└── CONTRIBUTING.md         # How to contribute: report tools, report dead links
```

## Curated-link principles

1. Only **free or public-domain** tools.
2. Every link is **verified** (HTTP check) at the time of writing; found a dead one → open an issue.
3. For copyrighted resources: **link-only**, no hosting, no quotation – a condition of the project's existence.
4. The hub is **self-contained static HTML**: no framework, no build step, no required JavaScript – opens in any browser, works offline.

## Credit (required when reusing)

When citing or reusing material, credit: **"Graecum VN – Trần Quốc Tân, https://github.com/qtan-tran/graecum-vn, CC BY-SA 4.0"**.

## Links

- **Graecum VN portal** – [repository](https://github.com/qtan-tran/graecum-vn) · [website](https://qtan-tran.github.io/graecum-vn/) · [48-lesson curriculum](https://github.com/qtan-tran/graecum-vn/blob/main/docs/CURRICULUM.md) · [English edition](https://qtan-tran.github.io/graecum-vn/en/)
- **Satzanalyse** (later) – the sentence-analysis platform, to be split into its own repository
