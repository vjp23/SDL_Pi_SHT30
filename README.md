#
# SDL_Pi_SHT30
#
# SHT30 Pure Python Library
# SwitchDoc Labs July 2019
#
#

Version 1.3: July 27, 2019:  Fixed typo and problem with T > 120F<BR>
Version 1.2: July 13, 2019:  Fixed Typo in fast reads <BR>
Version 1.1: July 8, 2019:  Initial Version<BR>
 

#Introduction

For the SwitchDoc Labs SHT30<BR>



# testing

```
import SHT30 
sens = SHT30.SHT30()
print sens.read_temperature()
print sens.read_humidity()
print sens.read_humidity_temperature()
print sens.read_humidity_temperature_crc()
```
