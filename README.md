# swingolf-homepage
Swingolf Homepage

# Tools
https://manytools.org/image/colorize-filter/
Teams: RGB: 241 238 107 Contrast -45 Duotone 

docker run --rm -v c:\tmp\:/data/ -w /data/ acleancoder/imagemagick-full mogrify -format jpg -resize "400x710^" -gravity center -crop 400x710+0+0 +repage *.jpg