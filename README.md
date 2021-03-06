# DonkeyKongReverse

Always wanted to know how it would be to play Donkey Kong in reverse??? 

It is now possible with this rom hack Donkey Kong Reverse.

In Donkey Kong Reverse, jumpman starts the barrels stage, conveyors stage and elevators stage at the top of the screen and has to grab Pauline's heart at the bottom: 

- Imaging running down the girders while being chased by the barrels behind you in the barrels stage. 
- Or trying to evade the bouncing springs while trying to ascend the top ladder in the elevator stage. 
- Or trying not to be grabbed by Donkey Kong at the top conveyor in the conveyor stage.

And in the rivets stage, instead of unplugging the rivets, jumpman has to plug them back in. Instead of the tactic in which you try to lock the firefoxes at one side of the screen, they are already locked when they spawn. And by plugging the rivets in, you free them and enable them to start roaming the screen.

YouTube video: https://youtu.be/GKTIVgMJeFo.

There are two ways to play this rom-hack:

- Play in an emulator that supports the rom-hack. Currently Homebrew Mame (HBMame) and Libretro FB Neo (lr-fbneo) support the game. Use the dkongrev.zip and place it in the appropriate rom location. On RetroPie you must use the lr-fbneo emulator to play the rom-hack. You might have to update Retropie lr-fbneo from source to get the most recent version of the emulator.

- On most other emulators (e.g. WolfMame) you can play this game by replacing the original dkong.zip by this Reverse version of the dkong.zip. You have to start the emulator without checksum checking (in WolfMame by starting it from the command line and specifying the romname).

Besides the reversed gameplay I've tried to keep the game as close to the original as possible. However, to increase the gameplay, I had to make the following adjustments:

- In the barrels stage, barrels do not disappear when they roll off the edge of a girder lower than jumpman's position. 

- In the elevators stage, the first bouncing spring starts immediately instead of waiting a few seconds.

- In the conveyors stage, jumpman is able to walk on the top conveyor belt and dies when he touches Donkey Kong.

- In the conveyors stage, firefoxes spawn from the oil can at the side opposite to jumpman and are more freely roaming.

- In the rivets stage the end of level animation no longer displays collapsing girders.

- In all stages it is a little easier to jump fireballs/firefoxes: they do not change direction when jumpman jumps them. 

