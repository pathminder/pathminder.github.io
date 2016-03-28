---
title: Warlord (Vanguard Commander)
sources:
  - Path of War
  - "Path of War: Expanded"
tags:
  - Base
  - Initiator

max_level: 20
hit_die: 10
prerequisites:
starting_age: Self-Taught
starting_wealth: ???

class_skills:
  - Acrobatics
  - Bluff
  - Climb
  - Craft
  - Diplomacy
  - Handle Animal
  - Intimidate
  - Knowledge (engineering)
  - Knowledge (history)
  - Knowledge (martial)
  - Profession
  - Ride
  - Sense Motive
  - Survival
  - Swim
skill_ranks_per_level: 4

bab_progression: full
fort_progression: good
ref_progression: poor
will_progression: good

initiating_progression: full

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

  - name: maneuvers
    levels: [1]
    text: |
      A warlord begins his career with knowledge of six martial maneuvers. The disciplines available to him are Eternal Guardian, Golden Lion, Iron Tortoise, Primal Fury, Scarlet Throne, and Thrashing Dragon. The warlord may also exchange access to one of his martial disciplines for the Unquiet Grave discipline. He gains the associated skill of each of his disciplines as a class skill.

      Once he knows a maneuver, he must ready it before he can use it (see Maneuvers Readied, below). A maneuver usable by warlords is considered an extraordinary ability unless otherwise noted in its description. His maneuvers are not affected by spell resistance, and he do not provoke attacks of opportunity when he initiates one. He learns additional maneuvers at higher levels, as shown on Table 1-3: The Warlord. The warlord must meet a maneuver's prerequisite to learn it.

      Upon reaching 4th level, and at every even numbered warlord level after that, he can choose to learn a new maneuver in place of one he already knows. In effect, the warlord loses the old maneuver in exchange for the new one. He can choose a new maneuver of any level he likes, as long as he observes his restriction on the highest-level maneuvers he knows. The warlord need not replace the old maneuver with a maneuver of the same level. The warlord can swap only a single maneuver at any given level. A warlord's initiation modifier is Charisma.

      *Maneuvers Readied:* A warlord can ready four of his six starting maneuvers, but as he advances in level and learns more maneuvers, he must choose which maneuvers to ready. He readies his maneuvers by going through weapon drills for 10 minutes. The maneuvers he chooses remain readied until he decides to repeat this again and change them. Warlords do not need to sleep or rest for any long period of time to ready their maneuvers; any time he spends 10 minutes in practice, he can change his readied maneuvers. He may not ready any individual maneuver more than once. He begins an encounter with all readied maneuvers unexpended, regardless of how many times he may have already used them since he chose them. When the warlord initiates a maneuver, he expends it for the current encounter, so each of his readied maneuver can be used once per encounter (until they are recovered, see below).

      For a warlord to recover expended maneuvers, he must perform one of two types of actions: a gambit action in which he gambles on his performance in battle (see Warlord's Gambit below), or he may spend a standard action to recover a single readied maneuver of his choosing.

      *Stances Known:* Warlords begin play with knowledge of one stance from any discipline open to warlords. At the indicated levels (see class table), the warlord selects an additional new stance. Unlike maneuvers, stances are not expended and he does not have to ready them. All the stances he knows are available to him at all times, and he can change the stance he is currently using as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance description. Unlike with maneuvers, the warlord cannot learn a new stance at higher levels in place of one he already knows.

  - name: warlord's gambit
    type: Ex
    levels: [1, 4, 8, 12, 16, 20]
    levels_text:
      1: 1 gambit
      4: 2 gambits
      8: 3 gambits
      12: 4 gambits
      16: 5 gambits
      20: 6 gambits
    text: |
      At his core, the warlord is a warrior who relies on both skill and daring; without this he is but any other combatant. By setting himself to danger, does his true skill shine, or so the motto of the warlord goes. At 1st level, the vanguard  commander selects one [gambit](/warlord-gambits/) as a method by which the warlord can recover expended maneuvers, and also gains the [guardian's gambit](/warlord-gambits/guardians-gambit/) gambit. At 4th level and every four levels thereafter, the warlord selects an additional gambit.

      Each gambit possesses three aspects---a risk, a rake, and a reward.

      Each gambit's risk describes an action that the warlord must undertake in order to attempt to recover an expended maneuver. The warlord begins a gambit as a swift action, effectively diving recklessly into the act he is attempting. The warlord then performs the action described in the gambit, and if he is successful, he regains maneuvers (see below). If he is not, he suffers the rake of the gambit and only regains a single maneuver of his choosing. While performing a gambit, the warlord may add his Charisma modifier to the d20 check(s) to aid in accomplishing the gambit as a luck bonus. A warlord may attempt the actions of a gambit, but without declaring the attempt a gambit attempt by spending a swift action to do so, the character does not regain any maneuvers nor does he suffer a rake for failure. The character may initiate a maneuver while performing a gambit (if the maneuver helps him accomplish it) but he may not recover the maneuver used to achieve the gambit as part of the reward.

      A gambit's rake is the penalty that the warlord suffers if he attempts his gambit and fails, such as failing a trip attempt or failing to strike an opponent with a charge attack. All gambits possess the same rake: the warlord only regains a single expended maneuver and suffers a --2 penalty on all d20 rolls for one round.

      A warlord who succeeds at fulfilling his gambit immediately recovers a number of expended maneuvers equal to his Charisma modifier (minimum 2) and enjoys the unique reward for each gambit. Allies who would receive benefits from a warlord's successful gambit must be within 60 ft. of the warlord and must be able to see him perform the action.

      Finally, gambits may not be initiated outside of combat due to their reliance upon the stresses of battle to bring out the best of the warlord.

  - name: Improved Shield Bash
    levels: [1]
    text: The vanguard commander gains the Improved Shield Bash feat as a bonus feat at 1st level.

  - name: bonus feat
    levels: [6, 10, 14, 18]
    levels_text:
      6:  1 feats
      10: 2 feats
      14: 3 feats
      18: 4 feats
    text: At 6th level, and then every four levels after, the warlord gains a bonus combat feat or teamwork feat of his choosing. The warlord must qualify for the feat before selecting it.

  - name: tactical presence
    type: Ex
    levels: [2, 7, 9]
    levels_text:
      2: 1 presence
      5: 2 presences
      7: free action
      9: 3 presences
    text: |
      At 2nd level, the warlord's innate charisma allows his very presence to aid and assist not only himself but his allies as well, just by his being around. Adopting a presence is a move-equivalent action, and only one presence may be maintained at any given time. At 7th level, the warlord is capable of adopting a presence as a free action.

      The warlord gains one [tactical presence](/tactical-presences/) at 2nd level, a second at 5th level, and a third at 9th level.

  - name: warleader
    levels: [3]
    text: |
      The warlord excels in the theater of war because he knows how best to work with his allies. At 3rd level, the warlord becomes an ever more capable commander and may share tactics with his allies. First, the warlord gains a teamwork feat as a bonus feat (he must meet the prerequisites for this feat to select it).

      As a standard action that the warlord performs, the warlord and allies within 30 feet of him can share teamwork feats that they possess with each other, acting as if they both possessed the teamwork feat that they are sharing. The warlord can only share one teamwork feat at a time, either one of his own (with all allies within 30-ft. of him) or an ally's (in which case only the warlord receives the ability to use the teamwork feat he does not possess). The warlord and allies retain the use of this feat for 3 + the warlord's Charisma modifier in rounds. The character may use this ability 1 + Charisma modifier times per day at 3rd level (minimum of 1), and one additional time per day for every four warlord levels the character possesses.

  - name: daring defense
    type: Ex
    levels: [3]
    text: The vanguard commander rushes the enemy lines, heedless of personal danger, with bold charges and bolder personality. This headstrong determination gives rise to vanguard commanders having an almost uncanny luck at avoiding dangers. At 3rd level, the vanguard commander may add his Charisma modifier to his Dexterity modifier to determine his Reflex save bonus. If the character is ever able to add his Charisma modifier to his Reflex save through use of another ability (for example. the paladin's divine grace) he may only add his Charisma modifier once to his Reflex save.

  - name: tactical flanker
    type: Ex
    levels: [4]
    text: At 4th level, the warlord is exceptionally gifted at working with his allies to bring down opponents and his skills assist any who ally with him. When flanking a target with an allied creature, both the warlord and the ally may use the warlord's Charisma modifier (min +2) for the bonus they receive on flanking their opponent.

  - name: defensive prowess
    type: Ex
    levels: [5, 12, 19]
    levels_text:
      5:  "+1"
      12: "+2"
      19: "+3"
    text: The vanguard commander lives to inspire his troops, and by training diligently to best defend himself in the midst of heavy combat he has developed techniques for higher survivability. At 5th level, while in a Golden Lion or Iron Tortoise stance, the vanguard commander reduces his armor check penalty by 1, gains a +1 competence bonus to his existing shield bonus to his Armor Class, and adds a +1 competence bonus to his CMD. This improves by +1 at 12th level, and again at 19th level.

  - name: heightened defenses
    type: Ex
    levels: [6]
    text: The vanguard commander is a capable warrior who can blend both defense and offense together with precision. At 6th level, the character gains an additional immediate action to be used for the purposes of initiating a counter on a round that he initiates a boost. He can use this additional immediate action a number of times per day equal to 1 + his Charisma modifier (minimum of 1).

  - name: vanguard's shield
    type: Ex
    levels: [8]
    text: The vanguard commander is lightning fast with his shield for both defense and offense. At 8th level, whenever the vanguard initiates a melee strike or uses a counter to defend against an attack from an adjacent foe, he may make a shield bash attempt as free action at his full base attack bonus against that creature.

  - name: dual tactical presence
    type: Ex
    levels: [11]
    text: At 11th level, the sight of the warlord on a field of combat inspires multiple feelings in those around him. He may select and use two presences, activating them together as a free action.

  - name: improved warleader
    levels: [13]
    text: At 13th level, the warlord's excellence in battle has enabled him to utilize the tactical skills of his allies as well as his own with greater speed. The warlord may now use his warleader class feature as a move action.

  - name: warlord's presence
    type: Ex
    levels: [15]
    text: At 15th level, the warlord is capable using three of his presences together at the same time, activating them together as a free action.

  - name: master warleader
    levels: [17]
    text: At 17th level, the warlord's peerless ability in the theater of war has enabled him to utilize the tactical skills of his allies as well as his own with the greatest of speed. The warlord may now use his warleader class feature as a swift action.

  - name: dual stance
    type: Ex
    levels: [20]
    text: At 20th level, the warlord's ability to use his stances improves, allowing him to gain the benefits of two known stances simultaneously. He must still adopt each stance individually, requiring him to expend one swift action for each stance.
---

Dynamos on the field of combat, warlords walk the line of victory and ruin through their determination to achieve glory. Where some may talk tactics, the warlord dives in. Where some may fight in strategic units, the warlord shines alone as an inspirational beacon on the field of combat; to be a warlord is to be a lord of war.

**Adventures:** Warlords adventure for many reasons, but one reason that will always be prominent is the desire to test their skill against the world's most dangerous opponents, to show their strength to themselves and to the world. Others may do this for profit, others for fun, others for revenge, but it is always certain that a warlord seeks the glory and honor only a battle well-fought can bring.

**Characteristics:** Brash arrogance and an irrepressible nature are hallmarks of the warlord. A devil-may-care warrior, many warlords are as fearless as they are fierce, and they both love life and live their lives to the fullest. Hedonists in some extreme cases, the warlord is drawn to combat as a moth to the flame.

**Alignment:** Any. Warlords can come from any and all ethical backgrounds, though they do tend more towards a chaotic alignment. Lawfully aligned warlords are rarer, and tend to compose their impulses through strict discipline.

**Religion:** While not overly religious, some warlords follow gods of war and battle with temperaments similar to their own.

**Background:** Warlords come from families with strong warrior traditions, from barbaric tribes and from academies that produce the strongest warriors. One thing that sets them apart is their reckless nature and the inspirational presence they possess.

**Races:** Humans and half-elves are prominent warlord races due to both possessing an impetuous nature. Half-orcs become very fearsome warlords in their own right, and dwarves are known for their ferocity when defending their homes.

**Other Classes:** Warlords get on well with fighters, rangers, and barbarians as their martial nature makes them amicable, but paladins and warders tend to chafe under their recklessness. Wizards and especially bards and sorcerers get on quite well with them, and clerics find them to be tolerable.

**Role:** Striker. As a very aggressive class, the warlord seeks to bring martial power to the field in the form of overwhelming force and ferocity. Additionally, warlords make excellent leaders, as they provide some passive benefits from their class features as well as active benefits from discipline choices and their gambits.

**Abilities:** Strength and Charisma are incredibly important to a warlord, as without Strength the warlord is weaker in combat and without Charisma many of his abilities will not function, as Charisma is the warlord's primary initiation attribute. Constitution is important for vital hit points. Intelligence and Dexterity take up the bottom of importance, for both skill points and defense (or ranged combat).
