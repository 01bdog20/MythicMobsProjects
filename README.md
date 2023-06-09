<!-- This is a comment. It will not be displayed in the rendered output. -->

# Bdog's MythicMobs Projects <a name="TOP"></a>
A repository for my minecraft projects using plugins: MythicMobs, ModelEngine, MythicCrucible, Libsdisguises. 
All files should work on 1.19.2.

## Table of Contents
- [Ore Detector](#XRAY)
- [Visibility Scoreboard System](#Visibility)
- [Launch Pad](#Launch)
- [Bottom](#BOTTOM)



## Ore Detector (Xray) <a name="Xray"></a>
Tool that you can use to scan for diamonds nearby.

### Files
[XrayMobs.yml](Mobs/XrayMobs.yml) & [XraySkills.yml](Skills/XraySkills.yml) & [XrayItems.yml](Items/XrayItems.yml)

### Usage
Hold the detector and face a cluster of blocks. Right-click to scan. This method scans ten 5x5 grids in the direction you're looking. Non-diamond ore blocks are temporarily masked as glass, and each block has a temporary mob spawned in it to detect if it's inside a diamond block. If it is, the mob disguises itself temporarily before despawning, otherwise, it despawns instantly. The detected ore positions are relative to the actual ore locations. (The mass of ores in the back of this gif are from a plugin called Orebfuscator, an Anti-Xray plugin)

<img src="/gifs/xray.gif" alt="" width="50%" height="50%">  


## Visibility Scoreboard System <a name="Visibility"></a>
Mobs can only be seen by players with a certain scoreboard value.


### Files
[VisibilityMob.yml](Mobs/VisibilityMob.yml) & [VisibilitySkills.yml](Skills/VisibilitySkills.yml)

### Usage
Once the files are installed in your mythicmob directories create a scoreboard value in game named **'Visibility'** of type dummy, then reload MythicMobs and summon the VisibilityMob. Here you can see me toggle my scoreboard value of **'Visibility'** from NULL to 1 to 0 to test the different boolean states that you can see the mob in.

<img src="/gifs/visibility.gif" alt="" width="50%" height="50%">  


## Launch Pad <a name="Launch"></a>
Launch pad that can modifies players vertical velocity. 

### Files
[LaunchPadMobs.yml](Mobs/LaunchPadMobs.yml) & [LaunchPadSkills.yml](Skills/LaunchPadSkills.yml)

### Usage
Spawn the LaunchPadUp mob and walk on it to be launched. Modify the x=# y=# z=# in LaunchPadSkills.yml to alter 3D velocity.

<img src="/gifs/launchpad.gif" alt="" width="50%" height="50%">  





.
.
.
.
.
.
.
.

[Back to top](#TOP) <a name="BOTTOM"></a>
