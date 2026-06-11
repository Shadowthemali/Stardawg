# StarDawg Landing Page (`index.html`)

This commit adds the final StarDawg landing page, replacing the minimal placeholder page with a fully branded, multi-section layout.

## Overview

The new `index.html` is a single-page, static site designed to present StarDawg ($DAWG) as a polished Solana meme token brand. It uses a dark, cosmic background with gold accent colors to match the StarDawg identity and focuses on clarity, readability, and quick navigation.

Key characteristics:

- **Single static file** (no build step required)
- **Responsive layout** (works on desktop and mobile)
- **Dark / gold theme** with a clean, modern UI
- **Simple navigation** using in-page anchors

## Page Structure

The page is organized into the following major sections:

1. **Header / Navigation**
   - Sticky header with the StarDawg logo badge (“DAWG”) and wordmark.
   - Navigation links: About, Tokenomics, Roadmap, Links.
   - Smooth-scroll behavior for in-page navigation.

2. **Hero Section**
   - Eyebrow text: “Built for the pack • Solana native • $DAWG”.
   - Main headline: positions StarDawg as “the pack’s signal in the stars”.
   - Supporting copy describing the site as the high-energy landing page for the project.
   - Primary call-to-action buttons:
     - “Explore links” → jumps to the Links section.
     - “View tokenomics” → jumps to the Tokenomics section.
   - Right-hand stat cards summarizing:
     - Token: `$DAWG`
     - Chain: `Solana`
     - Theme: `Dark / Gold`

3. **About Section**
   - Short explanation of what StarDawg represents: a meme-driven crypto brand with strong visual identity and clear messaging.
   - Emphasis on this being the “final”, non-placeholder version of the page.

4. **Tokenomics Section**
   - Three simple cards:
     - **Supply** – communicates a 1,000,000,000 token supply.
     - **Identity** – highlights the visual and thematic choices (gold accents, cosmic background).
     - **Community** – focuses on calls to action and future utility.

5. **Roadmap Section**
   - Concise, 3‑phase roadmap:
     - Phase 1: Final landing page and brand polish.
     - Phase 2: Community growth and social rollout.
     - Phase 3: Utility, updates, and ecosystem expansion.

6. **Links Section**
   - Button-style links intended to be wired to real project URLs:
     - Whitepaper
     - X / Twitter
     - Telegram
     - Chart
   - Currently placeholder `href="#"` values; meant to be updated with live URLs.

7. **Footer**
   - Simple footer text: `© 2026 StarDawg. Built for the pack.`

## Styling and UX Notes

- **CSS-in-HTML**: All styling lives inside a `<style>` block in the `<head>`, so there are no external CSS dependencies.
- **Accessibility**:
  - Includes a “Skip to content” link for keyboard and screen reader users.
  - Semantic sectioning: `<header>`, `<main>`, `<section>`, `<nav>`, `<footer>`.
- **Error Logging**:
  - Retains the existing `window.addEventListener('error', …)` and `unhandledrejection` handlers to log errors to the console.

## How to Customize

Before mainnet or wider promotion, you should:

- **Update project URLs** in the Links section:
  - Set real links for Whitepaper, X / Twitter, Telegram, and Chart.
- **Adjust copy**:
  - Tune the hero headline and lead text to match the final brand tone.
  - Update tokenomics and roadmap text as the project evolves.
- **Swap branding**:
  - If you have a custom StarDawg logo image, you can replace the “DAWG” text badge with an `<img>` tag in the header.

## Deployment

This file is designed to be served directly by GitHub Pages:

- Commit `index.html` to the repo’s publishing branch (commonly `main`).
- Ensure GitHub Pages is configured to publish from the correct branch and root folder.
- Once pushes work (auth/403 issues resolved), GitHub Pages will serve this landing page as the project site.
