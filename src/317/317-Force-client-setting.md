\[\[Category Packet\]\] \[\[Category Packet 317\]\] {{packet\|name=Force
client setting\|description=Forcefully alters a client setting value and
default value to some supplied
value.\|opcode=36\|type=Fixed\|length=3\|revision=317}} == Force Client
Setting ==

=== Description ===

The client stores various user settings in an array, the default values
are also stored in another array. This packet changes the default value
for a setting and its current value to the one given.

=== Packet Structure ===

{\| border=2 ! Data type ! Description \|- \| \[\[Data Types\#Standard
data types\|Short\]\] \[\[Data Types\#Byte Order\|Little Endian\]\] \|
Setting ID number. \|- \| \[\[Data Types\#Standard data types\|Byte\]\]
\| New value (and default value) for the setting. \|- \|}

=== Other Information === Opcode 87 (length 6) is extremely similar in
structure, but the new value is received as an Middle Endian Small Int.
This suggests its for use with bigger setting values.
