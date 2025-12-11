# Cajun Token Assets (PulseChain)

This repository hosts the official **Cajun (CAJUN)** token logo for PulseChain (chainId **369**), plus a token list entry for use by DEXs, wallets, and explorers.

## Files
- `logo.png` — 256×256 transparent PNG (recommended for listings)
- `tokenlist.json` — ERC‑20 style token metadata used by Uniswap‑compatible token lists

## Publish with GitHub Pages
1. Push this repo to GitHub.
2. In **Settings → Pages**, set **Source** to `Deploy from a branch`, Branch: `main`.
3. After it builds, your logo URL will be:
   `https://scottlncs-crypto.github.io/cajun-token-assets/logo.png`
4. Update `logoURI` in `tokenlist.json` with your actual username.

## Submit to PulseChain Token Lists / PulseX
Provide the `tokenlist.json` entry or the `logoURI` directly, including:
```json
{
  "name": "Cajun",
  "address": "0xa62c512adba29f39c27ce49d75afa599fbbed09a",
  "symbol": "CAJUN",
  "decimals": 18,
  "chainId": 369,
  "logoURI": "https://scottlncs-crypto.github.io/cajun-token-assets/logo.png"
}
```

## Optional: IPFS Hosting
- Pin `assets/logo.png` via Pinata/NFT.Storage.
- Use a gateway URL as `logoURI`: `https://ipfs.io/ipfs/<CID>`

## Notes
- Use a **square, text‑free** logo for best compatibility.
- 256×256 works everywhere; 512×512 is ideal where supported.
- Keep the URL permanent and cache‑friendly.
