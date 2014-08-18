Overview
===========

This is a Ruby language binding (glue code) for using [Pashua](www.bluem.net/jump/pashua) from Ruby. Pashua is a Mac OS X application for using native GUI dialog windows in various programming languages.

The repository contains two files: `Pashua.rb`, a Ruby module which handles the communication with Pashua, and `example.rb`, a simple script wich uses `Pashua.rb` to display a dialog. The way the module works is neither the best nor the only way to “talk” to Pashua from within Ruby, but rather one out of several possibe implementations.

Requirements
=============
This code requires Ruby 1.6 or higher and Pashua. The Ruby executable shipped by Apple as part of the last few releases of Mac OS X can be used to run the code.
