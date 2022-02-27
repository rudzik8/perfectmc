# PerfectMC: Mine¢raft textures for MineClone!
Fork of the mc-textures pack by EliasFleckenstein.
Everything not specially credited belongs to (C) Mojang, I don't own **any** of these.
**! ONLY FOR PERSONAL USE !**

Also, big thanks to [https://github.com/shmoobalizer](shmoobalizer) for creating the [https://www.planetminecraft.com/texture-pack/developer-art-plus/](Developer Art+ texture pack), i've used assets from it to add newer textures (from MCL5) in the classic pre-1.14 style.

## Screenshots
![Screenshot 1](https://i.ibb.co/RyXhP0F/screenshot-20220227-190230.png "Forest")
![Screenshot 2](https://i.ibb.co/rdTQs8b/screenshot-20220227-190309.png "Cave (and creative hud)")
![Screenshot 3](https://i.ibb.co/yykx6Qs/screenshot-20220227-190441.png "Nether (and survival hud with mine¢raft font)")

## How to install
**On linux (and on Windows with Git-for-Windows):** you can clone this repo (``git clone https://git.minetest.land/rudzik8/PerfectMC.git``) in your Minetest texture packs dir (``MINETESTDIR/textures/``) and ``git pull`` it sometimes to get new updates.
**On Windows (and for lazier users):** First-of-all, click there and download: 

![There](https://i.ibb.co/ZmmpqYM/screenshooooooooooot.png "right on the top of this page, yep")

And next just unzip the texture pack to your Minetest texture packs dir (``MINETESTDIR\textures\``)

**Enabling in the game**:
If you choosed
1. Open Minetest
2. Choose "Content" tab in the Main Menu
3. Find a green text in the list that says "PerfectMC" and double-click it
4. Ta-daa! PerfectMC texture pack has been succesfully enabled!

## Changes from the mc-textures
- Fixed the fire flame animated texture (scaled it to the default MCL size and copied for the HUD/Entities)
- Fixed the flowing water/lava texture (moved the second vertical tileset to the bottom so Minetest renders it normally, not as 32x)
- Fixed the experience bar texture (just renamed it lol)
- Added support for some (but not all currently) mods from MineClone 5 (and for [https://git.minetest.land/rudzik8/mcl_emerald_stuff](one my mod))
- Added spawn egg textures for every mob (...not sure about the ``extra_mobs``)
- Made banners look by using 3D inventory texture (just like in Mine¢raft)
- Made beds look more mc-alike (currently not all bed colors done but i'm working on it)
- Made crosshair (both normal and object) use more visible texture (just more wide default crosshair with black outline, so it's visible when looking on white stuff)

**↑** *object crosshair is just normal with a small plus below*
- Fixed redstone stuff (repeaters, comparators, levers...)
- Fixed some textures for ``mcl_armor`` (like 2D previews, inv textures, just textures and etc BUT not everything)
- **And more!**
