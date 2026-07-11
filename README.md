# Calculator Pro 🧮

A fast, keyboard-friendly scientific calculator that runs entirely in the browser. No frameworks, no build step, no tracking — just `index.html`, `style.css`, and `script.js`.

**[Live demo →](#)** *(update this link once deployed — see below)*

## Features

- **Standard & Scientific modes** — trig (with DEG/RAD toggle), logs, powers, roots, factorial, constants
- **Calculation history** — last 20 results, saved locally, click any entry to reuse it
- **Memory keys** — MC / MR / MS
- **Full keyboard support** — digits, `+ - * /`, `Enter`, `Backspace`, `Escape`, parentheses
- **Light & dark themes**, remembered between visits
- **Copy result** — click the display to copy the current value
- Fully responsive, accessible (focus states, `prefers-reduced-motion` respected)
- Everything persists locally via `localStorage` — nothing is sent anywhere

## Run it locally

Just open `index.html` in a browser — or serve it with any static server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a new repository on GitHub and push these files to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```
2. On GitHub, go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder, then **Save**.
4. Your site will be live in a minute or two at:
   `https://<your-username>.github.io/<your-repo>/`

## License

MIT — see [LICENSE](LICENSE).
# Calculator
