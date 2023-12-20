# Installing text mod

> [!CAUTION]
> CS2 has disabled text mods on 14 December, 2023. This no longer works.

1. [Click this link to download the file](https://raw.githubusercontent.com/xPaw/CS2/main/csgo_textmod.txt) (Press <kbd>Ctrl+S</kbd>)
2. Save this file as `csgo_textmod.txt` and put it inside this folder: `Steam\SteamApps\Common\Counter-Strike Global Offensive\game\csgo\resource`
3. Add `-language textmod` to your launch options

### Not working? Make sure that:
- `csgo_textmod.txt` is placed in the right folder (it needs to be inside the CS2 `game\csgo\resource` folder)
- Launch option is spelled correctly, this is an example that will work: `-novid -language textmod`

To enable letters inside of a circle for teammate colors, use `cl_teammate_colors_show 2`

This was based on bananagaming text mod, but I have been modifying it over the years for CS:GO.

----

# Installing practice config

1. [Click this link to download the file](https://raw.githubusercontent.com/xPaw/CS2/main/cs2practice.cfg) (Press <kbd>Ctrl+S</kbd>)
2. Save this file as `practice.cfg` and put it inside this folder: `Steam\SteamApps\Common\Counter-Strike Global Offensive\game\csgo\cfg`
3. Load a map locally
4. `exec practice` in console
