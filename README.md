# laserBelt
NeoPixel LED strip + micro Arduino + accelerometer = laserBelt

There's not much more to it. Was generally a big hit. Two main modes: propagating waves, or stationary pulses. Both triggered by the accelerometer. 

The rechargeable LiPo battery was lightweight and lasted for hours.

Biggest challenges were:
- filtering the accelerometer output to get useful impulse info, knowing that it might be rotating in all directions.
- calibrating the sensitivity.

The weak link is the LED strip itself. Enormous temptation to wave it around like a lightsaber but it quickly breaks near the handle. Hence the belt is quite a few LEDs shorter than it used to be.

<img src=https://user-images.githubusercontent.com/25584653/111915094-8d7fdc00-8a6c-11eb-8ebc-ce9c14e4ea48.gif width=25% height=50%>
