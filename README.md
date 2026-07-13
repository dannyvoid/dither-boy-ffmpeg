# dither-boy-ffmpeg

Pinned [FFmpeg](https://ffmpeg.org/) static binaries for [Dither Boy](https://github.com/dannyvoid/dither-boy-electron).

Dither Boy downloads these builds on demand (Settings -> Additional Components -> FFmpeg, or the first-run video prompt). They are installed into the app data folder and are not added to the system `PATH`.

## Releases

| Tag | Windows | macOS |
|-----|---------|-------|
| [ffmpeg-v1.0.0](https://github.com/dannyvoid/dither-boy-ffmpeg/releases/tag/ffmpeg-v1.0.0) | `ffmpeg-win64.zip` | `ffmpeg-macos.zip` |

Each zip contains a single binary at the root:

- **Windows:** `ffmpeg.exe`
- **macOS:** `ffmpeg` (x64 static; runs via Rosetta on Apple Silicon)

### ffmpeg-v1.0.0

| Platform | Version | Origin |
|----------|---------|--------|
| Windows x64 | `N-124567-g0857141823-20260521` | [BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds) |
| macOS x64 | `8.1-tessus` | [evermeet.cx](https://evermeet.cx/ffmpeg/) |

Download URLs (used by Dither Boy):

```
https://github.com/dannyvoid/dither-boy-ffmpeg/releases/download/ffmpeg-v1.0.0/ffmpeg-win64.zip
https://github.com/dannyvoid/dither-boy-ffmpeg/releases/download/ffmpeg-v1.0.0/ffmpeg-macos.zip
```

SHA-256 checksums for each zip are listed in the [release notes](https://github.com/dannyvoid/dither-boy-ffmpeg/releases/tag/ffmpeg-v1.0.0).

## License

**Release assets** are builds of FFmpeg and are licensed under the [GNU General Public License v2 or later](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html).

| Platform | Upstream source |
|----------|-----------------|
| Windows | https://github.com/FFmpeg/FFmpeg/commit/085714182302333dd83dcb9c36cf828dc4eba929 |
| macOS | https://github.com/FFmpeg/FFmpeg/tree/release/8.1 |

Full FFmpeg source: https://github.com/FFmpeg/FFmpeg

**This repository** (README and other non-binary files) is licensed under the [MIT License](LICENSE).