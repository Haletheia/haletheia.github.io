# HALETHEIA Organization Website

<div align="center">

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Visits](https://komarev.com/ghpvc/?username=haletheia-github-io&color=blue)]()

</div>

Official landing page and public documentation hub for the HALETHEIA ecosystem.
[https://haletheia.github.io](https://haletheia.github.io)

---

## 🎯 Architecture

This repository hosts the static frontend for the HALETHEIA platform. It serves as the public entry point showcasing our Open Core model: 5 Core Stacks, 14 Public Projects, the Security Triad v2.0, Internal Knowledge Engine, and the NIDALI Enterprise Harness.

```text
haletheia.github.io/
├── index.html              # Main landing page (Ecosystem Overview)
├── documentation.html      # Technical Guides (Gateway, Security, HCP)
├── use-cases.html          # Corporate & Enterprise Use Cases
├── specs.html              # HCP Protocol Specifications
├── waitlist.html           # NIDALI Beta Access Waitlist
└── README.md               # This documentation
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
