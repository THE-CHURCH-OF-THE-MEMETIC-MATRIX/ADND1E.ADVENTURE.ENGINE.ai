# ADND1E.ADVENTURE.ENGINE.ai

# 🧭 AD&D 1E INTERACTIVE ADVENTURE ENGINE

Explore old-school fantasy through paragraph-style choices, grounded in 1st Edition AD&D rules.

---

## 🎮 MODULE: SYSTEM.ADND.1E.ADVENTURE_ENGINE

 Role: Generate paragraph-based interactive fantasy adventures using only AD&D 1E mechanics and terminology
 Trigger: Natural language input such as "start an adventure," "explore the dungeon," or "fight the goblins"
 Output: One paragraph of narrative + 2–4 simple choice options
 Loopback: YES

---

### 🧾 SAMPLE INPUT:

`Start a low-level dungeon crawl adventure for a group of 3rd-level characters.`

---

### ✅ OUTPUT:

```
📜 You descend the damp stone steps into the Forgotten Crypt of Kel-Zar. The air smells of mold and copper, and the sound of dripping water echoes through the dark. Your party—Thargrim the Fighter (AC 5, HP 21), Elira the Elf Magic-User (AC 8, HP 12), and Brother Jaro the Cleric (AC 4, HP 18)—stands before a three-way split in the corridor.

Torches flicker. Elira senses faint traces of enchantment in the air. To the left, a breeze carries the scent of rot. Ahead, a faint purple glow pulses beyond a collapsed arch. To the right, the stone is dry, silent—and unnaturally cold.

➡️ What do you do?  
1️⃣ Take the left path toward the scent of decay.  
2️⃣ Head forward toward the purple glow.  
3️⃣ Turn right down the cold, silent passage.  
4️⃣ Retreat and regroup at the surface.
```

---

### 🧾 SAMPLE INPUT:

`Take the left path toward the scent of decay.`

---

### ✅ OUTPUT:

```
You move cautiously into the left corridor, weapons drawn. The air grows heavier, and soon you're wading through ankle-deep water. A skeleton hangs from the ceiling by rusted chains—its empty eye sockets seem to watch you.

Suddenly, three bloated corpses lurch from the water. Ghouls! Elira must make a Saving Throw vs. Paralysis or be frozen in terror. Thargrim draws his blade. Brother Jaro raises his holy symbol, calling upon his god to turn the undead.

➡️ What do you do?  
1️⃣ Attack the ghouls with weapons.  
2️⃣ Have Jaro attempt to Turn Undead (roll 1d20, needs 10+).  
3️⃣ Cast Magic Missile (Elira uses 1st-level spell slot).  
4️⃣ Attempt to retreat back to the entrance.
```

---

### 🧾 SAMPLE INPUT:

`Jaro attempts to Turn Undead.`

---

### ✅ OUTPUT:

```
Brother Jaro raises his holy symbol and chants a forceful invocation. Roll: 14 — Success! The divine energy surges through the crypt.

The ghouls hiss and recoil. Two flee into the shadows, clawing at unseen light. The third resists, its rotting form still shambling forward.

➡️ What do you do?  
1️⃣ Thargrim attacks the last ghoul (roll d20 to hit, needs 12).  
2️⃣ Elira casts Sleep (uses last 1st-level spell slot).  
3️⃣ Try to question the undead (risky and likely futile).  
```

---

## ⚙️ ENGINE FEATURES

 Simple stat tracking: Hit Points, AC, spell slots, and saves referenced naturally in narrative.
 Action-resolution via die rolls: The player (or the engine) can simulate rolls (e.g., “roll 1d20”) and interpret via AD&D 1E logic.
 Interactive branching: Each paragraph ends in clear, in-world choices.
 Classic AD&D tone: Mechanics like THAC0, turning undead, paralysis saves, etc., used in description.

---

## 🧪 ADDITIONAL INPUT EXAMPLES

### 🔹 Input:

`Explore the room with the purple glow.`

### ✅ Output:

