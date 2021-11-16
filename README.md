CMPUT404-assignment-websockets
==============================

CMPUT404-assignment-websockets

See requirements.org (plain-text) for a description of the project.

Make a shared state Websockets drawing program

Prereqs
=======
Create a virtual environment and install the required dependencies.

```bash
virtualenv venv --python=python3
source venv/bin/activate
pip install -r requirements.txt
```

Contributors / Licensing
========================

Generally everything is LICENSE'D under the Apache 2 license by Abram Hindle.

freetests.py is LICENSE'D under a BSD-like license:

From ws4py

Copyright (c) 2011-2014, Sylvain Hellegouarch, Abram Hindle
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

 * Redistributions of source code must retain the above copyright notice,
   this list of conditions and the following disclaimer.
 * Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.
 * Neither the name of ws4py nor the names of its contributors may be used
   to endorse or promote products derived from this software without
   specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.

Contributors
============

* Mark Galloway
* Abram Hindle
* Cole Mackenzie
* Sandy Huang


Sources
============

Borrowed class Client, send_all, send_all_json methods, subscribe_socket, read_ws
By: Abram Hindle
Source: https://github.com/uofa-cmput404/cmput404-slides/blob/master/examples/WebSocketsExamples/broadcaster.py
Licensed under the Apache License, Version 2.0 (the "License")


broadcast.html
By: Abram Hindle
https://github.com/uofa-cmput404/cmput404-slides/blob/master/examples/WebSocketsExamples/static/broadcast.html
Licensed under the Apache License, Version 2.0 (the "License");

Redirecting to URL in Flask https://stackoverflow.com/questions/14343812/redirecting-to-url-in-flask

Json dumps and loads https://www.educative.io/edpresso/what-is-the-difference-between-jsonloads-and-jsondumps

Json Parse https://www.w3schools.com/js/js_json_parse.asp

Sending and recieving data in JSOn format using POST/GET methods https://stackoverflow.com/questions/24468459/sending-a-json-to-server-and-retrieving-a-json-in-return-without-jquery

