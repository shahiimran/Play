# MeloShare

MeloShare is a lightweight YouTube playlist sharing website.

## Publish with GitHub Pages

1. Open **Settings** in this repository.
2. Select **Pages** from the sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/ (root)**, then Save.
5. Wait for GitHub Pages to finish publishing.

Your site address will be:

https://shahiimran.github.io/Play/

## Playlists

The website reads public playlist entries from `playlists.json` in the repository root. Each entry represents one YouTube video. Entries with the same `title` are grouped into one playlist.

Example:

```json
[
  {
    "id": "song-1",
    "title": "Bangla Favorites",
    "creator": "MeloShare",
    "category": "Bangla",
    "description": "Songs to enjoy",
    "videoId": "VIDEO_ID_HERE"
  }
]
```

Replace `VIDEO_ID_HERE` with an actual 11-character YouTube video ID. You can create/export entries using the private editor in the `Playpass` repository, then upload the exported JSON here.

## Notes

- Public playlists are loaded from `playlists.json`.
- Personal drafts are saved in the visitor's browser only.
- This static version has no account system or server-side admin authentication.
