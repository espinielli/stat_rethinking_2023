# Study material

## Videos and slides

In the R folder you find a script, `material.R`, which 
1. output the `video_urls.txt` file containing the URLs of the youtube videos of the lessons.
2. downloads the first 10 PDF files for the lessons which are not included in the original repo.

The `videos/` and `slides/` directories have been 'git ignored'.

To download locally the youtube videos of the lessons you ca use `yt-dld` as follows (from the
root of the [cloned] repo):

```shell
$ cd videos
$ yt-dld -f best -a ../video_urls.txt
```

## Launching videos
On MacOS you can launch the video using VLC as follows:

```shell
$ open -a /Applications/VLC.app videos/lesson_01.mp4
```
