## Waypoints
Waypoints provides an API to store waypoints for NPCs.

### Chat Commands

    - /waypoints_new -- Create a new waypoints list
    - /waypoints_add SPEED -- Add a waypoint (see below for more information)
    - /waypoints_save NAME -- Save waypoints
    - /waypoints_close -- Close waypoints and don't save
    - /waypoints_remove NAME -- Remove waypoints

### Usage

waypoints_add

When you add a speed, this speed is TO GET TO the CURRENT point, not to the next point (so the first point you set it to get from the last point to the first point).

If you set 2 waypoints on the SAME position, the NPC will stop moving for the amount of time that you set as the SPEED.

### Credits

Nogrod, the original author of the C# version of this plugin
Reneb, the original author of the Lua version
