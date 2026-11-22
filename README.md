# 🔬 OpportunityLab

**Discover real problems across India, and investigate them with evidence before you spend months building.**

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
![Version](https://img.shields.io/badge/version-0.2%20prototype-9b2cff)

**▶ Live demo:** https://gowthamkumar09.github.io/opportunity-lab/

![OpportunityLab screenshot](docs/screenshot.png)

## Why this exists
Most student founders pick an idea first and look for evidence later. OpportunityLab flips that: it helps you find problems worth solving, collect evidence, score ideas honestly, and reject weak ones early.

## What it does
- **Cinematic scroll experience:** a 3D opening (a glowing orb, a morphing particle cloud and glass beads on an orbit ring) that reacts to your mouse and to scrolling. Every section animates in as you scroll.
- **Four question slides:** what frustrates people, who is struggling, why existing tools fail, and whether anyone would pay. They end with your itch in one sentence, and every question explains why it is asked.
- **India problem finder:** 18 curated problem hypotheses across farms, clinics, shops, factories, fisheries, logistics, education and more.
  - Filter by state (Andhra Pradesh, Telangana, Tamil Nadu, Karnataka, Maharashtra, Uttar Pradesh, All-India) or search by text.
  - **Surface new problems** reveals three more at a time.
  - **Add your own** problem when you spot one we missed.
- **Evidence-based scoring (0–100):** seven weighted criteria, written evidence for each, a confidence level, and a list of missing information.
- **Research notes:** interview notes, competitor findings, assumptions and results, each tagged Verified / Hypothesis / Estimate / Unknown.
- **Clear buttons:** every main button says why you would use it.

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

Unrated criteria count as 0, so missing evidence can never inflate a score. A high score is a decision aid, not a prediction that a business will succeed.

## Run it
Open `index.html` in any browser. No install or build step.
The 3D scene and fonts load from the internet (Three.js from cdnjs, fonts from Google Fonts). Without a connection, the page falls back to a plain gradient and system fonts.
Your data is saved only in your own browser (localStorage), with no backup. Clearing browser data deletes it.

## Honest limitations
- The 18 problems are **curated starting hypotheses, not verified facts or live research**. Confirm each one by talking to real people.
- "Surface new problems" reveals more items from the built-in list. It does **not** browse the web.
- No automated competitor lookup, accounts or cloud sync.
- Single-file prototype (HTML, CSS and JavaScript).

## Roadmap
- [ ] Bring back the side-by-side comparison table (up to five problems)
- [ ] Customer validation planner (interview plan, experiments, go / pivot / stop rules)
- [ ] Export / import data as JSON
- [ ] Problems sourced from real, cited evidence
- [ ] More states, sectors and Indian languages
- [ ] React + Vite version

## Project files
| File | Purpose |
|---|---|
| `index.html` | The whole app |
| `docs/` | Screenshots used in this README |
| `LICENSE` | MIT license |
| `CONTRIBUTING.md` | How to help |

## Contributing
Ideas and pull requests are welcome. If you add a problem, phrase it as a hypothesis and say who has it and how they cope today. Don't add invented statistics. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License
MIT. See [LICENSE](LICENSE).
