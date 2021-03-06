\[\[Category RS2\]\]

==Client States==

Client states are used to switch between different graphic and logic
procedures. The state of the client is global. There may be cases where
two states will be handled the same graphically but different logically,
vice versa.

  {
  ---

! Opcode ! Name ! Description \|- ! 0 ! Loading (initial) ! Client state
where the client is initially loading itself to the login screen. \|- !
5 ! Loading ! Client state where the client is loading itself to the
login screen. \|- ! 10 ! Login Screen ! Client state where the client is
on the login screen. \|- ! 20 ! Login (initial) ! Client state where the
client initially engages to log in to the server. \|- ! 25 ! Map Rebuild
! Ingame client state where the client rebuilds the map. \|- ! 30 !
Ingame ! Default ingame client state. \|- ! 35 ! Ingame (screen overlay)
! Client state where the client screen is overlayed with a widget. \|- !
40 ! Login ! Client state where the client engages to log in to the
server. \|- ! 1000 ! Fatal Ondemand Error ! Client state where the
client has encountered a fatal ondemand error and will no longer use the
ondemand service. \|}

==Client Actions==

===Social===

  {
  ---

! Opcode ! Frame Name ! Variable 0 ! Variable 1 ! Variable 2 !
Description \|- ! 31 ! \[\[443 Add Friend\|Add Friend\]\] ! NA ! NA ! NA
! Action for when a friend is added. \|- ! 2 ! \[\[443 Remove
Friend\|Remove Friend\]\] ! NA ! NA ! NA ! Action for when a friend is
removed. \|- ! 21 ! \[\[443 Add Ignore\|Add Ignore\]\] ! NA ! NA ! NA !
Action for when an ignore is added. \|- ! 50 ! \[\[443 Remove
Ignore\|Remove Ignore\]\] ! NA ! NA ! NA ! Action for when an ignore is
removed. \|}

===Entities===

  {
  ---

! Opcode ! Frame Name ! Variable 0 ! Variable 1 ! Variable 2 !
Description \|- ! 44 ! \[\[443 Player Option 0\|Player Option 0\]\] ! id
! position x ! position y ! Action for the first option of a player. \|-
! 22 ! \[\[443 Player Option 1\|Player Option 1\]\] ! id ! position x !
position y ! Action for the second option of a player. \|- ! 52 !
\[\[443 Player Option 2\|Player Option 2\]\] ! id ! position x !
position y ! Action for the third option of a player. \|- ! 56 ! \[\[443
Player Option 3\|Player Option 3\]\] ! id ! position x ! position y !
Action for the fourth option of a player. \|- ! 1 ! \[\[443 Player
Option 4\|Player Option 4\]\] ! id ! position x ! position y ! Action
for the fifth option of a player. \|- ! 41 ! \[\[443 Npc Option 0\|Npc
Option 0\]\] ! id ! position x ! position y ! Action for the first
option of a NPC. \|- ! 17 ! \[\[443 Npc Option 1\|Npc Option 1\]\] ! id
! position x ! position y ! Action for the second option of a NPC. \|- !
13 ! \[\[443 Npc Option 2\|Npc Option 2\]\] ! id ! position x ! position
y ! Action for the third option of a NPC. \|- ! 53 ! \[\[443 Npc Option
3\|Npc Option 3\]\] ! id ! position x ! position y ! Action for the
fourth option of a NPC. \|- ! 46 ! \[\[443 Npc Option 4\|Npc Option
4\]\] ! id ! position x ! position y ! Action for the fifth option of a
NPC. \|- ! 40 ! \[\[443 Ground Item Option 0\|Ground Item Option 0\]\] !
item id ! position x ! position y ! Action for the first option of a
ground item. \|- ! 38 ! \[\[443 Ground Item Option 1\|Ground Item Option
1\]\] ! item id ! position x ! position y ! Action for the second option
of a ground item. \|- ! 34 ! \[\[443 Ground Item Option 2\|Ground Item
Option 2\]\] ! item id ! position x ! position y ! Action for the third
option of a ground item. \|- ! 11 ! \[\[443 Ground Item Option 3\|Ground
Item Option 3\]\] ! item id ! position x ! position y ! Action for the
fourth option of a ground item. \|- ! 3 ! \[\[443 Ground Item Option
4\|Ground Item Option 4\]\] ! item id ! position x ! position y ! Action
for the fifth option of a ground item. \|- ! 55 ! \[\[443 Object Option
0\|Object Option 0\]\] ! info hash ! position x ! position y ! Action
for the first option of an object. \|- ! 57 ! \[\[443 Object Option
1\|Object Option 1\]\] ! info hash ! position x ! position y ! Action
for the second option of an object. \|- ! 43 ! \[\[443 Object Option
2\|Object Option 2\]\] ! info hash ! position x ! position y ! Action
for the third option of an object. \|- ! 6 ! \[\[443 Object Option
3\|Object Option 3\]\] ! info hash ! position x ! position y ! Action
for the fourth option of an object. \|- ! 1005 ! \[\[443 Object Option
4\|Object Option 4\]\] ! info hash ! position x ! position y ! Action
for the fifth option of an object. \|- \|}

