\[\[Category Packet\]\] \[\[Category Packet 317\]\] {{packet\|name=Bank
5 items\|description=Sent when a player attempts to bank 5 of a certain
item.\|opcode=117\|type=Fixed\|length=6\|revision=317}} == Bank 5 Items
==

=== Description ===

This packet is sent when a player attempts to bank 5 of a certain
item.<br> '''Note:''' This packet is also used for buying/selling 1 of
an item from a shop.

=== Packet Structure === {\|border=2 ! Data Type ! Description \|- \|
\[\[Data Types\#Little Endian\|Little Endian\]\] \[\[Data
Types\#Standard data types\|Short\]\] \[\[Data Types\#Non Standard Data
Types\|Special A\]\] \| The frame ID. \|- \| \[\[Data Types\#Little
Endian\|Little Endian\]\] \[\[Data Types\#Standard data types\|Short\]\]
\[\[Data Types\#Non Standard Data Types\|Special A\]\] \| The item ID.
\|- \| \[\[Data Types\#Little Endian\|Little Endian\]\] \[\[Data
Types\#Standard data types\|Short\]\] \| The slot ID. \|- \|}
