# Interview Prep — Project Instructions

## What this project is

A single-page interview preparation dashboard (`index.html`) deployed on GitHub Pages. It contains tabs for HLD, LLD, LeetCode Plan, and a DSA Reference cheat sheet. Everything lives in one HTML file — no build tools, no external JS.

## How to work with this project

- All changes go in `index.html`. Never split into separate files.
- The site is deployed via GitHub Pages from the `main` branch. After pushing, deployment takes ~1-2 minutes.

## DSA Reference tab — keeping it up to date

The DSA Reference tab is the living part of this project. When I ask to add new strategies, algorithms, patterns, or problems:

1. **Add to the correct section** — find the matching top-level accordion (Arrays, Strings, Trees & Graphs, etc.) and the right subtopic within it.
2. **Create a new subtopic** if the pattern doesn't fit any existing one. Follow the same nested accordion structure: `dsa-subtopic` > `dsa-subtopic-header` + `dsa-subtopic-body` > `dsa-strategy` cards.
3. **Every strategy card must include**:
   - `.dsa-strategy-name` — the pattern/algorithm name
   - `.dsa-strategy-when` — 1-2 sentences on when to use it
   - `.dsa-badges` — time and space complexity badges using `complexity-badge time` and `complexity-badge space` classes
   - `.dsa-steps` — ordered list of 3-5 key steps
   - `.dsa-problems` — 3-5 problem chips as `<a class="problem-chip">` linking to `https://leetcode.com/problemset/?search=TERM`
4. **If I add a whole new data structure or category**, create a new `dsa-section` accordion block following the existing pattern (icon, title, chevron, collapsible body).
5. **Match the existing theme exactly** — use the CSS variables and classes already defined. Don't add new colors or fonts.
6. After changes, commit and push so GitHub Pages deploys automatically.

## Tab system

Tabs use `showTab(id, btn)`. Each tab has:
- A `<button class="tab" onclick="showTab('id',this)">` in the `.tabs` div
- A `<div id="id" class="tab-content">` for its content

When adding a new tab, add both the button and the content div.

## Styling conventions

- Headings: `font-family: 'Syne'`
- Body text: `font-family: 'DM Sans'`
- Code/tags/badges: `font-family: 'DM Mono'`
- Colors: `--accent` (purple #7c3aed), `--accent2` (cyan #06b6d4), `--accent3` (amber #f59e0b), `--accent4` (green #10b981)
- Tag classes: `tag-purple`, `tag-cyan`, `tag-amber`, `tag-green`, `tag-red`
