---
title: Rogue (Eldritch Scoundrel, Unchained)
sources:
  - Pathfinder Roleplaying Game Core Rulebook
  - "Pathfinder Player Companion: Arcane Anthology"
tags:
  - Arcane
  - Sneak Attack

max_level: 20
hit_die: 8
starting_wealth: 4d6 × 10 gp (average 140 gp)

class_skills:
  - Acrobatics
  - Appraise
  - Bluff
  - Climb
  - Craft
  - Disable Device
  - Escape Artist
  - Intimidate
  - Knowledge (arcana)
  - Knowledge (dungeoneering)
  - Knowledge (local)
  - Linguistics
  - Perception
  - Perform
  - Profession
  - Sense Motive
  - Sleight of Hand
  - Spellcraft
  - Stealth
  - Swim
  - Use Magic Device
skill_ranks_per_level: 4

bab_progression: mid
fort_progression: poor
ref_progression: good
will_progression: poor

spells_per_day: mid
spell_list: sorcerer/wizard

weapon_proficiencies:
  - Simple
  - hand crossbow
  - rapier
  - sap
  - short sword
  - shortbow
armor_proficiencies:
shield_proficiencies:

class_features:

  - name: spellcasting
    levels: [1]
    text: |
      An eldritch scoundrel casts arcane spells drawn from the wizard spell list. An eldritch scoundrel must choose and prepare her spells ahead of time. She learns, prepares, and casts spells exactly as a wizard does, including adding new spells to her spellbook and gaining two additional spells known (of any level she can cast) each time she gains a rogue level with this archetype.

      An eldritch scoundrel can cast only a certain number of spells of each spell level per day. Her base daily spell allotment is the same as the magus class.

  - name: finesse training
    type: Ex
    levels: [1, 3, 11, 19]
    levels_text:
      1: attack
      3: damage
      11: 2 weapon types
      19: 3 weapon types
    text: |
      At 1st level, a rogue gains Weapon Finesse as a bonus feat. In addition, starting at 3rd level, she can select any one type of weapon that can be used with Weapon Finesse (such as rapiers or daggers). Once this choice is made, it cannot be changed. Whenever she makes a successful melee attack with the selected weapon, she adds her Dexterity modifier instead of her Strength modifier to the damage roll. If any effect would prevent the rogue from adding her Strength modifier to the damage roll, she does not add her Dexterity modifier. The rogue can select a second weapon at 11th level and a third at 19th level.

  - name: sneak attack
    levels: [3, 7, 11, 15, 19]
    levels_text:
      3: +1d6
      7: +2d6
      11: +3d6
      15: +4d6
      19: +5d6
    text: |
      Starting at 3rd level, if a rogue can catch an opponent when he is unable to defend himself effectively from her attack, she can strike a vital spot for extra damage.

      The rogue's attack deals extra damage anytime her target would be denied a Dexterity bonus to AC (whether the target actually has a Dexterity bonus or not), or when the rogue flanks her target. This extra damage is 1d6 at 1st level, and increases by 1d6 every 2 rogue levels thereafter. Ranged attacks can count as sneak attacks only if the target is within 30 feet. This additional damage is precision damage and is not multiplied on a critical hit.

      With a weapon that deals nonlethal damage (such as a sap, unarmed strike, or whip), a rogue can make a sneak attack that deals nonlethal damage instead of lethal damage. She cannot use a weapon that deals lethal damage to deal nonlethal damage in a sneak attack—not even with the usual ---4 penalty.

      The rogue must be able to see the target well enough to pick out a vital spot and must be able to reach such a spot. A rogue cannot sneak attack while striking a creature with total concealment.

  - name: trapfinding
    levels: [1]
    text: A rogue adds 1/2 her level to Perception skill checks made to locate traps and to Disable Device skill checks (minimum +1). A rogue can use Disable Device to disarm magic traps.

  - name: evasion
    type: Ex
    levels: [2]
    text: At 2nd level, a rogue can avoid even magical and unusual attacks with great agility. If she succeeds at a Reflex saving throw against an attack that normally deals half damage on a successful save, she instead takes no damage. Evasion can be used only if the rogue is wearing light armor or no armor. A helpless rogue does not gain the benefit of evasion.

  - name: rogue talents
    levels: [4, 8]
    levels_text:
      4: 1 talent
      8: 2 talents
    text: |
      As a rogue gains experience, she learns a number of talents that aid her and confound her foes. Starting at 4th level, a rogue gains one unchained [rogue talent](/rogue-talents/). She gains an additional unchained rogue talent for every 4 levels of rogue attained after 4th level. A rogue cannot select an individual talent more than once.

      Only one of these talents that adds effects to the rogue's sneak attacks can be applied to an individual attack, and the decision must be made before the attack roll is made.

      A rogue cannot choose a ninja trick with the same name as a rogue talent.

  - name: alarm sense
    type: Su
    levels: [3]
    text: |
      At 3rd level, an eldritch scoundrel gains an intuitive sense that warns her when she is near a magic trap. This functions as the [trap spotter](/rogue-talents/trap-spotter/) rogue talent, but applies only if the eldritch scoundrel comes within 10 feet of a magic trap.

  - name: uncanny training
    levels: [4, 12]
    levels_text:
      4: uncanny dodge
      12: improved uncanny dodge
    text: Beginning at 4th level, the eldritch scoundrel can gain uncanny dodge instead of a rogue talent. Beginning at 12th level, the eldritch scoundrel can choose to gain improved uncanny dodge in place of an advanced talent.

  - name: debilitating injury
    type: Ex
    levels: [4]
    text: |
      At 4th level, whenever a rogue deals sneak attack damage to a foe, she can also debilitate the target of her attack, causing it to take a penalty for 1 round (this is in addition to any penalty caused by a rogue talent or other special ability). The rogue can choose to apply any one of the following penalties when the damage is dealt.

      - *Bewildered:* The target becomes bewildered, taking a --2 penalty to AC. The target takes an additional --2 penalty to AC against all attacks made by the rogue. At 10th level and 16th level, the penalty to AC against attacks made by the rogue increases by --2 (to a total maximum of --8).
      - *Disoriented:* The target takes a --2 penalty on attack rolls. In addition, the target takes an additional --2 penalty on all attack rolls it makes against the rogue. At 10th level and 16th level, the penalty on attack rolls made against the rogue increases by --2 (to a total maximum of --8).
      - *Hampered:* All of the target's speeds are reduced by half (to a minimum of 5 feet). In addition, the target cannot take a 5-foot step.

      These penalties do not stack with themselves, but additional attacks that deal sneak attack damage extend the duration by 1 round. A creature cannot suffer from more than one penalty from this ability at a time. If a new penalty is applied, the old penalty immediately ends. Any form of healing applied to a target suffering from one of these penalties also removes the penalty.

  - name: rogue's edge
    type: Ex
    levels: [5, 10, 15, 20]
    levels_text:
      5: 1 skill
      10: 2 skills
      15: 3 skills
      20: 4 skills
    text: |
      At 5th level, a rogue has mastered a single skill beyond that skill's normal boundaries, gaining results that others can only dream about. She gains the skill unlock powers for that skill as appropriate for her number of ranks in that skill. At 10th, 15th, and 20th levels, she chooses an additional skill and gains skill unlock powers for that skill as well.

  - name: advanced talents
    levels: [12, 16, 20]
    levels_text:
      12: 1 advanced talent
      16: 2 advanced talents
      20: 3 advanced talents
    text: |
      At 12th level and every 4 levels thereafter, a rogue can choose an unchained [rogue advanced talent](/rogue-advanced-talents/) in place of a rogue talent.

  - name: master strike
    type: Ex
    levels: [20]
    text: |
      At 20th level, an rogue becomes incredibly deadly when dealing sneak attack damage. Each time the rogue deals sneak attack damage, she can choose one of the following three effects: the target can be put to sleep for 1d4 hours, paralyzed for 2d6 rounds, or slain. Regardless of the effect chosen, the target can attempt a Fortitude save to negate the additional effect. The DC of this save is equal to 10 + 1/2 the rogue's level + the rogue's Dexterity modifier. Once a creature has been the target of a master strike, regardless of whether or not the save is successful, that creature is immune to that rogue's master strike for 24 hours. Creatures that are immune to sneak attack damage are also immune to this ability.

