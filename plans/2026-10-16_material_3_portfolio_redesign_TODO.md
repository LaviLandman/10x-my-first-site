# TODO - Material 3 Portfolio Redesign

## Context
Redesign the existing minimal portfolio page into a full, modern personal portfolio conforming to Google Material Design 3 (https://m3.material.io/). The implementation is isolated within a new Git worktree on branch `feature/material-3-redesign`, incorporates official Google Material Web Components (`@material/web`), English typography and content (Hero, About, Skills, Projects, Contact), and an interactive Light/Dark theme toggle using M3 design tokens.

## Tasks

- [x] 1. Create a dedicated git worktree
       Files: `../10x-my-first-site-m3`
       Done when: Worktree directory `../10x-my-first-site-m3` is created on new branch `feature/material-3-redesign` and verified via `git worktree list`.

- [x] 2. Define Material 3 design tokens, typography, and styling
       Files: `../10x-my-first-site-m3/styles.css`
       Done when: CSS file defines M3 light and dark theme color roles (sys/color/primary, surface, on-surface, outline, surface-container, etc.), Roboto and Material Symbols typography imports, container layouts, and responsive rules.

- [x] 3. Implement full portfolio layout with Material Web Components in index.html
       Files: `../10x-my-first-site-m3/index.html`
       Done when: `index.html` contains English language structure (`lang="en" dir="ltr"`), Material Web component imports via CDN (buttons, cards, chips, icon buttons, icons), and full sections: Top Navigation Bar, Hero/Introduction, About Me, Skills & Technologies, Featured Projects, and Contact/Social Links.

- [x] 4. Add interactive Material 3 Light/Dark theme toggle
       Files: `../10x-my-first-site-m3/theme.js` (or embedded script)
       Done when: Clicking the theme toggle switches between Light and Dark M3 color schemes, persists user preference in `localStorage`, and defaults gracefully to system `prefers-color-scheme`.

- [x] 5. Test and verify worktree site
       Files: `../10x-my-first-site-m3/index.html`, `../10x-my-first-site-m3/styles.css`, `../10x-my-first-site-m3/theme.js`
       Done when: Files are validated for clean syntax, proper component imports, and worktree git status is inspected and confirmed ready.

## Out of Scope
- Backend server or dynamic contact form processing (static client-side mailto / links only).
- Merging branch `feature/material-3-redesign` into `main` or pushing to remote (requires explicit user confirmation per Git guidelines).
- Building custom npm/webpack bundlers (CDN-based modern ES modules will be used).
