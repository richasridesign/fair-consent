# Fair consent

A playground for cookie banners that are friendly and fair. Every yes opens the blinds a little more, so you can see how much a website gets to see of you.

- Pick a style that suits the website: Simple, Night, Paper or Blueprint.
- Change the fairness settings (layout, button weight, where Reject sits, wording, defaults, a way back) or use the Make it tricky and Make it fair presets.
- The honesty check scores the banner against six rules, each linked to guidance from European privacy regulators. Not legal advice.

## Run it

It is one static HTML file with no build step.

```bash
python3 -m http.server 5176
```

Then open http://localhost:5176.

## Deploy

Netlify publishes the repository root from `main` (see `netlify.toml`).
