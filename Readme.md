Overview
===========

This is a Ruby language binding (glue code) for using [Pashua](http://www.bluem.net/jump/pashua) from Ruby. Pashua is a Mac OS X application for using native GUI dialog windows in various programming languages.

The repository contains two files: `Pashua.rb`, a Ruby module which handles the communication with Pashua, and `example.rb`, a simple script wich uses `Pashua.rb` to display a dialog. The way the module works is neither the best nor the only way to “talk” to Pashua from within Ruby, but rather one out of several possibe implementations.

Requirements
=============
This code requires Ruby 1.6 or higher and Pashua. The Ruby executable shipped by Apple as part of the last few releases of Mac OS X can be used to run the code.

License
=========
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

