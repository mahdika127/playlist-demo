# Playlist Demo

A lightweight, responsive, right-to-left web player for three Persian-language tracks.

**Live site:** [mahdika127.github.io/playlist-demo](https://mahdika127.github.io/playlist-demo/)

## Features

- Attempts autoplay when the page opens. Browsers may block audible autoplay; press **Play** if prompted.
- Plays tracks in order and loops back to the first track after the last one.
- Includes Play/Pause, Previous, Next, and direct track selection.
- Shows playback status, elapsed time, duration, and progress.
- Supports mobile and desktop layouts.

## Repository files

Keep these files in the repository root, beside `index.html`:

| File | Track |
| --- | --- |
| `to-ragi.mp3` | To Ragi — Shayea |
| `ghalb-mani.mp3` | Ghalbe Mani — Haamim |
| `dast-bardar-live.mp3` | Dast Bardar (Live) — Mira |

The player reads these exact filenames from the repository root. To change the playlist, edit the `tracks` array near the end of `index.html` and make sure each `src` matches its MP3 filename.

## Preview locally

Open `index.html` in a modern web browser. If autoplay is blocked, use the Play button.

## GitHub Pages

The site is published from the `main` branch and repository root. To publish future updates, commit them to `main`; GitHub Pages will rebuild the site.

## Audio rights

This repository is public, so its MP3 files are publicly accessible. Keep only audio that you are authorized to distribute publicly.

