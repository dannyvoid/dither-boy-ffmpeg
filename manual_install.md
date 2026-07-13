# Manual FFmpeg install

Quit Dither Boy first. Download from [dither-boy-ffmpeg releases](https://github.com/dannyvoid/dither-boy-ffmpeg/releases) - each zip has one binary at the root.

**Find your path:** Settings -> Video Engine (shown when installed), or use the defaults below.

## Windows

1. Download [ffmpeg-win64.zip](https://github.com/dannyvoid/dither-boy-ffmpeg/releases/download/ffmpeg-v1.0.0/ffmpeg-win64.zip)
2. Extract `ffmpeg.exe`
3. Put it here (create the folder if needed):

   `%LOCALAPPDATA%\Studio AAA\Dither Boy\ffmpeg\ffmpeg.exe`

## macOS

1. Download [ffmpeg-macos.zip](https://github.com/dannyvoid/dither-boy-ffmpeg/releases/download/ffmpeg-v1.0.0/ffmpeg-macos.zip)
2. Extract `ffmpeg`
3. Put it here (create the folder if needed) (it should end up as a file named ffmpeg inside the ffmpeg/ folder:

   `~/Library/Application Support/Dither Boy/ffmpeg/`

4. In Terminal:

   ```bash
   chmod +x ~/Library/Application\ Support/Dither\ Boy/ffmpeg/ffmpeg
   xattr -cr ~/Library/Application\ Support/Dither\ Boy/ffmpeg
   ```

To update, download a newer release zip and replace the same file.
