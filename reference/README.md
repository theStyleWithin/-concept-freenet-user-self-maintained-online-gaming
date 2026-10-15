# Reference projects (do not edit)

These folders are git submodules: links to other people's projects, pinned to a
fixed version. They are here to read and learn from, not to modify. Our own
code goes elsewhere in this repo.

| Folder | Project | License | Why it's here |
|---|---|---|---|
| `RetroArch/` | [libretro/RetroArch](https://github.com/libretro/RetroArch) | GPLv3 | Netplay code we build freenet-play on (`network/netplay/`) |
| `emufii/` | [theStyleWithin/emufii](https://github.com/theStyleWithin/emufii) | AGPL-3.0 | Design guide only, not used directly |
| `freenet-core/` | [freenet/freenet-core](https://github.com/freenet/freenet-core) | see repo | The Freenet node and app examples |
| `freenet-stdlib/` | [freenet/freenet-stdlib](https://github.com/freenet/freenet-stdlib) | see repo | Toolkit for writing Freenet contracts |

To download them after cloning this repo:

```
git submodule update --init --depth 1
```
