# subdb-fetcher


A badly written NodeJS script that downloads subtitles from [SubDB](thesubdb.com) for all video files in a specified directory.

```
node subdb-fetcher "D:\Movies"
```

Can be added to a torrent client such as **qBittorrent** to download subtitles automatically for every downloaded video.

* qBittorrent > Settings > Downloads > Run external program on torrent completion
* `node c:\scripts\subdb-fetcher.js "%R"`


Subtitles language is English, hard coded, due to excessive laziness.
