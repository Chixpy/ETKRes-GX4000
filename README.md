# ETKRes-GX4000
Resources for Emuteca: Amstrad GX4000

Icons, images, texts, videos, etc. for use with [Emuteca](https://github.com/Chixpy/Emuteca).

## About Images

Official resolutions (without border): 160x200, 320x200 and 640x200. Seem that all oficcial games use 320x200, and with the border the screenshots are 384X270; so the correct way to correct the aspect ratio without losing data is upscaling width*5 and height*6.

### About Icons

Icons are mainly extracted from game screenshots at original resolution. Usually they are protagonist frames or lives icons (if they are similar to protagonist).

All icon images are in .png format. Width and Height are variable, using it's original size without resizing to a fixed size or adding more border to make it square. Emuteca handle they automatically.

The only time that the image will be scaled is when all 'icon pixels' are 2x2, 3x3, etc. pixels.

After extracting the icon image with transparent background, a border is added: Middle grey, half transparency (128, 128, 128, 128). Emuteca have a GIMP's script in its distribution, that can add the border automatically after transparent background is created.

Of course, same problem about images aspect ratio is present here.

Download
--------

Use GIT to clone the repository or download it in zip:

https://github.com/Chixpy/ETKRes-GX4000/archive/master.zip