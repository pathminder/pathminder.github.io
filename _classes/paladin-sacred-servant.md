---
title: Paladin (Sacred Servant)
sources:
  - Pathfinder Roleplaying Game Core Rulebook
  - "Pathfinder Roleplaying Game: Advanced Player's Guide"
max_level: 20
hit_die: 10
prerequisites:
  - Lawful Good
starting_wealth: 5d6 × 10 gp (average 175 gp)
class_skills:
   - Craft
   - Diplomacy
   - Handle Animal
   - Heal
   - Knowledge (nobility)
   - Knowledge (religion)
   - Profession
   - Ride
   - Sense Motive
   - Spellcraft

bab_multiplier: 1

fort_adder: 4
fort_multiplier: 0.5

ref_adder: 1
ref_multiplier: 0.3333

will_adder: 4
will_multiplier: 0.5

spells_per_day: paladin

weapon_proficiencies:
  - Simple
  - Martial
armor_proficiencies:
  - Light
  - Medium
  - Heavy
shield_proficiencies:
  - Shields

class_features:

  - name: code of conduct
    levels: [1]
    text: |
      A paladin must be of lawful good alignment and loses all class features except proficiencies if she ever willingly commits an evil act.

      Additionally, a paladin's code requires that she respect legitimate authority, act with honor (not lying, not cheating, not using poison, and so forth), help those in need (provided they do not use the help for evil or chaotic ends), and punish those who harm or threaten innocents.

      **Associates:** While she may adventure with good or neutral allies, a paladin avoids working with evil characters or with anyone who consistently offends her moral code. Under exceptional circumstances, a paladin can ally with evil associates, but only to defeat what she believes to be a greater evil. A paladin should seek an atonement spell periodically during such an unusual alliance, and should end the alliance immediately should she feel it is doing more harm than good. A paladin may accept only henchmen, followers, or cohorts who are lawful good.

  - name: ex-paladins
    levels: [1]
    text: |
      A paladin who ceases to be lawful good, who willfully commits an evil act, or who violates the code of conduct loses all paladin spells and class features (except weapon, armor, and shield proficiencies). She may not progress any further in levels as a paladin. She regains her abilities and advancement potential if she atones for her violations (see *atonement*), as appropriate.

  - name: aura of good
    type: Ex
    levels: [1]
    text: The power of a paladin's aura of good (see the *detect good* spell) is equal to her paladin level.

  - name: detect evil
    type: Sp
    levels: [1]
    text: At will, a paladin can use *detect evil*, as the spell. A paladin can, as a move action, concentrate on a single item or individual within 60 feet and determine if it is evil, learning the strength of its aura as if having studied it for 3 rounds. While focusing on one individual or object, the paladin does not detect evil in any other object or individual within range.

  - name: smite evil
    type: Su
    levels: [1, 7, 10, 13, 16, 19]
    levels_text:
      1: 1/day
      7: 2/day
      10: 3/day
      13: 4/day
      16: 5/day
      19: 6/day
    text: |
      Once per day, a paladin can call out to the powers of good to aid her in her struggle against evil. As a swift action, the paladin chooses one target within sight to smite. If this target is evil, the paladin adds her Cha bonus (if any) to her attack rolls and adds her paladin level to all damage rolls made against the target of her smite. If the target of smite evil is an outsider with the evil subtype, an evil-aligned dragon, or an undead creature, the bonus to damage on the first successful attack increases to 2 points of damage per level the paladin possesses. Regardless of the target, smite evil attacks automatically bypass any DR the creature might possess.

      In addition, while smite evil is in effect, the paladin gains a deflection bonus equal to her Charisma modifier (if any) to her AC against attacks made by the target of the smite. If the paladin targets a creature that is not evil, the smite is wasted with no effect.

      The smite evil effect remains until the target of the smite is dead or the next time the paladin rests and regains her uses of this ability. At 7th level, and at every three levels thereafter, the paladin may smite evil one additional time per day, to a maximum of six times per day at 19th level.

  - name: divine grace
    type: Su
    levels: [2]
    text: At 2nd level, a paladin gains a bonus equal to her Charisma bonus (if any) on all saving throws.

  - name: lay on hands
    type: Su
    levels: [2]
    text: |
      Beginning at 2nd level, a paladin can heal wounds (her own or those of others) by touch. Each day she can use this ability a number of times equal to 1/2 her paladin level plus her Charisma modifier. With one use of this ability, a paladin can heal 1d6 hit points of damage for every two paladin levels she possesses. Using this ability is a standard action, unless the paladin targets herself, in which case it is a swift action. Despite the name of this ability, a paladin only needs one free hand to use this ability.

      Alternatively, a paladin can use this healing power to deal damage to undead creatures, dealing 1d6 points of damage for every two levels the paladin possesses. Using lay on hands in this way requires a successful melee touch attack and doesn't provoke an attack of opportunity. Undead do not receive a saving throw against this damage.

  - name: aura of courage
    type: Su
    levels: [3]
    text: At 3rd level, a paladin is immune to fear (magical or otherwise). Each ally within 10 feet of her gains a +4 morale bonus on saving throws against fear effects. This ability functions only while the paladin is conscious, not if she is unconscious or dead.

  - name: divine health
    type: Ex
    levels: [3]
    text: At 3rd level, a paladin is immune to all diseases, including supernatural and magical diseases, including mummy rot.

  - name: mercy
    type: Su
    levels: [3, 6, 9, 12, 15, 18]
    text: |
      At 3rd level, and every three levels thereafter, a paladin can select one mercy. Each mercy adds an effect to the paladin's lay on hands ability. Whenever the paladin uses lay on hands to heal damage to one target, the target also receives the additional effects from all of the mercies possessed by the paladin. A mercy can remove a condition caused by a curse, disease, or poison without curing the affliction. Such conditions return after 1 hour unless the mercy actually removes the affliction that causes the condition.

      At 3rd level, the paladin can select from the following initial mercies.

      - *Fatigued:* The target is no longer fatigued.
      - *Shaken:* The target is no longer shaken.
      - *Sickened:* The target is no longer sickened.

      At 6th level, a paladin adds the following mercies to the list of those that can be selected.

      - *Dazed:* The target is no longer dazed.
      - *Diseased:* The paladin's lay on hands ability also acts as remove disease, using the paladin's level as the caster level.
      - *Staggered:* The target is no longer staggered, unless the target is at exactly 0 hit points.

      At 9th level, a paladin adds the following mercies to the list of those that can be selected.

      - *Cursed:* The paladin's lay on hands ability also acts as remove curse, using the paladin's level as the caster level.
      - *Exhausted:* The target is no longer exhausted. The paladin must have the fatigue mercy before selecting this mercy.
      - *Frightened:* The target is no longer frightened. The paladin must have the shaken mercy before selecting this mercy.
      - *Nauseated:* The target is no longer nauseated. The paladin must have the sickened mercy before selecting this mercy.
      - *Poisoned:* The paladin's lay on hands ability also acts as neutralize poison, using the paladin's level as the caster level.

      At 12th level, a paladin adds the following mercies to the list of those that can be selected.

      - *Blinded:* The target is no longer blinded.
      - *Deafened:* The target is no longer deafened.
      - *Paralyzed:* The target is no longer paralyzed.
      - *Stunned:* The target is no longer stunned.

      These abilities are cumulative. For example, a 12th-level paladin's lay on hands ability heals 6d6 points of damage and might also cure Fatigued and Exhausted conditions as well as removing diseases and neutralizing poisons. Once a condition or spell effect is chosen, it can't be changed.

  - name: channel positive energy
    type: Su
    levels: [4]
    text: When a paladin reaches 4th level, she gains the supernatural ability to channel positive energy like a cleric. Using this ability consumes two uses of her lay on hands ability. A paladin uses her level as her effective cleric level when channeling positive energy. This is a Charisma-based ability.

  - name: spells
    levels: [4]
    text: |
      Beginning at 4th level, a paladin gains the ability to cast a small number of divine spells which are drawn from the paladin spell list. A paladin must choose and prepare her spells in advance.

      To prepare or cast a spell, a paladin must have a Charisma score equal to at least 10 + the spell level. The Difficulty Class for a saving throw against a paladin's spell is 10 + the spell level + the paladin's Charisma modifier.

      Like other spellcasters, a paladin can cast only a certain number of spells of each spell level per day. Her base daily spell allotment is given on Table: Paladin. In addition, she receives bonus spells per day if she has a high Charisma score (see Table: Ability Modifiers and Bonus Spells). When Table: Paladin indicates that the paladin gets 0 spells per day of a given spell level, she gains only the bonus spells she would be entitled to based on her Charisma score for that spell level.

      A paladin must spend 1 hour each day in quiet prayer and meditation to regain her daily allotment of spells. A paladin may prepare and cast any spell on the paladin spell list, provided that she can cast spells of that level, but she must choose which spells to prepare during her daily meditation.

      Through 3rd level, a paladin has no caster level. At 4th level and higher, her caster level is equal to her paladin level --3.

      The paladin also chooses one domain associated with her deity. Her effective cleric level for this domain is equal to her paladin level --3. In addition, she also gains one domain spell slot for each level of paladin spells she can cast. Every day she must prepare the domain spell from her chosen domain in that spell slot.

  - name: divine bond
    type: Su
    levels: [5, 8, 11, 14, 17, 20]
    levels_text:
      5: 1/day
      8: 2/day
      11: 3/day
      14: 4/day
      17: 5/day
      20: 6/day
    text: |
      At 5th level, a sacred servant forms a bond with her holy symbol.

      As a standard action, a sacred servant can bind a celestial spirit to her holy symbol for 1 minute per paladin level. When called, the spirit causes the sacred servant’s holy symbol to shed light like a torch.

      At 5th level, the spirit grants one bonus. For every three levels beyond 5th, the spirit grants one additional bonus. These bonuses can be spent in a number of ways to grant the paladin enhanced abilities to channel positive energy and to cast spells.

      Each bonus can be used to grant one of the following enhancements:

      - +1 caster level to any paladin spell cast
      - +1 to the DC to halve the damage of channel positive energy when used to harm undead
      - +1d6 to channel positive energy
      - +1 use/day of lay on hands

      These enhancements stack and can be selected multiple times. The enhancements granted by the spirit are determined when the spirit is called and cannot be changed until the spirit is called again. If the sacred servant increases her number of uses of lay on hands per day in this way, that choice is set for the rest of the day, and once used, these additional uses are not restored (even if the spirit is called again that day). The celestial spirit imparts no enhancements if the holy symbol is held by anyone other than the sacred servant, but resumes giving enhancements if returned to the sacred servant. A sacred servant can use this ability once per day at 5th level, and one additional time per day for every four levels beyond 5th, to a total of four times per day at 17th level.

      If a holy symbol with a celestial spirit is destroyed, the sacred servant loses the use of this ability for 30 days, or until she gains a level, whichever comes first. During this 30-day period, the sacred servant takes a --1 penalty on attack and weapon damage rolls.

  - name: call celestial ally
    type: Sp
    levels: [8, 12, 16]
    levels_text:
      8: "*lesser planar ally*"
      12: "*planar ally*"
      16: "*greater planar ally*"
    text: |
      At 8th level, a sacred servant can call upon her deity for aid, in the form of a powerful servant. This allows the sacred servant to cast lesser planar ally once per week as a spell-like ability without having to pay the material component cost or the servant (for reasonable tasks). At 12th level, this improves to planar ally and at 16th level, this improves to greater planar ally. The sacred servant’s caster level for this effect is equal to her paladin level.

  - name: aura of justice
    type: Su
    levels: [11]
    text: At 11th level, a paladin can expend two uses of her smite evil ability to grant the ability to smite evil to all allies within 10 feet, using her bonuses. Allies must use this smite evil ability by the start of the paladin's next turn and the bonuses last for 1 minute. Using this ability is a free action. Evil creatures gain no benefit from this ability.

  - name: aura of faith
    type: Su
    levels: [14]
    text: |
      At 14th level, a paladin's weapons are treated as good-aligned for the purposes of overcoming Damage Reduction. Any attack made against an enemy within 10 feet of her is treated as good-aligned for the purposes of overcoming Damage Reduction.

      This ability functions only while the paladin is conscious, not if she is unconscious or dead.

  - name: aura of righteousness
    type: Su
    levels: [17]
    text: |
      At 17th level, a paladin gains DR 5/evil and immunity to compulsion spells and spell-like abilities. Each ally within 10 feet of her gains a +4 morale bonus on saving throws against compulsion effects.

      This ability functions only while the paladin is conscious, not if she is unconscious or dead.

  - name: holy champion
    type: Su
    levels: [20]
    text: At 20th level, a paladin becomes a conduit for the power of her god. Her DR increases to 10/evil. Whenever she uses smite evil and successfully strikes an evil outsider, the outsider is also subject to a banishment, using her paladin level as the caster level (her weapon and holy symbol automatically count as objects that the subject hates). After the banishment effect and the damage from the attack is resolved, the smite immediately ends. In addition, whenever she channels positive energy or uses lay on hands to heal a creature, she heals the maximum possible amount.
---

Through a select, worthy few shines the power of the divine. Called paladins, these noble souls dedicate their swords and lives to the battle against evil. Knights, crusaders, and law-bringers, paladins seek not just to spread divine justice but to embody the teachings of the virtuous deities they serve. In pursuit of their lofty goals, they adhere to ironclad laws of morality and discipline. As reward for their righteousness, these holy champions are blessed with boons to aid them in their quests: powers to banish evil, heal the innocent, and inspire the faithful. Although their convictions might lead them into conflict with the very souls they would save, paladins weather endless challenges of faith and dark temptations, risking their lives to do right and fighting to bring about a brighter future.

**Role:** Paladins serve as beacons for their allies within the chaos of battle. While deadly opponents of evil, they can also empower goodly souls to aid in their crusades. Their magic and martial skills also make them well suited to defending others and blessing the fallen with the strength to continue fighting.
