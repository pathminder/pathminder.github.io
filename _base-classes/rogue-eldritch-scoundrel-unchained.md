---
title: Rogue (Eldritch Scoundrel)
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

      The rogue's attack deals extra damage anytime her target would be denied a Dexterity bonus to AC (whether the target actually has a Dexterity bonus or not), or when the rogue flanks her target. This extra damage is 1d6 at 3rd level, and increases by 1d6 every four rogue levels thereafter. Should the rogue score a critical hit with a sneak attack, this extra damage is not multiplied. Ranged attacks can count as sneak attacks only if the target is within 30 feet.

      With a weapon that deals nonlethal damage (like a sap, whip, or an unarmed strike), a rogue can make a sneak attack that deals nonlethal damage instead of lethal damage. She cannot use a weapon that deals lethal damage to deal nonlethal damage in a sneak attack, not even with the usual --4 penalty.

      The rogue must be able to see the target well enough to pick out a vital spot and must be able to reach such a spot. A rogue cannot sneak attack while striking a creature with concealment.

  - name: trapfinding
    levels: [1]
    text: A rogue adds 1/2 her level to Perception skill checks made to locate traps and to Disable Device skill checks (minimum +1). A rogue can use Disable Device to disarm magic traps.

  - name: evasion
    type: Ex
    text: At 2nd level and higher, a rogue can avoid even magical and unusual attacks with great agility. If she makes a successful Reflex saving throw against an attack that normally deals half damage on a successful save, she instead takes no damage. Evasion can be used only if the rogue is wearing light armor or no armor. A helpless rogue does not gain the benefit of evasion.

  - name: rogue talents
    levels: [4, 8]
    levels_text:
      4: 1 talent
      8: 2 talents
    text: |
      At 4th level and every 4 levels thereafter, the eldritch scoundrel gains a chained [rogue talent](/rogue-talents/) or ninja talent for which she meets the prerequisites (treating her rogue level as her ninja level). If a talent requires her to expend points from her ki pool, she can instead expend a spell slot with a spell level equal to the number of ki points she would normally expend. If a talent functions only if she has ki in her ki pool, it functions as long as she still has a spell of 1st level or higher prepared.

      Only one of these talents that adds effects to the rogue's sneak attacks can be applied to an individual attack, and the decision must be made before the attack roll is made.

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

  - name: advanced talents
    levels: [12, 16, 20]
    levels_text:
      12: 1 advanced talent
      16: 2 advanced talents
      20: 3 advanced talents
    text: At 12th level, and every four levels thereafter, a rogue can choose a chained [advanced rogue talent](/advanced-rogue-talents/) or advanced ninja talent in place of a rogue talent.

  - name: master strike
    type: Ex
    levels: [20]
    text: |
      Upon reaching 20th level, a rogue becomes incredibly deadly when dealing sneak attack damage. Each time the rogue deals sneak attack damage, she can choose one of the following three effects:

      The target can be...

      - put to sleep for 1d4 hours
      - paralyzed for 2d6 rounds, or
      - slain

      Regardless of the effect chosen, the target receives a Fortitude save to negate the additional effect. The DC of this save is equal to 10 + 1/2 the rogue's level + the rogue's Intelligence modifier. Once a creature has been the target of a master strike, regardless of whether or not the save is made, that creature is immune to that rogue's master strike for 24 hours. Creatures that are immune to sneak attack damage are also immune to this ability.

---
