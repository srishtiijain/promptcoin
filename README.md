# promptcoin
# PromptCoin — $PRMPT

> AI-native deflationary token landing page. Built for the **PromptX Competition**.

![PromptCoin](https://img.shields.io/badge/token-%24PRMPT-00e5ff?style=flat-square) ![Network](https://img.shields.io/badge/network-Ethereum%20%2B%20Solana-ffc400?style=flat-square) ![Audit](https://img.shields.io/badge/audit-CertiK-00e676?style=flat-square)

---



## Features

- **Live price engine** — simulated $PRMPT/USD price updating every 2 seconds across nav, hero card, and terminal
- **Scrolling ticker** — PRMPT/USD live price + BTC, ETH, SOL, GAS market data
- **Two separate modals**
  - **BUY NOW** → 3-step wallet connect flow (MetaMask / Phantom / WalletConnect → amount → confirm)
  - **SWAP TOKENS** → ETH→PRMPT exchange with live rate calculation
- **Coin shower** — 55 3D gold/cyan/silver coins explode from every button click
- **Plexus background** — constellation canvas with mouse repulsion
- **Custom cursor** — cyan dot + ring with lerp follow
- **Tokenomics donut** — interactive SVG pie chart
- **FAQ accordion** — 6 items, smooth max-height transition
- **Price terminal** — macOS-style window with live SVG chart
- **Scroll reveals** — IntersectionObserver fade-up animations
- **Copy contract** — clipboard copy with visual feedback

---

## Stack

| Layer | Tech |
|---|---|
| Markup | Semantic HTML5 |
| Styling | Pure CSS (custom properties, Grid, Flexbox, clip-path) |
| Logic | Vanilla JavaScript (IIFE, no frameworks) |
| Fonts | Google Fonts — Teko, Rajdhani, Share Tech Mono |
| Canvas | `requestAnimationFrame` — plexus + coin shower |
