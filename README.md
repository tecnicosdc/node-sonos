# node-sonos

Node.js Interface to [Sonos](http://sonos.com)

**This is horrible code and very hacky but useful. To find examples/what API's been implemented, check out the examples folder.**

Feel free to open pull-requests and ask questions @bencevans.

## API (Design)


* search()
* Class: Sonos
  * currentTrack(callback)
  * play([url], callback)
  * pause(callback)
  * next(callback)
  * previous(callback)
  * mute(callback)
  * volume(callback)
  * bass([value], callback)
  * treble([value], callback)
* Class: Search
  * Event: 'DeviceAvailable'


## Licence

(MIT Licence)

    Copyright (c) 2012 Ben Evans

    Permission is hereby granted, free of charge, to any person obtaining
    a copy of this software and associated documentation files (the
    "Software"), to deal in the Software without restriction, including
    without limitation the rights to use, copy, modify, merge, publish,
    distribute, sublicense, and/or sell copies of the Software, and to
    permit persons to whom the Software is furnished to do so, subject to
    the following conditions:

    The above copyright notice and this permission notice shall be
    included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
    EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
    MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
    NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
    LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
    OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
    WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.