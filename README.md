# The Pack's Signal in the Stars

StarDawg is a premium Solana meme token site with a strong visual identity, clear messaging, and real utility.

## About StarDawg

StarDawg represents more than just a token — it's a movement. Built on Solana's lightning-fast blockchain, $DAWG combines the energy of meme culture with genuine utility and premium positioning.

Our mission is clear: deliver a token with a distinctive visual identity, compelling messaging, and real-world use cases. StarDawg is engineered for communities that demand excellence.

## Features

- Premium green and black aesthetic with a cosmic, high-contrast feel.
- Animated 3D launch sequence (`welcome.html`) that spins the token logo and transitions into the main site.
- Static GitHub Pages hosting with no backend required.
- Dedicated whitepaper page for deeper project information.
- Live chart section for tracking $DAWG price, volume, and market trends, with automatic fallback to DEX Screener.
- Trading links to major Solana ecosystem tools (Jupiter, Raydium, Birdeye, DEX Screener, Cabana).
- Community and news links, including X/Twitter, Telegram, and Discord.
- `version.txt` deployment hash for quick verification of the live build.

## Live site

Visit the live site here: [StarDawg](https://shadowthemali.github.io/Stardawg/)

## Tokenomics

Designed for sustainability, growth, and community alignment.

### Total supply

1,000,000,000 $DAWG tokens carefully distributed to support long-term growth and community participation.

### Community utility

$DAWG powers governance, rewards, and ecosystem expansion. Holders gain access to exclusive features, strategic decisions, and future opportunities as the protocol evolves.

## Roadmap

Our vision for StarDawg unfolds across three strategic phases.

### Phase 1: Foundation

Landing page deployment, brand polish, GitHub Pages hosting, and community launch.

### Phase 2: Growth

Community expansion, social media rollout, partnerships, and ecosystem integrations.

### Phase 3: Utility

Protocol enhancements, real-world utility applications, ecosystem expansion, and governance implementation.

## Deployment

This site is deployed through GitHub Pages. Every production build includes a `version.txt` file that records the current short Git commit hash, making it easy to verify the live version.

To check the deployed version locally:

```bash
git rev-parse --short HEAD
curl https://shadowthemali.github.io/Stardawg/version.txt
```

If both values match, the deployed version is up to date.

## Repository structure

- `index.html` — the site's entry point. Shows the animated launch sequence and then redirects into `main.html`.
- `welcome.html` — a standalone copy of the launch sequence, kept for reference and local testing.
- `main.html` — the main StarDawg site (about, tokenomics, roadmap, chart, trade, connect, and news sections).
- `whitepaper.html` — whitepaper page.
- `version.txt` — current deploy hash.
- `assets/` — project images and other static assets, including the token logo.

## Local development

To preview the site locally, open `index.html` in a browser to see the launch sequence, or open `main.html` directly to go straight to the full site. You can also serve the folder with a local static server for a closer match to production behavior.

## Contributing

Contributions are welcome. Please keep updates consistent with the site's existing tone and branding, use relative or fully-qualified asset paths consistently, and avoid committing macOS metadata files such as `.DS_Store`.
