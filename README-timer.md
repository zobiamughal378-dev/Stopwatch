# ⏱️ Pro Timer

A precision stopwatch with lap tracking, split-view layout, CSV export, and light/dark themes. Single HTML file, no dependencies, fully responsive (mobile + desktop).

---

## ✨ Features
- Start / Pause / Resume / Stop / Reset with millisecond precision
- **Lap tracking** with per-lap diff (faster/slower vs previous), best & average lap highlighting
- **CSV export** of all recorded laps
- Light & dark theme toggle (saved in `localStorage`)
- Keyboard shortcuts:

  | Key | Action |
  |-----|--------|
  | `Space` | Start / Pause |
  | `R` | Reset |
  | `L` | Add Lap |
  | `Ctrl/Cmd + E` | Export CSV |

- Responsive split layout — timer + laps side-by-side on desktop, stacked on mobile
- Toast notifications for user feedback

---

## 📁 Project Structure
```
├── index.html      # the entire app (HTML + CSS + JS)
└── README.md
```

## ▶️ Run it
Just open `index.html` in any modern browser — no build step, no install.

## 🚀 Deploy with GitHub Pages
1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder → **Save**.
4. Your app will be live at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

## 🛠️ Tech Stack
Pure HTML5 / CSS3 / vanilla JavaScript — no frameworks, no dependencies, works fully offline once loaded.

## 📱 Browser Support
Latest versions of Chrome, Firefox, Safari, and Edge (desktop & mobile).

## 📄 License
MIT — free to use, modify, and distribute.

## 🤝 Contributing
Issues and pull requests are welcome. Fork the repo, make your changes, and open a PR.