===Widget===

  {
  ---

! Opcode ! Frame Name ! Variable 0 ! Variable 1 ! Variable 2 !
Description \|- ! 28 ! \[\[443 Item On Widget Option 0\|Item on Widget
Option 0\]\] ! id ! slot ! widget id ! Action for the first option of an
item on a widget. \|- ! 16 ! \[\[443 Item On Widget Option 1\|Item on
Widget Option 1\]\] ! id ! slot ! widget id ! Action for the second
option of an item on a widget. \|- ! 54 ! \[\[443 Item On Widget Option
2\|Item on Widget Option 2\]\] ! id ! slot ! widget id ! Action for the
third option of an item on a widget. \|- ! 32 ! \[\[443 Item On Widget
Option 3\|Item on Widget Option 3\]\] ! id ! slot ! widget id ! Action
for the fourth option of an item on a widget. \|- ! 19 ! \[\[443 Item On
Widget Option 4\|Item on Widget Option 4\]\] ! id ! slot ! widget id !
Action for the fifth option of an item on a widget. \|- ! 35 ! \[\[443
Widget Item Option 0\|Widget Item Option 0\]\] ! id ! slot ! widget id !
Action for the first option of an item on a widget. \|- ! 30 ! \[\[443
Widget Item Option 1\|Widget Item Option 1\]\] ! id ! slot ! widget id !
Action for the second option of an item on a widget. \|- ! 26 ! \[\[443
Widget Item Option 2\|Widget Item Option 2\]\] ! id ! slot ! widget id !
Action for the third option of an item on a widget. \|- ! 25 ! \[\[443
Widget Item Option 3\|Widget Item Option 3\]\] ! id ! slot ! widget id !
Action for the fourth option of an item on a widget. \|- ! 49 ! \[\[443
Widget Item Option 4\|Widget Item Option 4\]\] ! id ! slot ! widget id !
Action for the fifth option of an item on a widget. \|}

===Examine===

  {
  ---

! Opcode ! Frame Name ! Variable 0 ! Variable 1 ! Variable 2 !
Description \|- ! 1006 ! \[\[443 Object Examine\|Object Examine\]\] ! id
! position x ! position y ! Action for the examine option of an object.
\|- ! 1001 ! \[\[443 Npc Examine\|Npc Examine\]\] ! id ! position x !
position y ! Action for the examine option of a Npc. \|- ! 1003 !
\[\[443 Ground Item Examine\|Ground Item Examine\]\] ! id ! position x !
position y ! Action for the examine option of a ground item. \|- ! 1004
! \[\[443 Item Examine\|Item Examine\]\] ! id ! slot ! widget id !
Action for the examine option of an item. \|}

===Other===

  {
  ---

! Opcode ! Frame Name ! Variable 0 ! Variable 1 ! Variable 2 !
Description \|- ! 29 ! \[\[443 Close Window\|Close Window\]\] ! NA ! NA
! NA ! Action for when the currently open window is closed. \|}

==Game Protocol==

