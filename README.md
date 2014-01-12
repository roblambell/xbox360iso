Xbox360ISO
==========

Xbox 360 ISO / Xex Analysis &amp; Extraction

Requirements
------------
 * Python 3.x

Usage
------------

```python
# Import Xbox360ISO and parse an ISO
from xbox360iso import Xbox360ISO
props = Xbox360ISO().parse("Portal 2.iso")
if props:
	print("Game: %s [%s]" % (props["game_name"], props["title_id"]))
