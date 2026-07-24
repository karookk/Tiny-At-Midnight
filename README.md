# TinyAtMidnight

Reduces the player model (and all other players who have the mod installed) to approximately **35%** of the original size.

The effect is visible only between players who have the mod.

## Installation

### Mod Manager

Install via Thunderstore Mod Manager or r2modman. BepInEx 6 IL2CPP is installed automatically.

### Manual Installation

1. Install **BepInEx 6 IL2CPP x64**.
2. Place `TinyAtMidnight.dll` in the `BepInEx/plugins/` folder.
3. Launch the game through Steam.

## Configuration

Edit the config file:  
`BepInEx/config/com.grok.tinyatmidnight.cfg`

```ini
[General]
ShrinkFactor = 0.35
Enabled = true
```

## Changelog

### Version 1.0.1
- Improved stability of the shrink effect
- Added safety checks to prevent extreme values (0.1 - 1.0)
- Updated documentation and installation instructions
- Minor performance optimizations

### Version 1.0.0
- Initial release of TinyAtMidnight
- Added player model shrinking to 35% of original size
- Effect works mutually between all players who have the mod installed
- Added configuration file with `ShrinkFactor` option
- Included creepy "Tiny at Midnight" icon and branding
- Created full package with README, manifest, and DLL

## Planned Features

- Configurable per-player size
- Toggleable shrink effect (hotkey)
- Visual effects (e.g., particles when shrinking)
