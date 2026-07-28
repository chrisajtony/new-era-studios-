# New Era Studios

Company deck / one-page site for **New Era Studios** — the AI production studio built by filmmakers.

- Single static page: `index.html` (Tailwind via CDN, Google Fonts)
- Local media in `assets/`
- The four large showcase clips (Love, Sci-Fi, The Fae Prince, Viking) are **hosted externally**
  because they exceed GitHub's 100 MB per-file limit. Paste their URLs into the
  `VIDEO_URLS` object near the bottom of `index.html`. Until then, each card shows a poster still.

## Local preview
```
python3 -m http.server 3000
# open http://localhost:3000
```
