# Sweepbot UI (native-only)

This is a **client-side** (browser-only) page that lets you:

1. Connect your EVM wallet (MetaMask, Rabby, etc.)
2. Enter a **secure destination** address
3. Click **Sweep** to send **all your native balance minus gas** to that address

No backend. No API keys. Meant for **testnets first**.

---

## Features

- ✅ Native token sweep (ETH / BNB / MATIC / AVAX / L2 ETH)
- ✅ Dry-run mode (ON by default) so you can test without sending anything
- ✅ Balance check button
- ✅ Activity log
- ✅ Works on GitHub Pages (HTTPS)

---

## How to run locally

Option 1: open the file

1. Double-click `index.html`
2. Open in Chrome/Brave with MetaMask installed
3. Connect wallet → set address → test

Option 2: simple HTTP server

```bash
python -m http.server 8000
# then open http://localhost:8000
