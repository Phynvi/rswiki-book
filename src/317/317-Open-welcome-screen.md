\[\[Category Packet\]\] \[\[Category Packet 317\]\] {{packet\|name=Open
welcome screen\|description=Displays the welcome
screen.\|opcode=176\|type=Fixed\|length=10\|revision=317}} == Open
Welcome Screen ==

=== Description ===

This packet displays the welcome screen.

=== Packet Structure === {\|border=2 ! Data Type ! Description \|- \|
\[\[Data Types\#Standard data type\|Byte\]\] \[\[Data Types\#Non
Standard data types\|Special C\]\] \| Days since last recovery change
(200 for not yet set, 201 for members server). \|- \| \[\[Data
Types\#Standard data type\|Short\]\] \[\[Data Types\#Non Standard data
types\|Special A\]\] \| Number of unread messages. \|- \| \[\[Data
Types\#Standard data types\|Byte\]\] \| Member warning (1 for member, 0
for non-member). \|- \| \[\[Data Types\#Non Standard data
types\|Middle-Endian Big Integer\]\] \| Last logged IP. \|- \| \[\[Data
Types\#Standard data types\|Short\]\] \| Last logged successful log-n.
\|- \|}
