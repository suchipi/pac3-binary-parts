## PAC3 Binary Parts

Here are a set of PAC3 parts that aren't included in mainline pac3 because they have a dependency on clientside binary modules. Naturally, they require pac3 to function.

## Included parts

###vfs
Allows downloading of files to support other pac3 parts. Right now it only supports being used with the model part but this part is under heavy development and this could change.
Depends on the VFS Module, which you can obtain from http://vfs.suchipi.com/

## Installation

Git clone this repo in your addons folder to get the lua. All the modules should be placed in GarrysMod/garrysmod/lua/bin (Note: Won't work from addons, needs to be placed in your real GarrysMod/garrysmod/lua/bin)

## Special Thanks

* CapsAdmin for writing PAC3 and putting up with my bullshit
* Zeh Matt for writing the original VFS Module
* Python1320 for getting the VFS module working in Gmod 13 and adding RemoveFile and RemoveDir
* Meta Construct for letting me test there and putting up will all my github madness