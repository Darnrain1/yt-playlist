# Welcome to yt-playlist v2.x

## No spyware or adware. Respects your privacy. Does not login to YouTube, YouTube Music or Google. Does not use Google's api. Simplistic UI with a numeric layout, for faster access.<br>

### Features:
* Stream YouTube video up to 8k 60 FPS.
* 1080p 60 FPS video defaults to h264.
* Enable HW GPU on mpv player.
* Sponsors will be skipped automatically.
* Downlaod with sponsers cut out automatically.
* No YouTube/YouTube Music ads.
* Very little cpu usage and memory requirements.
* A text mode, listen to video or music.
* Background audio playback on Termux.
* Open a channel, playlist and album in NewPipe. Termux version only.
* Import Google takeout, your YouTube subscriptions and YouTube Music.
* Search YouTube for Playlists and Channels.
* Search YouTube Music for Playlists and Albums.
* Search Youtube Music for songs.
* Paste a YouTube or a YouTube Music url.
* Search results are saved to your history.
* Download YouTube Playlists from a Channel.
* Download up to 1080p 60 FPS videos.
* Download Audio or Video in real-time as mpv is playing.
* Download m4a and opus audio files with thumbnails and metadata included.
* No mp3 transcoding, native audio format only.
* A built in Sleep Timer, that slowly lowers volume level and closes mpv player.
* Automated installation Termux version.
* 100% open source and free.
* And more...
 
### Known issues:
* yt-playlist will not work on Ubuntu, because of the snap permissions.
* yt-playlist will work with mpv v0.34.1 but not all of the Audio effects will work.

### Tested OS and working as of 9-20-2023:
* macOS big sur
* Arch/Manjaro/EndeavourOS Linux
* Linux Mint
* MX Linux
* POP!_OS Linux
* Termux

### Command line arguments:
<pre>
Help menu:              -h or --help
Version:                -v or --version
yt-playlist setup       --setup
Play/Pause              --play_pause
Mute/Unmute             --mute_unmute
Next track              --next
Prev track              --prev
Stop or exit            --stop
Desktop and terminal
notifications get
artist and title        --title
Enable cover art
notifications           --cover_art
Download when playing
Audio/Video
Download audio          --download_audio opus
                        --download_audio m4a
Download video          --download_video mp4
Import Google takeout:  --import
Suppprted file types:
subscriptions.csv
music-library-songs.csv
Example: "yt-playlist --import subscriptions.csv"

--cover_art is Linux version only.
</pre>

### Credits, A Special Thank You
yt-dlp<br>
https://github.com/yt-dlp/yt-dlp

mpv<br>
https://github.com/mpv-player/mpv

ffmpeg<br>
https://github.com/FFmpeg/FFmpeg

fzf<br>
https://github.com/junegunn/fzf

jemalloc<br>
https://github.com/jemalloc/jemalloc

mpv_sponsorblock<br>
https://github.com/po5/mpv_sponsorblock

fx<br>
https://github.com/antonmedv/fx

Termux<br>
https://github.com/termux/termux-app

NewPipe<br>
Termux version.<br>
https://github.com/TeamNewPipe/NewPipe

billboard-hot-100 (1)<br>
https://github.com/mhollingshead/billboard-hot-100

billboard-hot-100 (2)<br>
Billboard 200<br>
Billboard Global 200<br>
Billboard Artist 100<br>
https://github.com/KoreanThinker/billboard-json

Rolling Stone's list of The 500 Greatest Songs of All Time.<br> 
https://gist.github.com/nanotaboada/a90ce99a9bc8ca3c63c0f1dfeb41d41d#file-songs-json

MIT License<br>

Copyright (c) 2023 darnrain1<br>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:<br>

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.<br>

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.<br>
