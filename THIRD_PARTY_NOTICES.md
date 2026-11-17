# Third-party software in MediaForge

MediaForge includes the following software and data. Each part remains under its own license.
The full license texts for FFmpeg and Chromium ship in the MediaForge installation folder:

- `resources/app.asar.unpacked/node_modules/ffmpeg-static/ffmpeg.exe.LICENSE`
- `LICENSES.chromium.html`

## FFmpeg (ffmpeg): GPL v3

MediaForge runs FFmpeg as a separate program to read, preview and export media. The bundled
binary is the "essentials" static build of FFmpeg 6.1.1 by gyan.dev. It's licensed under the
GNU General Public License version 3 and includes GPL components such as x264.

- Source code for this exact version: <https://github.com/FFmpeg/FFmpeg/commit/e38092ef93>
- Release tarball: <https://ffmpeg.org/releases/ffmpeg-6.1.1.tar.xz>
- Build information: <https://www.gyan.dev/ffmpeg/builds/>
- License: <https://www.gnu.org/licenses/gpl-3.0.html>

On request, the MediaForge author will provide the corresponding FFmpeg source code for at
least three years from the date of each release. Open an issue at
<https://github.com/kayceechris/mediaforge/issues>.

## FFmpeg (ffprobe): GPL v3

FFprobe 4.0.2, a static Windows build from Zeranoe (`--enable-gpl --enable-version3`), shipped
by the `ffprobe-static` package. It's used to read media information.

- Source: <https://ffmpeg.org/releases/ffmpeg-4.0.2.tar.xz>
- License: GNU GPL version 3

## Electron and Chromium

The app runtime. Electron is MIT-licensed. Chromium and its components are listed with their
licenses in `LICENSES.chromium.html`.

## Speech recognition

- **Transformers.js** (`@huggingface/transformers`): Apache License 2.0.
- **ONNX Runtime** (`onnxruntime-node`, `onnxruntime-web`): MIT License, © Microsoft.
- **Whisper** speech model (OpenAI, as converted by onnx-community): MIT License. MediaForge
  doesn't include it; the app downloads it from Hugging Face on first use.
- **sharp / libvips** (`sharp`, `@img/sharp-win32-x64`): Apache License 2.0; libvips is LGPL 3.0
  or later.

## Voice isolation

The RNNoise model `voice.rnnn` ("leavened-quisling") comes from
<https://github.com/GregorR/rnnoise-models>, whose authors state the trained models aren't
subject to copyright.

## Other libraries

React, React DOM, Zustand, Immer and electron-updater are MIT-licensed. Tailwind CSS is
MIT-licensed and only used at build time.
