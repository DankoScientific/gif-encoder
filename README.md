# gif-encoder

This script uses FFMPEG to make animated GIFs

Inspired by this blog post || http://blog.pkh.me/p/21-high-quality-gif-with-ffmpeg.html

gif-encoder requires a source video, scene start time, scale (set to 1 if scale remains the same, 2 is half 3 is a third, etc...)

example:
$ gif-encoder movie.mp4 300 1 
