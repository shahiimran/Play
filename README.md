# MeloShare

A static YouTube playlist sharing page hosted with GitHub Pages.

## Publish
GitHub repository Settings → Pages → Deploy from a branch → `main` → `/(root)`.

Site: https://shahiimran.github.io/Play/

## Public playlists
Edit `playlists.json` in the repository root. Each item is one YouTube video:
```json
[
  {"id":"song-1","title":"Bangla Favorites","creator":"MeloShare","category":"Bangla","description":"Songs to enjoy","videoId":"YOUTUBE_VIDEO_ID"}
]
```
Entries with the same title are grouped by the website. Use a real YouTube video ID.
