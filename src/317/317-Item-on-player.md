\[\[Category Packet\]\] \[\[Category Packet 317\]\] {{packet\|name=Item
on player\|description=Sent when a player uses an item on another
player.\|opcode=14\|type=Fixed\|length=8\|revision=317}} == Item on
Player ==

=== Description ===

This packet is sent when a player uses an item on another player.

=== Packet Structure === {\|border=2 ! Data Type ! Description \|- \|
\[\[Data Types\#Standard data types\|Short\]\] \[\[Data Types\#Non
Standard Data Types\|Special A\]\] \| The frame ID. \|- \| \[\[Data
Types\#Standard data types\|Short\]\] \| The other players ID. \|- \|
\[\[Data Types\#Standard data types\|Short\]\] \| The item ID. \|- \|
\[\[Data Types\#Little Endian\|Little Endian\]\] \[\[Data
Types\#Standard data types\|Short\]\] \| The items slot ID. \|- \|}
