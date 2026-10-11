# Skirmish & Global Conquest Remaster

This repository hosts files and code related to remastering the **Skirmish AI** and 
**Global Conquest** for **Command & Conquer 3 Kane's Wrath**.  

The goal is to improve AI behaviors over the base game, 
give AI actions more purpose and to assist players in identifying and learning vital
points of their base as well as their opponent's as well as encourage micro and macro management
under a more difficult experience. This AI Remaster is intended to be developed and distributed
alongside Masterleaf's 4K Mod and 1.02+ Community Patch.

---

## 📖 About

- **Skirmish AI**: Updated logic for more purposeful matches, improved consistency and scaling
 as well as to teach and prepare casual players for the pressures they will experience in PvP.  

- **Global Conquest**: Adjustments to create smarter and more immersive single-player experiences, 
various fixes and improved consistency.  

This project is community-driven and intended for research, education, and non-commercial modding.

**Note**: Not all of the required files for compilation are present in this repository and must 
be added by the user in order to have it be compiled.

---

## :memo: Change Log 

## Release (R25j):

## Campaign

- Fully adapted/fixed campaign maps will follow (with map specific fixes).
- Revamp entire General AI behaviour from scratch with compatibility for 1.02+.
- Fix and improve incomplete/incorrect Attack states (Proactive, Reactive & Context Specific).
- Scale Easy, Medium & Hard to a more suitable consistency.

## Skirmish

- Recreated Skirmish AI logic from scratch to comply with 1.01/1.02/1.02+ economy changes.
- Improved Personality types with distinct behaviours for each.
- Medium & Hard now have proper scaling in difficulty in relation to Easy and Brutal.
- Brutal retains base game 200% resoure modifier.
- Fixed incorrect unit listings, target types for prioritized targets (Engineers, Commandos, Bridges, Husks, Garrisons) for sub factions.
- Improved Budget management definitions.
- Fixed an issue where the AI would crash the game if it made Steel Talons Heavy Harvesters.
- Fixed an issue where reload/dock based aircraft would formation move for some states instead of moving at native speed.
- Fixed cases whereby Opening Moves would request to build units that are not available at certain tech levels
- Fixed cases whereby certain subfactions would request to build unit(s) in their Opening Moves and Unit Preferences that they do not have access to or do not exist/were cut from the game during development.
- Unit Preferences have been redesigned to be dynamic depending on specific battlefield/match conditions.
- Improved reactivity based on personality type and match conditions.
- AI now garrisons Epic units if idle/free infantry are available.
- AI will make more frequent use of Support Powers.

---

## ⚖️ License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.  
See the [LICENSE](https://github.com/Solar-Messenger/RemasteredAI/tree/master?tab=GPL-3.0-1-ov-file) file for details.

### Important Notes
- The **original modding support** was released by **Electronic Arts (EA)** under **GPLv3**.  
- All rights, trademarks, and assets related to the original game remain the property of **Electronic Arts**.  
- This repository does **not** distribute original game assets. To use this project, you must legally own a copy of the game.