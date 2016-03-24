---
title: Inquisitor (Sanctified Slayer)
sources:
  - Pathfinder Roleplaying Game Advanced Class Guide
tags:
  - Divine

max_level: 20
hit_die: 8
prerequisites:
  - Alignment must be within one step of deity's, along either the law/chaos axis or the good/evil axis.
starting_wealth: 4d6 × 10 gp (average 140 gp)

class_skills:
   - Bluff
   - Climb
   - Craft
   - Diplomacy
   - Disguise
   - Heal
   - Intimidate
   - Knowledge (arcana)
   - Knowledge (dungeoneering)
   - Knowledge (nature)
   - Knowledge (planes)
   - Knowledge (religion)
   - Perception
   - Profession
   - Ride
   - Sense Motive
   - Spellcraft
   - Stealth
   - Survival
   - Swim
skill_ranks_per_level: 6

bab_progression: mid
fort_progression: good
ref_progression: poor
will_progression: good

spells_per_day: mid
spells_known: mid

weapon_proficiencies:
  - Simple
  - hand crossbow
  - longbow
  - repeating crossbow
  - shortbow
  - deity's favored weapon
armor_proficiencies:
  - Light
  - Medium
shield_proficiencies:
  - Shields

class_features:

  - name: ex-inquisitors
    levels: [1]
    text: An inquisitor who slips into corruption or changes to a prohibited alignment loses all spells and the judgment ability. She cannot thereafter gain levels as an inquisitor until she atones (see the *atonement* spell description). An inquisitor who becomes an ex-inquisitor can, with the GM's permission, take the heretic archetype, replacing her class abilities with the appropriate archetype abilities. If the character atones or joins a different faith, she loses her heretic abilities and regains her previous inquisitor class abilities.

  - name: spells
    levels: [1]
    text: |
      An inquisitor casts divine spells drawn from the inquisitor spell list. She can cast any spell she knows at any time without preparing it ahead of time, assuming she has not yet used up her allotment of spells per day for the spell's level.

      To learn or cast a spell, an inquisitor must have a Wisdom score equal to at least 10 + the spell level. The Difficulty Class for a saving throw against an inquisitor's spell is 10 + the spell level + the inquisitor's Wisdom modifier.

      An inquisitor can cast only a certain number of spells of each spell level each day. Her base daily spell allotment is given on Table: Inquisitor. In addition, she receives bonus spells per day if she has a high Wisdom score (see Table: Ability Modifiers and Bonus Spells).

      An inquisitor's selection of spells is extremely limited. An inquisitor begins play knowing four 0-level spells and two 1st-level spells of the inquisitor's choice. At each new inquisitor level, she gains one or more new spells as indicated on Table: Inquisitor Spells Known. (Unlike spells per day, the number of spells an inquisitor knows is not affected by her Wisdom score. The numbers on Table: Inquisitor Spells Known are fixed.)

      Upon reaching 5th level, and at every third inquisitor level thereafter (8th, 11th, and so on), an inquisitor can choose to learn a new spell in place of one she already knows. In effect, the inquisitor “loses” the old spell in exchange for the new one. The new spell's level must be the same as that of the spell being exchanged, and it must be at least one level lower than the highest-level inquisitor spell she can cast. The inquisitor may swap out only a single spell at any given level and must choose whether or not to swap the spell at the same time that she gains new spells known for the level.

      *Chaotic, Evil, Good, and Lawful Spells:* An inquisitor can't cast spells of an alignment opposed to her own or her deity's (if she has one). Spells associated with particular alignments are indicated by the chaotic, evil, good and lawful descriptors in their spell descriptions.

  - name: domain
    levels: [1]
    text: |
      Like a cleric's deity, an inquisitor's deity influences her alignment, what magic she can perform, and her values. Although not as tied to the tenets of the deity as a cleric, an inquisitor must still hold such guidelines in high regard, despite that fact she can go against them if it serves the greater good of the faith. An inquisitor can select one domain from among those belonging to her deity. She can select an alignment domain only if her alignment matches that domain. With the GM's approval, an inquisitor can be devoted to an ideal instead of a deity, selecting one domain to represent her personal inclination and abilities. The restriction on alignment domains still applies.

      Each domain grants a number of domain powers, depending on the level of the inquisitor. An inquisitor does not gain the bonus spells listed for each domain, nor does she gain bonus spell slots. The inquisitor uses her level as her effective cleric level when determining the power and effect of her domain powers. If the inquisitor has cleric levels, one of her two domain selections must be the same domain selected as an inquisitor. Levels of cleric and inquisitor stack for the purpose of determining domain powers and abilities, but not for bonus spells.

      Instead of a domain, an inquisitor may choose an inquisition, which are similar to domains but do not include domain spells.

  - name: monster lore
    type: Ex
    levels: [1]
    text: The inquisitor adds her Wisdom modifier on Knowledge skill checks in addition to her Intelligence modifier, when making skill checks to identify the abilities and weaknesses of creatures.

  - name: orisons
    levels: [1]
    text: |
      Inquisitors learn a number of orisons, or 0-level spells, as noted on Table: Inquisitor Spells Known. These spells are cast like any other spell, but they are not expended when cast and may be used again. Orisons prepared using other spell slots, such as those due to metamagic feats, are expended normally.

  - name: stern gaze
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
    text: Inquisitors are skilled at sensing deception and intimidating their foes. An inquisitor receives a morale bonus on all Intimidate and Sense Motive checks equal to 1/2 her inquisitor level (minimum +1).

  - name: studied target
    type: Ex
    levels: [1, 5, 7, 10, 15, 20]
    levels_text:
      1: "+1"
      5: "+2"
      7: move or swift action
      10: "+3"
      15: "+4"
      20: "+5"
    text: |
      A sanctified slayer can study an opponent he can see as a move action. The sanctified slayer then gains a +1 bonus on Bluff, Knowledge, Perception, Sense Motive, and Survival checks attempted against that opponent, and a +1 bonus on weapon attack and damage rolls against it. The DCs of sanctified slayer class abilities against that opponent increase by 1. A sanctified slayer can only maintain these bonuses against one opponent at a time; these bonuses remain in effect until either the opponent is dead or the sanctified slayer studies a new target.

      If a sanctified slayer deals sneak attack damage to a target, he can study that target as an immediate action, allowing him to apply his studied target bonuses against that target (including to the normal weapon damage roll).

      At 5th, 10th, 15th, and 20th levels, the bonuses on weapon attack rolls, damage rolls, and skill checks and to sanctified slayer DCs against a studied target increase by 1. In addition, at each such interval, the sanctified slayer is able to maintain these bonuses against an additional studied target at the same time. The sanctified slayer may discard this connection to a studied target as a free action, allowing him to study another target in its place.

      At 7th level, a sanctified slayer can study an opponent as a move or swift action

  - name: cunning initiative
    type: Ex
    levels: [2]
    text: At 2nd level, an inquisitor adds her Wisdom modifier on initiative checks, in addition to her Dexterity modifier.

  - name: "*detect alignment*"
    type: Sp
    levels: [2]
    text: At 2nd level, atwill, an inquisitor can use *detect chaos*, *detect evil*, *detect good*, or *detect law*. She can only use one of these at any given time.

  - name: track
    levels: [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]
    levels_text:
      2:  "+1"
      4:  "+2"
      6:  "+3"
      8:  "+4"
      10: "+5"
      12: "+6"
      14: "+7"
      16: "+8"
      18: "+9"
      20: "+10"
    text: At 2nd level, an inquisitor adds half her level on Survival skill checks made to follow or identify tracks.

  - name: solo tactics
    type: Ex
    levels: [3]
    text: At 3rd level, all of the inquisitor's allies are treated as if they possessed the same teamwork feats as the inquisitor for the purpose of determining whether the inquisitor receives a bonus from her teamwork feats. Her allies do not receive any bonuses from these feats unless they actually possess the feats themselves. The allies' positioning and actions must still meet the prerequisites listed in the teamwork feat for the inquisitor to receive the listed bonus.

  - name: teamwork feat
    levels: [3, 6, 9, 12, 15, 18]
    levels_text:
      3: 1 feat
      6: 2 feats
      9: 3 feats
      12: 4 feats
      15: 5 feats
      18: 6 feats
    text: |
      At 3rd level, and every three levels thereafter, the inquisitor gains a bonus feat in addition to those gained from normal advancement. These bonus feats must be selected from those listed as teamwork feats. The inquisitor must meet the prerequisites of the selected bonus feat.

      As a standard action, the inquisitor can choose to learn a new bonus teamwork feat in place of the most recent bonus teamwork feat she has already learned. In effect, the inquisitor loses the bonus feat in exchange for the new one. She can only change the most recent teamwork feat gained. Whenever she gains a new teamwork feat, the previous teamwork feat becomes set and cannot be changed again. An inquisitor can change her most recent teamwork feat a number of times per day equal to her Wisdom modifier.

  - name: sneak attack
    type: Ex
    levels: [4, 7, 10, 13, 16, 19]
    levels_text:
      4: +1d6
      7: +2d6
      10: +3d6
      13: +4d6
      16: +5d6
      19: +6d6
    text: |
      At 4th level, if a sanctified slayer catches an opponent unable to defend itself effectively from her attack, she can strike a vital spot to deal extra damage. The sanctified slayer's attack deals additional damage anytime her target would be denied a Dexterity bonus to AC (whether or not the target actually has a Dexterity bonus), or when the sanctified slayer flanks her target. This additional damage is 1d6 at 4th level, and increases by 1d6 every 3 levels thereafter. Should a sanctified slayer score a critical hit with the sneak attack, this extra damage is not multiplied. Ranged attacks can count as sneak attacks only if the target is within 30 feet. With a weapon that deals nonlethal damage (such as a sap, whip, or an unarmed strike), a sanctified slayer can make a sneak attack that deals nonlethal damage instead of lethal damage. She cannot use a weapon that deals lethal damage to deal nonlethal damage in a sneak attack, even with the usual --4 penalty.

      A sanctified slayer must be able to see the target well enough to pick out a vital spot and must be able to reach such a spot. A sanctified slayer cannot use sneak attack while striking a creature with concealment.

  - name: bane
    type: Su
    levels: [5]
    text: At 5th level, an inquisitor can imbue one of her weapons with the bane weapon special ability as a swift action. She must select one creature type when she uses this ability (and a subtype if the creature type selected is humanoid or outsider). Once selected, the type can be changed as a swift action. This ability only functions while the inquisitor wields the weapon. If dropped or taken, the weapon resumes granting this ability if it is returned to the inquisitor before the duration expires. This ability lasts for a number of rounds per day equal to the inquisitor's level. These rounds do not need to be consecutive.

  - name: "*discern lies*"
    type: Sp
    levels: [5]
    text: At 5th level, an inquisitor can discern lies, as per the spell, for a number of rounds per day equal to her inquisitor level. These rounds do not need to be consecutive. Activating this ability is an immediate action.

  - name: stalwart
    type: Ex
    levels: [11]
    text: At 11th level, an inquisitor can use mental and physical resiliency to avoid certain attacks. If she makes a Fortitude or Will saving throw against an attack that has a reduced effect on a successful save, she instead avoids the effect entirely. This ability can only be used if the inquisitor is wearing light armor, medium armor, or no armor. A helpless inquisitor does not gain the benefit of the stalwart ability.

  - name: greater bane
    type: Su
    levels: [12]
    text: At 12th level, whenever an inquisitor uses her bane ability, the amount of bonus damage dealt by the weapon against creatures of the selected type increases to 4d6.

  - name: exploit weakness
    type: Ex
    levels: [14]
    text: At 14th level, the inquisitor learns to take advantage of any opportunity that presents itself. Whenever the inquisitor scores a critical hit, she ignores any damage reduction the target might have. In addition, if the target has regeneration, the creature loses regeneration on the round following the critical hit and can die normally during that round. Creatures whose regeneration always functions are immune to this ability. Finally, if the inquisitor deals energy damage to a creature with vulnerability to that energy type, she deals +1 point of damage per die rolled.

  - name: talented slayer
    type: Ex
    levels: [8, 16, 17, 20]
    levels_text:
      8: 1 talent
      16: 2 talents
      17: 3 talents
      20: 4 talents
    text: At 8th, 16th, 17th, and 20th levels, a sanctified slayer can gain a single slayer talent, including those from the list of [rogue talents](/rogue-talents/) that a slayer can take, but not an advanced slayer talent.

---

Grim and determined, the inquisitor roots out enemies of the faith, using trickery and guile when righteousness and purity is not enough. Although inquisitors are dedicated to a deity, they are above many of the normal rules and conventions of the church. They answer to their deity and their own sense of justice alone, and are willing to take extreme measures to meet their goals.

While all inquisitors root out enemies of the faith, in many orders and churches there's a select group of these religious hunters devoted to one goal, and one goal alone---to terminate the enemies of the faith wherever they can be found. Sometimes these sanctified slayers are given special dispensation to commit ruthless murders for the faith's greater good. Other times, they're simply willing to take the initiative to revel in the zeal of such grisly work.

**Role:** Inquisitors tend to move from place to place, chasing down enemies and researching emerging threats. As a result, they often travel with others, if for no other reason than to mask their presence. Inquisitors work with members of their faith whenever possible, but even such allies are not above suspicion.

**Alignment:** An inquisitor's alignment must be within one step of her deity's, along either the law/chaos axis or the good/evil axis.
