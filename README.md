# MeloShare

A mobile-friendly playlist sharing web app built with HTML, CSS, JavaScript, Firebase Authentication (anonymous) and Cloud Firestore.

## Setup
1. Create a Firebase project and register a Web App.
2. Copy the Firebase web config into the `firebaseConfig` object in `index.html`.
3. In Firebase Authentication, enable **Anonymous** sign-in. There is no visible login screen; anonymous auth gives each browser a private owner identity.
4. Create a Cloud Firestore database.
5. Paste `firestore.rules` into Firestore Rules and publish.
6. Enable GitHub Pages for this repository (Settings → Pages → Deploy from a branch → main → /(root)) to host the static site.

## YouTube
Add a YouTube video URL or 11-character video ID to a playlist. Playback uses YouTube's privacy-enhanced embedded player. This starter does not download audio/video and does not include automatic YouTube search.

## Notes
- Public playlists are readable by everyone; private playlists are readable only by their owner.
- Anonymous ownership is tied to browser storage. Clearing browser data or changing devices can lose access to playlists created under that anonymous identity. Add account linking before depending on permanent ownership.
- Review and strengthen Firestore rules and add abuse controls before a large public launch.
