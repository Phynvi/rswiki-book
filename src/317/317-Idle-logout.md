\[\[Category Packet\]\] \[\[Category Packet 317\]\] {{packet\|name=Idle
logout\|description=Sent when the player has become idle and should be
logged out. \|opcode=202\|type=Fixed\|length=0\|revision=317}} == Idle
logout ==

=== Description ===

This is sent when the player becomes idle and should be logged out. This
is sent after the player is idle for 60 seconds, after that it is sent
every 10 seconds as long as the player is idle.
