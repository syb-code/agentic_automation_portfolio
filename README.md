# agentic_automation_portfolio

Portfolio site for Michael Gomez: web experience, growth marketing, and the AI systems (agents, orchestration and scheduled automation) behind them.

- `index.html` is the whole site: plain HTML and CSS with one small script for the copy-email button. No build step.
- `assets/img/` holds the project screenshots and portrait.

## View locally

```bash
python3 -m http.server 8000
# open http://127.0.0.1:8000
```

## Publish on GitHub Pages

Settings → Pages → Deploy from a branch → `main`, folder `/ (root)`. The `.nojekyll` file makes Pages serve the files as-is.
