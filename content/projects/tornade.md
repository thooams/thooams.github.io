---
title: "Tornade (macOS App)"
subtitle: "Lossless Audio Player for macOS"
description: "Tornade is a native macOS music player built in Rust and SwiftUI, designed for audiophiles who want full control over their lossless library with keyboard-centric navigation and minimal resource usage."
image: "/images/pic09.jpg"
weight: 1
doc_label: "Tornade"
doc_url: "https://tornade.tf/"
cta:
  heading: "To Resume"
  text: "Tornade is a native music player built for people who care about audio quality and library control. With near-zero CPU at rest, instant startup, and a full-text search engine powered by SQLite FTS5, it handles large libraries without compromise."
  links:
    - label: "Tornade website"
      url: "https://tornade.tf/"
      external: true
    - label: "GitHub"
      url: "https://github.com/tornade-player"
      external: true
---

{{< section-content >}}
### A native music player built for lossless audio

<img src="/images/portfolio/tornade/albums.webp" alt="Tornade albums view" class="img-right" />

**Tornade** is a native macOS music player built with [Rust](https://www.rust-lang.org/) and [SwiftUI](https://developer.apple.com/xcode/swiftui/), designed for audiophiles who want full control over their music library without bloat.

The interface follows a three-panel layout: a sidebar for navigation (Search, Tracks, Albums, Artists, Genres), a content area, and a persistent queue panel on the right. A mini-player anchored at the bottom provides playback controls and volume at all times.

Tornade scans local directories, extracts metadata automatically, and caches album artwork - turning a folder of audio files into a fully browsable library in seconds.

#### Technology

Tornade is built with [Rust](https://www.rust-lang.org/) for the audio engine and core logic, [SwiftUI](https://developer.apple.com/xcode/swiftui/) for the native macOS interface, [SQLite](https://www.sqlite.org/) with FTS5 for full-text search, and [Symphonia](https://github.com/pdeljanov/Symphonia) for lossless codec decoding.
{{< /section-content >}}

{{< section-accent >}}
## Lossless Audio, Every Format

FLAC, ALAC, OGG, MP3, WAV, AIFF - decoded natively via Symphonia

The track list shows the exact audio format for every file, so you always know whether you are listening to a lossless source or a compressed one.
{{< /section-accent >}}

{{< section-content >}}
### Tracks view

<img src="/images/portfolio/tornade/tracks.webp" alt="Tornade tracks view" class="img-left" />

The tracks view lists the entire library in a dense table with columns for title, artist, album, duration, and format. Each row displays the codec badge (FLAC, ALAC, AAC...) so the audio quality is always visible at a glance.

The library is sorted and filterable in real time. Tornade uses **SQLite FTS5** for full-text search across all metadata fields, delivering instant results even on libraries with tens of thousands of tracks.

Playback state persists across restarts: Tornade remembers the current track, queue position, and volume, so you pick up exactly where you left off.
{{< /section-content >}}

{{< section-dark >}}
## Albums and Artist Pages

Rich metadata views with album artwork, artist bios, and discography

Each album and artist page is built from metadata extracted directly from the audio files - no external API calls, no internet required.
{{< /section-dark >}}

{{< section-content >}}
### Album detail

<img src="/images/portfolio/tornade/album-show.webp" alt="Tornade album detail" class="img-right" />

The album page surfaces the full track list alongside an info panel showing year, genre, label, and format. Below the tracklist, Tornade displays other albums by the same artist and any featuring collaborators - all derived from embedded tags.

Clicking a track adds it to the queue without interrupting playback. The queue panel on the right updates in real time and supports drag-to-reorder.

### Artist page

<img src="/images/portfolio/tornade/artists.webp" alt="Tornade artist page" class="img-left" />

Each artist page aggregates all albums and tracks attributed to that artist across the library. A short biography sourced from the embedded metadata is displayed alongside the discography.

The right-hand queue panel remains visible throughout, so adding tracks from an artist page to the current session is a single click.
{{< /section-content >}}

{{< section-accent >}}
## Browse by Genre

A visual genre browser built from your own library tags

Tornade groups tracks by genre automatically, generating a mosaic of album covers that makes browsing large, varied libraries intuitive.
{{< /section-accent >}}

{{< section-content >}}
### Genres view

<img src="/images/portfolio/tornade/genres.webp" alt="Tornade genres view" class="img-right" />

The genres view displays each genre as a card with a representative album cover and a track count. With 67+ genres detected automatically from file tags, it transforms a flat folder structure into a browsable music collection.

Clicking a genre filters the library instantly, showing all matching tracks and albums without a page reload.

### Global search

<img src="/images/portfolio/tornade/global-search.webp" alt="Tornade global search" class="img-left" />

The global search bar queries the entire library simultaneously across artists, albums, and tracks. Results appear grouped by type in real time as you type, powered by SQLite FTS5.

The search is keyboard-centric: navigate results with arrow keys, press Enter to play or add to queue - no mouse required.
{{< /section-content >}}

{{< section-content >}}
### Tornade, it is

- A native macOS app with a SwiftUI interface and a Rust core
- Lossless audio decoding via Symphonia (FLAC, ALAC, OGG, MP3, WAV, AIFF)
- Full-text library search powered by SQLite FTS5
- Persistent queue, playback history, and track ratings (0-5 stars)
- M3U playlist import and export
- Near-zero CPU at rest, minimal RAM footprint, instant startup
- A free Terminal UI (TUI) version built with ratatui, open-source

**Technology:** Rust / SwiftUI / SQLite / Symphonia / ratatui
{{< /section-content >}}
