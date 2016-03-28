---
title: Stalker (Bushi, Vigilante)
sources:
  - Path of War
  - "Path of War: Expanded"
tags:
  - Initiator
  - Inspiration

max_level: 20
hit_die: 8
prerequisites:
starting_age: Trained
starting_wealth: ???

class_skills:
  - Acrobatics
  - Appraise
  - Bluff
  - Climb
  - Craft
  - Disable Device
  - Disguise
  - Escape Artist
  - Heal
  - Intimidate
  - Knowledge (dungeoneering)
  - Knowledge (geography)
  - Knowledge (history)
  - Knowledge (local)
  - Knowledge (martial)
  - Knowledge (nature)
  - Knowledge (nobility)
  - Knowledge (religion)
  - Perception
  - Perform
  - Profession
  - Sense Motive
  - Sleight of Hand
  - Stealth
skill_ranks_per_level: 6

bab_progression: mid
fort_progression: poor
ref_progression: poor
will_progression: good

initiating_progression: stalker

weapon_proficiencies:
  - Simple
  - Martial
armor_proficiencies:
  - Light
shield_proficiencies:

class_features:

  - name: maneuvers
    levels: [1]
    text: |
      A stalker begins his career with knowledge of six martial maneuvers. The disciplines available to him are Broken Blade, Primal Fury, Riven Hourglass, Scarlet Throne, Steel Serpent, Tempest Gale, Thrashing Dragon. The stalker may also exchange access to one of his martial disciplines for the Unquiet Grave discipline, and must choose one of his martial disciplines to exchange for the Mithral Current discipline. He gains the associated skill of each of his disciplines as a class skill.

      Once he knows a maneuver, he must ready it before he can use it (see Maneuvers Readied, below). A maneuver usable by stalkers is considered an extraordinary ability unless otherwise noted in its description. His maneuvers are not affected by spell resistance, and he does not provoke attacks of opportunity when he initiates one. He learns additional maneuvers at higher levels, as shown above. The stalker must meet a maneuver's prerequisite to learn it.

      Upon reaching 4th level, and at every even numbered stalker level after that, he can choose to learn a new maneuver in place of one he already knows. In effect, the stalker loses the old maneuver in exchange for the new one. The stalker need not replace the old maneuver with a maneuver of the same level. He can choose a new maneuver of any level he likes, as long as he observes his restriction on the highest-level maneuvers he knows. The stalker can swap only a single maneuver at any given level. A stalker's initiator modifier is Intelligence.

      *Maneuvers Readied:* A stalker can ready four of his six starting maneuvers, but as he advances in level and learns more maneuvers, he must choose which maneuvers to ready. He readies his maneuvers by meditating and focusing his *ki* for 10 minutes. The maneuvers he chooses remain readied until he decides to repeat this again and change them. Stalkers do not need to sleep or be well rested to ready their maneuvers; any time he spends 10 minutes in meditation, he can change his readied maneuvers. He may not ready any individual maneuver more than once. He begins an encounter with all readied maneuvers unexpended, regardless of how many times he may have already used them since he chose them. When the stalker initiates a maneuver, he expends it for the current encounter, so each of his readied maneuvers can be used once per encounter (until they are recovered, see below).

      To recover maneuvers, the vigilante must open his mind to the flow of battle and the inherent patterns therein as a full-round action. When he does so, he recovers a number of expended maneuvers equal to his vigilante initiation modifier (minimum 2), gains a +4 insight bonus to his AC for one round and can move up to to his speed during the action, provoking attacks of opportunity as normal. In addition, the next attack he makes this encounter adds his sneak attack damage if it hits, regardless of whether or not the target his flanked or flat-footed.

      *Stances Known:* Stalkers begin play with knowledge of one stance from any discipline open to stalkers. At the indicated levels (see class table), the stalker selects an additional new stance. Unlike maneuvers, stances are not expended and he does not have to ready them. All the stances he knows are available to him at all times, and he can change the stance he is currently using as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance description. Unlike with maneuvers, the stalker cannot learn a new stance at higher levels in place of one he already knows.

  - name: inspiration
    type: Ex
    levels: [1]
    text: |
      A vigilante relies on his insight to aid him in his mission, using his cunning to augment skill checks and ability checks. The vigilante has an inspiration pool equal to 1/2 his class level + his vigilante initiation modifier (minimum 1). An vigilante’s inspiration pool refreshes each day, typically after he gets a restful night’s sleep. As a free action, he can expend one use of inspiration from his pool to add 1d6 to the result of that check, including any on which he takes 10 or 20. This choice is made after the check is rolled and before the results are revealed. An vigilante can only use inspiration once per check or roll. The vigilante can use inspiration on any Knowledge, Perception, or Sense Motive skill checks without expending a use of inspiration, provided he’s trained in the skill.

      Inspiration can also be used on attack rolls and saving throws, although it costs two points of inspiration rather than one. Using inspiration while making a saving throw is an immediate action, rather than a free action.

  - name: trapfinding
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
    text: A vigilante adds 1/2 his level as a bonus on Perception checks to locate traps and to Disable Device checks (minimum 1). A vigilante can use Disable Device to disarm magical traps.

  - name: sneak attack
    type: Ex
    levels: [1, 4, 7, 10, 13, 16, 19]
    levels_text:
      1:  +1d6
      4:  +2d6
      7:  +3d6
      10: +4d6
      13: +5d6
      16: +6d6
      19: +7d6
    text: |
      If a vigilante can catch an opponent when he is unable to defend himself effectively from the vigilante’s attack, he can strike a vital spot for extra damage.

      The vigilante’s attack deals extra damage any time his target would be denied a Dexterity bonus to AC (whether the target actually has a Dexterity bonus or not), or when the vigilante flanks his target. This extra damage is 1d6 at 1st level, and increases by 1d6 every three vigilante levels thereafter (2d6 at 4th level, 3d6 at 7th level, and so on). Ranged attacks can count as sneak attacks only if the target is within 30 feet. This additional damage is precision damage and is not multiplied on a critical hit.

      With a weapon that deals nonlethal damage (such as a sap, unarmed strike, or whip), a vigilante can make a sneak attack that deals nonlethal damage instead of lethal damage. He cannot use a weapon that deals lethal damage to deal nonlethal damage in a sneak attack---not even with the usual --4 penalty.

      The vigilante must be able to see the target well enough to pick out a vital spot and must be able to reach such a spot. A vigilante cannot sneak attack while striking a creature with total concealment.

  - name: iaido
    type: Ex
    levels: [1]
    text: In addition to his normal maneuver recovery, a bushi can recover his maneuvers by sheathing his blade and taking a brief moment of quiet contemplation. When he sheathes a weapon (normally a move action), he recovers one maneuver. He cannot recover more than one maneuver per round this way, no matter how many weapons he sheathes or how many times he sheathes an individual weapon per round, nor can he use a maneuver in the same round it is recovered in this way. A bushi cannot use this ability to recover a maneuver in the same round in which it was initiated.

  - name: iaido training
    type: Ex
    levels: [1]
    text: At 1st level, a bushi gains Exotic Weapon Proficiency (katana) and Exotic Weapon Proficiency (wakizashi) as bonus feats, even if he does not meet their prerequisites.

  - name: Quick Draw
    type: Ex
    levels: [1]
    text: At 1st level, a bushi gains Quick Draw as a bonus feat, even if he does not meet the prerequisites. In addition, the bushi may sheathe his weapon without provoking attacks of opportunity.

  - name: combat insight
    type: Su
    levels: [2, 4, 8, 12, 18]
    levels_text:
      2: defensive reflexes
      4: uncanny dodge
      8: critical hits
      12: critical recovery
      18: blindsight
    text: |
      At 2nd level, the keen senses and awareness of the stalker delivers him a sort of sixth sense. This insight performs as an intuitive alarm, alerting him of danger. Through his rigorous practice and learning to trust his instincts and intuition to an unearthly level, the senses of the stalker are unusually sharp.

      At 2nd level, the stalker's combat sense opens his third eye, granting him defensive reflexes that protect him in combat. The stalker may add his Wisdom modifier to his initiative score and to Reflex saving throws as an insight bonus.

      At 4th level, the heightened perceptions of the stalker allow him to know when his prey could get the jump on him, granting him the uncanny dodge class feature, as per the rogue class.

      At 8th level, the killer's instinct in the stalker is honed to a razor's fine edge, allowing him to add his Wisdom modifier as a competence bonus to confirm critical hits. This ability counts as if the character possessed the Critical Focus feat, and for the purposes of taking critical feats that the character qualifies for. The character may not select the Critical Focus feat once he has this ability, and should he have it before he gains this ability, he loses the Critical Focus feat and may select a critical feat in its place.

      At 12th level, the stalker's insight allows him to funnel the *ki* of his foes into his form with his deadly attacks. The character can recover a single expended maneuver when he scores a successful critical hit against a living creature. This ability does not function against constructs, undead, or creatures with under 1⁄2 HD.

      At 18th level, the heightened precognitive abilities of the stalker manifest in his ability to sense things around him that others cannot, granting him blindsight with a range of 30 feet. This is a supernatural ability.

  - name: dodge bonus
    type: Ex
    levels: [2, 6, 10, 14, 18]
    levesl_text:
      2:  "+1"
      6:  "+2"
      10: "+3"
      14: "+4"
      18: "+5"
    text: The stalker's heightened perception of danger allows him to defend himself from attacks as they are made against him, anticipating the attacks as they come. A stalker gains a +1 dodge bonus to his Armor Class at 2nd level, which improves by an additional +1 every four stalker levels thereafter. When recovering maneuvers as a full round action, the character may add his Wisdom modifier to his AC as an additional dodge bonus; his defensive precognition being heightened by centering his *ki* through maneuver recovery.

  - name: stalker arts
    levels: [3, 7, 11, 15, 19]
    levels_text:
      3:  1 art
      7:  2 arts
      11: 3 arts
      15: 4 arts
      19: 5 arts
    text: |
      As a stalker gains experience, he learns a number of arts that aid him and confound his foes. Starting at 3rd level, a stalker gains one [stalker art](/stalker-arts/); he gains an additional art every four class levels attained after 3rd level. A stalker cannot select an individual art more than once (unless noted).

      Instead of selecting a stalker art at the appropriate level, a vigilante can select an investigator talent instead, treating his stalker level as his effective investigator level. He must meet the prerequisites for this investigator talent as normal. The vigilante cannot select investigator talents which augment alchemy, nor can he select stalker arts which require a ki pool to function. Any investigator talent which augments studied strike instead affects the vigilante’s sneak attacks.

  - name: bushido
    type: Su
    levels: [3]
    text: As a bushi grows in power, he gains access to abilities through the refinement of his spirit and his weapon by adhering to the principles of bushido. Beginning at 3rd level, a stalker bushi can choose to take a [bushido](/bushido/) in place of a stalker art he would gain.

  - name: Mixed Combat
    type: Ex
    levels: [6]
    text: At 6th level, a bushi gains Mixed Combat as a bonus feat, even if he does not meet the prerequisites. In addition, the bushi is considered to be threatening all adjacent squares even if his weapon is sheathed, and can draw his weapon when making any attack (including attacks of opportunity).

  - name: dual strike
    type: Ex
    levels: [10, 14, 18]
    levels_text:
      10: 1/day
      14: 2/day
      18: 3/day
    text: Once per day at 10th level, the stalker's deadly skill in combat improves, allowing him to initiate two martial strikes as a full round action. The strikes the stalker initiates must have an initiation action of one standard action, and he must have both strikes readied. Boosts may not be applied to a dual strike due to the need to concentrate on two separate martial movements. When a dual strike is used, the action must be declared beforehand and when used, both strikes are resolved separately and are expended. At 14th level the character may use dual strike twice per day, and three times per day at 18th level.

  - name: inspired vengeance
    type: Ex
    levels: [20]
    text: At 20th level, a vigilante has mastered inspiration to such an extent that he instinctively places his attacks in near-perfect paths. The vigilante can use inspiration on any attack roll he makes without spending any points from his pool. In addition, the vigilante can spend one point of inspiration once per round as a free action to to add 1d6 the save DC of a maneuver he initiates.
