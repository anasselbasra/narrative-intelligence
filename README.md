# Narrative Intelligence — NI-2026-NATO-001

Analytical report on the NATO information environment during the Iranian nuclear crisis (February–April 2026). Four-phase intelligence program covering 3,510 posts collected on Twitter/X.

**Live:** [narrative-intelligence.systems](https://narrative-intelligence.systems)

---

## Structure

```
├── index.html                          # Main interface (sidebar navigation + iframe viewer)
├── NI-2026-NATO-001_Resume_Executif.pdf
├── logo.svg
├── CNAME
└── reports/
    ├── NATO_Intro_Overview.html        # Project overview & methodology
    ├── NATO_Phase1_AnalyseDescriptive.html   # Module 01 — Signal Landscape
    ├── NATO_Phase2_TopicModeling.html        # Module 02 — Threat Clusters (UMAP + HDBSCAN)
    ├── NATO_Phase3_AnalyseNarrative.html     # Module 03 — Threat Matrix (21 narratives)
    └── NATO_Phase4_AnalyseVisuelle.html      # Module 04 — Coordination Patterns
```

---

## Analytical program

| Module | Content | Key output |
|--------|---------|------------|
| 01 · Signal Landscape | Descriptive analysis of the corpus | 3,510 posts · 9.6M engagements |
| 02 · Threat Clusters | UMAP dimensionality reduction + HDBSCAN clustering | 36 semantic clusters · 30.6% noise |
| 03 · Threat Matrix | Canonical narrative extraction · cosine similarity ≥ 0.70 | 21 narratives · N18 dominant (362 texts) |
| 04 · Coordination Patterns | Visual similarity × temporal scoring · threshold ≥ 0.90 | 9 significant groups · 82 accounts |

---

## Data

- **Platform:** Twitter/X (English)
- **Collection period:** 1 February – 3 April 2026 (62 days)
- **Filter:** min_retweets = 5
- **Corpus:** 3,510 posts · 531 unique URLs

---

## Author

**Anass El Basraoui** — Narrative Intelligence Analyst  
[LinkedIn](https://www.linkedin.com/in/el-basraoui/) · [Portfolio](https://elbasraoui.engineer/) · [anasselbasraoui0@gmail.com](mailto:anasselbasraoui0@gmail.com?subject=Briefing%20Request%20%E2%80%94%20NI-2026-NATO)

---

## License

See [LICENSE](LICENSE).
