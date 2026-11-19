# MediaForge

A desktop video and audio editor for Windows: cut, arrange, add titles and transitions,
clean up sound, generate subtitles, and export, all on your own computer.

**[⬇ Download the latest version](https://github.com/kayceechris/mediaforge/releases/latest)**
(`MediaForge-Setup-x.y.z.exe`, Windows 10/11, 64-bit)

**[📖 Read the user manual](USER_MANUAL.md)**: everything from your first video to exporting,
plus shortcuts and troubleshooting.

**[🎬 Watch the video tutorials](https://kayceechris.github.io/mediaforge/tutorials/)**: 20 short
narrated videos, from the basics to green screen and speed ramps ([list](TUTORIALS.md)). They're
also in the app under Help → Video tutorials.

## Features

- **Timeline editing:** multiple video, audio and title tracks; trim, split, ripple delete,
  snapping, markers, undo/redo.
- **Smooth preview:** playback with audio and video in sync, and J/K/L shuttle. Formats that are
  hard to play get a preview copy automatically.
- **Video:** crossfade, dip-to-black and wipe transitions; titles; speed changes that keep the
  pitch; picture-in-picture; crop, scale and rotate; brightness, contrast and saturation.
- **Audio:** volume and fades, normalize to podcast loudness, noise reduction, voice
  isolation, silence detection and removal, voice-over recording.
- **AI tools:** automatic subtitles (Whisper speech recognition), filler-word removal, and
  splitting at scene changes. All of it runs on your computer; nothing is uploaded.
- **Export:** MP4 (1080p, 720p, 4K), WebM, MP3 and WAV. Exports run in a queue with a progress
  bar, and can use hardware encoding (NVIDIA, Intel, AMD) when available.
- **Projects:** saving, autosave and crash recovery, recent projects, and relinking moved media.

## Installing

1. Download `MediaForge-Setup-x.y.z.exe` from
   [Releases](https://github.com/kayceechris/mediaforge/releases/latest) and run it.
2. Windows may show **"Windows protected your PC"**, because the installer isn't code-signed
   yet. Click **More info**, then **Run anyway**.
3. Choose where to install it. No administrator rights are needed.

MediaForge updates itself: new versions download in the background, and a **Restart to
update** button appears in the status bar.

The first time you generate subtitles, MediaForge downloads a speech model (about 76 MB) once.
After that it works offline.

## Getting started

- **Import** media (Ctrl+I) or drag files into the Media Library, then drag them onto the
  timeline.
- Select a clip to adjust it in the **Inspector**: transitions, speed, colour, audio tools and
  AI tools.
- **Export** with Ctrl+E. Press **?** at any time to see all keyboard shortcuts.

## Problems and suggestions

Open an issue at <https://github.com/kayceechris/mediaforge/issues>.

## License

MediaForge is free to download and use. Copyright © 2026 psdanalyst. All rights reserved.

MediaForge includes third-party software under its own licenses, including **FFmpeg**
(GNU GPL v3). See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md), which is also included with
the app (Help → Third-party licenses). It explains where to get the FFmpeg source code.
