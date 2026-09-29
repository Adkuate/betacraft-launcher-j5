# BetaCraft Launcher

BetaCraft launcher aims to provide easy access to old Minecraft versions and improve the overall game experience. This
fork of 1.09_16 is for adding Java 5 support to the launcher.

For now, Discord RPC has been removed due to its compilation version (being locked at Java 8).

## Features

- Supports versions from Pre-Classic to 1.5.2:
    - skins & sound in versions that can handle them
    - starting Indev and early Infdev versions
    - mouse fix for Classic, Indev-Infdev versions on macOS
    - a1.1.1 gray screen fix
    - AMD clouds fix
    - fix for crash on `Mojang` screen before r1.3
    - multiplayer online-mode handling for pre-b1.8 versions
    - joining custom servers with the c0.0.15a version
    - resize game easily in versions that don't support resizing
    - can play every currently available legacy Minecraft version
- Microsoft/Mojang sign in
- Mod repository, featuring great community mods
- Server list:
    - servers with live playercount and description
    - join servers by clicking on them
    - automatically downloads the mod a server uses if it's in mod repository
- Addons:
    - OfflineDATSave - allows for saving Classic levels on your disk (currently the only way to save in Classic)
    - Fullscreen - enables fullscreen mode for versions that don't officially have support for it
    - Demo - triggers demo mode for versions 12w16a and later
    - UnlicensedCopy - triggers `Unlicensed Copy :(` label for versions b1.6-tb3 to b1.7.3
    - QuitGame - shows the `Quit Game` button in versions b1.0 to 1.5.2
    - GameModeSwitch - switches to the opposite gamemode in versions c0.28_01 to inf-20100630-1835
    - ClassicNotPaid - displays `Premium only!` message when trying to save in any revision of c0.30
- Discord RPC
- Configurable:
    - JVM arguments
    - path to Java
    - instance directory
    - instance icon
    - starting resolution
- Console output

### Additional features

- BetaEvolutions support
- Launcher language options

## Supported platforms

- Windows 7 and later (32 bit); Windows 11 (64 bit)
- Any up-to-date Linux distro (32/64 bit)
- macOS 10.8 (Mountain Lion) and later

### Note

- Silicon Macs have inverted blue/red colors, for now you can only bypass this by going fullscreen
- Earlier versions of Windows (like Windows XP) may work, so long as the Java they run on can handle TLSv1.3 for
  official Microsoft/Mojang links. There's no guarantee that the launcher will work in full. Earliest Java updates to
  support TLSv1.3 are **8u181**, **7u191** and **6u201**
- Earlier versions of macOS 10.8 (Mountain Lion) are not tested yet. They were distributed with their own
  versions of Java, in order: **Java 5** (macOS 10.4 and 10.5), **Java 6** (macOS 10.6), **Java 7** (macOS 10.7)

## Reporting bugs or requesting features

Report bugs in [issues](https://github.com/Moresteck/BetaCraft-Launcher-Java/issues) or on our Discord server below.

## Contact:

- Discord: https://discord.gg/d4WvXeQ
- BlueSky: [@betacraft.uk](https://bsky.app/profile/betacraft.uk)
- Website: https://betacraft.ee - account option is only there if you wish to have your modern versions skin separate
  from legacy versions, there's no other additional functionality.
