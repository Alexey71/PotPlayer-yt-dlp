## Installation
 Download the full plugin archive here https://github.com/Alexey71/PotPlayer-yt-dlp/releases
 
 Extract the files from the archive: `MediaPlayParse - yt-dlp.as`, `MediaPlayParse - yt-dlp.ico`, `Update-yt-dlp.bat`, `yt-dlp.exe` into the `Extension\Media\PlayParse` folder, by default located at `C:\Program Files\DAUM\PotPlayer`.

Change or delete https://github.com/Alexey71/PotPlayer-yt-dlp/blob/fe1f9ce0be031bc9b5e9f918dd3b6147c2e34552/MediaPlayParse%20-%20yt-dlp.as#L44C35-L44C65 `--cookies-from-browser firefox`. My default browser Firefox. The description of the parameter is given here https://github.com/yt-dlp/yt-dlp

## Configuration and Usage
### Use as default
 To use as the default when opening youtube URLs, go to  `Preferences (F5) > Extensions > Media Playlist/Playitem` and move it above the default.

## How update `yt-dlp.exe`
Run `Update-yt-dlp.bat`. Updating to the latest `master` channel.

Or download the file manually from the official https://github.com/yt-dlp/yt-dlp
