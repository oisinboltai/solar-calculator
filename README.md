# ☀️ SolarCalc — Solar Savings Estimator

A clean, interactive solar savings calculator for renewable energy installers. Built as a static HTML/CSS/JS app — no build step required.

## Features

- Estimate annual savings based on bill, roof size, location & tariff
- System size & panel count calculator
- Payback period with visual progress bar
- CO₂ offset & tree equivalent
- Mobile responsive

## Deploy

This is a static site. Deploy on Coolify, Vercel, Netlify, or any static host.

No build step needed — just serve `index.html`.

## Customisation

Edit the constants in the `<script>` block:
- `costPerKwp` — installed cost per kWp (default €1600)
- `exportRate` — feed-in tariff multiplier (default 30% of retail)
- Panel efficiency, system losses, CO₂ factor

## License

MIT
