# 🦞 LEPE — 4chan Lobster Pepe

> *"Sort yourself out. Buy LEPE. Dominate the hierarchy."*

A funny futuristic single-page website for the **$LEPE** memecoin on Solana — the perfect fusion of Pepe the Frog and the legendary 4chan lobster meme.

## Live Site

**[lepe.pro](https://lepe.pro)**

Or open `index.html` locally — no build step, no server, no dependencies.

## Stack

- Pure **HTML / CSS / JavaScript** (zero frameworks)
- Google Fonts — [Orbitron](https://fonts.google.com/specimen/Orbitron) + [Share Tech Mono](https://fonts.google.com/specimen/Share+Tech+Mono)
- Animated matrix rain canvas
- Fully responsive

## Features

| Section | Description |
|---|---|
| Hero | Animated mascot, glitch title, copy-to-clipboard CA |
| Ticker | Live-scrolling meme news bar |
| Lore | 4chan greentext origin story |
| Why $LEPE | Feature cards with lobster / Peterson jokes |
| Tokenomics | 0% tax, LP burned, 100% community |
| Roadmap | 4 phases: Crawl → Pinch → Ascend → Feels Good Man |
| How to Buy | Step-by-step Solana guide |
| Community | Links to X Community & DexScreener |

## Token Info

| | |
|---|---|
| **Name** | LEPE — 4chan Lobster Pepe |
| **Ticker** | $LEPE |
| **Chain** | Solana |
| **Contract** | `3QsVBTqry3d2iqyttSWpy2H8jsKweHUoCNcesypzpump` |
| **Launched on** | pump.fun |
| **Community** | [X Community](https://x.com/i/communities/2025206134982803533) |
| **Chart** | [DexScreener](https://dexscreener.com/solana/3QsVBTqry3d2iqyttSWpy2H8jsKweHUoCNcesypzpump) |

## Deploy to GitHub Pages + lepe.pro

### 1. Push to GitHub
```bash
git remote add origin https://github.com/YOUR_USERNAME/lepe-website.git
git branch -M main
git push -u origin main
```

### 2. Enable GitHub Pages
- Go to repo **Settings → Pages**
- Source: `main` branch, `/ (root)`
- Custom domain: `lepe.pro`
- Check **Enforce HTTPS** once DNS propagates

### 3. Configure DNS on Hostinger
In your Hostinger DNS Zone, add these records:

| Type  | Name | Value               | TTL  |
|-------|------|---------------------|------|
| A     | @    | 185.199.108.153     | 3600 |
| A     | @    | 185.199.109.153     | 3600 |
| A     | @    | 185.199.110.153     | 3600 |
| A     | @    | 185.199.111.153     | 3600 |
| CNAME | www  | YOUR_USERNAME.github.io | 3600 |

DNS propagation takes up to 24–48 hours. GitHub Pages will auto-provision an SSL certificate once it verifies your domain.

## Disclaimer

Not financial advice. The lobster is not responsible for your portfolio decisions.
Past performance of crustaceans is not indicative of future gains. Trade responsibly, anon. 🦞
