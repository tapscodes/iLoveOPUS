# iLoveOPUS
A program to convert MP3, AAC(M4A), ALAC, and FLAC files to 192kbps OGG OPUS while retaining (most) metadata. 

Cover art is all resized to 1000x1000 jpgs as well in the process if selected and
if files aren't converted in-place, they're converted into "Downloads/opus_exports".

## Dependencies
- Python (https://www.python.org/)
- Kivy (https://kivy.org/) ```pip install kivy```
- Mutagen (https://github.com/quodlibet/mutagen) ```pip install mutagen```
- FFMPEG (https://ffmpeg.org/)

## Dev Run Command
```pip install kivy mutagen```
```python main.py```