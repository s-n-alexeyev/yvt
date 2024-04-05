# YVT - Yandex Video Translate
The operation is based on the [vot-cli](https://github.com/FOSWLY/vot-cli) script.

- The script downloads videos from most popular video hosting platforms.
- It performs translation of video using Yandex neural network into one of the three available languages: Russian (by default), English, and Kazakh.
- It saves audio tracks of the original and translated versions.
- Embeds subtitles, by default in English.
- Default encoding is done with a bitrate of 450 Kbit, video codec - h264, audio codec - aac.
- It allows working with a list of links.
- Parameters can be viewed by running the script without parameters or using the `--help key`.

![screenshot](/img/example.png)
