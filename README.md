# gif-encoder

This script uses FFMPEG to make animated GIFs

Inspired by this blog post || http://blog.pkh.me/p/21-high-quality-gif-with-ffmpeg.html

gif-encoder requires a source video, scene start time, scale (set to 1 if scale remains the same), and scene crop (use iw:ih if not needed)

# note: re-write scene crop so that if left blank it auto sets to iw:ih instead of manually having to enter iw:ih
