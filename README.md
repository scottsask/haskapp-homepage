# jekyll-mdl
To encode the app demo gif for the site:
ffmpeg -i 15s_take2.mov -pix_fmt rgb24 -r 10 -f gif - | gifsicle --optimize=3 --delay=10 > out3.gif
