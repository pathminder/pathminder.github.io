---
title: Barbarian (Primal Disciple, Superstition)
sources:
  - Pathfinder Roleplaying Game Core Rulebook
  - "Path of War: Expanded"

max_level: 20
hit_die: 12
starting_wealth: 3d6 × 10 gp (average 105 gp)

class_skills:
  - Acrobatics
  - Climb
  - Craft
  - Handle Animal
  - Intimidate
  - Knowledge (nature)
  - Perception
  - Ride
  - Survival
  - Swim
skill_ranks_per_level: 4

weapon_proficiencies:
  - Simple
  - Martial
armor_proficiencies:
  - Light
  - Medium
shield_proficiencies:
  - Shields

bab_progression: full
fort_progression: good
ref_progression: poor
will_progression: poor

initiating_progression: partial

class_features:

  - name: ancestral style
    levels: [1, 6]
    levels_text:
      1: 1 feat
      6: 2 feats
    text: |
      Primal disciples draw their skill and strength from longstanding traditions of combat and skill in their tribes. At 1st level and again at 6th level, a primal disciple gains one of the following feats as a bonus feat: Enduring Protector, Martial Charge, Martial Power, Prodigious Two Weapon Fighting, Seize the Opportunity, or Victorious Recovery. She must meet the prerequisites for these feats as normal.

  - name: race
    type: Ex
    levels: [1]
    text: |
      A barbarian can call upon inner reserves of strength and ferocity, granting her additional combat prowess. Starting at 1st level, a barbarian can rage for a number of rounds per day equal to 4 + her Constitution modifier. At each level after 1st, she can rage for 2 additional rounds. Temporary increases to Constitution, such as those gained from rage and spells like bear's endurance, do not increase the total number of rounds that a barbarian can rage per day. A barbarian can enter rage as a free action. The total number of rounds of rage per day is renewed after resting for 8 hours, although these hours do not need to be consecutive.

      While in rage, a barbarian gains a +4 morale bonus to her Strength and Constitution, as well as a +2 morale bonus on Will saves. In addition, she takes a --2 penalty to Armor Class. The increase to Constitution grants the barbarian 2 hit points per Hit Dice, but these disappear when the rage ends and are not lost first like temporary hit points. While in rage, a barbarian cannot use any Charisma-, Dexterity-, or Intelligence-based skills (except Acrobatics, Fly, Intimidate, and Ride) or any ability that requires patience or concentration.

      A barbarian can end her rage as a free action and is fatigued after rage for a number of rounds equal to 2 times the number of rounds spent in the rage. A barbarian cannot enter a new rage while fatigued or exhausted but can otherwise enter rage multiple times during a single encounter or combat. If a barbarian falls unconscious, her rage immediately ends, placing her in peril of death.

  - name: maneuvers
    levels: [1]
    text: |
      A primal disciple begins her career with knowledge of three martial maneuvers. The disciplines available to her are Golden Lion, Piercing Thunder, Primal Fury, and Thrashing Dragon. A primal disciple gains Diplomacy as a class skill.

      Once the primal disciple knows a maneuver, she must ready it before she can use it (see Maneuvers Readied, below). A maneuver usable by primal disciples is considered an extraordinary ability unless otherwise noted in it or its discipline’s description. A primal disciple’s maneuvers are not affected by spell resistance, and she does not provoke attacks of opportunity when she initiates one.

      The primal disciple learns additional maneuvers at higher levels, as indicated on Table: The Barbarian. The maximum level of maneuvers gained through primal disciple levels is limited by those listed in that table as well, although this restriction does not apply to maneuvers added to his maneuvers known through other methods, such as prestige classes or the Advanced Study feat. A primal disciple must meet a maneuver’s prerequisite to learn it. See the Systems and Use chapter in Path of War for more details on how maneuvers are used.

      Upon reaching 4th level, and at every even numbered initiator level thereafter (6th, 8th, 10th, and so on), the primal disciple can choose to learn a new maneuver in place of one she already knows. In effect, she loses the old maneuver in exchange for the new one. She can choose a new maneuver of any level she likes, as long as she observes the restriction on the highest-level maneuvers she knows; the primal disciple need not replace the old maneuver with a maneuver of the same level. She can swap only a single maneuver at any given level. A primal disciple’s initiation modifier is Wisdom, and each primal disciple level is counted as a full initiator level.

      *Maneuvers Readied:* A primal disciple can ready all three of her maneuvers known at 1st level, and as she advances in level and learns more maneuvers, she is able to ready more, but must still choose which maneuvers to ready. A primal disciple must always ready her maximum number of maneuvers readied. She readies her maneuvers by practicing weapon drills or communing with her ancestors for ten minutes. The maneuvers she chooses remain readied until she decides to meditate again and change them. The primal disciple does not need to sleep or rest for any long period of time in order to ready her maneuvers; any time she spends ten minutes in communion with her ancestors, she can change her readied maneuvers.

      A primal disciple begins an encounter with all her readied maneuvers unexpended, regardless of how many times she might have already used them since she chose them. When she initiates a maneuver, she expends it for the current encounter, so each of her readied maneuvers can be used once per encounter (unless she recovers them, as described below).

      In order for the primal disciple to recover maneuvers, she must draw on the strength of her ancestors as a full- round action. When she does so, she recovers a number of expended maneuvers equal to her primal disciple initiation modifier (minimum 2), regains one round of rage, and if she is fatigued as a result of her rage class feature, she can make a Fortitude save (DC 10 + the number of rounds the fatigue would last). Alternately, the primal disciple may focus inward and recover a single maneuver as a standard action.

      *Stances Known:* A primal disciple begins play with knowledge of one stance from any discipline open to primal disciples. At 4th, 7th, 11th, and 13th levels, she can select an additional stance to learn. The maximum level of stances gained through primal disciple levels is limited by those listed in Table: The Barbarian. Unlike maneuvers, stances are not expended and the primal disciple does not have to ready them. All the stances she knows are available to her at all times, and she can change the stance she is currently maintaining as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance or discipline description.

      Unlike with maneuvers, a primal disciple cannot learn a new stance at higher levels in place of one she already knows.

  - name: superstition
    type: Ex
    levels: [2, 4, 8, 12, 16, 20]
    levels_text:
      2:  "+1"
      4:  "+2"
      8:  "+3"
      12: "+4"
      16: "+5"
      20: "+6"
    text: At 2nd level, the barbarian gains a +2 morale bonus on saving throws made to resist spells, supernatural abilities, and spell-like abilities. This bonus increases by +1 at 4th level and every 4 levels thereafter. While raging, the barbarian cannot be a willing target of any spell and must make saving throws to resist all spells, even those cast by allies.

  - name: uncanny dodge
    type: Ex
    levels: [2]
    text: |
      At 2nd level, a barbarian gains the ability to react to danger before her senses would normally allow her to do so. She cannot be caught flat-footed, nor does she lose her Dex bonus to AC if the attacker is invisible. She still loses her Dexterity bonus to armor class if immobilized. A barbarian with this ability can still lose her Dexterity bonus to armor class if an opponent successfully uses the feint action against her.

      If a barbarian already has uncanny dodge from a different class, she automatically gains improved uncanny dodge (see below) instead.

  - name: improved uncanny dodge
    type: Ex
    levels: [5]
    text: |
      At 5th level and higher, a barbarian can no longer be flanked. This defense denies a rogue the ability to sneak attack the barbarian by flanking her, unless the attacker has at least four more rogue levels than the target has barbarian levels.

      If a character already has uncanny dodge (see above) from another class, the levels from the classes that grant uncanny dodge stack to determine the minimum rogue level required to flank the character.

  - name: damage reduction
    type: Ex
    levels: [7, 10, 13, 16, 19]
    levels_text:
      7: 1
      10: 2
      13: 3
      16: 4
      19: 5
    text: At 7th level, a barbarian gains damage reduction. Subtract 1 from the damage the barbarian takes each time she is dealt damage from a weapon or a natural attack. At 10th level, and every three barbarian levels thereafter (13th, 16th, and 19th level), this damage reduction rises by 1 point. Damage reduction can reduce damage to 0 but not below 0.

  - name: greater rage
    type: Ex
    levels: [11]
    text: At 11th level, when a barbarian enters rage, the morale bonus to her Strength and Constitution increases to +6 and the morale bonus on her Will saves increases to +3.

  - name: indomitable will
    type: Ex
    levels: [14]
    text: While in rage, a barbarian of 14th level or higher gains a +4 bonus on Will saves to resist enchantment spells. This bonus stacks with all other modifiers, including the morale bonus on Will saves she also receives during her rage.

  - name: tireless rage
    type: Ex
    levels: [17]
    text: Starting at 17th level, a barbarian no longer becomes fatigued at the end of her rage.

  - name: mighty rage
    type: Ex
    levels: [20]
    text: At 20th level, when a barbarian enters rage, the morale bonus to her Strength and Constitution increases to +8 and the morale bonus on her Will saves increases to +4.
---
