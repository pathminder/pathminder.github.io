---
title: Soulknife (Augmented Blade, High Psionics)
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
  - Martial
armor_proficiencies:
  - Light
  - Medium
  - Heavy
shield_proficiencies:
  - Shields

class_features:

  - name: augmented bladeworks
    levels: [1]
    text: |
      At 1st level, the augmented blade may select a bonus feat from the following list: Point Blank Shot, Power Attack, Two- Weapon Fighting, or Weapon Focus. If the augmented blade chooses feats that select specific weapon types (such as Improved Critical, Weapon Focus, or Weapon Specialization), she may select 'mind blade' and gain the benefits of that feat regardless of what type of weapon she is currently augmenting.

  - name: psicrystal augment
    levels: [1, 3, 5, 7, 9, 11, 13, 15, 17, 19]
    levels_text:
      3:  +1, max +1
      5:  +2, max +1
      7:  +3, max +2
      9:  +4, max +3
      11: +5, max +3
      13: +6, max +4
      15: +7, max +5
      17: +8, max +5
      19: +9, max +5
    text: |
      At 1st level, the augmented blade learns how to attach her psicrystal to a weapon and cause it to bond to the item as a move action (reclaiming the psicrystal is a free action). Some weapons become covered in a thin sheen of crystal, for other augmented blades the entire weapon becomes psychic energy---the result is the same regardless of the cosmetic appearance. Once bonded, this psicrystal augmentation allows for the bonded weapon to be used with blade skills and is treated as a masterwork item when augmented. Weapons created through temporary means (such as the *call weaponry* power, or the *flame blade* spell) may not be bonded with the augmented blade’s psicrystal due to their ephemeral nature.

      If the augmented blade is ever separated from her weapon (or an item augmented by her psicrystal), the psicrystal stays with that object(s) as long as the item stays within range of the augmented blade and his telepathic link (one mile) with the psicrystal. At any time, the augmented blade can cause the psicrystal to abandon them item as a free action within that range and command her psicrystal as normal.

      Starting at 3rd level, the bonded weapon gains a cumulative +1 enhancement bonus that increases every odd level thereafter that they may spend on an actual enhancement bonus or on weapon special abilities. An augmented blade’s level determines her maximum enhancement bonus. The augmented blade may (and must, when her total enhancement is higher than her maximum bonus) apply any special ability from Table: Weapon Special Abilities instead of an enhancement bonus, as long as she meets the level requirements. This overrides any magical or psionic enhancements that may already be on this weapon, but the weapon retains any material or masterwork bonuses it may have. An augmented blade can choose any combination of weapon special abilities and/or enhancement bonus for attack and damage rolls before assigning any special abilities each time that the augmented blade uses this ability.

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

      This counts as the form mind blade and enhanced mind blade class features for prerequisites or requirements.

  - name: shape mind blade
    levels: [1]
    text: |
      The soulknife's mind blade retains the last chosen form every time it is formed until the soulknife reshapes it. If the soulknife chooses to reshape his blade, it requires a full-round action to do so. She may also re-assign the type of damage dealt as part of reshaping his mind blade if he so chooses.

      A soulknife can reassign the ability or abilities he has added to his mind blade; see below. To do so, he must first spend 8 hours in concentration. These cannot be the normal 8 hours used for rest, even if the soulknife does not require sleep. After that period, the mind blade materializes with the new ability or abilities selected by the soulknife.

  - name: Psicrystal Affinity
    levels: [1]
    text: At 1st level, the augmented blade gains the [Psicrystal Affinity](/blade-skills/psicrystal-affinity/) blade skill.

  - name: wild talent
    levels: [1]
    text: |
      The soulknife gains Wild Talent as a bonus feat at 1st level. This provides his with the psionic power necessary to manifest his mind blade. A character who is already psionic instead gains the Psionic Talent feat.

  - name: blade skills
    levels: [2, 4, 8, 10, 12, 14, 16, 18, 20]
    levels_text:
      2:  1 blade skill
      4:  2 blade skills
      8:  3 blade skills
      10: 4 blade skills
      12: 5 blade skills
      14: 6 blade skills
      16: 7 blade skills
      18: 8 blade skills
      20: 9 blade skills
    text: |
      Beginning at 2nd level and every even soulknife level thereafter except 6th level, the augmented blade may choose a [blade skill](/blade-skills/) to add to his repertoire. Some blade skills have prerequisites that must be met before they can be chosen. All blade skills may only be chosen once and require the soulknife to be using his mind blade unless otherwise stated in the skill's description.

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

  - name: fast augmentation
    levels: [5]
    text: At 5th level, the augmented blade can augment an item in her possession with her psicrystal as a free action once per round.

  - name: weapon training
    type: Ex
    levels: [6, 12, 18]
    levels_text:
      1:  +1, 1 group
      12: +2, 2 groups
      18: +3, 3 groups
    text: At 6th level, the augmented blade gains weapon training, as the fighter ability, adding an additional weapon group every six levels after 6th (to a maximum of three groups at 18th level) and increasing the bonus on attack and damage rolls for weapon groups chosen by +1.

  - name: fighter training
    type: Ex
    levels: [7]
    text: At 7th level, the augmented blade counts her soulknife level --3 as her fighter level for the purpose of qualifying for feats. If she has levels in fighter, these levels stack.

  - name: mind blade mastery
    levels: [20]
    text: At 20th level, a soulknife reaches the pinnacle of his art and his connection to his blade is so strong it cannot be severed. She no longer requires a Will save to maintain his mind blade in a null psionics field, although it still loses any enhancement bonus and special abilities. In addition, he may change the configurations of his mind blade's special abilities at will as a full-round action, which also resets any penalties that may have accrued from the Fluid Form and Improved Fluid Form blade skills.
---

Never caught unarmed, the soulknife is the literal interpretation of using the power of the mind as a weapon. Creating a mind blade is the core of the soulknife, and with it, he is a deadly combatant. Versatile and varied, the soulknife can be found in all shapes and sizes, wielding blades unique to the wielder and customized to fit the needs of the soulknife. Fluid in function, the soulknife has mastered how to alter her mind blade to fit the situation, bringing power and versatility into any combat.

Most soulknives rely on the idealized weapon-form that is created by their concentrated will and effort. Some soulknives, however, are unable to physically manifest a solid-thought weapon into existence and use this for war because they prefer to rely on physical weapons. These soulknives introduce a psicrystal to their combat method to utilize their arts. By focusing this weapon-manifesting energy into their psicrystal, they can cause it to bind to a weapon and augment its abilities in combat just like more traditional soulknives.

**Role:** As a wielder of a weapon first and foremost, the soulknife excels as a front-line combatant on the battlefield. Her limited armor options and defensive abilities can be a hindrance, but her varied blade abilities can make her an excellent mobile warrior or battlefield controller.
