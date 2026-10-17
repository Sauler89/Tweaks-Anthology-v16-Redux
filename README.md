# Tweaks Anthology v16 Redux

**An unofficial revision based on Tweaks Anthology v18, with selected problematic components removed and targeted compatibility fixes.** “v16 Redux” is the project name; the code base is v18, with upstream fixes through `7649ced`.

## Install

Download the [1.0 release](https://github.com/Sauler89/Tweaks-Anthology-v16-Redux/releases/tag/v1.0). Extract both the **Tweaks Anthology v16 Redux** folder and **setup-Tweaks Anthology v16 Redux.exe** into the game directory, next to `chitin.key`, then run the setup. The WeiDU executable is included only in the release ZIP; the repository contains the mod sources.

Uninstall the original Anthology, Custom Lite, or an earlier Redux package with its original installer before replacing it. Mods that detect the original installer filename may need compatibility updates.

## Redux 1.0

- **372 active installer options.** See the [excluded component list](Tweaks%20Anthology%20v16%20Redux/EXCLUSIONS.md).
- Preserves SCS's Nalia levelling data, including changed NPC script names; fixes party movement controllers and Grey's SoD coverage.
- Makes #3122's neutral reputation comments take precedence over #3125.
- Enables the existing EE dual-class proficiency workaround and handles extra kit columns correctly. Single-class clerics/druids can also assign one pip to the added proficiencies; their weapon restrictions remain.
- Corrects Coran's early Cloakwood quest timer and the EEex Ctrl shortcut for four weapon slots.
- Bottomless bags, four weapon slots and Explicit Cast Warnings remain available; some options require EEex.

The previous compatibility fixes and exclusions are retained. The release ZIP contains the mod folder and the supplied WeiDU setup side by side. No test folder is distributed. The 17 October audit checked all 372 installer options, ten languages, and 74 synthetic regression scenarios, including reinstall/uninstall. No in-game playthrough or performance benchmark was performed.

## Credits

Original components by **CamDawg and The Tweaks Anthology authors and contributors**. Redux selection and additional fixes maintained by **Sauler89**.

[Original project](https://github.com/Gibberlings3/Tweaks-Anthology) · [Original component documentation](https://gibberlings3.github.io/Documentation/readmes/readme-cdtweaks.html)
