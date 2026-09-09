# BusinessCentralTechnicalDocs

Public changelog for Interpolimeri's Business Central SaaS environment, published via GitHub Pages at https://interpolimeri.github.io/BusinessCentralTechnicalDocs/. The entire published page is a single file: `docs/index.html`.

BC source code lives in a separate repo, `C:\Repo\BusinessCentral` (GitHub `interpolimeri/BusinessCentral`). That repo's `tools/changelog/*.ps1` scripts are a **retired** automated pipeline (fetch → AI-enhance → combine → publish) that produced every entry through release 27.4.408.0. Do not run or extend it — it's kept only as historical reference. Since release 28.3.415.0, every changelog entry is drafted manually in a Claude Code chat, reviewed by the user step by step (not autonomous).

## When asked to draft a new release entry

Follow this sequence, checking in with the user at each step rather than running it end to end unattended:

1. **Gather the source material.** Get the diff / merged commits / PR description for the new release from `C:\Repo\BusinessCentral` (or the user pastes it). Identify what changed since the last published release.
2. **Filter for relevance.** Keep only what a Business Central *user* would notice or care about: new functionality, changed workflows, fixed bugs that were user-visible. Drop pure noise: refactors, `settings.json`/build/CI tweaks, internal renames, permission-set plumbing, dependency bumps with no user-facing effect. Confirm the filtered list with the user before writing prose.
3. **Draft the narrative.** Write it in the exact tone/structure of the current "Latest Release" section in `docs/index.html` — see Style guide below. Show the draft, iterate with the user.
4. **Edit `docs/index.html`** (see HTML edit points below). Get explicit confirmation before touching the file if the draft isn't fully settled yet.
5. **Visually verify** — open the file in a browser, check the new `<details>` card opens/closes, light/dark theme still renders correctly, sidebar link works.
6. **Commit & push only with explicit user confirmation** — this is a public page.

## Style guide for changelog prose

Match release 28.3.415.0 in `docs/index.html`, currently the reference example:

- Three categories, in this order, each its own `<section class="section modern-release-block">`:
  - `<h2>✨ New Features</h2>`
  - `<h2>🚀 Improvements</h2>`
  - `<h2>🪲 Corrections and Stability Improvements</h2>` (this one is often a single summarizing `<p>`, not itemized, when fixes are minor/numerous)
- Inside New Features / Improvements: one `<div class="item"><h3>Short Title</h3><p>1-3 sentence paragraph(s)</p></div>` per feature. Business/functional language — describe what changed for the user and why it matters, not which table/field/object was touched.
- **No** `[App: X - Author: Y]` tags, **no** per-module grouping (Finance/Sales/Purchase/...) — that granular technical style belongs only to the pre-August-2026 archived entries and should not be reintroduced for new ones.
- Archived entries going forward are archived **in this same narrative style**, not converted to the old technical bullet format — see decision in project memory. Don't maintain two content styles.

## HTML edit points in `docs/index.html`

The file is one long minified-ish HTML document (few very long lines) — use Grep/targeted Read with offset+limit, not a full Read (it exceeds the token read limit).

When publishing a new release, four places change:

1. **Hero badges** (near `id="top"`): `<span class="badge">Latest Version X.Y.Z.W</span>` and the date badge next to it.
2. **Sidebar nav** (top of `<aside class="sidebar">`): the `latest-link` becomes a normal `release-link` pointing at the new archived id, and a new `latest-link` line is added at the top for the new release. Add a new `<div class="nav-year">YYYY</div>` block only if the year changed.
3. **`<section id="latest-release">`**: replace its content with the new narrative draft. Grep for `id="latest-release"` to find it.
4. **Archive the previous latest release**:
   - Add a row to the `id="archived-releases"` table (`Release | Type | Highlights`), as the first `<tr>`.
   - Wrap the *previous* "Latest Release" content into a new `<details class="changelog-card" id="release-X-Y-Z-W"><summary><span>Release X.Y.Z.W - DD/MM/YYYY</span><small>PR #NNN</small></summary><div class="archived-content">...</div></details>`, inserted as the first card right after `<section ... id="archived-changelogs">`.

Grep for `id="release-27-4-408-0"` or similar to see a concrete example of an existing archived card's structure.
