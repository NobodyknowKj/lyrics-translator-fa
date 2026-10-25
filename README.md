# متن و ترجمه‌ی آهنگ

A single-file Persian (RTL) website version of the private song-lyrics bot:
type a singer and a song, get the lyrics with a line-by-line Persian
translation, or paste lyrics yourself to translate them.

- Lyrics: lrclib first, lyrics.ovh as fallback.
- Translation: Google Translate, with MyMemory as fallback, batched in
  20-line chunks with per-line retry.
- Everything runs in the visitor's browser; there is no server and
  nothing is stored anywhere except recent searches in localStorage.

Live via GitHub Pages from `index.html` on `main`.
