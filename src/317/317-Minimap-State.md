\[\[Category Packet\]\] \[\[Category Packet 317\]\]
{{packet\|name=Minimap State\|description=Sets the state of the clients
minimap.\|opcode=99\|type=Fixed\|length=1\|revision=317}} == Minimap
State ==

=== Description ===

This packet sets the Minimaps state

'''States:''' \* 0 - '''Active''': Clickable and viewable \* 1
-'''Locked''': viewable but not clickable \* 2 -'''Blacked-out''':
Minimap is replaced with black background

=== Packet Structure === {\|border=2 ! Data Type ! Description \|- \|
\[\[Data Types\#byte\|byte\]\] \| The state. \|- \|}
