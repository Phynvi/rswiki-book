\[\[Category Packet\]\] \[\[Category Packet 317\]\] {{packet\|name=Move
item\|description=Sent when the player moves an item from one slot to
another.\|opcode=214\|type=Fixed\|length=7\|revision=317}} == Move Item
==

=== Description ===

This packet is sent when a player moves an item from one slot to
another.

=== Packet Structure === {\|border=2 ! Data Type ! Description \|- \|
\[\[Data Types\#Little Endian\|Little Endian\]\] \[\[Data
Types\#Standard data types\|Short\]\] \[\[Data Types\#Non Standard Data
Types\|Special A\]\] \| The frame ID. \|- \| \[\[Data Types\#Standard
data types\|Byte\]\] \| Insert mode. \|- \| \[\[Data Types\#Little
Endian\|Little Endian\]\] \[\[Data Types\#Standard data types\|Short\]\]
\[\[Data Types\#Non Standard Data Types\|Special A\]\] \| Starting slot.
\|- \| \[\[Data Types\#Little Endian\|Little Endian\]\] \[\[Data
Types\#Standard data types\|Short\]\] \| New slot. \|- \|}