---

An effective warrior wielding both skill and stealth, the stalker is a martial disciple who battles in the deep shadows and the hidden underworld of night. Through rigorous training and deep, intuitive instincts, the stalker is a trained killer whose very art is considered illegal in some places. Part mystic, part warrior, and part assassin, the stalker's arts are varied, but always deadly.

Bushi are honorable and noble warriors who specialize in Iaijutsu, the art of the draw cut. With a single swing of his katana, a bushi can cleave through armor, bones and organs as easily as straw. Bushi follow the code of bushido and exemplify the virtues of righteousness, courage, benevolence, respect, honesty, honor and loyalty.

**Adventures:** Stalkers adventure for many reasons, but most do so either as part of a guild of fellow stalkers on a mission, for money and profit, or for deeper, often darker purposes of the heart. Some adventure for the test of their skill, but this is slightly rarer; whatever the reason, the path of the stalker is often a self-absorbed one.

**Characteristics:** Stalkers universally are very introspective people, they rely so heavily upon their intuitive reactions to situations and their heightened reflexes through athletic skill that they usually have an air of detachment. Some are braggarts, but many are quiet and calm, paying close attention to their surroundings should they need to use their lethal skills.

**Alignment:** Any. Stalkers do not lean to any particular alignment trend, running the gamut of all walks of life.

