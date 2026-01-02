# TripleBondChallenge
A difficult challenge that brings a roguelike experience in Pokemon HeartGold with a focus of using 3 Pokemon as a squad. Very accessible for even new players and filled with tons of QOL features!

<img width="649" height="452" alt="image" src="https://github.com/user-attachments/assets/a1bb16a9-cb59-4a81-b0ef-3a7089bc19c2" />


Please join the Discord for updates/feedback/help: [https://discord.gg/mg3G3VqVbf](https://discord.gg/mg3G3VqVbf)

**Challenge developed by [Arex](https://twitch.tv/Arex)**

Special thanks to the following: Kalaay and Yako for helping with changing hardcoded stuff including the EXP split. Fantafaust for HM QOL integration. AdAstra and Mixone for DSPRE and tools. PyroMike for the initial Intro Patch this was built on. All the wonderful helpful people from Kingdom of DS Hacking. OnlySpaghettiCode, UTDZac, and Mixone for helping make the NDS tracker compatible with the challenge. Everyone from the Discord that helped test the early versions including Orin for playing an insane amount which really helped with data.

## **Core Rules**

### Party Rules
- You may only ever have **three Pokemon** in your party if you're going to battle.
- Once you beat Falkner, you're locked in on your 3 Pokemon in your party.
  - The only time you can replace a Pokemon is after you beat gym 4. See Bug Catching Scout Reward.

### Permadeath
- If **any one** of your 3 mons faints at any time, their bond is broken and you must reset by starting a new seed.

### Victory Conditions
- **Win:** Defeat the mysterious trainer after Lance.
  - You do not go to Kanto in this challenge.
- **Lose:** If **any one** of your 3 dies, reset.
  - Exception is Bug Catching

### Controls
- **Select Button**: While in/out of battle you can cycle between your party members to see information.

- **L Button**: Toggle EVs window to see the current EVs on your Pokemon.

- **Start Button**: Only while in battle you can cycle between the enemy mon information and your active mon.

- **R Button**: You can Fast Travel to anywhere you've been after you beat the 1st Rival fight.

### Starter Mon
- You must pick a ball before you look at the mons. That is your starter.

### Trainer & Game Rules
- If there isn't a rule listed on this page, you're allowed to do it. **This applies to almost everything.**
- **No healing outside of battle** except for using the Pokemon Center.
- You are only allowed to fight trainers for EXP.
- No shopping except for evo items from GoldenRod City.
- Once you enter a building, cave, gym, if you start fighting a trainer, you cannot leave to go to heal and come back to fight more trainers. You may, however, re-enter the area to pass through.
  - Exception (Radio Tower): When you leave Radio Tower to go to the basement segment, you may heal. When you leave the basement to go back to the tower, you may heal again.
- You must beat all trainers in a gym before fighting the Gym Leader.

### Catching Rules
- You are only allowed to catch 1 mon from each area/cave/hall.
  - You are NOT allowed to scout/fight these mons. You can only catch them.
- You are not allowed to use Headbutt to get more mons.

### Pokemon Restrictions
- No dupes of the same Pokemon.
  - If a Pokemon happens to evolve into the same mon as another in your party. it's fine.

### Move Restrictions
- Banned moves: Switcheroo, Aqua Ring, Leech Seed, Rest, Spore, and Pain Split.
  - They're not taken out of the randomization so that the enemy can still use them.
- You can only use healing moves once per Pokemon per battle.
  - If you're in a building, cave, gym, you can only use the move once per Pokemon.

### Setup Moves/Items restrictions
- Any pure setup move (that does not deal damage) can only be used once per Pokemon per battle.
  - If your mon has Simple, 2 stage setup moves are banned.
- Additionally, Battle Items are treated as Setup Moves. However, only 1 can be used per Pokemon.

### TMs/HMs usage
- TMs will not disappear after use due to a bug. You cannot keep using that TM. Please keep track. I will try to fix this eventually.

### NPC Rewards
- Outside of gym leaders and required progression NPCs, you are not allowed to use any extra items/TMs you get.
- Not allowed to use extra move learning NPCs outside of Bug Catching and Move Relearner in Blackthorne.
- This subset of rules will be updated after a new patch.

### Bug Catching Scout Reward
- After you beat Gym 4, you are now allowed to replace 1 mon from your team via the Bug Catching area in National Park.
  - You are allowed to scout these Pokemon freely.
  - You can only catch 3 Pokemon to look at and decide on **only one**.
- If any of your Pokemon dies from scouting, you are no longer allowed to catch the mon that killed your mon. You do not reset.
  - Same rule applies if you kill the mon you're trying to scout.
- You are allowed to increase the level of a mon that can evolve before making your decision for Bug Catching.

### Rock Smash
- You are only allowed to Rock Smash each rock that you find once.

### Lake Rage Shiny
- You may catch this to use if you like but you must give up one of your mons immediately after you catch it.

### Information
- If you're new to Triple Bond, talk to Oak. He'll give you important information.
<img width="104" height="97" alt="image" src="https://github.com/user-attachments/assets/22fcb0db-b315-4546-a083-1110560ff632" />

- If you're new to Pokemon Heart Gold challenges, look out for Celebi in the intro areas. It's guiding you were to go.
<img width="65" height="77" alt="image" src="https://github.com/user-attachments/assets/2cd42293-88c5-4495-9c43-ebd3542e9c83" />

- If you're new to Pokemon Heart Gold IN GENERAL, please look at this map. It shows lots of information including hidden items.
[https://kelseyyoung.github.io/HGSSIronmonMap/](https://kelseyyoung.github.io/HGSSIronmonMap/)

- And then here is a general guide to follow on where to go to progress through HeartGold for the Main Storyline.
[https://bulbapedia.bulbagarden.net/wiki/Walkthrough:Pok%C3%A9mon_HeartGold_and_SoulSilver](https://bulbapedia.bulbagarden.net/wiki/Walkthrough:Pok%C3%A9mon_HeartGold_and_SoulSilver)

### Red's Fight
- Before you talk to Red you must **make sure you are NOT in Diamond Dust**.
- Diamond Dust looks like this (slower with smaller flakes):
<img width="668" height="511" alt="image" src="https://github.com/user-attachments/assets/d6913cf8-1395-4e6c-a192-a2791dffd7b9" />

- **You want this type of snowstorm (faster and ball-like):**
<img width="657" height="494" alt="image" src="https://github.com/user-attachments/assets/b5a9f885-0bae-457a-bbd4-e2b8def643ec" />

- If you have Diamond Dust then please refer to the Required Emulator Settings below.

---
## Extra Information (not rules)
### QOL Updates and Features
- Changed the intro so that everything is done as soon you leave the lab. The 1st 3 routes with Pokemon are all connected by halls. Starting up a run is quick.
- Static encounters instead of wild encounters for ease of use.
- You can now catch up to 4 mons (from 11 mons available) before the rival.
- You will ALWAYS run away from battle. No longer need Smoke Ball.
- Fast Travel (Fly) with pressing the R button. This is unlocked from the beginning of the game but don't start using until you beat the rival.
- Tracker changes so that you can cycle through your party of mons really easily with pressing Select.
- EXP is **evenly distributed** among all three Pokemon (via patch).
  - It doesn't matter if they participated in the battle or not.
- The game is set to Switch mode BUT you cannot see what the enemy will use. This is on purpose by design for the challenge.
- Added HMs to the randomized move pool.
- No longer need an HM friend.
- Removed moves and abilities to better adjust for challenge.
- Some moves have been modified to fit the challenge. Mainly weak moves have been buffed, drain moves changed, and other changes.
- Move Releaner NPC at the Bug Catching Contest
- Move Tutor for Spite at the Bug Catching Contest

### Randomizer Settings
- Moves, abilities, evolutions (same typing), stats, etc are all randomized.
- Trainer Pokemon levels are increased by 30%.
- Forced evos for enemy mons at level 30.
- Gym leaders, bosses, and Elite Four trainers have held items.

### Favorites
- There's no need to do Favorites like seen in other challenges but feel free to do it if you want.

### Documenation
- I'll eventually get to this sorry.

---
## Setup
Information for setting up to run the challenge. 

Please note: **If there's ever an update of the rom patch that requires you to update the randomizer/tracker it will say so with an additional text file named with UPDATE YOUR RANDOMIZER/TRACKER**

### How to patch your game for Triple Bond Challenge
Video Tutorial for patching rom: [https://youtu.be/N_i5NUixlV0](https://youtu.be/N_i5NUixlV0) 


Download the [patch](https://github.com/arexbold/TripleBondChallenge/releases) and apply it to a vanilla USA HeartGold rom with the Rom Patcher: [https://www.marcrobledo.com/RomPatcher.js/](https://www.marcrobledo.com/RomPatcher.js/)

### Required Emulator
Please use Bizhawk for this challenge: [https://github.com/TASEmulators/BizHawk/releases/tag/2.10](https://github.com/TASEmulators/BizHawk/releases/tag/2.10)

Version 2.11 JUST came out and this challenge patch and the tracker have not been tested with it yet so v 2.10 is linked above.

### Required Emulator Settings
Initial Time and Use Real Time settings should be exactly like the images below. **Do not manipulate time to get extra items/battles.**

Bizhawk > NDS > Settings 

<img width="343" height="414" alt="image" src="https://github.com/user-attachments/assets/c0b375e9-80ba-4278-851a-6b539c11fe96" />


### Required Tracker and Randomizer
It is required that you use the custom tracker and randomizer for this challenge.

Tracker and Randomizer: [https://github.com/arexbold/TripleBondTracker/releases](https://github.com/arexbold/TripleBondTracker/releases)
Video Tutorial for tracker setup: [https://youtu.be/JEbL4Elem0o](https://youtu.be/JEbL4Elem0o)

### Helpful map
If you don't have HeartGold memorized then it's required you use this map otherwise you will miss so much. The only thing that's wrong are the levels on the trainers. Everything else is accurate.
[https://kelseyyoung.github.io/HGSSIronmonMap/](https://kelseyyoung.github.io/HGSSIronmonMap/)

### Folder Structure
Here's an example of what files to have in your Triple Bond Tracker folder (minus Bizhawk which can be elsewhere)
<img width="869" height="261" alt="image" src="https://github.com/user-attachments/assets/f80172f2-d314-41f2-a766-ac9166d28442" />



## Known Bugs
- TMs will not disappear after use. Please sell them after you use it.
