# PolEi

This small circuit (developed by Gerald Klein) is intended for polarity testing when setting up DCC track systems - e.g. from modules. It is designed for voltages from 12 to 17 volts effective.

***Usage***:<br>
Place the PolEi over the separation point so that each current collector has a track connection.
The following statements are possible with the LEDs:<br> 
- **LED left lights up**: DCC signal present on the left track.<br>
- **LED on the right lights up**: DCC signal present on the right track.<br>
- **Right and left LEDs light up**: Both middle LEDs remain dark: DCC phase position at the track separation point is correct.<br>
- **Right and left LEDs light up**, **red LED flashes**: Booster limits are reversed![^1]<br>
- **LED right and left and the middle yellow LED lights up**: there is a polarity reversal at the track disconnection point within a booster district!<br>

### miscellaneous
A description was published in "Digitale Modellbahn 01/2018".<br>

Original files can be found her:<br>
- https://fremodcc.sourceforge.net/diy/PolEi/index.de.html<br>
- https://sourceforge.net/p/fremodcc/svn/HEAD/tree/PolungsPruefer/<br>

A kit is available here:<br>
- https://www.h0fine.de/Shop2/product_info.php?products_id=32<br>

An alternative housing can be found here:<br>
- https://www.thingiverse.com/thing:4565243

[^1]: Prerequisite for a correct measurement is that the two neighboring boosters are not supplied with power via a common power supply unit. 
