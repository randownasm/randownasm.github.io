# wnasmile4evr (`v0.8.4.3` ➔ `v0.9`)

Welcome to **wnasmile4evr**, the revived, overhauled, and future-proofed home of the `wnasmile` game library and web dashboard portal. 

This repository picks up right where the old live site left off, shifting development focus toward cleaning up the lightweight backend architecture, modernizing the frontend experience, and driving development toward the highly anticipated **Version 0.9** milestone.

## 🚀 The Stack
*   **Frontend:** Pure Semantic HTML5, Modular CSS3 (Custom Theme Engines), and Vanilla JavaScript
*   **Light Backend:** Google Apps Script (`.gs`) managing user data pipelines, widgets, and dynamic configurations.

---

## 🗺️ The Road to v0.9

We are currently building on top of stable build **v0.8.4.3**. Here is our core checklist as we march toward the `v0.9` release:

- [ ] **Codebase Modernization** - Refactor inline scripts and unify theme-loading priorities (Classic, Redux, etc.).
- [ ] **Apps Script Optimization** - Streamline the Google Apps Script backend to handle user configurations, profile edits, and external widget loading faster.
- [ ] **Data Portability Stability** - Solidify local user storage pipelines (Import/Export/Transfer Data features) to prevent save state data loss.
- [ ] **Discovery & Widget Expansion** - Re-index the dynamic Discovery section and improve performance for embedded widgets and iframe sandboxing.
- [ ] **Bug Polish** - Resolve the "blob:null" edge cases and settle layout shifts during theme preloads.

---

## 🛠️ Project Architecture

A quick map of how the project is organized to help you navigate the directories:

```text
├── assets/             # Shared branding, themes (classic/redux), and favicons
├── system/             # Core structural game & portal assets
│   ├── js/             # Script modules (versioning, settings engines)
│   └── pages/          # Embedded views (Favorites, Discovery, News, About, DMCA)
├── index.html          # Gateway portal and container layout
└── .gitignore          # Keeps the local credentials and system junk out of GitHub
