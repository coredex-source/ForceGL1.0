# ForceGL1.0
- A Minecraft mod for [Fabric](https://fabricmc.net/), [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/), [Quilt](https://quiltmc.org/) & [NeoForge](https://neoforged.net) that forces the game to use OpenGL 1.0.
- You can download it using [CurseForge](https://www.curseforge.com/minecraft/mc-mods/forcegl2-0-remapped), [Modrinth](https://modrinth.com/mod/forcegl2.0-remapped).

## This version of the mod is only available for fabric rn, you can request for another mod loader in the issues section.

## Fixes-
- Fixes game not launching due to GL errors on EXTREMELY OLD GPUs.

## Why?
- Users with extremely old GPUs who could probably never play the game .. can now play the latest version!
- This Minecraft mod makes the game work again for those players by reverting the OpenGL GLFW hints to how it was in idk probably the first version of Minecraft.

## But does it work?
- As far as I tested, there have been no issues. However, you must remember that this mod forces the game to run on an unsupported OpenGL version. There may be unexpected issues with other mods or resource packs.  
- **While it is fine to use this mod to run newer versions of Minecraft, please do consider upgrading to a newer graphic card as soon as possible.**

## I found an issue!
- I don't have a system old enough to test an OpenGL1 backport on. So, support will depend on if I can find the bug in the code.
- And for a fact, I know that this mod can be a disastrous mess.

## Compiling the mod
- If you want to compile ForceGL20 by yourself, use the following command:
```
./gradle build  
```
- Use the build from {LoaderType}/build/libs.

## Orignal mod
- Orignal mod by KabanFriends - [Github](https://github.com/KabanFriends/ForceGL20) [Modrinth](https://modrinth.com/mod/forcegl20)
