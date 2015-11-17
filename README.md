CocoaCall
=========

CocoaCall (name currently tentative) is an online service for connecting individuals for meetings. Want to grab coffee with an available friend? Our service can help you do that and so much more. We connect to Google Calendars and search for available time slots between your connections to see how you can best fill your free time.


Table of Contents
-----------------

- [Features](#features)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Deployment](#deployment)
- [Changelog](#changelog)
- [Contributing](#contributing)
- [License](#license)


Features
--------

- TBD


Prerequisites
-------------

- [VirtualEnv](https://virtualenv.readthedocs.org/en/latest/)
- [Node.js](http://nodejs.org)
- [Webpack](https://github.com/webpack/webpack)

**Note:** If you run into any errors, then follow whatever instructions the bugs in your terminal tell you to do, because I haven't run into any bugs installing or getting started. It will most likely deal with node/virtualenv/something not being symlinked or something.


Getting Started
---------------

Get started by first cloning the repository:

```bash
# Get the latest version:
$ git clone https://github.com/danxyu/CocoaCall.git
$ cd CocoaCall

# Create isolated python environment and install dependencies:
$ virtualenv venv
$ source venv/bin/activate
$ pip install -r requirements.txt

# Run the app locally:
$ webpack
$ python app.py
```

**Note:** After each time you make changes, you're going to need to run the webpack command in order for the webpack compiler to rebundle your assets and create a static file attachable to the web app. Do this by just re-running the command and restarting the server. We should probably get a grunt config running so that can be automated.


Deployment
----------

How do you even deploy. Bruh.


Changelog
---------
### 0.0.0 (November 17, 2015)
- Made hello world from react.js, looks super basic.
- Set up webpack configuration and python environment.



License
-------

The MIT License (MIT)

Copyright (c) 2015-2016 Badass Pejman Mar Team 2k15

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.