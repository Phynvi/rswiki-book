\[\[Category Packet\]\] \[\[Category Packet 317\]\]
{{packet\|name=Report player\|description=Sent when a player reports
another player.\|opcode=218\|type=Fixed\|length=8\|revision=317}} ==
Report Player ==

=== Description ===

This packet is sent when a player reports another player.

=== Packet Structure === {\|border=2 ! Data Type ! Description \|- \|
\[\[Data Types\#Standard data types\|Long\]\] \| The players name as a
long. \|- \| \[\[Data Types\#Standard data types\|Byte\]\] \| The rule
that's being reported \|- \| \[\[Data Types\#Standard data
types\|Byte\]\] \| Mute for 48 hours - Sent as either 1 or 0 for a
boolean client-side \|}
