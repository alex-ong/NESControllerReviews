8bitdo n30 USB (also has Bluetooth. not tested)
===
Polling Rate - Somewhere between 16ms and 32ms

![image](https://github.com/alex-ong/NESControllerReviews/raw/master/USB/8bitdo_N30/images/face.png)

Tests generously supplied by EricICX
This is connected via USB.

![image](https://github.com/alex-ong/NESControllerReviews/raw/master/USB/8bitdo_N30/images/test1.png)
![image](https://github.com/alex-ong/NESControllerReviews/raw/master/USB/8bitdo_N30/images/test2.png))

From testing, we can assume that it probably attempts to round inputs to 16ms frames, before sending. 
However, due to its processor probably being a tad slow, it often rounds to 30ms segements instead.

EricICX tested the Tomee adapter and got the same result as me (16ms~), so we can rule out hardware 
errors on his end.

Bluetooth latency has *not* been tested; this is through USB.

