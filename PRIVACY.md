# Sonvela Privacy Policy

_Last updated: October 31, 2026_

Sonvela is a desktop music player for Windows. This policy explains what data the app handles. In short: **your library stays on your computer, Sonvela has no servers of its own, and it does not collect analytics, show ads or sell data.**

## Data stored on your computer

The following is saved locally in your Windows user profile and never sent to us:

- your liked songs, playlists, saved albums and artists;
- listening history and search history (both can be turned off or cleared in **Settings → Privacy**);
- settings, window position, the play queue;
- technical error logs (used only for troubleshooting; you can open the folder from **Settings → System → Logs**).

**Settings → Privacy → Delete all local data** removes your library and history from the computer.

## Services Sonvela connects to

Sonvela talks directly to these services. We do not run any servers in between and cannot see these requests.

| Service | When | What is sent |
|---|---|---|
| **YouTube Music / YouTube** (Google) | Browsing, searching, playing music | Search queries and the IDs of songs, albums, artists and playlists you open. Playback uses YouTube's official embedded player. Google's [Privacy Policy](https://policies.google.com/privacy) applies to these requests. |
| **LRCLIB** (lrclib.net) | Showing lyrics | The title, artist, album and length of the current song. |
| **Google account** (optional) | Only if you choose **Sign in with Google** | Sign-in happens in your browser; Sonvela never sees your password. It asks for read-only access to your YouTube data (`youtube.readonly`) to show your own playlists and liked videos. The access token is stored on your computer, encrypted with Windows DPAPI, and is revoked when you sign out. |
| **Spotify** (optional) | Only if you connect Spotify to import playlists | Read access to your playlists. The token is stored on your computer and removed when you disconnect. |
| **Discord** (optional) | Only if **Show in Discord** is on | The current song's title, artist and cover are sent to the Discord app running on your computer, which shows them on your profile. |
| **GitHub** | Versions downloaded from GitHub check for updates | A request for the latest version number. The Microsoft Store version is updated by the Store instead. |

Use of YouTube data through Sonvela is also subject to the [YouTube Terms of Service](https://www.youtube.com/t/terms).

## What we do not do

- No analytics or tracking, no advertising IDs, no ads.
- No selling or sharing of personal data.
- No account with us is needed; we do not have your name, email or any profile.

## Children

Sonvela is not directed at children under 13 and does not knowingly collect their personal information.

## Changes

If this policy changes, the new version will be published at this address with a new date.

## Contact

Questions or requests: [open an issue on GitHub](https://github.com/Lean302302/sonvela/issues).
