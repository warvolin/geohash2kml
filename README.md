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

*** Apache License 2.0
   Copyright 2011 Hiroaki Kawai

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

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

*** New BSD License
Copyright (c) 2011, Hiroaki Kawai
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:
    * Redistributions of source code must retain the above copyright
      notice, this list of conditions and the following disclaimer.
    * Redistributions in binary form must reproduce the above copyright
      notice, this list of conditions and the following disclaimer in the
      documentation and/or other materials provided with the distribution.
    * Neither the name of the python-geohash nor the
      names of its contributors may be used to endorse or promote products
      derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL Hiroaki Kawai BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
