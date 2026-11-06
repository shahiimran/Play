# MeloShare

A no-backend playlist sharing web app hosted as a static site. Built with plain HTML, CSS and JavaScript.

## Features
- No login, Firebase, database, or API key.
- Create and edit playlists in this browser.
- Save playlists locally with LocalStorage.
- Share a playlist using a self-contained link (playlist data is encoded into the URL fragment).
- Anyone with the shared link can open and play the playlist.
- YouTube playback uses the official privacy-enhanced embedded player.
- Dark/light theme and English/Bangla interface.

## Hosting on GitHub Pages
1. Open repository **Settings → Pages**.
2. Select **Deploy from a branch**.
3. Choose branch `main` and folder `/(root)`, then Save.
4. Wait for GitHub Pages to publish. The expected URL is https://shahiimran.github.io/Play/

## Important limitation
Without a server or shared database, there is no central public playlist directory or automatic cross-device sync. Playlists you create are saved only in your current browser. To share one, use its Share button: the playlist is embedded in the generated link, and anyone with that link can view/play it. If you want a global discover page where everyone automatically sees all newly created public playlists, a backend/database is required.

## YouTube
Add a YouTube video URL or 11-character video ID. Playback happens inside YouTube's privacy-enhanced embedded player. MeloShare does not download audio/video.
