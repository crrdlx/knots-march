# Knotzi Death March Countdown

A doomsday-clock-styled countdown to BIP-110, tracking how many blocks remain before users running Knot nodes are forked off the Bitcoin network.

## What it does

Fetches the current Bitcoin block height from [mempool.space](https://mempool.space) and counts down to block **961,632** — the BIP-110 activation target. The UI is styled after the Bulletin of the Atomic Scientists' Doomsday Clock, with an analog clock face, serif typography, and a minimal dark aesthetic.

## Background

- [A Layman's Guide to BIP-110](https://blog.lopp.net/a-laymans-guide-to-bip-110/)
- [It's Knot a Serious Project](https://blog.lopp.net/knot-a-serious-project/)

## Usage

Open `index.html` in any browser. No build step, no dependencies beyond Bootstrap 5 and Google Fonts (both CDN). Block height refreshes every 60 seconds.

## Technical details

- **Target block:** 961,632
- **Start block:** 840,000 (progress baseline)
- **Block time estimate:** 10 minutes/block
- **Data source:** `mempool.space/api/blocks/tip/height`

## License

Open source — see [github.com/jlopp/knotzi-death-march](https://github.com/jlopp/knotzi-death-march)