# Lemen Studio Player+

A premium, single-file music player. Open `index.html` in a browser, or serve the folder:

```
py -m http.server 8766
```

Then visit http://127.0.0.1:8766/

## What it does

- Hash-routed pages: Home, Search, Library, Upload, Liked Songs, Playlists, Now Playing, Settings
- Upload local audio (MP3, M4A, WAV, OGG, FLAC, and more depending on the browser)
- IndexedDB for audio files, localStorage for playlists, likes, and settings
- Custom player bar, queue, visualizer, likes, and playlists

## Formats

Playback depends on the browser. MP3, M4A/AAC, WAV, OGG/Opus, FLAC, and WebM usually work. Some WMA/AIFF files may be skipped.

## Storage

Audio blobs are stored in IndexedDB (`lemen-studio`). Playlists, likes, settings, and history are stored in localStorage (`lemen-meta-v1`).
