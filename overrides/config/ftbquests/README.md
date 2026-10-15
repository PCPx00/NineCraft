# Nine Craft Quest Book

An original quest book written for the Nine Craft modpack: 43 chapters and about 1,650 quests, organized the way a big kitchen-sink pack's book usually is (start here, basics, resources, tech, Modern Industrialization, storage, magic, adventure).

## Install
1. In your instance folder, delete the old `config/ftbquests/quests` folder.
2. Delete the old `kubejs/assets/ninecraft` folder if it's there (it held the recolored ATM10 images, which this book no longer uses).
3. Copy `config/` and `kubejs/` from this zip into the instance folder.
4. On a server, copy `config/ftbquests/quests` to the server as well.

## What's inside
- Every mod chapter runs from start to finish: beginner quests explain the basics step by step, the middle walks you through the main machines, and the last quest in each chapter is a big "Mastered" milestone for the mod's endgame.
- Every quest ends with a yellow **How to complete:** paragraph that says exactly what to find, craft, kill or visit, with the real item names and amounts.
- Every chapter is split into **tiers**: rows stacked top to bottom, each with a pixel label (for example Mystical Agriculture goes Inferium, Prudentium, Tertium, Imperium, Supremium, Insanium). Arrows only run inside a row, so nothing crosses over. The chapter's final milestone sits on the right.
- Full chapters for Nine Craft's own mods by xTri6: **Grim Soul Industries** (Resources and Farming group), **Grim Pipe Industries** and **Grim Storage Industries** (Storage and Logistics group), with links to them from other chapters.
- Every quest, description, chapter tree and piece of art is new. Nothing is copied from ATM10's quest text, layouts or images.
- Chapter title art uses a blocky purple pixel style based on the 9MM banner. The welcome chapter shows the banner itself.
- Rewards:
  - Things you find, mine, farm, loot or kill, plus info checkmarks, give XP levels.
  - Things you craft give one random roll from a Nine Craft loot table: Common, Uncommon, Rare or Epic. The further into a chapter (and the bigger the milestone), the better the table.
  - About 110 quests also hand you materials for the next step (planks after logs, coal after cobblestone, a stack of redstone before Mekanism, and so on).
  - Edit the loot tables in-game from the quest book's reward table screen, or in `config/ftbquests/quests/reward_tables/`.
- Each chapter has a hidden Nine Craft notice quest that only shows up in edit mode.

## Editing
Open the quest book, turn on edit mode (the pencil button) and change anything you like. You may want to adjust quest positions: the trees are laid out automatically, left to right.

## Notes
- Some item names in tasks may differ if a mod renames an item in a future update. If a task shows a missing item, edit the quest and pick the right one.
- Chapters for RFTools, XNet and Silent's Gems aren't included yet.