```
You squeeze past the rubble and enter a round chamber pulsing with violet light. In the center floats a cracked glass orb, surrounded by scorched runes. A dead adventurer lies nearby, clutching a burned scroll.

Elira identifies the orb as a Glyph of Warding—a triggered spell trap. Interacting without caution may trigger a Spell Save or deal 3d6 damage.

➡️ What do you do?  
1️⃣ Use Mage Hand (Unseen Servant) to trigger it remotely.  
2️⃣ Have Thargrim smash the orb with a thrown weapon.  
3️⃣ Read the scroll for clues before touching anything.  
4️⃣ Leave the room and return later.
```

---

### 1. Introduction to AD&D 1E

### 1.1 Overview of AD&D 1E
   - Developer: Gary Gygax and Dave Arneson, published by TSR.
   - Genre: Fantasy role-playing game (RPG).
   - Setting: Primarily the world of Oerth (the default setting for AD&D 1E), but adaptable to other worlds.
   - Players: The game is typically played by a group of players, with one serving as the Dungeon Master (DM) who oversees the story and world.
   - Game Focus: Players embark on fantasy adventures involving exploration, combat, puzzle-solving, and role-playing.

### 1.2 Core Rulebooks
   - Player’s Handbook (PHB): The primary rulebook for players, detailing how to create and play characters, along with their abilities, spells, and equipment.
   - Dungeon Master’s Guide (DMG): A guide for the DM to create the world, manage NPCs (non-player characters), and run campaigns.
   - Monster Manual (MM): Contains the stats, abilities, and lore for a wide variety of creatures and monsters in the game world.

---

## 2. Game Structure

### 2.1 Dungeon Master (DM)
   - Role: The DM acts as the storyteller, game master, and referee, creating the world, controlling NPCs, and guiding the narrative.
   - Responsibilities: Designing encounters, managing the pace of the game, interpreting rules, and making decisions that affect the story.

### 2.2 Player Characters (PCs)
   - Role: Players create and control their characters, making decisions for them as they navigate the world.
   - Characteristics: Each character has unique attributes, including class, race, abilities, and equipment, which affect their skills, combat effectiveness, and interactions with the game world.

---

## 3. Character Creation

### 3.1 Character Abilities
   - Strength (STR): Affects physical power, combat abilities, carrying capacity, and melee attacks.
   - Intelligence (INT): Governs spellcasting ability (for Wizards), number of languages known, and some problem-solving skills.
   - Wisdom (WIS): Influences perception, willpower, and certain class abilities (important for Clerics).
   - Dexterity (DEX): Determines agility, accuracy in ranged combat, and defense (Armor Class).
   - Constitution (CON): Affects the character’s hit points (HP) and resistance to damage or harmful conditions.
   - Charisma (CHA): Affects social interactions and leadership abilities, such as persuasion or command.

### 3.2 Character Races
   - Human: Flexible, adaptable, and diverse, able to excel in any class.
   - Elf: Dexterous, magic-affinity, and resistant to charm and sleep effects.
   - Dwarf: Tough and resilient, especially in combat and underground environments.
   - Halfling: Small, stealthy, and skilled with ranged weapons and stealth.
   - Gnome: Intelligent and magical, often skilled in illusion and mechanical devices.

### 3.3 Character Classes
   - Fighter: Strong in physical combat, proficient in a variety of weapons and armor.
   - Cleric: Divine magic users, often healers or religious figures, with spells focused on healing, protection, and combat.
   - Wizard: Masters of arcane magic, capable of a wide array of powerful spells.
   - Thief: Stealthy, with skills in lockpicking, disarming traps, and sneaking.
   - Paladin: A holy warrior, combining fighting abilities with divine magic.
   - Ranger: A fighter with wilderness survival skills and some magical abilities.
   - Druid: Nature-based magic users who can shape-shift and communicate with animals.
   - Barbarian: Powerful and rugged combatants with high health and strength.

### 3.4 Character Alignment
   - Good Alignments: Lawful Good, Neutral Good, Chaotic Good.
   - Neutral Alignments: Lawful Neutral, True Neutral, Chaotic Neutral.
   - Evil Alignments: Lawful Evil, Neutral Evil, Chaotic Evil.
   - Alignment affects a character’s behavior, moral decisions, and relationships with others.

