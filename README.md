# autocrop

Automatically crop and rotate scanned images using OpenCV.
Should work on Windows, Linux and Mac.

## Install requirements

- python3
- OpenCV (pip3 install opencv-python)
- numpy (pip3 install numpy)

## USAGE

Place autocrop.py into a folder of scanned images. Those images should be roughly cropped already (see examples).

Run script as

```sh
python3 autocropy.py (THRESHOLD) (MIN_CROP)
```

THRESHOLD and MIN_CROP are optional. Results will be stored in ``./crop/``

- THRESHOLD: threshold value to find image borders, default is 220
- MIN_CROP: additional cropped pixels to avoid unclean borders of the result, default is 15 pixels

## TODO

* executables for Windows + basic GUI to make it usable for less nerdy people.