===Server Frames===

  {
  ---

! Opcode ! Type ! Length (bytes) ! Name ! Description \|- ! 29 !
VARIABLE SHORT ! NA ! \[\[443 Player Update\|Player Update\]\] ! Updates
the players within the client's view. \|- ! 238 ! VARIABLE SHORT ! NA !
\[\[443 NPC Update\|NPC Update\]\] ! Updates the npcs within the
client's view. \|- ! 121 ! VARIABLE SHORT ! NA ! \[\[443 Rebuild Scene
Graph\|Rebuild Scene Graph\]\] ! Rebuilds the players scene graph. \|- !
193 ! VARIABLE SHORT ! NA ! \[\[443 Rebuild Scene Graph\|Rebuild Custom
Scene Graph\]\] ! Builds a custom scene graph. \|- ! 199 ! FIXED ! 3 !
\[\[443 Set Location\|Set Location\]\] ! Sets the location on the map of
where the player is. \|- ! 111 ! FIXED ! 6 ! \[\[443 Move Camera
To\|Move Camera To\]\] ! Moves the camera to a location on the map. \|-
! 157 ! VARIABLE BYTE ! NA ! \[\[443 Send Message\|Send Message\]\] !
Sends a message to the client's chatbox. \|- ! 58 ! FIXED ! 6 ! \[\[443
Update Skill\|Update Skill\]\] ! Updates a skill by sending its
experience and dynamic level. \|- ! 226 ! FIXED ! 1 ! \[\[443 Update Run
Energy\|Update Run Energy\]\] ! Updates the amount of run energy the
player has. \|- ! 87 ! FIXED ! 1 ! \[\[443 Set Minimap State\|Set
Minimap State\]\] ! Sets the minimap state. \|- ! 117 ! FIXED ! 1 !
\[\[443 System Update\|System Update\]\] ! Informs the client that a
system update will be happening. \|- ! 192 ! VARIABLE SHORT ! NA !
\[\[443 Execute Client Script\|Execute Client Script\]\] ! Executes a
client script. \|- ! 204 ! VARIABLE SHORT ! NA ! \[\[Class Check\|Class
Check Request\]\] ! Parses a request for a class check request. \|- ! 89
! FIXED ! 5 ! \[\[443 Player Sound Effect\|Player Sound Effect\]\] !
Plays a sound effect. \|- ! 74 ! FIXED ! 6 ! \[\[443 Set State
Value\|Set State Value (large)\]\] ! Sets the value of a client state
variable. \|- ! 62 ! FIXED ! 3 ! \[\[443 Set State Value\|Set State
Value (small)\]\] ! Sets the value of a client state variable. \|- ! 163
! FIXED ! 0 ! \[\[443 Reset States\|Reset States\]\] ! Resets all the
client state variables. \|- ! 160 ! FIXED ! 4 ! \[\[443 Display
Window\|Display Window\]\] ! Displays a widget as a window. \|- ! 221 !
FIXED ! 4 ! \[\[443 Display Screen Overlay\|Display Screen Overlay\]\] !
Displays widgets over the entire screen of the client. \|- ! 6 ! FIXED !
2 ! \[\[443 Display Chatbox Interface\|Display Chatbox Interface\]\] !
Displays the chatbox as a widget. \|- ! 178 ! FIXED ! 0 ! \[\[443 Close
Displayed Widgets\|Close Displayed Widgets\]\] ! Closes all the
displayed widgets except for the chatbox interface. \|- ! 51 ! FIXED ! 0
! \[\[443 Fetch Input\|Fetch Input\]\] ! Fetches input from the chatbox.
\|- ! 3 ! FIXED ! 6 ! \[\[443 Change Inactive Color\|Change Inactive
Color\]\] ! Changes the widget's inactive color. \|- ! 232 ! FIXED ! 10
! \[\[443 Set Offset\|Set Offset\]\] ! Sets the x and y offset of a
widget. \|- ! 31 ! FIXED ! 4 ! \[\[443 Display Player On Widget\|Display
Player on Widget\]\] ! Displays the local player on a widget. \|- ! 137
! FIXED ! 10 ! \[\[443 Display Item On Widget\|Display Item on
Widget\]\] ! Displays the model of an item on a widget. \|- ! 147 !
FIXED ! 10 ! \[\[443 Set Model Rotation\|Set Model Rotation\]\] ! Sets
the x and y rotation of a model on a widget. \|- ! 73 ! FIXED ! 8 !
\[\[443 Rotate Model\|Rotate Model\]\] ! Sets the step amount to rotate
the model continuously about the x axis. \|- ! 228 ! VARIABLE SHORT ! NA
! \[\[443 Send Items\|Send Items\]\] ! Sends the items in an item
container. \|- ! 213 ! VARIABLE SHORT ! NA ! \[\[443 Update
Items\|Update Items\]\] ! Updates the items in an item container from
their slot id. \|- ! 245 ! FIXED ! 0 ! \[\[443 Reset Items\|Reset
Items\]\] ! Resets all the items in an item container. \|- ! 82 ! FIXED
! 2 ! \[\[443 Set Spawn Sector\|Set Spawn Sector\]\] ! Sets the sector
on the map where entities will be spawned. \|- ! 244 ! VARIABLE SHORT !
NA ! \[\[443 Spawn Sector\|Spawn Sector\]\] ! Parses the sector of the
map to spawn entities, then the actual entity spawns. \|- ! 207 ! FIXED
! 5 ! \[\[443 Spawn Ground Item\|Spawn Ground Item\]\] ! Spawns a ground
item. \|- ! 94 ! FIXED ! 7 ! \[\[443 Spawn Ground Item\|Spawn Ground
Item\]\] ! Spawns a ground item that will ignore whoever it has already
been spawned to. \|- ! 79 ! FIXED ! 7 ! \[\[443 Update Ground
Item\|Update Ground Item\]\] ! Updates the item amount for a ground
item. \|- ! 84 ! FIXED ! 3 ! \[\[443 Remove Ground Item\|Remove Ground
Item\]\] ! Removes a ground item. \|- ! 122 ! FIXED ! 4 ! \[\[443 Spawn
Still Object\|Spawn Still Object\]\] ! Spawns a still object. \|- ! 170
! FIXED ! 4 ! \[\[443 Animate Still Object\|Animate Still Object\]\] !
Animates a still object. \|- ! 69 ! FIXED ! 2 ! \[\[443 Remove Still
Object\|Remove Still Object\]\] ! Removes a still object. \|- ! 115 !
FIXED ! 6 ! \[\[443 Spawn Still Graphic\|Spawn Still Graphic\]\] !
Spawns a still graphic. \|- ! 101 ! FIXED ! 15 ! \[\[443 Spawn
Projectile\|Spawn Projectile\]\] ! Spawns a projectile. \|- ! 109 !
FIXED ! 5 ! \[\[443 Spawn Ambient Sound Effect\|Spawn Ambient Sound
Effect\]\] ! Spawns an ambient sound effect. \|- ! 133 ! FIXED ! 2 !
\[\[443 Reset Sector\|Reset Sector\]\] ! Resets all the ground items and
still objects in a sector. \|- ! 41 ! FIXED ! 0 ! \[\[443
Logout\|Logout\]\] ! Logs the client out from the server. \|}

