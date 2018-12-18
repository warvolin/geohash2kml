geohash2kml
===========

<!---
                   _               _     ___  _              _
                  | |             | |   |__ \| |            | |
   __ _  ___  ___ | |__   __ _ ___| |__    ) | | ___ __ ___ | |
  / _` |/ _ \/ _ \| '_ \ / _` / __| '_ \  / /| |/ / '_ ` _ \| |
 | (_| |  __/ (_) | | | | (_| \__ \ | | |/ /_|   <| | | | | | |
  \__, |\___|\___/|_| |_|\__,_|___/_| |_|____|_|\_\_| |_| |_|_|
   __/ |
  |___/

--->

About
-----
geohash2kml is a simple command line script that supports the creation of a Google Earth visualization of a tab delimited text file that includes geohashes with corresponding counts.

You could use this to create a 3d 'heatmap' of a geospatial quantity that you are measuring.


Usage
-----
python geohash2kml.py minneapolis_counts.txt minneapolis

geohash.py license
-----
* python-geohash
python-geohash is a fast, accurate python geohashing library.

** History
python-geohash 0.8 introduced uint64 representation.

python-geohash 0.7.1 starts supporting python3k.

python-geohash 0.3 can create C extension. If you want to use python-geohash
without C extension, simply copy geohash.py into your system. geohash.py will
work fine without C extension.

** LICENSE
Code is licensed under Apache License 2.0, MIT Licence and NEW BSD License.
You can choose one of these licences. Declarations follow:

*** MIT License
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
