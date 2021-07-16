8bitdo n30 USB (also has Bluetooth. not tested)
===
![image](https://github.com/alex-ong/NESControllerReviews/raw/master/USB/8bitdo_N30/images/face.png)

**8Bitdo n30 USB has received a firmware update. Please update to get lowest latency!**

Polling Rate stock - Somewhere between **16ms and 32ms**
After Update - **4ms**

*Read below for tests before and after the firmware update*

Stock firmware speed
===


Tests generously supplied by EricICX
This is connected via USB.

![image](https://github.com/alex-ong/NESControllerReviews/raw/master/USB/8bitdo_N30/images/test1.png)
![image](https://github.com/alex-ong/NESControllerReviews/raw/master/USB/8bitdo_N30/images/test2.png))

From testing, we can assume that it probably attempts to round inputs to 16ms frames, before sending. 
However, due to its processor probably being a tad slow, it often rounds to 30ms segments instead.

After firmware update (Late 2020~)
===
![image](https://github.com/alex-ong/NESControllerReviews/raw/master/USB/8bitdo_N30/images/test3.png))
After the updated firmware, the USB rate is now 1000hz and the internal polling rate seems boosted to 250hz.
This should be fine for frame perfect games.

EricICX tested the Tomee adapter and got the same result as me (16ms~), so we can rule out hardware 
errors on his end.

Bluetooth latency has *not* been tested; this is through USB.

