<p align=right>Source: https://github.com/phazus/lofiatc.sh</p>

# lofiatc.sh

Small bash file that implements https://www.lofiatc.com with two running [mpv](https://mpv.io/) instances.

```sh
$ ./lofiatc.sh 
Playing: KLAX - Los Angeles International Airport
https://www.youtube.com/watch?v=Q9zwUZr6yPA

Playing: https://www.youtube.com/watch?v=5V2nGGbUE6c (+) Audio --aid=1 --alang=eng (*) (opus 2ch 48000Hz)
AO: [alsa] 48000Hz stereo 2ch float
A: 00:01:08 / 00:02:45 (42%) Cache: 90s/3MB
```

## Getting Started

```sh
git clone https://github.com/phazus/lofiatc.sh.git
cd lofiatc.sh
./lofiatc.sh
```

## Other Notes

- Following LiveATC's [Terms of Service](https://www.liveatc.net/legal/), links to their streams have been replaced by freely available YouTube videos.
- Support for [Broadcastify's top feeds](https://www.broadcastify.com/listen/top) has been added if you want to listen to live feeds.
- Temporary: `lofimp3.m3u` and `lofiyt.m3u` were swapped.
- Inspired by: <https://github.com/phazus/lofiatc.sh>
