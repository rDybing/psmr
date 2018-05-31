Post Scriptum Mortar Range &amp; Bearing tool

CCBY Roy Dybing 2018

### Simple Bash tool to find range and bearing from point A to point B on the Post Scriptum maps
#### aka making mortars accurate and easy to use

Takes coordinates in PS format, eg: C9-6-7. First enter origin coordinates, hit enter. Then enter target coordinates, hit enter.

The first letter can be either upper or lower case, doesn't matter. For best results make sure your mortars are placed roughly in the middle of the smallest map-squares.

### Calculations done:

#### Range:
distance = sqrt((x2 - x1) ^ 2 + (y2 - y1) ^ 2)

#### Bearing
radians = atan2(y2 - y1, x2 - x1)
degrees = (radians + PI) * 360.0 / (2.0 * PI)
