---
title: Bard (Archeologist)
sources:
  - Pathfinder Roleplaying Game Core Rulebook
  - Pathfinder Roleplaying Game Ultimate Combat

tags:
  - Arcane

max_level: 20
hit_die: 8

class_skills:
  - Acrobatics
  - Appraise
  - Bluff
  - Climb
  - Craft
  - Diplomacy
  - Disguise
  - Escape Artist
  - Intimidate
  - Knowledge
  - Linguistics
  - Perception
  - Perform
  - Profession
  - Sense Motive
  - Sleight of Hand
  - Spellcraft
  - Stealth
  - Use Magic Device
skill_ranks_per_level: 6

bab_progression: mid
fort_progression: poor
ref_progression: good
will_progression: good

spells_per_day: mid
spells_known: mid
spell_list: bard
spell_list_levels: 6

weapon_proficiencies:
  - Simple
  - longsword
  - rapier
  - sap
  - shortsword
  - shortbow
  - whip
armor_proficiencies:
  - Light
shield_proficiencies:
  - Shields

class_features:

  - name: spells
    levels: [1]
    text: |
      A bard casts arcane spells drawn from the bard spell list. He can cast any spell he knows without preparing it ahead of time. Every bard spell has a verbal component (singing, reciting, or music). To learn or cast a spell, a bard must have a Charisma score equal to at least 10 + the spell level. The Difficulty Class (DC) for a saving throw against a bard's spell is 10 + the spell level + the bard's Charisma modifier.

      Like other spellcasters, a bard can cast only a certain number of spells of each spell level per day. His base daily spell allotment is given on Table: The Bard. In addition, he receives bonus spells per day if he has a high Charisma score.

      The bard's selection of spells is extremely limited. A bard begins play knowing four 0-level spells and two 1st-level spells of the bard's choice. At each new bard level, he gains one or more new spells, as indicated on Table: Bard Spells Known. (Unlike spells per day, the number of spells a bard knows is not affected by his Charisma score.)

      Upon reaching 5th level, and at every third bard level after that (8th, 11th, and so on), a bard can choose to learn a new spell in place of one he already knows. In effect, the bard “loses” the old spell in exchange for the new one. The new spell's level must be the same as that of the spell being exchanged, and it must be at least one level lower than the highest-level bard spell the bard can cast. A bard may swap only a single spell at any given level, and must choose whether or not to swap the spell at the same time that he gains new spells known for the level.

      A bard need not prepare his spells in advance. He can cast any spell he knows at any time, assuming he has not yet used up his allotment of spells per day for the spell's level.

      A bard can cast bard spells while wearing light armor and using a shield without incurring the normal arcane spell failure chance. Like any other arcane spellcaster, a bard wearing medium or heavy armor incurs a chance of arcane spell failure if the spell in question has a somatic component. A multiclass bard still incurs the normal arcane spell failure chance for arcane spells received from other classes.

  - name: bardic knowledge
    type: Ex
    levels: [1, 4, 6, 8, 10, 12, 14, 16, 18, 20]
    levels_text:
      1:  "+1"
      4:  "+2"
      6:  "+3"
      8:  "+4"
      10: "+5"
      12: "+6"
      14: "+7"
      16: "+8"
      18: "+9"
      20: "+10"
    text: A bard adds half his class level (minimum 1) to all Knowledge skill checks and may make all Knowledge skill checks untrained.

  - name: archaeologist's luck
    type: Ex
    levels: [1, 5, 11, 17]
    levels_text:
      1: "+1"
      5: "+2"
      11: "+3"
      17: "+4"
    text: Fortune favors the archaeologist. As a swift action, an archaeologist can call on fortune's favor, giving him a +1 luck bonus on attack rolls, saving throws, skill checks, and weapon damage rolls. He can use this ability for a number of rounds per day equal to 4 + his Charisma modifier. Maintaining this bonus is a free action, but it ends immediately if the archaeologist is killed, paralyzed, stunned, knocked unconscious, or otherwise prevented from taking a free action to maintain it each round. Archaeologist's luck is treated as bardic performance for the purposes of feats, abilities, effects, and the like that affect bardic performance. Like bardic performance, it cannot be maintained at the same time as other performance abilities. This bonus increases to +2 at 5th level, +3 at 11th level, and +4 at 17th level.

  - name: cantrips
    type: Sp
    levels: [1]
    text: |
      Bard's learn a number of cantrips, or 0-level spells, as noted on Table: Bard Spells Known under "Spells Known." These spells are cast like any other spell, but they do not consume any slots and may be used again.

  - name: clever explorer
    type: Ex
    levels: [2, 6]
    levels_text:
      6: take 10
    text: At 2nd level, an archaeologist gains a bonus equal to half his class level on Disable Device and Perception checks. He can disable intricate and complex devices in half the normal amount of time (minimum 1 round) and open a lock as a standard action. At 6th level, an archaeologist can take 10 on Disable Device checks, even if distracted or endangered, and can disarm magical traps.

  - name: uncanny dodge
    type: Ex
    levels: [2]
    text: |
      At 2nd level, an archaeologist can react to danger before her senses would normally allow her to do so. She cannot be caught flat-footed, nor does she lose her Dex bonus to AC if the attacker is invisible. She still loses her Dexterity bonus to AC if immobilized. An archaeologist with this ability can still lose her Dexterity bonus to AC if an opponent successfully uses the feint action against her.

      If the archaeologist already has uncanny dodge from a different class, she automatically gains improved uncanny dodge (as the rogue ability) instead.

  - name: trap sense
    type: Ex
    levels: [3, 6, 9, 12, 15, 18]
    levels_text:
      3: +1
      6: +2
      9: +3
      12: +4
      15: +5
      18: +6
    text: At 3rd level, an archaeologist gains an intuitive sense that alerts her to danger from traps, giving her a +1 bonus on Reflex saves made to avoid traps and a +1 dodge bonus to AC against attacks made by traps. This bonus improves by +1 for every three levels gained after 3rd, to a maximum of +6 at 18th level. Trap sense bonuses gained from multiple classes stack.

  - name: rogue talent
    levels: [4, 8]
    levels_text:
      4: 1 talent
      8: 2 talents
    text: |
      At 4th level, an archaeologist gains a chained [rogue talent](/rogue-talents/). He gains an additional rogue talent for every four levels of archaeologist gained after 4th level. An archaeologist cannot select an individual talent more than once.

      Only one of these talents that adds effects to the rogue's sneak attacks can be applied to an individual attack, and the decision must be made before the attack roll is made.

      An archaeologist can't choose a ninja trick with the same name as a rogue talent.

  - name: lore master
    type: Ex
    levels: [5, 11, 17]
    levels_text:
      5: 1/day
      11: 2/day
      17: 3/day
    text: At 5th level, the bard becomes a master of lore and can take 10 on any Knowledge skill check that he has ranks in. A bard can choose not to take 10 and can instead roll normally. In addition, once per day, the bard can take 20 on any Knowledge skill check as a standard action. He can use this ability one additional time per day for every six levels he possesses beyond 5th, to a maximum of three times per day at 17th level.

  - name: evasion
    type: Ex
    levels: [6]
    text: At 6th level, an archaeologist can avoid even magical and unusual attacks with great agility. If she makes a successful Reflex saving throw against an attack that normally deals half damage on a successful save, she instead takes no damage. Evasion can be used only if the archaeologist is wearing light armor or no armor. A helpless archaeologist does not gain the benefit of evasion.

  - name: jack of all trades
    type: Ex
    levels: [10, 16, 19]
    levels_text:
      10: untrained
      16: class skills
      19: take 10
    text: At 10th level, the bard can use any skill, even if the skill normally requires him to be trained. At 16th level, the bard considers all skills to be class skills. At 19th level, the bard can take 10 on any skill check, even if it is not normally allowed.

  - name: advanced talent
    levels: [12, 16, 20]
    levels_text:
      12: 1 advanced talent
      16: 2 advanced talents
      20: 3 advanced talents
    text: At 12th level, and every four levels thereafter, an archaeologist can choose a chained [advanced rogue talent](/advanced-rogue-talents/) in place of a rogue talent.

---

Untold wonders and secrets exist for those skillful enough to discover them. Through cleverness, talent, and magic, these cunning few unravel the wiles of the world, becoming adept in the arts of persuasion, manipulation, and inspiration. Typically masters of one or many forms of artistry, bards possess an uncanny ability to know more than they should and use what they learn to keep themselves and their allies ever one step ahead of danger. Bards are quick-witted and captivating, and their skills might lead them down many paths, be they gamblers or jacks-of-all-trades, scholars or performers, leaders or scoundrels, or even all of the above. For bards, every day brings its own opportunities, adventures, and challenges, and only by bucking the odds, knowing the most, and being the best might they claim the treasures of each.

No stodgy researcher, this archaeologist meets his research head-on in the field. Archaeologists sacrifice the bard's inspirational performance for a smattering of rogue talents.

**Role:** Bards capably confuse and confound their foes while inspiring their allies to ever-greater daring. While accomplished with both weapons and magic, the true strength of bards lies outside melee, where they can support their companions and undermine their foes without fear of interruptions to their performances.