**Religion:** Some stalkers are deeply religious, finding solace in their meditations to gods of night, death, travels, or revelry. Other stalkers find no use for gods, for if the gods protected and cared for their flock, then they wouldn't make their followers so easy to kill.

**Background:** Stalkers often arise from the poor and underprivileged who live in city slums, trained from their youth to be unfeeling killers. Others are trained in remote areas in a more monastic fashion, taught to be warriors who strike from the shadows. The training of stalkers can also be an individual thing, each master teaching a student in their own way, the way they were taught.

**Races:** Humans and outcast races tend to be drawn to the path of the stalker. Half-orcs and half-elves make up a majority of the non-human stalkers, with goblinoids coming in next.

**Other Classes:** Stalkers get on well with rogues and rangers due to having complementary roles. Paladins and clerics often chafe when partied with stalkers, as their reputation as killers (rightly or wrongly) often sours opinions of them. Other classes generally have a neutral opinion of stalkers, unless that stalker has come for them.

**Role:** Striker. In the party, the stalker follows the heavily armored fighter into combat, using them as shields and distractions so they can inflict maximum damage on their foes. In addition, the stalker can serve quite well as the party scout, finding danger and warning the party before they stumble upon it.

**Abilities:** Dexterity and Wisdom are prime attributes for stalkers, as many of their skills are governed by these abilities and their combat capabilities are augmented by them as well. Wisdom is the primary initiating attribute for stalker. Strength is valuable for damage, but can fall behind Constitution for endurance in battle.
