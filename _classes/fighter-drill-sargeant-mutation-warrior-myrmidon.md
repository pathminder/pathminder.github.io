---
title: Fighter (Drill Sargeant, Mutation Warrior, Myrmidon)
sources:
  - Pathfinder Roleplaying Game Core Rulebook
  - "Pathfinder Player Companion: Melee Tactics Toolbox"
  - "Path of War: Expanded"
tags:
  - Alchemy
  - Initiator

max_level: 20
hit_die: 10
starting_wealth: 5d6 x 10 gp (average 175 gp)
starting_age: ???

class_skills:
   - Acrobatics
   - Bluff
   - Climb
   - Craft
   - Diplomacy
   - Intimidate
   - Knowledge (dungeoneering)
   - Knowledge (engineering)
   - Knowledge (martial)
   - Perception
   - Profession
   - Ride
   - Survival
   - Swim
skill_ranks_per_level: 4

bab_progression: full
fort_progression: good
ref_progression: poor
will_progression: poor

initiating_progression: mid

weapon_proficiencies:
  - Simple
  - Martial
armor_proficiencies:
  - Light
  - Medium
  - Heavy
shield_proficiencies:
  - Shields
  - Tower Shields

class_features:

  - name: bonus feats
    levels: [1, 4, 8, 12, 16, 20]
    levels_text:
      1: 1 feat
      4: 2 feats
      8: 3 feats
      12: 4 feats
      16: 5 feats
      20: 6 feats
    text: |
      At 1st level, 4th level, and every four levels thereafter, a fighter gains a bonus feat in addition to those gained from normal advancement. These bonus feats must be selected from those listed as Combat Feats, sometimes also called "fighter bonus feats."

      Upon reaching 4th level, and every four levels thereafter (8th, 12th, and so on), a fighter can choose to learn a new bonus feat in place of a bonus feat he has already learned. In effect, the fighter loses the bonus feat in exchange for the new one. The old feat cannot be one that was used as a prerequisite for another feat, prestige class, or other ability. A fighter can only change one feat at any given level and must choose whether or not to swap the feat at the time he gains a new bonus feat for the level.

  - name: maneuvers
    levels: [1]
    text: |
      A myrmidon begins his career with knowledge of three martial maneuvers. When he takes his first myrmidon level, he selects four of the following disciplines to gain access to for myrmidon maneuvers: Broken Blade, Golden Lion, Iron Tortoise, Mithral Current, Piercing Thunder, Primal Fury, Scarlet Throne, Tempest Gale, and Thrashing Dragon. If one of his selected disciplines' associated skills is not on his class skill list, he gains it as a class skill.

      Once the myrmidon knows a maneuver, he must ready it before he can use it (see Maneuvers Readied, below). A maneuver usable by myrmidons is considered an extraordinary ability unless otherwise noted in it or its discipline's description. A myrmidon's maneuvers are not affected by spell resistance, and he does not provoke attacks of opportunity when he initiates one.

      The myrmidon learns additional maneuvers at higher levels, as indicated on Table: The Fighter. The maximum level of maneuvers gained through myrmidon levels is limited by those listed in that table as well, although this restriction does not apply to maneuvers added to his maneuvers known through other methods, such as prestige classes or the Advanced Study feat. A myrmidon must meet a maneuver's prerequisite to learn it. See the Systems and Use chapter in Path of War for more details on how maneuvers are used.

      Upon reaching 4th level, and at every even numbered initiator level thereafter (6th, 8th, 10th, and so on), the myrmidon can choose to learn a new maneuver in place of one he already knows. In effect, he loses the old maneuver in exchange for the new one. He can choose a new maneuver of any level he likes, as long as he observes the restriction on the highest-level maneuvers he knows; the myrmidon need not replace the old maneuver with a maneuver of the same level. He can swap only a single maneuver at any given level. A myrmidon's initiation modifier is Wisdom, and each myrmidon level is counted as a full initiator level.

      **Maneuvers Readied:** A myrmidon can ready all three of his maneuvers known at 1st level, and as he advances in level and learns more maneuvers, he is able to ready more, but must still choose which maneuvers to ready. A myrmidon must always ready his maximum number of maneuvers readied. He readies his maneuvers by performing weapon drills for ten minutes. The maneuvers he chooses remain readied until he decides to practice again and change them. The myrmidon does not need to sleep or rest for any long period of time in order to ready his maneuvers; any time he spends ten minutes practicing, he can change his readied maneuvers.

      A myrmidon begins an encounter with all his readied maneuvers unexpended, regardless of how many times he might have already used them since he chose them. When he initiates a maneuver, he expends it for the current encounter, so each of his readied maneuvers can be used once per encounter (unless he recovers them, as described below).

      In order for the myrmidon to recover maneuvers, he must take on a defensive form as a full-round action, resetting his rhythm to continue the battle. When he does so, he recovers a number of maneuvers equal to his myrmidon initiation modifier (minimum 2) and until the start of his next turn, attacks made against him provoke an attack of opportunity and he can take a 5-foot step each time he is attacked (even if he has already taken one this round). In addition, he gains the benefit of the Combat Reflexes feat, and can us myrmidon initiation modifier instead of his Dexterity modifier for determining how many additional attacks of opportunity he can make. Alternately, the myrmidon may take a moment to focus, recovering a single maneuver as a standard action.

      **Stances Known:** A myrmidon begins his career with knowledge of one stance from any discipline open to myrmidons. At 4th, 7th, 11th, and 13th levels, he can select an additional stance to learn. The maximum level of stances gained through myrmidon levels is limited by those listed in Table: The Fighter. Unlike maneuvers, stances are not expended and the myrmidon does not have to ready them. All the stances he knows are available to his at all times, and he can change the stance he is currently maintaining as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance or discipline description.

      Unlike with maneuvers, a myrmidon cannot learn a new stance at higher levels in place of one he already knows.

  - name: grit
    type: Ex
    levels: [1]
    text: |
      At 1st level, the myrmidon makes his mark upon the world with nerves of steel and superior training. Through determination, verve, or otherwise dumb luck, the myrmidon is capable of forcing incredible feats of daring and skill through their own tenacity. In game terms, grit is a fluctuating measure of a myrmidon's ability to perform incredible actions in combat. At the start of each day, a myrmidon gains a number of grit points equal to his myrmidon initiation modifier (minimum 1). His grit goes up or down throughout the day, but usually cannot go higher than his myrmidon initiation modifier (minimum 1), though some feats and magic items may affect this maximum. A myrmidon spends grit to accomplish [deeds](#deeds), and regains grit in the following ways.

      - *Critical Hit:* Each time the myrmidon confirms a critical hit while in the heat of combat with a weapon with which he has Weapon Focus or is in a weapon group associated with a discipline he has Discipline Focus for, he regains one grit point. Confirming a critical hit on a helpless or unaware creature or on a creature that has fewer Hit Dice than half the myrmidon's character level does not restore grit.
      - *Killing Blow with a Maneuver:* When the myrmidon reduces a creature to 0 or fewer hit points with a maneuver or with a weapon he has Weapon Focus with, he regains 1 grit point. Destroying an unattended object, reducing a helpless or unaware creature to 0 or fewer hit points, or reducing a creature that has fewer Hit Dice than half the myrmidon's character level to 0 or fewer hit points does not restore any grit.

      With the GM's approval, a myrmidon can regain grit by performing daring acts. As a general rule, a daring act should be risky and dramatic. It should take a good deal of guts, and its outcome should have a low probability of success. If it is successful, the myrmidon regains 1 grit point. Before attempting a daring act, the player should ask the GM whether the act qualifies. The GM is the final arbiter of what’s considered a daring act, and can grant a regained grit point for a daring act even if the player does not ask beforehand whether the act qualifies.

  - name: deeds
    levels: [1, 3, 6, 10, 14]
    levels_text:
      1: heroic recovery, man of action, unbreakable
      3: ready for trouble, utility trick
      6: warrior's determination
      10: improved warrior's determination
      14: greater warrior's determination
    text: |
      Myrmidons spend grit points to accomplish deeds. Most deeds grant the myrmidon some momentary bonus or effect, but there are some that provide longer lasting effects. Some deeds stay in effect as long as the myrmidon has at least 1 grit point. The following is the list of base myrmidon deeds. A myrmidon can only perform deeds of his level or lower. Unless otherwise noted, a deed can be performed multiple successive times, as long as the appropriate amount of grit is spent to perform the deed.

      *Unbreakable (Ex):* Starting at 1st level, a myrmidon is trained very well to protect himself against the many unnatural elements of this world where he must rely on only his wits and training to protect him from harm. He can spend 1 grit point as an immediate action to gain a +4 circumstance bonus on a single saving throw.

      *Heroic Recovery (Ex):* Starting at 1st level, a myrmidon spend 1 grit point as a swift action to recover a single expended maneuver.

      *Man of Action (Ex):* Starting at 1st level, a myrmidon can spend 1 grit point as a swift action to gain a circumstance bonus on a single Acrobatics, Climb, or Swim check equal to his class level.

      *Ready for Trouble (Ex):* Starting at 3rd level, as long as the myrmidon has at least 1 grit point, he gains a +2 bonus on initiative checks and Will saves to resist compulsion and fear effects. In addition, if his hands are free and unrestrained, he can spend 1 grit point as part of making an initiative check to draw a single non- hidden light or one-handed weapon or to draw and don a shield (except a tower shield).

      *Utility Trick (Ex):* Starting at 3rd level, as long as the myrmidon has at least 1 grit point, he can perform any of the following utility tricks. The myrmidon must declare the utility trick he is using before using the ability.

      - *Field Bandage:* By using a healer's kit to quickly dress and bandage a wound, the myrmidon can grant 1d6 temporary hit points per three character levels to himself or an adjacent creature as a full- round action. These temporary hit points cannot increase a creature's hit points beyond its normal maximum, and last for ten minutes. A creature can only only receive the benefits of this ability once per day or until they have received magical healing equal to or greater than the amount of temporary hit points granted by the myrmidon's field bandage. This ability also halts a bleeding wound, stopping a creature from taking further bleed damage.
      - Makeshift Tool: Should he need a tool in a combat situation, the myrmidon makes due with his weapons. He is not penalized for not having a proper tool when making skill checks in combat.
      - Improvise Weapon: The myrmidon can use objects not intended to be normal weapons or cobble together something that can be used as a weapon. He only takes a --2 penalty while wielding improvised weapons, rather than --4.

      *Warrior's Determination (Ex):* The myrmidon gains an uncanny ability to force himself through many hardships and keep on going through his superior training and experience. Starting at 6th level, he can spend 1 grit point as an immediate action to negate a single condition currently affecting him until the end of the encounter, at which point it returns as if its duration had not been interrupted. The myrmidon can activate this ability even if he would not normally be able to act because of the condition in question. A myrmidon can use this ability multiple times in an encounter, spending 1 grit point and negating a single condition each time he does.

      - At 6th level, the myrmidon can temporarily negate the fatigued, shaken, or sickened conditions using this ability.
      - At 10th level, a myrmidon can temporarily negate the dazed or staggered conditions, or ignore the effects of a disease (including ability damage he may have taken from the disease) using this ability.
      - At 14th level, a myrmidon can temporarily negate the exhausted, frightened, or nauseated conditions using this ability.

  - name: tactician
    type: Ex
    levels: [2, 5, 10, 15, 20]
    levels_text:
      2: 1/day
      5: 2/day
      10: 3/day
      15: 4/day
      20: 5/day
    text: At 2nd level, the fighter receives a teamwork feat as a bonus feat. He must meet the prerequisites for this feat. As a standard action, the fighter can grant this feat to all allies within 30 feet who can see and hear him. Allies retain the use of this bonus feat for 3 rounds plus 1 round for every two levels the fighter possesses. Allies do not need to meet the prerequisites of these bonus feats. The fighter can use this ability once per day at 2nd level, plus one additional time per day at 5th level and for every 5 levels thereafter.

  - name: mutagen
    type: Su
    levels: [3]
    text: At 3rd level, a mutation warrior discovers how to create a mutagen that he can imbibe in order to heighten his physical prowess at the cost of his personality. This ability functions as the alchemist's mutagen ability, using his fighter level as his alchemist level.

  - name: weapon training
    type: Ex
    levels: [5, 9, 13, 17]
    levels_text:
      5: "+1"
      9: "+2"
      13: "+3"
      17: "+4"
    text: |
      At 5th level, a fighter can select one group of weapons from the list below. Whenever he attacks with a weapon from this group, he gains a +1 bonus on attack and damage rolls. Every four levels thereafter (9th, 13th, and 17th), the bonuses granted by the selected weapon group increases by +1.

      A fighter also adds this bonus to any combat maneuver checks made with weapons from this group. This bonus also applies to the fighter's Combat Maneuver Defense when defending against disarm and sunder attempts made against weapons from this group.

      - *Axes:* bardiche, battleaxe, collapsible kumade, dwarven waraxe, gandasa, greataxe, handaxe, heavy pick, hooked axe, knuckle axe, kumade, light pick, mattock, orc double axe, pata, throwing axe, and tongi.
      - *Blades, Heavy:* Ankus, dueling sword, bastard sword, chakram, double chicken saber, double walking stick katana, elven curve blade, estoc, falcata, falchion, flambard, greatsword, great terbutje , katana, khopesh, klar, longsword, nine-ring broadsword, nodachi, scimitar, scythe, seven-branched sword, shotel, temple sword, terbutje, and two-bladed sword.
      - *Blades, Light:* bayonet, butterfly knife, butterfly sword, chakram, dagger, Deer horn knife, gladius, hunga munga, kama, katar, kerambit, kukri, machete, madu, manople, pata, quadrens, rapier, sawtooth sabre, scizore, shortsword, sica, sickle, starknife, swordbreaker dagger, sword cane, wakizashi, and war razor.
      - *Bows:* composite longbow, composite shortbow, longbow, and shortbow.
      - *Close:* bayonet, brass knuckles, cestus, dan bong, emei piercer, fighting fan, gauntlet, heavy shield, iron brush, katar, light shield, madu, mere club, punching dagger, rope gauntlet, sap, scizore, spiked armor, spiked gauntlet, spiked shield, tekko-kagi, tonfa, unarmed strike, wooden stake, and wushu dart.
      - *Crossbows:* double crossbow, hand crossbow, heavy crossbow, launching crossbow, light crossbow, heavy repeating crossbow, light repeating crossbow, and tube arrow shooter.
      - *Double:* bo staff, chain spear, dire flail, double walking stick katana, double-chained kama, dwarven urgrosh, gnome hooked hammer, kusarigama, orc double axe, quarterstaff, two-bladed sword, and weighted spear.
      - *Firearms:* all one-handed, two-handed, and siege firearms.
      - *Flails:* battle poi, bladed scarf, chain spear, dire flail, double chained kama, flail, flying blade, gnome pincher, halfling rope-shot, heavy flail, kusarigama, kyoketsu shoge, meteor hammer, morningstar, nine-section whip, nunchaku, sansetsukon, scorpion whip, spiked chain, urumi, and whip.
      - *Hammers:* aklys, battle aspergillum, club, greatclub, heavy mace, light hammer, light mace, mere club, planson, taiaha, tetsubo, wahaika, and warhammer.
      - *Monk:* bo staff, brass knuckles, butterfly sword, cestus, dan bong, deer horn knife, double chained kama, double chicken saber, emei piercer, fighting fan, hanbo, jutte, kama, kusarigama, kyoketsu shoge, lungshuan tamo, monk's spade, nine-ring broadsword, nine-section whip, nunchaku, quarterstaff, rope dart, sai, sansetsukon, seven-branched sword, shang gou, shuriken, siangham, temple sword, tiger fork, tonfa, tri-point double-edged sword, unarmed strike, urumi, and wushu dart.
      - *Natural:* unarmed strike and all natural weapons, such as bite, claw, gore, tail, and wing.
      - *Polearms:* bardiche, bec de corbin, bill, crook, glaive, glaive-guisarme, guisarme, halberd, hooked lance, lucerne hammer, mancatcher, monk's spade, naginata, nodachi, ranseur, rhomphaia, tepoztopilli, and tiger fork.
      - *Siege engines:* Ballista, bombard, catapult, corvus, firedrake, firewyrm, gallery, ram, siege tower, springal, trebuchet, and all other siege engines.
      - *Spears:* amentum, boar spear, chain spear, elven branched spear, javelin, harpoon, lance, longspear, orc skull ram, pilum, planson, shortspear, sibat, spear, tiger fork, trident, and weighted spear.
      - *Thrown:* aklys, amentum, atlatl, blowgun, bolas, boomerang, brutal bolas, chakram, club, dagger, dart, deer horn knife, halfling sling staff, harpoon, hunga munga, javelin, lasso, kestros, light hammer, net, poisoned sand tube, rope dart, shortspear, shuriken, sibat, sling, sling glove, spear, starknife, throwing axe, throwing shield, trident, and wushu dart.

  - name: mutagen discovery
    type: Su
    levels: [7, 11, 15, 19]
    levels_text:
      7: 1 discovery
      11: 2 discoveries
      15: 3 discoveries
      19: 4 discoveries
    text: At 7th level and every 4 levels thereafter, the mutation warrior can choose one of the following alchemist discoveries to augment his abilities: feral mutagen, grand mutagen, greater mutagen, infuse mutagen, nauseating flesh, preserve organs, rag doll mutagen, spontaneous healing, tentacle, vestigial arm, wings. The mutagen warrior uses his fighter level as his effective alchemist level for the purpose of these discoveries.

  - name: greater tactician
    type: Ex
    levels: [9]
    text: At 9th level, the fighter receives an additional teamwork feat as a bonus feat. He must meet the prerequisites for this feat. The fighter can grant this feat to his allies using the tactician ability. Using the tactician ability is a swift action.

  - name: master tactician
    type: Ex
    levels: [17]
    text: At 17th level, the fighter receives an additional teamwork feat as a bonus feat. He must meet the prerequisites for this feat. The fighter can grant this feat to his allies using the tactician ability. Whenever the fighter uses the tactician ability, he grants any two teamwork feats that he knows. He can select from any of his teamwork feats, not just his bonus feats.

  - name: weapon mastery
    type: Ex
    levels: [20]
    text: At 20th level, a fighter chooses one weapon, such as the longsword, greataxe, or longbow. Any attacks made with that weapon automatically confirm all critical threats and have their damage multiplier increased by 1 (×2 becomes ×3, for example). In addition, he cannot be disarmed while wielding a weapon of this type.
---

Some take up arms for glory, wealth, or revenge. Others do battle to prove themselves, to protect others, or because they know nothing else. Still others learn the ways of weaponcraft to hone their bodies in battle and prove their mettle in the forge of war. Lords of the battlefield, fighters are a disparate lot, training with many weapons or just one, perfecting the uses of armor, learning the fighting techniques of exotic masters, and studying the art of combat, all to shape themselves into living weapons. Far more than mere thugs, these skilled warriors reveal the true deadliness of their weapons, turning hunks of metal into arms capable of taming kingdoms, slaughtering monsters, and rousing the hearts of armies. Soldiers, knights, hunters, and artists of war, fighters are unparalleled champions, and woe to those who dare stand against them.

**Role:** Fighters excel at combat—defeating their enemies, controlling the flow of battle, and surviving such sorties themselves. While their specific weapons and methods grant them a wide variety of tactics, few can match fighters for sheer battle prowess.
