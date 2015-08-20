# PebbleActionList
Since Pebble OS 3.0, we could find a better solution to replace ActionBarLayer to give users a more flexible actions list, which is called [ActionMenu](http://developer.getpebble.com/docs/c/User_Interface/Window/ActionMenu/#ActionMenu) and is used in some of the built-in system apps. But before Pebble SDK 3.3, this feature wasn't included in the SDK, and since SDK 3.3, this feature is still not available for Aplite platform.

I've created this project to realize a simplified single level actions list for both Aplite/Basalt platforms before Pebble SDK 3.3 was published, and it works fine for most of my needs.

There's a known issue that sometimes when we show the actions list for the 1st time, its MenuLayer's scroll position is incorrect...

I use it in my project [PebbleTransilien](https://github.com/CocoaBob/PebbleTransilien), where you can find some demo codes, and here's a screenshot to demonstrate.

<p align="center">
<img src="https://raw.githubusercontent.com/CocoaBob/PebbleActionList/master/demo.gif" width="144" height="168"/>
</p>

## The MIT License (MIT)

Copyright (c) 2015 CocoaBob

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

## Donation

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=A5CD3B7AQMQES)