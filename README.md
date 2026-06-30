# The Notebooks
## A Series of Living Practice Repositories

A landing hub linking a series of practitioner-focused, AI-coached framework notebooks.

**Live site:** `https://bwtwong.github.io/notebooks` *(update once deployed — or use as your GitHub profile landing page)*

---

## The series

| Notebook | Focus | Repo |
|---|---|---|
| **Health Equity WA Notebook** | Visual policy knowledge hub for WA health equity | `health-equity-WA-notebook` |
| **The Consulting Playbook** | 31 frameworks across consulting practice, including case interviews | `consulting-playbook` |
| **Health Commercialisation & Innovation Playbook** | TGA/PBAC/MSAC pathways, readiness scales, HEOR | `health-innovation-playbook` |
| **Impact Investing Playbook** | 14 frameworks — measurement, deal structuring, portfolio construction | `impact-investing-playbook` |
| **Implementation Science & MEL Cheatsheet** | 8 academic frameworks for proving something survives scale and handoff — reference only, no AI practice mode | `implementation-science-cheatsheet` |

---

## Design principle

Every notebook in this series follows the same model: frameworks built to be **applied**, not just read. Each includes a realistic practice scenario and AI-coached feedback (via the Claude API), so the goal throughout is rehearsal, not memorisation.

They are living documents — updated as new frameworks are encountered in practice — and publicly accessible to anyone navigating the same path.

## The Journey (why this exists)

The hub includes a section called "Why This Exists" — a reflection on the pattern that emerged after building four notebooks: every framework, regardless of discipline, does its work at one of five recurring stages of any project — **Diagnose, Decide, Fund, Prove, Scale**. The page includes an interactive map showing which frameworks from which notebooks cluster at each stage, demonstrating that consulting, health innovation, impact investing, and implementation science all reinvent the same underlying moves with different vocabulary. All 66 frameworks across the series are represented on the map.

This section is personal, not just structural — it's a working thesis about translation across complex systems as a career direction, evidenced by the act of building the notebooks themselves.

---

## Setup notes

This hub is a single static HTML file with hardcoded links to the other four repos. If you rename any of the other repositories, update the corresponding `href` in `index.html`.

To deploy: create a new repo (suggested name: `notebooks` or use this as your GitHub Pages profile site at `bwtwong.github.io`), upload `index.html` and this README, then enable GitHub Pages under Settings → Pages.

**Tip:** if you name this repo exactly `bwtwong.github.io`, it becomes your default GitHub profile landing page — visible at `https://bwtwong.github.io` directly, no extra path needed.

All interactive elements (notebook cards, journey map stages) are keyboard-operable and screen-reader labelled — `role="button"`, `tabindex`, `aria-expanded`, and visible focus states are applied throughout.

---

## Tech

Plain HTML/CSS. No dependencies, no build step.
