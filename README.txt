There are totally 4 files in this folder: 
1.Design Document 
2.README file 
3.Unity Project zipped file
3.Unity Project after build (MacOS only)

The Battle of GCube

The game is basically developed in Unity3D on MacOS.

Developers:
Bowen Deng     53132293
Shaolong Lin   36039856
Yuqing Li      37925764
Yaowen Zhang   61347325
Yuran Yan      78666452
Jing Li        78011180
Yian Li        68342735


To play the game, you need one person start the game as LAN Host. Another person should start as LAN Client. Two players should stay under same network environment. Client should enter Host's IPv4 address to enter the game. The game cannot be started if there is only one player in the game.

Basic game-loop:
This is a two players competitive game. There is a 6 minutes timer in this game. Two players need to collect resources named GCube and store the GCube into the resource storage. The GCube and the resource storage will change their positions randomly every 30 seconds in a specific range. When the timer changes to 0 minutes, the player who has more GCube in the resource storage will be the winner. In the game, players can fight against each other to sabotage another player to collect GCube. The knocked down player will have 5 seconds to respawn.  

Basic-controls:
Forward		    W
Backward            S
Left                A
Right		    D
Jump		    Space
Shoot               Left Click
Direction Change    Mouse

Upgrade weapons:
The basic weapon for the players is hammer. The hammer has lower attack power and shorter range. Players can upgrade weapon by picking up randomly respawning guns on the map. The upgraded weapon is a AK47, which has higher attack power and longer range. Competing for gun upgrade will enable players to gain better resistance. The gun can only exist for 30 seconds for every picking up.

Mini Map:
The mini map will show the position of the resource, the resource storage and the enemy player. Through capture the positions on the mini map to have a better view of the game. 
