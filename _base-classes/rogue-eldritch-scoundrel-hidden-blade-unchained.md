---
title: Rogue (Eldritch Scoundrel, Hidden Blade, Unchained)
sources:
  - Pathfinder Roleplaying Game Core Rulebook
  - "Pathfinder Player Companion: Arcane Anthology"
  - "Path of War: Expanded"
tags:
  - Arcane
  - Initiator
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

initiating_progression: mid

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

  - name: maneuvers
    levels: [1]
    text: |
      A hidden blade begins her career with knowledge of three martial maneuvers. The disciplines available to her are Mithral Current, Thrashing Dragon, and Veiled Moon.

      Once the hidden blade knows a maneuver, she must ready it before she can use it (see Maneuvers Readied, below). A maneuver usable by hidden blades is considered an extraordinary ability unless otherwise noted in it or its discipline's description. A hidden blade's maneuvers are not affected by spell resistance, and she does not provoke attacks of opportunity when she initiates one.

      The hidden blade learns additional maneuvers at higher levels, as indicated on Table: The Rogue. The maximum level of maneuvers gained through hidden blade levels is limited by those listed in that table as well, although this restriction does not apply to maneuvers added to his maneuvers known through other methods, such as prestige classes or the Advanced Study feat. A hidden blade must meet a maneuver's prerequisite to learn it. See the Systems and Use chapter in Path of War for more details on how maneuvers are used.

      Upon reaching 4th level, and at every even numbered initiator level thereafter (6th, 8th, 10th, and so on), the hidden blade can choose to learn a new maneuver in place of one she already knows. In effect, she loses the old maneuver in exchange for the new one. She can choose a new maneuver of any level she likes, as long as she observes the restriction on the highest- level maneuvers she knows; the hidden blade need not replace the old maneuver with a maneuver of the same level. She can swap only a single maneuver at any given level. A hidden blade's initiation modifier is Intelligence, and each hidden blade level is counted as a full initiator level.

      **Maneuvers Readied:** A hidden blade can ready all three of her maneuvers known at 1st level, and as she advances in level and learns more maneuvers, she is able to ready more, but must still choose which maneuvers to ready. A hidden blade must always ready her maximum number of maneuvers readied. She readies her maneuvers by meditating or performing martial katas for ten minutes. The maneuvers she chooses remain readied until she decides to meditate again and change them. The hidden blade does not need to sleep or rest for any long period of time in order to ready her maneuvers; any time she spends ten minutes in meditating, she can change her readied maneuvers.

      A hidden blade begins an encounter with all her readied maneuvers unexpended, regardless of how many times she might have already used them since she chose them. When she initiates a maneuver, she expends it for the current encounter, so each of her readied maneuvers can be used once per encounter (unless she recovers them, as described below).

      In order for the hidden blade to recover maneuvers, she must play a gambit (see the [gambit class feature](#gambit)). Alternately, the hidden blade may take a moment to reposition, recovering a single maneuver as a standard action.

      **Stances Known:** A hidden blade begins play with knowledge of one stance from any discipline open to hidden blades. At 4th, 7th, 11th, and 13th levels, she can select an additional stance to learn. The maximum level of stances gained through hidden blade levels is limited by those listed in Table: The Rogue. Unlike maneuvers, stances are not expended and the hidden blade does not have to ready them. All the stances she knows are available to her at all times, and she can change the stance she is currently maintaining as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance or discipline description.

      Unlike with maneuvers, a hidden blade cannot learn a new stance at higher levels in place of one she already knows.

  - name: hidden specialization
    type: Ex
    levels: [1]
    text: At 1st level, a hidden blade adds Broken Blade, Shattered Mirror, or Tempest Gale to her list of available disciplines for her [maneuvers](#maneuvers). If the hidden blade does not have that discipline's associated skill as a class skill, she gains it as a class skill.

  - name: hidden weapons
    type: Ex
    levels: [1]
    text: A hidden blade is adept at storing and retrieving weapons from places that no one would expect to find them. At 1st level, she gains Quick Draw as a bonus feat, even if she does not meet the prerequisites. In addition, she can draw hidden weapons as a free action, rather than a move action.

  - name: portable hole specialist
    type: Ex
    levels: [1]
    text: Starting at 1st level, a hidden blade becomes adept at smuggling and storing objects into and out of extradimensional spaces, and can retrieve items from bags of holding or portable holes as a move action, regardless of how full or unorganized the bag is.

  - name: gambits
    type: Ex
    levels: [1, 4, 8, 12, 16, 20]
    levels_text:
      1: 2 gambits
      4: 3 gambits
      8: 4 gambits
      12: 5 gambits
      16: 6 gambits
      20: 7 gambits
    text: |
      A hidden blade is a cunning warrior who seizes opportunities as they present themselves to put his enemies in untenable positions. At 1st level, a hidden blade selects two gambits from the [warlord gambits](/warlord-gambits/) or the hidden blade gambits listed below. At 4th level and every four levels thereafter, a hidden blade selects an additional gambit to learn. Any gambit that would normally use the hidden blade's Charisma modifier to determine its effects instead uses her hidden blade initiation modifier. These gambits allow the hidden blade to recover maneuvers. Due to their reliance on the stresses of combat to bring out the best of the hidden blade, gambits cannot be used outside combat.

      A gambit has two aspects: a risk and a reward. A gambit's risk describes an action the hidden blade must take in order to play the gambit. The hidden blade begin a gambit as a swift action, then performs the gambit's risk action. She may add her hidden blade initiation modifier as a luck bonus on any d20 rolls made while performing this action (such as the Acrobatics check of an acrobatic gambit, or the attack roll of a brave gambit). The hidden blade only gets this bonus if she used a swift action to begin the gambit; if taking the actions normally, she gains no additional benefits. If the hidden blade initiates a maneuver as part of a gambit, she cannot recover that maneuver when the gambit is completed (even if it's her only expended maneuver).

      If the hidden blade succeeds at her gambit's risk, she recovers a number of expended maneuvers equal to her hidden blade initiation modifier (minimum 2) and gains the reward listed in the gambit's description. Allies who would gain a benefit from the gambit's reward must be within 60 feet of the hidden blade and able to see her perform the gambit's risk.

      If the hidden blade fails her gambit (such as missing the charge attack of a brave gambit, or failing the saving throw of an unbreakable gambit), she suffers the gambit's rake, recovering only a single expended maneuver and taking a --2 penalty on all d20 rolls for one round.

      **Stealth Gambit (Su):** *Risk:* The hidden blade makes a Stealth check to hide. *Reward:* The hidden blade becomes invisible for a number of rounds equal to her initiation modifier, as if under the effect of an *invisibility* spell.

      **Flanker's Gambit:** *Risk:* The hidden blade attacks an opponent adjacent to one of the hidden blade's other allies. *Reward:* The hidden blade is considered to be flanking that opponent until the end of her next turn, even if the hidden blade is not in a position that would allow her to flank them.

      **Coward's Gambit:** *Risk:* The hidden blade attacks a flat-footed opponent or an opponent she is flanking. *Reward:* The hidden blade's allies gain a bonus on damage rolls against that opponent equal to the hidden blade's Intelligence modifier for one round.

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

  - name: alarm sense
    type: Su
    levels: [3]
    text: |
      At 3rd level, an eldritch scoundrel gains an intuitive sense that warns her when she is near a magic trap. This functions as the [trap spotter](/rogue-talents/trap-spotter/) rogue talent, but applies only if the eldritch scoundrel comes within 10 feet of a magic trap.

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

  - name: master strike
    type: Ex
    levels: [20]
    text: |
      At 20th level, an rogue becomes incredibly deadly when dealing sneak attack damage. Each time the rogue deals sneak attack damage, she can choose one of the following three effects: the target can be put to sleep for 1d4 hours, paralyzed for 2d6 rounds, or slain. Regardless of the effect chosen, the target can attempt a Fortitude save to negate the additional effect. The DC of this save is equal to 10 + 1/2 the rogue's level + the rogue's Dexterity modifier. Once a creature has been the target of a master strike, regardless of whether or not the save is successful, that creature is immune to that rogue's master strike for 24 hours. Creatures that are immune to sneak attack damage are also immune to this ability.

---

Life is an endless adventure for those who live by their wits. Ever just one step ahead of danger, rogues bank on their cunning, skill, and charm to bend fate to their favor. Never knowing what to expect, they prepare for everything, becoming masters of a wide variety of skills, training themselves to be adept manipulators, agile acrobats, shadowy stalkers, or masters of any of dozens of other professions or talents. Thieves and gamblers, fast talkers and diplomats, bandits and bounty hunters, and explorers and investigators all might be considered rogues, as well as countless other professions that rely upon wits, prowess, or luck. Although many rogues favor cities and the innumerable opportunities of civilization, some embrace lives on the road, journeying far, meeting exotic people, and facing fantastic danger in pursuit of equally fantastic riches. In the end, any who desire to shape their fates and live life on their own terms might come to be called rogues.

Students of arcane magic, legerdemain, and stealth, eldritch scoundrels are a rare breed of adventurer most commonly found seeking lost and valuable arcane writings in the ruins of fallen empires.

**Role:** Rogues excel at moving about unseen and catching foes unaware, and tend to avoid head-to-head combat. Their varied skills and abilities allow them to be highly versatile, with great variations in expertise existing between different rogues. Most, however, excel in overcoming hindrances of all types, from unlocking doors and disarming traps to outwitting magical hazards and conning dull-witted opponents.
