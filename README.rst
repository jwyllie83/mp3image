========
mp3image
========

*mp3image* is an easy way to write JPEG album covers to mp3 files.  It's
compatible with ID3v2 tags 2.2 and above (covers virtually all mp3 files).
Usage is simple::

mp3image -i image_file.jpg some.mp3 mp3.mp3 files.mp3 

The above example will create or overwrite the album art in all the listed .mp3
files with image_file.jpg.  It doesn't do back covers or any of the other
various images that an ID3v2 tag can hold (it's actually a large list) as most
software won't use it when displaying.

*mp3image* is written in Python and uses the ``pytagger`` library, found at
http://code.google.com/p/liquidx/

*mp3image* was written by Jim Wyllie, with some code borrowed from Alastair Tse
for his examples on how to use ``pytagger``.  Examples cited in source.
