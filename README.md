AI Development for Enemy Groups as part of my work at "Rabbiot Game Studio"
Technical Assignment: Enemies move across the map in groups of N to M units along predetermined points, maintaining equal distance between each other. The movement sequence is looped, with enemies returning to their initial point. When one enemy in the group spots the player, the entire group enters combat mode. Enemies primarily engage in melee combat, with occasional ranged attacks (e.g., throwing a rock).

Enemy behavior is implemented according to this scheme: Punk behavior tree_scheme.png.
Technical Guide: Developed a guide for GD/LD: Notion link (duplicated in Technological_Guide.zip).
Demo video: Demo_video.

Key Features:
BP Coordinator: Assigns roles to bots within the group (leader, front, etc.), marks them, and tracks the number and structure of the squad.
Squad member roles: Bots act according to their assigned roles.
Crowd AI controller: Manages interactions between bots in the group.
BT-based behavior: The behavior tree primarily consists of custom tasks, services, and decorators.
Dice roll logic: Implemented to create visually chaotic behavior for enemies.
