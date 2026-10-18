# Glowtape

A neon synthwave music and video player for Windows 10 and 11 that plays **any** audio format, plays videos, keeps your library organized, makes playlists and imports music from the web. 100% free: no ads, no accounts.

## Features

- **Plays everything:** MP3, FLAC, ALAC, AAC/M4A, WAV, AIFF, OGG, Opus, WMA, APE, WavPack, Musepack, DSD (DSF/DFF), AC3/DTS, tracker modules and more. Windows' own decoders handle the common formats, and the free FFmpeg add-on (downloaded automatically when it's needed) covers the rest.
- **Videos:** MP4, MKV, AVI, MOV, WMV, WebM and more, with hardware decoding, subtitles (built-in and .srt/.vtt files), full screen, playback speed and "continue watching" so you can pick up where you left off. Unusual formats are converted automatically with FFmpeg.
- **Library:** watches your music folders and picks up new, changed and deleted files by itself. Browse by songs, albums, artists or liked songs, with instant search, album art and play counts.
- **Playlists:** create, rename, drag to reorder, and import/export `.m3u8` files.
- **Import from the web:** paste a YouTube, YouTube Music, SoundCloud, Bandcamp or Mixcloud link, or search YouTube/SoundCloud inside the app. You can import single songs, whole playlists and albums, or keep the video as an MP4, with cover art and tidied tags (powered by the free yt-dlp and FFmpeg tools).
- **Equalizer and effects:** 10-band EQ with 15 presets and a live response curve, plus preamp, bass boost, crossfade, gapless playback and volume leveling (ReplayGain or automatic).
- **Synced lyrics:** shown karaoke-style, from `.lrc` files, embedded tags, or the free LRCLIB database.
- **Mini player:** small and always on top. Media keys, the Windows media pop-up and the lock screen all work too.
- **Background playback:** keeps playing in the tray, can start with Windows, and opens audio and video files from Explorer ("Open with").
- **Your place is saved:** resumes your queue and position, and lets you edit tags.
- Automatic updates.

## Requirements

Windows 10 (version 2004 or newer) or Windows 11, 64-bit.

## Install

Download `Glowtape-Setup-<version>.exe` from [Releases](https://github.com/AntiLegend93/Glowtape/releases) and run it. No admin rights are needed.

## Updates

Glowtape checks for updates when it starts and every 6 hours after that. When a new version is out, a bar appears at the top of the window (or a notification, if it's playing in the tray). Click **Update now**: it downloads the new installer, updates itself in a few seconds and reopens. You can turn automatic checks off, or check by hand, in **Settings**.

## A note on importing

Only import music you have the right to download: your own uploads, free and Creative Commons releases, or tracks the artist offers for download. Downloading from some sites may be against their terms of service.

## Credits

Built with free, open-source projects: [NAudio](https://github.com/naudio/NAudio), [TagLib#](https://github.com/mono/taglib-sharp), [SQLite](https://www.sqlite.org/), [FFmpeg](https://ffmpeg.org/), [yt-dlp](https://github.com/yt-dlp/yt-dlp) and [LRCLIB](https://lrclib.net/).
