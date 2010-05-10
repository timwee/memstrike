memstrike
=========
memcached benchmark tool


## Requirements

Following programs are requred to build:

 - gcc >= 4.1
 - libmemcached > 0.23


## Usage

    Usage: memstrike  [options]  <num requests>
      -l HOST=127.0.0.1  : memcached server address
      -p PORT=11211      : memcached server port
      -k SIZE=8          : size of key >= 8
      -v SIZE=1024       : size of value
      -m NUM=1           : get multiplex
      -t NUM=1           : number of threads
      -b                 : use binary protocol
      -g                 : omit to set values
      -s                 : omit to get benchmark
      -o NUM=0           : key offset
      -h                 : print this help message


## License

    Copyright (c) 2008-2010 FURUHASHI Sadayuki
    
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

