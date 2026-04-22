# HALETHEIA Organization Website

<div align="center">

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Visits](https://komarev.com/ghpvc/?username=haletheia-github-io&color=blue)]()

</div>

Official landing page and public documentation hub for the HALETHEIA ecosystem.
[https://haletheia.github.io](https://haletheia.github.io)

---

## 🎯 Architecture

This repository hosts the static frontend for the HALETHEIA platform. It serves as the public entry point showcasing our Open Core model: 5 Core Stacks, 14 Public Projects, the Security Triad v2.0, Hidden-Brain RAG 4.0, and the NIDALI Agent Harness.

```text
haletheia.github.io/
├── index.html              # Main landing page (Ecosystem Overview)
├── security.html           # Security Stack (Xokito, Ethilia, GAIA, Cutufato)
├── knowledge.html          # Knowledge Stack (Hidden-Brain RAG 4.0)
├── agents.html             # NIDALI Harness (NIDA, LiiaDA, AIR Platform)
├── hcp.html                # HCP Protocol (Context Engineering)
├── waitlist.html           # Beta Access Waitlist
├── products/               
│   └── security-triad.html # Deep dive into the Security Triad
├── README.md               # This documentation
└── .github/
    └── workflows/
        └── deploy.yml      # GitHub Actions CI/CD for automated deployments
```

---

## 🚀 Local Development

The site is built with pure semantic HTML5 and vanilla CSS/JS. **Zero build steps required.**

```bash
# Clone the repository
git clone https://github.com/haletheia/haletheia.github.io
cd haletheia.github.io

# Start a local server (Python 3)
python3 -m http.server 8000

# Open in your browser
# http://localhost:8000
```

---

## 🛠️ Tech Stack

- **Pure Semantic HTML5**: No frameworks, no build steps.
- **Custom CSS**: Zero dependencies. Uses CSS variables, grid, and flexbox for responsive design.
- **Vanilla JavaScript**: Lightweight DOM manipulation (IntersectionObserver for scroll animations).
- **Fonts**: Space Grotesk & JetBrains Mono (loaded via Google Fonts).
- **Hosting**: GitHub Pages.
- **CI/CD**: GitHub Actions.

---

**Organization**: [github.com/haletheia](https://github.com/haletheia)
