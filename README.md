# GCalcSearch
Advanced Calculator Gnome Shell Extension

# Important Stuff

### Information

The Advanced Calculator tool supports everything Gnome calculator supports, plus the following extensions:

The phrase 'pi' (single quotes included) can be used to denote the constant (3.14159...)

Numbers are by default entered in decimal.
Numbers can be entered in the following bases by prefixing the number with the value listed after the ':'
	16 : 0x
	8 : 0
	2 : 0b

	
The result is by default displayed in decimal. It can be displayed in one of the following bases by ending with the listed string (without the quotes):
	16 : "in hex"
	8 : "in octal"
	2 : "in binary"

For instance the following string:
	(065 - 0b1011) * 0x3A + 12 in octal
displays the answer in octal, which is
	04620

Please note that fractional values are not currently supported for alternate base entry. 
	I.e. 0xA.2 will not register as a hex value. 
They are also not supported for final display. The result will be rounded down to the nearest integer before being converted to an alternate base.
	I.e. "'pi' in octal" displays "03"
