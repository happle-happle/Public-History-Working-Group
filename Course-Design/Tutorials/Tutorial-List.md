# FFMPEG Tools
## image magick for cropping and resizing

cd ~/folder

ls

(get file name)

magick identify filename.png

(get dimensions)

magick filename.png -crop WidthxHeight+0+0 (crop from top right corner) newfilename.png

magick newfilename.png resize DimensionxDimension resizednewfilename.png
