---
title: Soulknife (High Psionics)
sources:
  - Ultimate Psionics
  - "Psionics Augmented: Soulknives"
tags:
  - Psionic

max_level: 20
prerequisites:
hit_die: 10
starting_wealth: ???
class_skills:
  - Acrobatics
  - Autohypnosis
  - Climb
  - Craft
  - Intimidate
  - Knowledge (psionics)
  - Perception
  - Profession
  - Stealth
  - Swim
skill_ranks_per_level: 4

bab_progression: full
fort_progression: poor
ref_progression: good
will_progression: good

manifesting_progression: soulknife

weapon_proficiencies:
  - Simple
  - mind blade
armor_proficiencies:
  - Light
  - Medium
shield_proficiencies:
  - Shields

class_features:

  - name: bonus feat
    levels: [1]
    text: The soulknife may choose Power Attack, Two-Weapon Fighting, or Weapon Focus (mind blade) as a bonus feat at 1st level.

  - name: form mind blade
    type: Su
    levels: [1]
    text: |
      As a move action, a soulknife can form a semi-solid weapon composed of psychic energy distilled from his own mind.

      A soulknife must choose the form of his mind blade at 1st level. He can either form it into a light weapon, a one-handed weapon, or a two-handed weapon. Once chosen, his mind blade stays in this form every time the soulknife forms his mind blade. The light weapon deals 1d6 points of damage, the one-handed weapon deals 1d8 points of damage, and the two-handed weapon deals 2d6 points of damage. All damages are based on a Medium- sized creature wielding Medium-sized weapons; adjust the weapon damage as appropriate for different sized weapons. In all forms, the mind blade has a critical range of 19-20/x2. A soulknife with powerful build or any similar ability forms an appropriately-sized mind blade dealing the size-appropriate amount of damage.

      If the soulknife's chosen form is a light weapon, he may choose to form two light weapons when forming his mind blade if he so chooses, but he suffers the standard penalties for two-weapon fighting.

      Regardless of the weapon form a soulknife has chosen, his mind blade does not have a set damage type. When shaping his weapon and assigning abilities to it, the soulknife chooses whether it will deal bludgeoning, piercing, or slashing damage. The soulknife may change the damage type of an existing mind blade, or may summon a new mind blade with a different damage type, as a full-round action; otherwise, the mind blade retains the last damage type chosen every time it is summoned.

      The blade can be broken (it has hardness 10 and 10 hit points); however, a soulknife can simply create another on his next move action. The moment he relinquishes his grip on his blade, it dissipates (unless he intends to throw it; see below). A mind blade is considered a magic weapon for the purpose of overcoming damage reduction and is considered a masterwork weapon.

      A soulknife can use feats such as Power Attack or Combat Expertise in conjunction with the mind blade just as if it were a normal weapon. He can also choose his mind blade for feats requiring a specific weapon choice, such as Weapon Focus and Improved Critical. Powers or spells that upgrade weapons can be used on a mind blade. The soulknife can use feats such as Weapon Finesse that work on light weapons with his mind blade, but such feats only work on mind blades in a light weapon form.

      Even in places where psionic effects do not normally function (such as within a null psionics field), a soulknife can attempt to sustain his mind blade by making a DC 20 Will save. On a successful save, the soulknife maintains his mind blade for a number of rounds equal to his class level before he needs to check again, although the mind blade is treated for all purposes as a non-magical, masterwork weapon while in a place where psionic effects do not normally function. On an unsuccessful attempt, the mind blade vanishes.

      As a move action on her turn, the soulknife can attempt a new Will save to rematerialize his mind blade while he remains within the psionics-negating effect. He gains a bonus on Will saves made to maintain or form his mind blade equal to the total enhancement bonus of his mind blade (see below).

      The soulknife chooses the appearance of his mind blade, although its shape must reflect the selections the soulknife has chosen: a bludgeoning mind blade would be blunt, slashing would have an edge, etc.

  - name: shape mind blade
    levels: [1]
    text: |
      The soulknife's mind blade retains the last chosen form every time it is formed until the soulknife reshapes it. If the soulknife chooses to reshape his blade, it requires a full-round action to do so. She may also re-assign the type of damage dealt as part of reshaping his mind blade if he so chooses.

      A soulknife can reassign the ability or abilities he has added to his mind blade; see below. To do so, he must first spend 8 hours in concentration. These cannot be the normal 8 hours used for rest, even if the soulknife does not require sleep. After that period, the mind blade materializes with the new ability or abilities selected by the soulknife.

  - name: throw mind blade
    levels: [1]
    text: |
      All soulknives have some knowledge of how to throw their mind blades, though the range increment varies by form and the largest of blade forms cannot be thrown. Light weapon mind blades have a range increment of 20 ft. One-handed weapon mind blades have a range increment of 15 ft. Two-handed weapon mind blades cannot be thrown without the Two-Handed Throw blade skill. Whether or not the attack hits, a thrown mind blade then dissipates.

  - name: wild talent
    levels: [1]
    text: |
      The soulknife gains Wild Talent as a bonus feat at 1st level. This provides his with the psionic power necessary to manifest his mind blade. A character who is already psionic instead gains the Psionic Talent feat.

  - name: blade skills
    levels: [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]
    levels_text:
      2: 1 blade skill
      4: 2 blade skills
      6: 3 blade skills
      8: 4 blade skills
      10: 5 blade skills
      12: 6 blade skills
      14: 7 blade skills
      16: 8 blade skills
      18: 9 blade skills
      20: 10 blade skills
    text: |
      Beginning at 2nd level and every even soulknife level thereafter, a soulknife may choose a [blade skill](/blade-skills/) to add to his repertoire. Some blade skills have prerequisites that must be met before they can be chosen. All blade skills may only be chosen once and require the soulknife to be using his mind blade unless otherwise stated in the skill's description.

  - name: enhanced mind blade
    levels: [3, 5, 7, 9, 11, 13, 15, 17, 19]
    levels_text:
      3: +1, max +1
      5: +2, max +1
      7: +3, max +2
      9: +4, max +3
      11: +5, max +3
      13: +6, max +4
      15: +7, max +5
      17: +8, max +5
      19: +9, max +5
    text: |
      A soulknife's mind blade improves as the character gains higher levels. At 3rd level and every odd level thereafter, the mind blade gains a cumulative +1 enhancement bonus that he may spend on an actual enhancement bonus or on weapon special abilities. A soulknife's level determines his maximum enhancement bonus (see Table: The Soulknife). The soulknife may (and must, when his total enhancement is higher than his maximum bonus) apply any special ability from the table below instead of an enhancement bonus, as long as he meets the level requirements. A soulknife can choose any combination of weapon special abilities and/or enhancement bonus that does not exceed the total allowed by the soulknife's level, but he must assign at least a +1 enhancement bonus before assigning any special abilities.

      If the soulknife shapes his mind blade into two items, the enhancement bonus of his mind blade (if any) is reduced by 1 (to a minimum of 0). If this would reduce the enhancement bonus on the mind blades to 0 and weapon special abilities are applied, the soulknife must reshape his mind blade to make the options valid. Both mind blades have the same selection of enhancement bonus and weapon special abilities (if any). This penalty does not apply when using the Mind Shield blade skill.

      | Weapon Special Ability                 | Enhancement Bonus Value | Required Level |
      |:---------------------------------------|:-----------------------:|:--------------:|
      | Agile                                  |           +1            |       5        |
      | Allying                                |           +1            |       5        |
      | Conductive                             |           +1            |       5        |
      | Corrosive                              |           +1            |       5        |
      | Cunning                                |           +1            |       5        |
      | Defending                              |           +1            |       5        |
      | Distance                               |           +1            |       5        |
      | Dueling                                |           +1            |       5        |
      | Flaming                                |           +1            |       5        |
      | Frost                                  |           +1            |       5        |
      | Furious                                |           +1            |       5        |
      | Ghost touch                            |           +1            |       5        |
      | Huntsman                               |           +1            |       5        |
      | Keen (works regardless of damage type) |           +1            |       5        |
      | Lucky                                  |           +1            |       5        |
      | Menacing                               |           +1            |       5        |
      | Merciful                               |           +1            |       5        |
      | Mighty cleaving                        |           +1            |       5        |
      | Psychokinetic                          |           +1            |       5        |
      | Seeking (ranged only)                  |           +1            |       5        |
      | Shock Sundering                        |           +1            |       5        |
      | Vicious                                |           +1            |       5        |
      | Anarchic                               |           +2            |       7        |
      | Axiomatic                              |           +2            |       7        |
      | Collision                              |           +2            |       7        |
      | Corrosive burst                        |           +2            |       7        |
      | Flaming burst                          |           +2            |       7        |
      | Holy                                   |           +2            |       7        |
      | Icy burst                              |           +2            |       7        |
      | Linked striking                        |           +2            |       7        |
      | Mindcrusher                            |           +2            |       7        |
      | Psychokinetic burst                    |           +2            |       7        |
      | Shocking burst                         |           +2            |       7        |
      | Suppression                            |           +2            |       7        |
      | Unholy                                 |           +2            |       7        |
      | Wounding                               |           +2            |       7        |
      | Wrenching (ranged only)                |           +2            |       7        |
      | Bodyfeeder                             |           +3            |       9        |
      | Dislocator                             |           +3            |       9        |
      | Mindfeeder                             |           +3            |       9        |
      | Soulbreaker                            |           +3            |       9        |
      | Brilliant energy                       |           +4            |       12       |
      | Great dislocator                       |           +4            |       12       |
      | Greater energy (ranged only)           |           +4            |       12       |
      | Coup de grace                          |           +5            |       15       |

  - name: manifesting
    levels: [3]
    text: |
      At 3rd level, the soulknife gains the ability to manifest a small number of psionic powers, which are drawn from the soulknife power list.

      A soulknife chooses his powers from the soulknife power list. At 3rd level, a soulknife knows one soulknife power of your choice. He learns new powers as indicated on Table: The Soulknife. Asoulknife can manifest any power that has a power point cost equal to or lower than his manifester level. The total number of powers a soulknife can manifest per day is limited only by his daily power points.

      A soulknife never needs to prepare powers ahead of time; he draws them from his mind when needed. When a soulknife recovers his daily power points after resting, he may choose to rotate one or more powers he knows for new ones. These powers must always be chosen from the soulknife power list, and the maximum number of powers the soulknife may know at any one time in this fashion is listed on Table: The Gifted Blade. If a soulknife learns a power through other means, such as the Expanded Knowledge feat, the Mental Power blade skill, or psychic chirurgery, this power is known in addition to his normal powers. He may never exchange it for another power from the soulknife list when he chooses his powers known, and it doesn't count against his limit of powers known at any one time.

      The Difficulty Class for saving throws against soulknife powers is 10 + the power's level + the soulknife's Wisdom modifier.

      Through 2nd level, a soulknife has no manifester level. At 3rd level and higher, a soulknife's manifester level is equal to his soulknife level --2.

      A soulknife gains the ability to learn 1st-level powers at 3rd level. Every four levels thereafter (7th, 11th, etc), a soulknife gains the ability to master more complex powers, up to 4th level powers at level 15.

      To learn or manifest a power, a soulknife must have a Wisdom score of at least 10 + the power's level.

      A soulknife's ability to manifest powers is limited by the power points he has available. His base daily allotment of power points is given on Table: Soulknife. In addition, he receives bonus power points per day if he has a high Wisdom score. His race may also provide bonus power points per day, as may certain feats and items. If a soulknife has power points from a different class, those points are pooled together and usable to manifest powers from either class.

  - name: psychic strike
    type: Su
    levels: [3, 7, 11, 15, 19]
    levels_text:
      3: +1d8
      7: +2d8
      11: +3d8
      15: +4d8
      19: +5d8
    text: |
      As a move action, a soulknife of 3rd level or higher can imbue his mind blade with until he chooses to use it, and the charge is not wasted if an attack misses. Mindless creatures are immune to this damage, although non-mindless creatures immune to mind-affecting effects are affected by this damage as normal. (Unlike the rogue's sneak attack, the psychic strike is not precision damage and can affect creatures otherwise immune to extra damage from critical hits or more than 30 feet away.)

      A mind blade deals this extra damage only once when this ability is called upon, but a soulknife can imbue his mind blade with psychic energy again by taking another move action. Additionally, he may recharge it as a swift action by expending his psionic focus.

      Once a soulknife has prepared his blade for a psychic strike, it holds the extra energy until it is used (whether the attack is successful or not). Even if the soulknife drops the mind blade (or it otherwise dissipates, such as when it is thrown), it is still imbued with psychic energy when the soulknife next materializes it.

      If the soulknife forms his mind blade into two weapons, he may imbue each mind blade with psychic strike as normal. If he reshapes his mind blade into a single weapon form, the additional psychic strike imbued into the additional weapon is lost.

      At every four levels thereafter (7th, 11th, etc), the extra damage from a soulknife's psychic strike increases by 1d8.

  - name: quick draw
    levels: [5]
    text: A 5th level soulknife may manifest his mind blade as a free action, though he may still only attempt to do so once per round (unless throwing the weapon multiple times using the Multiple Throw blade skill).

  - name: mind blade mastery
    levels: [20]
    text: At 20th level, a soulknife reaches the pinnacle of his art and his connection to his blade is so strong it cannot be severed. She no longer requires a Will save to maintain his mind blade in a null psionics field, although it still loses any enhancement bonus and special abilities. In addition, he may change the configurations of his mind blade's special abilities at will as a full-round action, which also resets any penalties that may have accrued from the Fluid Form and Improved Fluid Form blade skills.
---

Never caught unarmed, the soulknife is the literal interpretation of using the power of the mind as a weapon. Creating a mind blade is the core of the soulknife, and with it, he is a deadly combatant. Versatile and varied, the soulknife can be found in all shapes and sizes, wielding blades unique to the wielder and customized to fit the needs of the soulknife. Fluid in function, the soulknife has mastered how to alter her mind blade to fit the situation, bringing power and versatility into any combat.

**Role:** As a wielder of a weapon first and foremost, the soulknife excels as a front-line combatant on the battlefield. Her limited armor options and defensive abilities can be a hindrance, but her varied blade abilities can make her an excellent mobile warrior or battlefield controller.
