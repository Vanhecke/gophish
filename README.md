![gophish logo](https://raw.github.com/Vanhecke/gophish/master/static/images/gophish_purple.png)

Gophish
=======

[![Join the chat at https://gitter.im/gophish/gophish](https://badges.gitter.im/gophish/gophish.svg)](https://gitter.im/gophish/gophish?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Build Status](https://travis-ci.org/gophish/gophish.svg?branch=master)](https://travis-ci.org/gophish/gophish) [![GoDoc](https://godoc.org/github.com/Vanhecke/gophish?status.svg)](https://godoc.org/github.com/Vanhecke/gophish)

Gophish: Open-Source Phishing Toolkit

[Gophish](https://getgophish.com) is an open-source phishing toolkit designed for businesses and penetration testers. It provides the ability to quickly and easily setup and execute phishing engagements and security awareness training.

### Current Status
**Update 2/19/2017**

<<<<<<< HEAD
Gophish version 0.2 binaries have been released! Head on over to the [releases page](https://github.com/Vanhecke/gophish/releases/tag/v0.2.0) to download the latest binaries.
=======
Gophish version 0.2.1 binaries will be released soon! I am just fixing a few final bugs and then I will build the final binaries. 
>>>>>>> refs/remotes/gophish/master

### Install

Installation of Gophish is dead-simple - just download and extract the zip containing the [release for your system](https://github.com/Vanhecke/gophish/releases/), and run the binary. Gophish has binary releases for Windows, Mac, and Linux platforms.

### Building From Source
**If you are building from source, please note that Gophish requires Go v1.5 or above!**

To build Gophish from source, simply run ```go get github.com/Vanhecke/gophish``` and ```cd``` into the project source directory. Then, run ```go build```. After this, you should have a binary called ```gophish``` in the current directory.

### Docker
You can also use Gophish via an unofficial Docker container [here](https://hub.docker.com/r/matteoggl/gophish/).

### Setup
After running the Gophish binary, open an Internet browser to http://localhost:3333 and login with the default username (admin) and password (gophish).

### Documentation

Documentation can be found on our [site](http://getgophish.com/documentation). Find something missing? Let us know by filing an issue!

### Issues

Find a bug? Want more features? Find something missing in the documentation? Let us know! Please don't hesitate to [file an issue](https://github.com/Vanhecke/gophish/issues/new) and we'll get right on it.

### License
```
Gophish - Open-Source Phishing Framework

The MIT License (MIT)

Copyright (c) 2013 - 2017 Jordan Wright

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software ("Gophish Community Edition") and associated documentation files (the "Software"), to deal
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
```