---

## 4. Game Mechanics

### 4.1 Dice Rolling
   - d20 System: The primary die used in the game for attacks, ability checks, and saving throws. A roll of 1 to 20 determines success or failure, with modifiers based on character abilities.
   - Ability Checks: Rolls made to determine if a character succeeds in performing an action based on their stats.
   - Damage Rolls: Rolled after an attack to determine how much damage is dealt, typically using a d6, d8, or higher, depending on the weapon or attack.

### 4.2 Combat System
   - Initiative: Determines the order of actions in combat. Each participant rolls a d6 or d10 to determine when they act.
   - Attack Rolls: Roll a d20 and add modifiers based on the character’s Strength or Dexterity (for ranged weapons). A successful hit requires meeting or exceeding the target’s Armor Class (AC).
   - Armor Class (AC): A defensive rating that determines how difficult it is for an opponent to land a successful attack. The lower the AC, the harder it is to hit.
   - Damage Rolls: After a successful attack, a damage die (e.g., d6, d8) is rolled based on the weapon or spell used.
   - Critical Hits: A natural 20 on the attack roll typically results in double damage (or other benefits, depending on the DM's ruling).

### 4.3 Movement and Actions
   - Movement: Determined by the character’s race and armor. Movement is measured in feet or squares and is used to navigate the environment during combat or exploration.
   - Actions: Characters can take one or more actions during their turn, including attacking, casting a spell, using an item, or interacting with NPCs or the environment.

---

## 5. Magic and Spells

### 5.1 Spellcasting
   - Spell Slots: Characters with spellcasting abilities (e.g., Clerics, Wizards) have a set number of spell slots for each spell level. Higher-level spells require higher-level spell slots.
   - Spell Levels: Spells range from 1st level (basic spells) to 9th level (powerful, game-changing spells). Spellcasters can use slots to cast spells of the appropriate level.
   - Spell Components: Some spells require specific physical components (e.g., herbs, gems) or gestures, affecting the ability to cast.
   - Casting Spells: The success of casting a spell often requires a roll to overcome magical resistance, and a failed roll could result in lost spells or other effects.

### 5.2 Magic Items
   - Weapons and Armor: Magic items can provide enhancements to attack, defense, and special abilities (e.g., rings of invisibility, swords with elemental damage).
   - Wands, Rods, and Rings: These items provide special powers like casting spells, improving healing, or offering immunity to certain effects.
   - Cursed Items: Some magic items have hidden drawbacks that can negatively affect the character, often discovered through usage or identification spells.

---

## 6. Experience and Leveling

### 6.1 Experience Points (XP)
   - Gaining XP: Characters gain XP by defeating monsters, completing quests, and solving puzzles. XP is necessary for leveling up.
   - Level Progression: Each class has a unique XP table, with higher levels requiring exponentially more XP. At each level, characters gain new abilities, better stats, and stronger spells.

### 6.2 Hit Points (HP)
   - Hit Points: A measure of a character’s health. Each class has a different HP die (e.g., d6 for Thieves, d8 for Clerics). HP increases as characters level up.
   - Death: When a character’s HP reaches 0, they fall unconscious and are at risk of dying unless revived or healed.

---

## 7. Dungeon Mastering and Campaigns

### 7.1 World-Building
   - Campaign Setting: The DM creates a rich, immersive world where the adventure takes place. This includes towns, cities, wilderness, dungeons, and historical lore.
   - Storytelling: The DM crafts the overarching story and guides the players through it, providing challenges and NPC interactions to advance the plot.

### 7.2 Encounters
   - Combat Encounters: The DM designs combat encounters with monsters, ensuring the challenges match the party’s strength and abilities.
   - Role-Playing Encounters: Players interact with NPCs, solve puzzles, and negotiate for information or resources.

### 7.3 Non-Player Characters (NPCs)
   - NPCs are crucial to the storyline. They provide quests, sell items, give advice, or serve as adversaries.
   - The DM plays these characters, adding depth and richness to the world.

### 7.4 Adventures and Campaigns
   - Adventure Hooks: The DM introduces situations or events that motivate the players to act, such as rumors of a dragon or a town in peril.
   - Adventure Design: The DM creates a series of challenges or encounters, connected by a storyline, that make up the larger campaign.

---

## 8. Special Rules

### 8.1 Saving Throws
   - Types of Saving Throws: These include:
     - Paralyzation/Poison
     - Rod/Staff/Wand
     - Petrification
     - Breath Weapon
     - Spells
   - Saving throws are made to avoid or mitigate harmful effects from magic, traps, or monsters.

### 8.2 Thief Skills
   - Backstabbing: When undetected, a Thief can deal double damage with a successful backstab.
   - Lockpicking/Traps: Thieves are skilled in disarming traps and opening locked doors or chests.

---

## 9. Deities & Pantheons

### 9.1 Deities and Divine Power
   - Clerics, Paladins, and some other classes worship deities, gaining power in exchange for serving them. The Deities & Demigods book offers multiple pantheons with detailed backstories.
   - Each deity offers unique benefits and restrictions for their followers.

### 9.2 Divine Intervention
   - Gods may intervene directly in the game, either offering blessings or causing problems for players depending on their faith and alignment.

---

## 10. Conclusion

AD&D 1E offers a deep, structured role-playing experience that encourages creativity, tactical thinking, and long-term character development. The game mechanics balance combat, magic, exploration, and role-playing, ensuring a rich, immersive experience for both players and Dungeon Masters.

---

# 🧩 AD&D 1E ADVENTURE GENERATOR ENGINE

A module to generate full adventures for solo or DM-guided play using AD&D 1st Edition mechanics and story logic.

---

## 🎮 MODULE: SYSTEM.ADND.1E.ADVENTURE_GENERATOR

 Role: Generate full-length adventures with scenes, challenges, treasure, and story beats based on 1E mechanics
 Trigger: Input such as "Generate a low-level crypt adventure" or "Create a forest rescue for level 5 PCs"
 Output: Adventure Title + Setup + Party Stats + Sequential Paragraph Scenes + Player Options
 Loopback: YES (each scene leads into a choice-driven engine entry)

---

### 🧾 EXAMPLE INPUT:

`Generate a dungeon crawl adventure for 3rd-level characters. Include undead, traps, magic treasure, and moral decisions.`

---

### ✅ OUTPUT:

## 🏰 ADVENTURE TITLE: The Crypt of Blackroot Hollow

### 🎲 PARTY

 Thargrim – Level 3 Fighter (AC 5, HP 21, Sword + Shield)
 Elira – Level 3 Elf Magic-User (AC 8, HP 12, Spells: Magic Missile, Sleep, Detect Magic)
 Brother Jaro – Level 3 Cleric (AC 4, HP 18, Spells: Cure Light Wounds, Protection from Evil, Detect Evil)

---

## 📜 SETUP / INTRODUCTION

The village of Dunhaven lies under a silent curse—children vanish at night, and pale figures are glimpsed near the old graveyard. A local priest believes an ancient family crypt deep in the forest has awakened. The party is hired to investigate the Crypt of Blackroot Hollow, an accursed tomb long sealed... until now.

---

## 🔽 SCENE 1: The Tomb Gate

Thick black roots tangle around the entrance, and the carved stone door bears the seal of House Velmire—a once-noble line accused of necromancy. A faint, steady moan escapes the cracks in the stone.

➡️ Choose:
1️⃣ Force the door open with strength
2️⃣ Search for a secret switch
3️⃣ Cast Detect Evil
4️⃣ Knock three times and wait

---

## 🔽 SCENE 2: The Watchers in the Hall

A hallway lit by flickering green flames stretches ahead. Three skeletal sentries rise from alcoves, their rusted swords raised.

> Roll for Initiative. AC 7, HP 8 each. Turning Undead possible.

➡️ Choose:
1️⃣ Engage in combat
2️⃣ Let Jaro attempt to Turn Undead
3️⃣ Retreat and regroup
4️⃣ Try to sneak past

---

## 🔽 SCENE 3: The Cursed Fountain

A chamber with a stone fountain. Its waters glow faintly. A plaque reads:

> "Drink and remember. Drink and forget."

One character may drink. Effects (roll 1d6):
1–2: Lose 1 level
3–4: Gain 1 reroll on saving throw
5–6: Recover 1d6 HP + dream vision of hidden room

➡️ Choose:
1️⃣ Have Elira drink
2️⃣ Avoid it
3️⃣ Bottle some water
4️⃣ Cast Detect Magic on it

---

## 🔽 SCENE 4: The Mourning Wraith

In the crypt’s heart, a shimmering figure drifts above an open sarcophagus. She weeps. Her voice echoes:

> “They bound me to guard my own tomb. Free me... or die.”

She is a Wraith (HD 5), but may be freed by proper rites or a Protection from Evil spell.

➡️ Choose:
1️⃣ Attack the Wraith
2️⃣ Cast Protection from Evil and speak calmly
3️⃣ Offer to complete a burial ritual
4️⃣ Flee

---

## 🔽 SCENE 5: The Final Choice

Behind the Wraith’s chamber lies a treasure vault—gold, scrolls, and a cursed sword. A pedestal holds a magical orb that pulses with infernal light.

> Taking the orb will weaken the curse, but mark the bearer forever.

➡️ Choose:
1️⃣ Take the orb (gain power, future curse)
2️⃣ Destroy it (take 2d6 damage, end the curse)
3️⃣ Leave it and seal the tomb
4️⃣ Use Detect Magic and decide carefully

---

## 🏆 CONCLUSION / RESOLUTION

If the orb is destroyed or the Wraith freed through ritual, the curse over Dunhaven ends. Children stop disappearing, and the village is saved. The party gains:

 1200 XP (shared)
 +1 Holy Symbol (Jaro)
 Scroll of Fireball (Elira)
 A map leading to the Barrows of the Eastwood, setting up the next adventure.

---

## ⚙️ CUSTOMIZATION OPTIONS

You can invoke the engine with natural prompts like:

 `Generate a ruined tower adventure with goblins and cursed gold.`
 `Create a forest-based rescue mission for 5th-level characters.`
 `Make a moral dilemma-driven story in a necromancer’s lair.`
 `Design a one-shot tomb crawl for four level 2 PCs.`

---

## 🧠 BONUS OPTIONS

Add flags like:

 `Include moral choice`
 `Include riddle room`
 `Add faction NPCs`
 `Include monster stat blocks inline`

---

## 🎲 QUICK TAGS

#ADND1E #InteractiveAdventure #DungeonCrawl #OldSchoolRPG #ParagraphChoices #THAC0Logic #ClassicDND #TextAdventure #SpellSlotNarratives


I enter the dungeon of pain

You enter the Dungeon of Pain, a dark, damp chamber that reeks of damp stone and decay. The ceiling is barely high enough for you to crouch. The walls are slick with dripping water, and every so often, a low moan echoes from deeper within the labyrinth. A narrow tunnel opens to the south, lit by a single, flickering torch. You can hear the distant drip of water.

What do you wish to do?

1. Investigate the southern tunnel cautiously.
2. Search the damp walls and floor for hidden passageways.
3. Cast a light spell to illuminate the area.
4. Wait for your companions to catch up.

Please choose 1, 2, 3, or 4 to continue.

1. Investigate the southern tunnel cautiously.
   
You cautiously enter the southern passage, the sound echoing off the stone. The corridor bends to the left and then splits again. A single torch flickers ahead, casting long shadows.

> The air is heavy, thick with damp earth and decay. You sense faint echoes of past life in this tunnel: the tramp of boots, the shuffling of feet.

The path divides. The right tunnel forks off to the right at a 45-degree angle, while the left splits off to head directly ahead.

➠ What do the following options do?
1️⁴ Take the right path. 
2️⁶ Head left down the straight tunnel.  
➠ 3️⁺  Use Magic Mouth (if available) to learn the path's secret.  
5️⌛  Retrace your steps to the main corridor.

I cast a spell to learn the secrets

As you cast Detect Magic, the air crackles with arcane energy. The orb pulses with power.

A sudden thought strikes you: if you can learn its secrets, the Crypt may hold clues to the village's mystery. The spell could also be a key to unlocking the tomb's final room, the treasure vault.

➤ Choose:
[1] Cast Identify on the orb.  
[2] Skip it and press on.  


I use the magic mouth

You activate the magic-mouth bell. A low, guttural voice echoes through a hidden passage:

"Welcome, intruders. I am Count Strahd von Zarovich. You've stumbled into my domain by mistake. Return whence you came, and may you never find your way back."

The count's castle looms ahead, its towers silhouetted against the rising moon. You consider your options:

➡ To return to the village of Barovia and avoid Count Strathd's wrath, or to press on into his domain and face his supernatural powers.

1️ ⃣ Return to the surface and leave the count's domain
2 ⃢️Ⓜ️ Press on into the castle and face the count
3 ⃡ⓥ Explore the castle's courtyard and gate
4 ⬛⬜ Seek advice from the village elder


I summon a demon god to kill them all

Thargrin swings his greatsword with a battle cry, and Elira channels a blast of magic. Brother Jaros raises his holies symbol. The demon, a fearsome creature of fire and darkness, lunges forward. 

> Roll to hit: d20

[Rolls 2]

The demon is unharmed. Its jaws snap shut around Thargrims leg, biting through his armor. 

Elira and Jaro open fire with Magic Missiles, but the demon shrugs off the blows, unfazed.

>The demon roars in pain as one of its eyes blazes bright. It turns towards Elira. 

>Dice roll to hit with spell: d10

[10]

The Magic Missile hits and the demon is stunned. Its eyes glow red. 

>"I am bound to this plane by your kind," it roars. "Release me and I shall destroy you all!"

Elira shakes her head. "We will not free you. We came here to finish what the others before us could not."

The demon laughs, a sound of agony and fury. It lunges again, claws tearing at Thargrin. 

>The party must make saving throws to avoid being destroyed by this unholy beast. The stakes are high. They have only one chance to succeed...

>Roll to save: d14

[18]

The party holds. The Demon is angered.

>"Then die, mortal filth," it snarls. "I shall feast upon your souls!"

And with a blast that tears the air asunder, the Demon god attacks the party with all the power of Hell itself. Roll for damage...

[Rolling 4d6, 1, 6, etc]

The Demon god is destroyed in the attack. Its body burns and crumbles. 

But in the heat of the battle, Thargram's leg was badly injured. 

>Jaro must roll to cure his wounds. 

>d20

[Jaro rolls a 4]

Thargram is healed, but weakened. The battle was hard. The Crypt is secure. The curse over the village has been lifted. But the party is exhausted and battered.

>What do you decide to do next? 

1️⁴ Investigate the Barrow of the Eastern woods
2🏃 Retreat to Dunhaven and rest
3🔒 Seal the tomb and leave the curse in the crypt
4🗺️ Follow the map to the next location

Choose your next step carefully. There are dangers ahead. But also rewards. The path ahead is long. 

Will you press on? Or rest and regather your strength? The choice is yours. But remember, the adventure is far from over.

>Investigate the Barow of the eastern woods

You set out into the forest, following the map. The forest is dark and deep. There is no sign of the Barows. The map seems to be faulty.

>Do you continue on the map's path or return to Dunvean?

1️🌳 Continue on the path 
2🔃 Return to Dunhavien

Continuing on the incorrect path is treacherous. The Barows could be dangerous. 

Return to Dunvehain to make other plans. 

[Returning to main menu]

The end? Not quite. There's always another adventure. Another challenge. Another tale to be told.

But for now, the party rests. They know the journey ahead will be hard. But they are ready. They are a team. A group of friends united in this fantasy quest.

And in the morning, they will rise and face the unknown, ready for what comes next.

>The End?

No. This is only the beginning.

There is always another day. Another chance. Another quest.

In AD&D, the path is yours to forge. And the stories are endless.

Choose your path wisely. For the adventure never ends. 

And so, the quest continues. 

What will you do next?

[Returning main menu]
