# BoredTrencher — Free Solana Wallet Tracker

**Built with Claude AI. Single HTML file. No install. Runs in your browser.**

A free, open-source Solana wallet intelligence tool. Paste any wallet address, add your free Helius API key, and get a full plain-English breakdown of what that wallet has been doing on-chain.

[**→ Full version with Token Story + Big Buy Scanner at boredtrencher.xyz**](https://boredtrencher.xyz)

---

## What it does

### BoredTrencher
- Transaction history decoded into plain English — buys, sells, swaps, transfers (depth is user-selected)
- Current token holdings with SOL balances
- Outgoing transfer tracking
- AI verdict (optional) — Claude reads the on-chain data and gives a plain-English summary of what the wallet is actually doing. Requires an Anthropic API key.
- Choose how far back to look: 1,000 / 2,000 / 5,000 / 10,000 transactions

### Watchlist
- Add any number of Solana wallets to monitor
- Live polling — checks for new transactions automatically
- Browser notifications when a watched wallet makes a move
- Alert on buys, sells, or deposits — configure per wallet
- Scan back through recent history on any watched wallet

---

## How to use

1. Download `BoredTrencherLite.html`
2. Open it in your browser — no server, no install, no dependencies
3. Get a free Helius API key at [dashboard.helius.dev](https://dashboard.helius.dev)
4. Paste any Solana wallet address and hit Go

**Optional:** Add an Anthropic API key at [console.anthropic.com](https://console.anthropic.com) to enable the AI verdict feature.

---

## API keys needed

| Key | Required | Cost | Get it |
|-----|----------|------|--------|
| Helius | Yes | Free tier available | [dashboard.helius.dev](https://dashboard.helius.dev) |
| Anthropic | No (AI verdict only) | Pay as you go | [console.anthropic.com](https://console.anthropic.com) |

---

## Tech

- Single `.html` file — HTML, CSS, JavaScript
- No frameworks, no npm, no build step
- Helius API for on-chain transaction data
- Jupiter + Birdeye for token symbol enrichment
- Claude API (optional) for AI analysis
- Built entirely with [Claude](https://claude.ai)

---

## Full version

This is the lite version — Wallet Story and Watchlist only.

The full [BoredTrencher](https://boredtrencher.xyz) tool also includes:
- **Token Story** — analyse any token's buyer list, see who bought early, how much, and when
- **Big Buy Scanner** — real-time discovery of large buys on new and graduating tokens

[boredtrencher.xyz](https://boredtrencher.xyz)

---

## Disclaimer

Live on-chain data. Not financial advice. Not affiliated with Helius or Anthropic.