---

Life is an endless adventure for those who live by their wits. Ever just one step ahead of danger, rogues bank on their cunning, skill, and charm to bend fate to their favor. Never knowing what to expect, they prepare for everything, becoming masters of a wide variety of skills, training themselves to be adept manipulators, agile acrobats, shadowy stalkers, or masters of any of dozens of other professions or talents. Thieves and gamblers, fast talkers and diplomats, bandits and bounty hunters, and explorers and investigators all might be considered rogues, as well as countless other professions that rely upon wits, prowess, or luck. Although many rogues favor cities and the innumerable opportunities of civilization, some embrace lives on the road, journeying far, meeting exotic people, and facing fantastic danger in pursuit of equally fantastic riches. In the end, any who desire to shape their fates and live life on their own terms might come to be called rogues.

Students of arcane magic, legerdemain, and stealth, eldritch scoundrels are a rare breed of adventurer most commonly found seeking lost and valuable arcane writings in the ruins of fallen empires.

**Role:** Rogues excel at moving about unseen and catching foes unaware, and tend to avoid head-to-head combat. Their varied skills and abilities allow them to be highly versatile, with great variations in expertise existing between different rogues. Most, however, excel in overcoming hindrances of all types, from unlocking doors and disarming traps to outwitting magical hazards and conning dull-witted opponents.
