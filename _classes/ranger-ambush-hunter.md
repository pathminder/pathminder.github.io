---
title: Ranger (Ambush Hunter)
sources:
  - Pathfinder Roleplaying Game Core Rulebook
  - Pathfinder Roleplaying Game Advanced Player's Guide
  - Pathfinder Roleplaying Game Advanced Class Guide
  - "Path of War: Expanded"
tags:
  - Initiator

max_level: 20
hit_die: 8
starting_wealth: 5d6 × 10 gp (average 175 gp)

class_skills:
  - Climb
  - Craft
  - Handle Animal
  - Heal
  - Intimidate
  - Knowledge (dungeoneering)
  - Knowledge (geography)
  - Knowledge (nature)
  - Perception
  - Profession
  - Ride
  - Spellcraft
  - Stealth
  - Survival
  - Swim
skill_ranks_per_level: 6

bab_progression: full
fort_progression: good
ref_progression: good
will_progression: poor

initiating_progression: partial

weapon_proficiencies:
  - Simple
  - Martial
armor_proficiencies:
  - Light
  - Medium
shield_proficiencies:
  - Shields

class_features:

  - name: maneuvers
    levels: [1]
    text: |
      An ambush hunter begins his career with knowledge of three martial maneuvers. The disciplines available to him are Golden Lion and Primal Fury.

      Once the ambush hunter knows a maneuver, he must ready it before he can use it (see Maneuvers Readied, below). A maneuver usable by ambush hunters is considered an extraordinary ability unless otherwise noted in it or its discipline's description. An ambush hunter's maneuvers are not affected by spell resistance, and he does not provoke attacks of opportunity when he initiates one.

      The ambush hunter learns additional maneuvers at higher levels, as indicated on Table: The Ranger. The maximum level of maneuvers gained through ambush hunter levels is limited by those listed in that table as well, although this restriction does not apply to maneuvers added to his maneuvers known through other methods, such as prestige classes or the Advanced Study feat. An ambush hunter must meet a maneuver's prerequisite to learn it. See the Systems and Use chapter in Path of War for more details on how maneuvers are used.

      Upon reaching 4th level, and at every even numbered initiator level thereafter (6th, 8th, 10th, and so on), the ambush hunter can choose to learn a new maneuver in place of one he already knows. In effect, he loses the old maneuver in exchange for the new one. He can choose a new maneuver of any level he likes, as long as he observes the restriction on the highest-level maneuvers he knows; the ambush hunter need not replace the old maneuver with a maneuver of the same level. He can swap only a single maneuver at any given level. An ambush hunter's initiation modifier is Wisdom, and each ambush hunter level is counted as a full initiator level.

      *Maneuvers Readied:* An ambush hunter can ready all three of his maneuvers known at 1st level, and as he advances in level and learns more maneuvers, he is able to ready more, but must still choose which maneuvers to ready. An ambush hunter must always ready his maximum number of maneuvers readied. He readies his maneuvers by meditating or observing his animal companion for ten minutes. The maneuvers he chooses remain readied until he decides to practice again and change them. The ambush hunter does not need to sleep or rest for any long period of time in order to ready his maneuvers; any time he spends ten minutes meditating, he can change his readied maneuvers.

      An ambush hunter begins an encounter with all his readied maneuvers unexpended, regardless of how many times he might have already used them since he chose them. When he initiates a maneuver, he expends it for the current encounter, so each of his readied maneuvers can be used once per encounter (unless he recovers them, as described below).

      In order for the ambush hunter to recover maneuvers, he must blend into the shadows and position himself to strike. As a full-round action, the ambush hunter and his animal companion gain hide in plain sight (as the ranger class feature) for one round, each can make a Stealth check to hide, and then each can move up to their speed. When he does so, he recovers a number of expended maneuvers equal to his ambush hunter initiation modifier (minimum 2). The ambush hunter and his animal companion do not take a penalty on their Stealth checks from moving while using this ability. Alternately, the ambush hunter may take a moment to reassess his prey, recovering a single maneuver as a standard action.

      *Stances Known:* An ambush hunter begins his career with knowledge of one stance from any discipline open to ambush hunters. At 4th, 7th, 11th, and 13th levels, he can select an additional stance to learn. The maximum level of stances gained through ambush hunter levels is limited by those listed in Table: The Ranger. Unlike maneuvers, stances are not expended and the ambush hunter does not have to ready them. All the stances he knows are available to his at all times, and he can change the stance he is currently maintaining as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance or discipline description.

      Unlike with maneuvers, an ambush hunter cannot learn a new stance at higher levels in place of one he already knows.

  - name: martial style
    type: Ex
    levels: [1]
    text: |
      At 1st level, the ambush hunter selects an additional martial discipline to gain access to from the following list. This choice also determines which combat styles he can choose from when he gains the combat style class feature. If the ambush hunter does not have the discipline's associated skill as a class skill, he gains it as a class skill.

      - *Broken Blade:* associated skill---Acrobatics; allowed combat styles---Natural Weapon or Two-Weapon Combat.
      - *Iron Tortoise:* associated skill---Bluff; allowed combat styles---Thrown or Weapon and Shield.
      - *Piercing Thunder:* associated skill---Acrobatics; allowed combat styles---Mounted or Two-Handed Weapons.
      - *Scarlet Throne:* associated skill---Sense Motive; allowed combat styles---Mounted or Two-Handed Weapons.
      - *Solar Wind:* associated skill---Perception; allowed combat styles---Archery, Crossbow or Thrown.
      - *Tempest Gale:* associated skill---Sleight of Hand; allowed combat styles---Archery, Crossbow or Thrown.
      - *Thrashing Dragon:* associated skill---Acrobatics; allowed combat styles---Thrown or Two-Weapon Combat.

  - name: track
    type: Ex
    levels: [1]
    text: A ranger adds half his level (minimum 1) to Survival skill checks made to follow tracks.

  - name: wild empathy
    type: Ex
    levels: [1]
    text: |
      A ranger can improve the initial attitude of an animal. This ability functions just like a Diplomacy check to improve the attitude of a person (see Using Skills). The ranger rolls 1d20 and adds his ranger level and his Charisma bonus to determine the wild empathy check result. The typical domestic animal has a starting attitude of indifferent, while wild animals are usually unfriendly.

      To use wild empathy, the ranger and the animal must be within 30 feet of one another under normal visibility conditions. Generally, influencing an animal in this way takes 1 minute, but, as with influencing people, it might take more or less time.

      The ranger can also use this ability to influence a magical beast with an Intelligence score of 1 or 2, but he takes a --4 penalty on the check.

  - name: combat style feat
    type: Ex
    levels: [2, 6, 10, 14, 18]
    levels_text:
      2: 1 feat
      6: 2 feats
      10: 3 feats
      14: 4 feats
      18: 5 feats
    text: |
      At 2nd level, the ranger must select one combat style to pursue from the list of combat styles available from his martial style.

      The ranger's expertise manifests in the form of bonus feats at 2nd, 6th, 10th, 14th, and 18th level. He can choose feats from his selected combat style, even if he does not have the normal prerequisites.

      The benefits of the ranger's chosen style feats apply only when he wears light, medium, or no armor. He loses all benefits of his combat style feats when wearing heavy armor. Once a ranger selects a combat style, it cannot be changed.

      *Archery:* If the ranger selects archery style, he can choose from the following list whenever he gains a combat style feat: Far Shot, Focused Shot, Point Blank Shot, Precise Shot, and Rapid Shot.

      At 6th level, he adds Crossbow Mastery, Improved Precise Shot, Parting Shot, Point Blank Master and Manyshot to the list.

      At 10th level, he adds Pinpoint Targeting and Shot on the Run to the list.

      *Crossbow:* If the character selects crossbow style, he can choose from the following list whenever he gains a combat style feat: Deadly Aim, Focused Shot, Precise Shot, and Rapid Reload.

      At 6th level, he adds Crossbow Mastery and Improved Precise Shot to the list.

      At 10th level, he adds Pinpoint Targeting and Shot on the Run to the list.

      *Mounted Combat:* If the character selects mounted combat style, he can choose from the following list whenever he gains a combat style feat: Mounted Combat, Mounted Archery, Ride-By Attack, and Trick Riding.

      At 6th level, he adds Mounted Shield and Spirited Charge to the list.

      At 10th level, he adds Mounted Skirmisher and Unseat to the list.

      *Natural Weapon:* If the character selects natural weapon style, he can choose from the following list whenever he gains a combat style feat: Aspect of the Beast, Improved Natural Attack, Rending Claws, and Weapon Focus.

      At 6th level, he adds Eldritch Claws and Vital Strike to the list.

      At 10th level, he adds Multiattack and Improved Vital Strike to the list.

      *Thrown Weapon:* If the character selects thrown weapon style, he can choose from the following list whenever he gains a combat style feat: Distance Thrower, Precise Shot, Quick Draw, Two-Weapon Fighting.

      At 6th level, he adds Close-Quarters Thrower and False Opening to the list.

      At 10th level, he adds Pinpoint Targeting and Shot on the Run to the list.

      *Two-Handed Weapon:* If the character selects two-handed weapon style, he can choose from the following list whenever he gains a combat style feat: Cleave, Power Attack, Pushing Assault, and Shield of Swings.

      At 6th level, he adds Furious Focus and Great Cleave to the list.

      At 10th level, he adds Dreadful Carnage and Improved Sunder to the list.

      *Two-Weapon Combat:* If the ranger selects two-weapon combat style, he can choose from the following list whenever he gains a combat style feat: Double Slice, Improved Shield Bash, Quick Draw, and Two-Weapon Fighting.

      At 6th level, he adds Improved Two-Weapon Fighting and Two-Weapon Defense to the list.

      At 10th level, he adds Greater Two-Weapon Fighting and Two-Weapon Rend to the list.

      *Weapon and Shield:* If the character selects weapon and shield style, he can choose from the following list whenever he gains a combat style feat: Improved Shield Bash, Shield Focus, Shield Slam and Two-Weapon Fighting.

      At 6th level, he adds Saving Shield and Shield Master to the list.

      At 10th level, he adds Bashing Finish and Greater Shield Focus to the list.

  - name: endurance
    type: Ex
    levels: [3]
    text: A ranger gains Endurance as a bonus feat at 3rd level.

  - name: favored terrain
    type: Ex
    levels: [3, 8, 13, 18]
    levels_text:
      3: 1 terrain
      8: 2 terrains
      13: 3 terrains
      18: 4 terrains
    text: |
      At 3rd level, a ranger may select a type of terrain from the list below. The ranger gains a +2 bonus on initiative checks and Knowledge (geography), Perception, Stealth, and Survival skill checks when he is in this terrain. A ranger traveling through his favored terrain normally leaves no trail and cannot be tracked (though he may leave a trail if he so chooses).

      - Cold (ice, glaciers, snow, and tundra)
      - Desert (sand and wastelands)
      - Forest (coniferous and deciduous)
      - Jungle
      - Mountain (including hills)
      - Plains
      - Planes (pick one, other than Material Plane)
      - Swamp
      - Underground (caves and dungeons)
      - Urban (buildings, streets, and sewers)
      - Water (above and below the surface)

      At 8th level and every five levels thereafter, the ranger may select an additional favored terrain. In addition, at each such interval, the skill bonus and initiative bonus in any one favored terrain (including the one just selected, if so desired), increases by +2.

      If a specific terrain falls into more than one category of favored terrain, the ranger's bonuses do not stack; he simply uses whichever bonus is higher.

  - name: martial companion
    type: Ex
    levels: [4]
    text: |
      At 4th level, an ambush hunter gains the companionship of a loyal animal companion. The ambush hunter can choose from the following list: badger, bird, camel, cat (small), dire rat, dog, horse, pony, snake (viper or constrictor), or wolf. If the campaign takes place wholly or partly in an aquatic environment, the ranger may choose a shark instead. This animal is a loyal companion that accompanies the ranger on his adventures as appropriate for its kind. This ability functions like the druid animal companion ability (which is part of the Nature Bond class feature), except that the ranger's effective druid level is equal to his ranger level --3.

      The ambush hunter's animal companion gains a list of maneuvers and stances known equal to 1/2 the number of maneuvers or stances known by the ambush hunter (rounded down). The animal companion can only learn maneuvers from the Primal Fury discipline, and treats its natural attacks as Primal Fury discipline weapons. For example, a 4th level ambush hunter knows 5 maneuvers and 2 stances; his animal companion would learn 2 maneuvers and 1 stance from the Primal Fury discipline.

      The animal companion does not ready its maneuvers; it has access to each of its known maneuvers at all times. When the animal companion initiates a maneuver, the ambush hunter expends one of his readied maneuvers of his choice. If the ambush hunter has no unexpended maneuvers, the animal companion cannot initiate its maneuvers. The animal companion's initiation modifier is Wisdom, and its initiator level is equal to the ambush hunter's initiator level.

  - name: ambush tactics
    type: Ex
    levels: [4]
    text: The ambush hunter is adept at maneuvering with his animal companion to take advantage of any weakness his enemies present. Starting at 4th level, whenever an ambush hunter or his animal companion attack a flat-footed creature or are both flanking the same creature, they both add the ambush hunter's initiation modifier as a bonus on damage rolls made with strikes against that flat-footed or flanked creature. Whenever the ranger and the animal companion successfully attack the same creature in a single round, the ambush hunter recovers one expended maneuver.

  - name: woodland stride
    type: Ex
    levels: [7]
    text: |
      Starting at 7th level, a ranger may move through any sort of undergrowth (such as natural thorns, briars, overgrown areas, and similar terrain) at his normal speed and without taking damage or suffering any other impairment.

      Thorns, briars, and overgrown areas that are enchanted or magically manipulated to impede motion, however, still affect him.

  - name: pack savagery
    type: Ex
    levels: [8]
    text: Starting at 8th level, whenever the ambush hunter or his animal companion initiates a boost from the Primal Fury or Golden Lion disciplines, both the ambush hunter and his animal companion gain the benefits of the boost. The ambush hunter and the animal companion can only benefit from one such boost per round, even if they use this ability.

  - name: swift tracker
    type: Ex
    levels: [8]
    text: Beginning at 8th level, a ranger can move at his normal speed while using Survival to follow tracks without taking the normal --5 penalty. He takes only a –10 penalty (instead of the normal --20) when moving at up to twice normal speed while tracking.

  - name: evasion
    type: Ex
    levels: [9]
    text: When he reaches 9th level, a ranger can avoid even magical and unusual attacks with great agility. If he makes a successful Reflex saving throw against an attack that normally deals half damage on a successful save, he instead takes no damage. Evasion can be used only if the ranger is wearing light armor, medium armor, or no armor. A helpless ranger does not gain the benefit of evasion.

  - name: camouflage
    type: Ex
    levels: [12]
    text: A ranger of 12th level or higher can use the Stealth skill to hide in any of his favored terrains, even if the terrain doesn't grant cover or concealment.

  - name: improved evasion
    type: Ex
    levels: [16]
    text: At 16th level, a ranger's evasion improves. This ability works like evasion, except that while the ranger still takes no damage on a successful Reflex saving throw against attacks, he henceforth takes only half damage on a failed save. A helpless ranger does not gain the benefit of improved evasion.

  - name: hide in plain sight
    type: Ex
    levels: [17]
    text: While in any of his favored terrains, a ranger of 17th level or higher can use the Stealth skill even while being observed.

  - name: unbreakable bond
    type: Su
    levels: [19]
    text: At 19th level, the ambush hunter's bond with his animal companion is so strong that it transcends time, space, life, and death. The ambush hunter always knows the exact location of his animal companion, regardless of distance (even if the animal companion is on another plane) and can view his animal companion's location as if by a scrying spell for a number of minutes per day equal to his ambush hunter initiation modifier. The caster level for this effect is equal to the ambush hunter's initiator level. In addition, if the ambush hunter's animal companion dies, it reincarnates 24 hours later in a random location within 1 mile of the ambush hunter.

  - name: master hunter
    type: Ex
    levels: [20]
    text: A ranger of 20th level becomes a master hunter. He can always move at full speed while using Survival to follow tracks without penalty.
---

For those who relish the thrill of the hunt, there are only predators and prey. Be they scouts, trackers, or bounty hunters, rangers share much in common: unique mastery of specialized weapons, skill at stalking even the most elusive game, and the expertise to defeat a wide range of quarries. Knowledgeable, patient, and skilled hunters, these rangers hound man, beast, and monster alike, gaining insight into the way of the predator, skill in varied environments, and ever more lethal martial prowess. While some track man-eating creatures to protect the frontier, others pursue more cunning game—even fugitives among their own people.

**Role:** Ranger are deft skirmishers, either in melee or at range, capable of skillfully dancing in and out of battle. Their abilities allow them to deal significant harm to specific types of foes, but their skills are valuable against all manner of enemies.
