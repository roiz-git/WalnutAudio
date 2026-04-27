# Walnut Audio for iOS

An iOS app to control [Music Player Daemon (MPD)](https://www.musicpd.org/) servers — with HTTP audio streaming, multi-device coordination, and iOS Shortcuts integration.

Walnut Audio is a streamlined MPD client designed for music lovers who want efficient control without visual distractions. Text-based, fast, and focused.

## How It Works

Walnut Audio is built around two primary listening modes:

### All Music Mode

- Load your entire library with shuffle on
- As you listen, search and queue songs one after another
- Queued songs play next, then shuffle continues
- Discover and rediscover tracks effortlessly

### Playlist Mode

- Load curated playlists for focused sessions
- Want to add a song from outside the playlist? Use Search More to find any song in your library
- Queue it without replacing your current playlist

## Smart Queue Management

Build your listening session without interruption:

- **Add to Queue** — Queue songs to play next without clearing what's playing
- **Priority System** — Queued songs play before shuffle continues
- **Queue View** — See and manage your upcoming tracks

## Show Song in List

Hear a track that reminds you of another song from the same album or folder? Tap **Show Song in List** to jump to that song's location in your queue. Browse nearby tracks, then play or queue what you want to hear next.

## Exclusive Play

Sometimes you want to focus on one artist or album:

- **By Artist** — Clear queue, load all songs by an artist, shuffle, play
- **By Album** — Clear queue, load full album, shuffle, play

One tap to dive deep.

## Co-Play

When multiple devices share the same Bluetooth speaker, Walnut Audio coordinates so playback stays smooth and controllable from any device:

- **Collision detection** — When you start streaming and another device is already playing to the same speaker, Walnut asks whether to stream to the iPhone speaker, take over the BT speaker, or just control playback
- **Take Over** — Seamlessly grab the BT speaker from another device
- **Hand Over** — Transfer streaming to another Walnut device
- **Remote Volume** — Adjust the streaming device's volume from any device

## Song Tagging

Tag songs on the fly with genre shortcuts, then review and apply the changes later — great for curating your library without breaking your listening flow.

## Features

- Play, pause, skip, seek, volume control
- Real-time status via MPD idle monitoring
- Multi-word search across artist, album, title, genre
- Multiple server profiles with Bonjour auto-discovery
- HTTP streaming with phone call handling (pause/resume)
- Lock screen & Control Center integration
- Siri Shortcuts for profile switching, playlist loading, and streaming control
- Co-Play multi-device coordination
- Song tagging for later library updates

## Companion to Walnut Audio for macOS

Part of the MpdForApple family. Walnut Audio shares its core with Walnut Audio for macOS, the menu bar client for Mac.

iOS adds: HTTP streaming, Bonjour discovery, phone call handling, Siri Shortcuts, Co-Play multi-device coordination, song tagging, and touch-optimized controls.

## Requirements

- iOS 26 or later
- An MPD server reachable on your network

## Install

[Download Walnut Audio on the App Store](https://apps.apple.com/us/app/walnut-audio/id6757301795)

## Credits

- [Music Player Daemon](https://www.musicpd.org/) — the audio player Walnut controls
