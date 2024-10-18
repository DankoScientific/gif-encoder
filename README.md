#: gif-encoder

This script uses FFMPEG to make animated GIFs

Inspired by this blog post:

http://blog.pkh.me/p/21-high-quality-gif-with-ffmpeg.html

gif-encoder requires in the following order: source video, scene start time, and scale. Optional is crop.

Most commonly, I set the scale to 4 - this takes the input WIDTH and HEIGHT and divides by 4, so a 1920x1080 video becomes 480x270

Here's an example:

$ gif-encoder my_favorite_movie.mp4 300 4

gif-encoder will then prompt you for other parameters: dithering options, duration, and filename

CTRL+C to end it all

remember since this is a BASH script you'll probably want to:

sudo cp gif-encoder /usr/local/bin/

sudo chmod +x /usr/local/bin/gif-encoder
