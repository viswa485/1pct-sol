# 1% BATTERY ($1PCT)

**The future is updating. Your bills aren't.**

1% BATTERY is an internet-culture project built around the feeling of trying to navigate modern life with 1% battery left. Its themes are economic pressure, AI and the future of work, and cybersecurity and online safety.

> **Project status:** The repository currently contains a landing-page prototype. Do not treat the token as launched, the displayed token specifications as verified, or the placeholder links as official live destinations until they have been independently confirmed.

## Project identity

- **Brand:** 1% BATTERY
- **Ticker:** $1PCT (project-selected symbol; verify the mint address before any token interaction)
- **Community concept:** The 1% Club
- **Network / launch platform concept:** Solana / Pump.fun
- **Tagline:** The future is updating. Your bills aren't.

The project is intended to use humour and community participation to explore three themes:

1. **ECON.EXE** — rent, salaries, job hunting, subscriptions and everyday costs.
2. **AI.EXE** — AI tools, changing skills and the future of work.
3. **CYBER.EXE** — phishing, fake job offers, deepfakes and digital safety.

## What's in this repository

- `index.html` — a responsive single-page landing site.
- A built-in canvas meme generator with preset captions and custom top/bottom text.
- Project sections introducing the three themes and displaying token information.
- Placeholder links and contract-address text that must be replaced before public promotion.

The landing page is plain HTML, CSS and JavaScript. It does not require a package manager, build step or server-side application.

## Run locally

You can open `index.html` directly in a browser, or start a simple local web server from the repository directory:

```bash
python3 -m http.server 8000
```

Then visit:

```
http://localhost:8000
```

## Configure the website before publishing

Open the `CONFIG` object near the bottom of `index.html` and replace the placeholders only when the official destinations exist and have been verified:

```js
const CONFIG = {
  CONTRACT_ADDRESS: "YOUR_VERIFIED_SOLANA_MINT_ADDRESS",
  PUMP_FUN_URL: "YOUR_OFFICIAL_PUMP_FUN_COIN_URL",
  DEXSCREENER_URL: "YOUR_VERIFIED_DEXSCREENER_PAIR_URL",
  TELEGRAM_URL: "YOUR_OFFICIAL_TELEGRAM_URL",
  X_URL: "YOUR_OFFICIAL_X_PROFILE_URL"
};
```

Also review the visible token name, ticker, token-supply display, fair-launch wording and disclaimer in the HTML. These are website content, not proof of an on-chain token configuration or completed launch. Update them only after checking the actual token and the project's approved disclosures.

Do not publish a fabricated contract address, fake social account, unsupported supply claim, guaranteed return, guaranteed graduation claim or unverified liquidity statement.

## Publish with GitHub Pages

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**.
4. Save the settings and wait for GitHub Pages to finish deploying.

Expected project URL:

https://viswa485.github.io/1pct-sol/

The URL becomes active only after GitHub Pages is enabled and its deployment succeeds. Check the Pages settings or Actions deployment status if it does not load.

## Editing and contributing

For a simple content or design change:

1. Edit `index.html`.
2. Test it locally at desktop and mobile widths.
3. Check every navigation link and interactive control.
4. Commit the change to the `main` branch.

Keep the site lightweight and accessible. Use original artwork or assets that the project has permission to use.

## Roadmap ideas (not promises)

The broader community concept may explore useful, free resources related to:

- **Scam awareness:** explain suspicious signals in messages, URLs and recruitment offers.
- **AI and careers:** practical AI literacy and skill-learning resources.
- **Money and everyday life:** educational cost-of-living and budgeting tools.

These are ideas for future exploration, not currently delivered products or token-holder entitlements. Any product should be useful without requiring someone to buy or hold the token.

## Risk and transparency

$1PCT is intended as a speculative memecoin. Crypto-assets can be extremely volatile and buyers can lose all of the money they spend. A website, community, meme, roadmap or Pump.fun listing does not guarantee value, liquidity, adoption, graduation or future development.

- No guaranteed profit or price target.
- No guaranteed liquidity or exchange listing.
- No promise of passive income or revenue share.
- Token ownership does not represent company equity or ownership of project products.
- Verify the official mint address and links independently before interacting with a token or pool.
- Never share a wallet seed phrase or private key.
- Disclose paid promotions and material project-wallet interests.
- Do not use fake followers, wash trading, artificial volume or misleading claims.

If the project makes a public token offer or promotes a crypto-asset in Germany or elsewhere in the EU, obtain appropriate legal advice and complete the applicable regulatory review before launch or promotion. Technical availability on a launch platform is not proof of legal compliance.

## Disclaimer

This repository is for the project's website and community information. It is not investment, financial, legal or tax advice, and nothing here is an offer or recommendation to buy a crypto-asset. Do your own research and only risk money you can afford to lose.
