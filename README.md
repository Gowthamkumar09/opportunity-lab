# 🔬 OpportunityLab

**Investigate startup ideas with evidence before you spend months building them.**

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

**▶ Live demo:** https://gowthamkumar09.github.io/opportunity-lab/

![OpportunityLab screenshot](docs/screenshot.png)

## Why this exists
Most student founders pick an idea first and look for evidence later. OpportunityLab flips that: it helps you collect evidence, score ideas honestly, and reject weak ones early.

## Features
- **Discover:** search and filter problems by industry and geography, and add your own.
- **Score (0–100):** seven weighted criteria, each needing written evidence, with a confidence level and a list of missing information.
- **Compare:** up to five opportunities side by side.
- **Validate:** neutral interview questions, a 10–15 interview plan, landing-page and paid-pilot experiments, and go/pivot/stop criteria.
- **Prototype:** a small interactive workflow demo.
- **Tracker:** interview notes, competitors, assumptions, results and decisions, each tagged Verified / Hypothesis / Estimate / Unknown.

## How scoring works
| Criterion | Weight |
|---|---|
| Severity & frequency of the problem | 20% |
| Evidence of willingness to pay | 20% |
| Ease of reaching customers | 15% |
| Weaknesses in existing solutions | 15% |
| Feasibility for a student founder | 10% |
| Market size & expansion | 10% |
| Competitive defensibility | 10% |

Unrated criteria count as 0, so missing evidence can never inflate a score.

## Run it
Open `index.html` in any browser. No install needed. Data is saved only in your browser (localStorage), with no backup.

## Honest limitations
- The seeded problems are **simulated hypotheses**, not research findings.
- No web research or competitor lookup is automated; you enter findings manually.
- Single-file prototype, with no accounts or cloud sync.

## Roadmap
- [ ] Export/import data as JSON
- [ ] CSV export of the comparison table
- [ ] More prototype workflows
- [ ] React + Vite version

## Contributing
Ideas and pull requests are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License
MIT. See [LICENSE](LICENSE).
