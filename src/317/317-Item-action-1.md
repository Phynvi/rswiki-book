\[\[Category Packet\]\] \[\[Category Packet 317\]\] {{packet\|name=Item
action 1\|description=Sent when the player clicks the first option of an
item.\|opcode=122\|type=Fixed\|length=6\|revision=317}} == Item Action 1
==

=== Description ===

This packet is sent when a player clicks the first option of an item,
such as "Bury" for bones or "Eat" for food.

=== Packet Structure === {\|border=2 ! Data Type ! Description \|- \|
\[\[Data Types\#Little Endian\|Little Endian\]\] \[\[Data
Types\#Standard data types\|Short\]\] \[\[Data Types\#Non Standard Data
Types\|Special A\]\] \| The frame ID. \|- \| \[\[Data Types\#Standard
data types\|Short\]\] \[\[Data Types\#Non Standard Data Types\|Special
A\]\] \| The slot the item is in. \|- \| \[\[Data Types\#LITTLE
Endian\|Little Endian\]\] \[\[Data Types\#Standard data types\|Short\]\]
\| The ID of the item. \|- \|}
