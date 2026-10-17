# Excluded components

Redux 1.0 excludes **69 active upstream IDs** and the already-deprecated #3470: **70 removed declarations** in total. #260 and #3440 were already disabled upstream. The remaining installer has **372 active IDs** and 17 deprecated entries.

This is a conservative selection covering continuous-listener overhead, area-reset interactions, reported bugs, and selected compatibility risks. Exclusion does not mean that every option has an independently confirmed performance defect.

| ID | Component |
|---|---|
| 50 | Avatar Morphing Script |
| 1050 | Gradual Drow Item Disintegration |
| 2100 | Allow Thieving and Stealth in Heavy Armor per PnP |
| 2160 | Alter Weapon Proficiency System → Rebalanced weapon proficiencies |
| 2161 | Alter Weapon Proficiency System → BG-style weapon proficiencies, with weapon styles [the bigg] |
| 2162 | Alter Weapon Proficiency System → BG-style weapon proficiencies, without weapon styles [the bigg] |
| 2163 | Alter Weapon Proficiency System → IWD-style proficiencies with weapon styles |
| 2164 | Alter Weapon Proficiency System → IWD-style proficiencies without weapon styles |
| 2450 | Enforce PnP Proficiency Rules on Dual-Classed Characters [subtledoctor] |
| 2620 | Make Certain Creatures Immune to Backstab/Sneak Attack [Luke] |
| 2630 | Improved Cure/Cause Wounds [Luke] |
| 2650 | Make Grease ignitable [Luke] |
| 2660 | Make Bears and Boars Continue Fighting after Reaching 0 Hit Points [Luke] |
| 2680 | Make Infravision Useful [Luke] |
| 2690 | Alternate Concentration Check [Luke] → v1 (check readme) |
| 2691 | Alternate Concentration Check [Luke] → v2 (check readme) |
| 2692 | Alternate Concentration Check [Luke] → v3 (check readme) |
| 2693 | Alternate Concentration Check [Luke] → v4 (check readme) |
| 2700 | Revised Troll Regeneration [Luke] |
| 2710 | NWN-Style Summons [Luke] |
| 2750 | Force the AI to cast AoE spells on the ground [Luke] |
| 2760 | Disable stealing at fences [Luke] |
| 2770 | Standardize buying/selling markups for all stores [Luke] |
| 3183 | Romance Cheats [Sabre, Richardson, Weimer] |
| 3420 | More Sensible Cowled Wizards [Luke] |
| 3430 | More Stoneskin Feedback [Luke] |
| 3450 | More Sensible Fireshield [Luke] |
| 3460 | More Sensible Blade Barrier [Luke] |
| 3470 | Dynamic FPS Change [Luke] |
| 3480 | More Sensible Morentherene [Luke] |
| 3520 | "Bank" XP when dualing a character [Luke (EEex)] |
| 4160 | Allow Yeslick to Use Axes |
| 4200 | Make Rancor +1 a Bit More Reliable |
| 4240 | Make sure you are getting back what Yoshimo has "taken" from you [Luke (EEex)] |
| 6000 | Disarm Class Feat for Rogues [Luke] |
| 6010 | Knockdown Class Feat for Fighters and Monks [Luke] |
| 6020 | Spellcaster Skill/Counterspell Class Talent [Luke] |
| 6030 | Spontaneous Casting for Clerics [Luke] |
| 6040 | Weapon Finesse Class Feat for Thieves [Luke] |
| 6050 | Dual-Wield Class Feat for Rangers [Luke] |
| 6060 | NWN-Style Armor vs. Dexterity [Luke] |
| 6070 | Defensive Roll Class Feat for Thieves [Luke] |
| 6080 | Divine Grace/Dark Blessing Feat for Paladins/Blackguards [Luke] |
| 6090 | Good Aim Racial Feat for Halflings [Luke] |
| 6100 | Cleave Class Feat for Fighters and Monks [Luke] |
| 6110 | Sneak Attack Class Feat for Blackguards [Luke] |
| 6120 | Fearless Racial Feat for Halflings [Luke] |
| 6130 | Poison Save Class Feat for Assassins [Luke] |
| 6140 | Planar Turning Class Feat for Clerics/Paladins [Luke] |
| 6150 | Circle Kick Class Feat for Monks [Luke] |
| 6160 | NWN-style Barbarian Rage [Luke] |
| 6170 | "Force" the Archer Kit to Use Bows [Luke] |
| 6180 | Blind Fight Innate Feat for Berserkers [Luke] |
| 6190 | Dirty Fighting Class Feat for Chaotic-Aligned Rogues [Luke] |
| 6200 | Overwhelming/Devastating Critical Class Feat for Trueclass Fighters [Luke] |
| 6210 | Self Concealment Class Feat for Monks [Luke] |
| 6220 | Parry Mode Kit Feat for Blades and Swashbucklers [Luke] |
| 6230 | Armored Caster Class Feat for Bards [Luke] |
| 6240 | Trackless Step Class Feat for Rangers [Luke] |
| 6250 | Nature Sense Class Feat for Druids [Luke] |
| 6260 | Uncanny Dodge Class Feat for Barbarians and Rogues [Luke] |
| 6270 | NWN-style Sneak Attack/Crippling Strike Class Feat for Thieves and Stalkers [Luke] |
| 6280 | Evasion Class Feat for Monks and Rogues [Luke] |
| 6290 | Spell Penetration Class Feat for Spellcasters [Luke] |
| 6300 | Smite Evil/Good Class Feat for Paladins/Blackguards [Luke] |
| 6310 | Woodland Stride Class Feat for Druids [Luke] |
| 6320 | Bane of Enemies Class Feat for Rangers [Luke] |
| 6330 | Cantrips Class Feat for Spellcasters [Luke] |
| 6340 | Animal Companion Class Feat for Beastmasters [Luke] |
| 6350 | Opportunist Class Feat for Chaotic-Aligned Rogues [Luke] |

The additional removals in Redux 1.0 are **2100, 2160–2164, 2450, 2630, and 2690–2693**. Their implementations and dedicated supporting files are deleted. #4160 and its dedicated Lua/translations are also absent. Some earlier exclusions retain unused source assets, but have no installer entry.

Intentionally retained: **3040** (bottomless bags), **3280** (four weapon slots), and **3410 / 3411 / 3412** (alternative Explicit Cast Warnings options).
