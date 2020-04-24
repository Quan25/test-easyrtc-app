Testing Project of Open-EasyRTC for self use only
=======

[![npm version](https://img.shields.io/npm/v/open-easyrtc.svg?style=flat)](https://www.npmjs.com/package/open-easyrtc)
[![Build Status](https://travis-ci.org/open-easyrtc/open-easyrtc.svg?branch=master)](https://travis-ci.org/open-easyrtc/open-easyrtc)

this project is a Fork of Open-EasyRTC, include an EasyRTC server and client API, HTML5 and JavaScript demos under a BSD 2 license.

Original Source and Fork intent
--------------------

This NodeJS `open-easyrtc` module version is a fork of `easyrtc` hosted on Github originally made by `Priologic Software Inc.` and available here: https://github.com/open-easyrtc/open-easyrtc


Features
--------
 * Install EasyRTC's WebRTC Server on your own Linux, Windows, or Mac server in minutes not days.
 * Use our EasyRTC API and sample application code to build and deploy your WebRTC app in hours not weeks.
 * EasyRTC is completely free and open source under a BSD 2 license. No usage costs or other hidden fees.

Installation In A Nutshell
--------------------------
 1. Install [Node.js](http://nodejs.org)
 2. Download the EasyRTC distribution from github (https://github.com/open-easyrtc/open-easyrtc.git)
 3. Run `npm install` in the easyrtc directory.
 4. Enter the easyrtc/server_example directory by executing `cd server_example`
 5. Run `npm install` in the server_example directory.
 4. Start EasyRTC by running `node server.js` while in the server_example directory.
 5. Browse the examples using a WebRTC enabled browser. *(defaults to port `8080`)*

Important note: Chrome will not grant access to local microphones or cameras for a page served using http except for the localhost case. See the docs/easyrtc_server_ssl.md file for instructions on serving files using https.

Step by step instructions including additional setup options can be found in `/docs/easyrtc_server_install.md`

Note: there is no corresponding need to install the client files specifically; they were installed as part of EasyRTC in step 3.

Included Demos
--------------

EasyRTC comes with a number of demo's which work immediately after installation.

 * Video and/or Audio connections
 * Multi-party video chat
 * Text Messaging with or without Data Channels
 * Screen and tab sharing
 * File transfer
 * Client side video recording

License
-------

Copyright (c) 2016, Priologic Software Inc.
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

    * Redistributions of source code must retain the above copyright notice,
      this list of conditions and the following disclaimer.
    * Redistributions in binary form must reproduce the above copyright
      notice, this list of conditions and the following disclaimer in the
      documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.
