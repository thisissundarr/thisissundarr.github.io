# Sundararaman Rengarajan, Personal Portfolio

Minimal multi-page personal website for GitHub Pages, inspired by [mallesham.com](https://mallesham.com/).

## Files

| File | Page |
|------|------|
| `index.html` | Landing |
| `about.html` | Personal statement |
| `work.html`  | Publications, research, awards, teaching, service, education |
| `portfolio.html` | Selected research projects (question, method, finding, impact) |
| `notes.html` | Talks, podcasts, writing |
| `life.html`  | Personal narrative |
| `style.css`  | Shared stylesheet |
| `Sugar_Slay_Acorn_Presentation.pdf` | Sugar Slay overview deck, linked from the portfolio page |

## Deploy on GitHub Pages

1. Create a repo named `thisissundarr.github.io` (your GitHub username plus `.github.io`)
2. Upload all files to the repo root (including `Sugar_Slay_Acorn_Presentation.pdf`, so the portfolio deck link resolves)
3. Settings, then Pages, then Deploy from branch, then main, then / (root)
4. Live at `https://thisissundarr.github.io` within about 1 minute

## Add your photo

Replace the placeholder div on `index.html` and `work.html`:

```html
<img src="profile.jpg" alt="Sundararaman Rengarajan" class="photo">
```

Upload `profile.jpg` to the repo root.
