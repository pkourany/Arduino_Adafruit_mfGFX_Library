Adafruit_mfGFX_Library
======================

Multifont version of Adafruit_GFX library created by Paul Kourany, 2014

This library supports any compatible Adafruit_GFX display driver.  The free TheDotFactory Windows program
is recommended for created data compatible with the Adafruit_mfGFX library.

Please see the README.pdf files for instructions on creating and adding new fonts.  The base library
comes with 4 fonts and a "test" font so new candidate font data can easily be added and tested before
being permanently added to the library.

BE AWARE that though font data does not take up RAM, they do however take up PROGMEM space so having
too many fonts may prove problematic.

By default, GLCDFONT from original GFX library is the default font so code based on older font will work.
This is the core graphics library for all our displays, providing a common set of graphics
primitives (points, lines, circles, etc.).  It needs to be paired with a hardware-specific
library for each display device we carry (to handle the lower-level functions).

Adafruit_GFX
------------

Adafruit invests time and resources providing this open source code, please support Adafruit
and open-source hardware by purchasing products from Adafruit!

Written by Limor Fried/Ladyada for Adafruit Industries.
BSD license, check license.txt for more information.
All text above must be included in any redistribution.

To download, click the DOWNLOAD ZIP button, uncompress and rename the uncompressed folder
Adafruit_mfGFX. Confirm that the Adafruit_mfGFX folder contains Adafruit_mfGFX.cpp and
Adafruit_GFX.h.

Place the Adafruit_mfGFX library folder your <arduinosketchfolder>/Libraries/ folder. You may need
to create the Libraries subfolder if its your first library. Restart the IDE.






