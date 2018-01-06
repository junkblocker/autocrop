# autocrop
Automatically crop and rotate scanned images using OpenCV.
Only working under Linux so far (file/folder stuff, easy to adopt for someone with a Windows machine).

# Install requirements

- OpenCV (pip install cv2)
- numpy (pip install numpy)

# USAGE: python autocropy.py (THRESHOLD) (CROP)

Place autocrop.py into a folder of scanned images. Those images should be roughly cropped already (see examples).

Run script as described above. THRESHOLD and CROP are optional. Results will be stored in /crop/.

- THRESHOLD: threshold value to find image borders, default is 220
- CROP: additional cropped pixels to avoid unclean borders of the result, default is 15 pixels
