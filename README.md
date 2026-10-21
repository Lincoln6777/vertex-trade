# Vertex Trade (simulated)

A fake, live-updating stock brokerage dashboard. All prices, trades and balances are simulated in the browser — no real market data or money is involved.

**Live demo:** https://vertex-trade-three.vercel.app

## Run locally

It's a single file with no dependencies. Open `index.html` in any browser.

## Customize

At the top of the `<script>` in `index.html`:

- `USER` — the name shown in the greeting and notifications
- `START_VALUE` — the starting account value

## Hidden controls

| Key | Action |
|---|---|
| `4` | Steady climb of +$10k–$50k |
| `3` | Steady climb of +$3k–$8k |
| `1` | Gradual dip of −$2k–$6k |
| `2` | Gradual drop of −$8k–$15k |
| `0` | Stop the current move |
| `9` | Smoothly undo all moves |
| `` ` `` | Toggle the admin panel (custom amounts, target value, pause auto-trading) |

## License

MIT