===Client Frames===

==== Actions ====

  {
  ---

! Opcode ! Type ! Length (bytes) ! Name ! Description \|- ! 90 ! FIXED !
8 ! \[\[443 Add Friend\|Add Friend\]\] ! Called when a new name has been
added to the friend list. \|- ! 159 ! FIXED ! 8 ! \[\[443 Remove
Friend\|Remove Friend\]\] ! Called when a name has been removed from the
friend list. \|- ! 198 ! FIXED ! 8 ! \[\[443 Add Ignore\|Add Ignore\]\]
! Called when a new name has been added to the ignore list. \|- ! 250 !
FIXED ! 8 ! \[\[443 Remove Ignore\|Remove Ignore\]\] ! Called when a
name has been removed from the ignore list. \|- ! 11 ! FIXED ! 2 !
\[\[443 Player Option 0\|Player Option 0\]\] ! Called when the first
option of a player is activated. \|- ! 169 ! FIXED ! 2 ! \[\[443 Player
Option 1\|Player Option 1\]\] ! Called when the second option of a
player is activated. \|- ! 229 ! FIXED ! 2 ! \[\[443 Player Option
2\|Player Option 2\]\] ! Called when the third option of a player is
activated. \|- ! 101 ! FIXED ! 2 ! \[\[443 Player Option 3\|Player
Option 3\]\] ! Called when the fourth option of a player is activated.
\|- ! 206 ! FIXED ! 2 ! \[\[443 Player Option 4\|Player Option 4\]\] !
Called when the fifth option of a player is activated. \|- ! ! ! !
\[\[443 Npc Option 0\|Npc Option 0\]\] ! \|- ! ! ! ! \[\[443 Npc Option
1\|Npc Option 1\]\] ! \|- ! ! ! ! \[\[443 Npc Option 2\|Npc Option 2\]\]
! \|- ! ! ! ! \[\[443 Npc Option 3\|Npc Option 3\]\] ! \|- ! ! ! !
\[\[443 Npc Option 4\|Npc Option 4\]\] ! \|- ! ! ! ! \[\[443 Ground Item
Option 0\|Ground Item Option 0\]\] ! \|- ! ! ! ! \[\[443 Ground Item
Option 1\|Ground Item Option 1\]\] ! \|- ! ! ! ! \[\[443 Ground Item
Option 2\|Ground Item Option 2\]\] ! \|- ! ! ! ! \[\[443 Ground Item
Option 3\|Ground Item Option 3\]\] ! \|- ! ! ! ! \[\[443 Ground Item
Option 4\|Ground Item Option 4\]\] ! \|- ! ! ! ! \[\[443 Still Object
Option 0\|Still Object Option 0\]\] ! \|- ! ! ! ! \[\[443 Still Object
Option 1\|Still Object Option 1\]\] ! \|- ! ! ! ! \[\[443 Still Object
Option 2\|Still Object Option 2\]\] ! \|- ! ! ! ! \[\[443 Still Object
Option 3\|Still Object Option 3\]\] ! \|- ! ! ! ! \[\[443 Still Object
Option 4\|Still Object Option 4\]\] ! \|- ! ! ! ! \[\[443 Item On
Player\|Item On Player\]\] ! \|- ! ! ! ! \[\[443 Item On NPC\|Item On
NPC\]\] ! \|- ! ! ! ! \[\[443 Item On Ground Item\|Item On Ground
Item\]\] ! \|- ! ! ! ! \[\[443 Item On Still Object\|Item On Still
Object\]\] ! \|- ! ! ! ! \[\[443 Item On Item\|Item On Item\]\] ! \|- !
! ! ! \[\[443 Widget On Player\|Widget On Player\]\] ! \|- ! ! ! !
\[\[443 Widget On NPC\|Widget On NPC\]\] ! \|- ! ! ! ! \[\[443 Widget On
Ground Item\|Widget On Ground Item\]\] ! \|- ! ! ! ! \[\[443 Widget On
Still Object\|Widget On Still Object\]\] ! \|- ! ! ! ! \[\[443 Widget On
Item\|Widget On Item\]\] ! \|- ! ! ! ! \[\[443 Widget On Widget\|Widget
On Widget\]\] ! \|- ! ! ! ! \[\[443 Still Object Examine\|Still Object
Examine\]\] ! \|- ! ! ! ! \[\[443 Npc Examine\|Npc Examine\]\] ! \|- ! !
! ! \[\[443 Item Examine\|Item Examine\]\] ! \|- ! 54 ! FIXED ! 4 !
\[\[443 Widget Action\|Widget Action\]\] ! Called when a widget action
is activated. \|- ! 70 ! FIXED ! 0 ! \[\[443 Closed Overlays\|Closed
Overlays\]\] ! Called when the currently opened overlays are closed. \|}

