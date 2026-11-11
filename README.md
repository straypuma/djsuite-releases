# DJ Suite

A lightweight, native macOS DJ app: two decks with key-locked tempo, sync, hot cues and loops, a three-band mixer,
and tracks from your Mac, YouTube Music, and Spotify, Tidal and YouTube playlists. It works with a Pioneer DDJ-400.
About 8 MB, built for Apple silicon.

## Download

Get **DJSuite-x.y.dmg** from the [latest release](https://github.com/straypuma/djsuite-releases/releases/latest).

1. Open the DMG and drag **DJ Suite** into **Applications**.
2. Open it. The first time, macOS blocks it because it isn't notarized by Apple: go to
   **System Settings ▸ Privacy & Security**, scroll down and click **Open Anyway**. After that it opens normally.

**Requires** an Apple silicon Mac on macOS 15 (Sequoia) or later. Playing from YouTube Music needs yt-dlp and Deno
from [Homebrew](https://brew.sh): `brew install yt-dlp deno`.

## Updates

DJ Suite checks for updates once a day and offers to install them (or **DJ Suite ▸ Check for Updates…**).
Updates are signed, so only builds from this page are accepted.

This repository only hosts releases; the source is private.
