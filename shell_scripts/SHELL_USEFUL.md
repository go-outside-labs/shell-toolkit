# Some Quick and Useful Shell Commands

## Downloading all pdfs of url

$ wget --recursive --level=2 --no-directories --no-host-directories --accept pdf


## Extended attributes of files
$ xattr -l $file


## Check signatures of Apps
$ codesign -dvvv $file.app


## Show all the configs
$ system_profiler -detaillevel full

## 瑪麗
$ convert -size 360x360 xc:white -font "FreeMono" -pointsize 12 -fill black -draw @ascii.txt