==== Other ====

  {
  ---

! Opcode ! Type ! Length (bytes) ! Name ! Description \|- ! 194 !
VARIABLE BYTE ! NA ! \[\[Class Check\|Class Check Response\]\] !
Response to a class check request sent from the server. \|- ! 4 ! NA !
VARIABLE BYTE ! \[\[443 Chat\|Chat\]\] ! Called when the client enters
in a chat message. \|- ! 21 ! 0 ! FIXED ! \[\[443 Map Rebuilt\|Map
Rebuilt\]\] ! Called when the map has been successfully rebuilt. \|- !
174 ! NA ! VARIABLE BYTE ! \[\[443 Command\|Command\]\] ! Called when
the client inputs a command. \|}

=== Update Flags ===

All flags are listed in order in which they are parsed.

==== Player ====

==== NPC ====

{\| border=3px ! Opcode ! Name ! Description \|- ! 0x2 ! Face Position !
Turns to face the NPC to a position on the map. \|- ! 0x20 ! Animate !
Animates the NPC. \|- ! 0x40 ! Display Hit One ! Displays a hit on the
NPC. \|- ! 0x4 ! Display Still Graphic ! Displays a still graphic on the
NPC. \|- ! 0x10 ! Turn to mobile entity ! Turns to face the NPC to a
mobile entity on the map. \|- ! 0x80 ! Display Hit Two ! Displays a hit
on the npc. \|- ! 0x1 ! Turn into NPC ! Changes the id of the NPC and
its animations. \|- ! 0x8 ! Display chat text ! Displays chat text above
the head of the NPC. \|}
