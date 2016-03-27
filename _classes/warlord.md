---
title: Warlord
sources:
  - Path of War
tags:
  - Initiator

max_level: 20
hit_die: 10
prerequisites:
starting_age: Self-Taught
starting_wealth: ???

class_skills:
  - Acrobatics
  - Climb
  - Craft
  - Diplomacy
  - Handle Animal
  - Intimidate
  - Knowledge (engineering)
  - Knowledge (history)
  - Knowledge (martial)
  - Perception
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
shield_proficiencies:
  - Shields

class_features:

  - name: maneuvers
    levels: [1]
    text: |
      A warlord begins his career with knowledge of six martial maneuvers. The disciplines available to him are Golden Lion, Primal Fury, Scarlet Throne, Solar Wind, and Thrashing Dragon. Once he knows a maneuver, he must ready it before he can use it (see Maneuvers Readied, below). A maneuver usable by warlords is considered an extraordinary ability unless otherwise noted in its description. His maneuvers are not affected by spell resistance, and he do not provoke attacks of opportunity when he initiates one. He learns additional maneuvers at higher levels, as shown on Table 1-3: The Warlord. The warlord must meet a maneuver's prerequisite to learn it.

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
      At his core, the warlord is a warrior who relies on both skill and daring; without this he is but any other combatant. By setting himself to danger, does his true skill shine, or so the motto of the warlord goes. At 1st level, a warlord selects two gambits as methods by which the warlord can recover expended maneuvers. Each gambit possesses three aspects---a risk, a rake, and a reward.

      Each gambit's risk describes an action that the warlord must undertake in order to attempt to recover an expended maneuver. The warlord begins a gambit as a swift action, effectively diving recklessly into the act he is attempting. The warlord then performs the action described in the gambit, and if he is successful, he regains maneuvers (see below). If he is not, he suffers the rake of the gambit and only regains a single maneuver of his choosing. While performing a gambit, the warlord may add his Charisma modifier to the d20 check(s) to aid in accomplishing the gambit as a luck bonus. A warlord may attempt the actions of a gambit, but without declaring the attempt a gambit attempt by spending a swift action to do so, the character does not regain any maneuvers nor does he suffer a rake for failure. The character may initiate a maneuver while performing a gambit (if the maneuver helps him accomplish it) but he may not recover the maneuver used to achieve the gambit as part of the reward.

      A gambit's rake is the penalty that the warlord suffers if he attempts his gambit and fails, such as failing a trip attempt or failing to strike an opponent with a charge attack. Each gambit possesses a unique reward that the warlord enjoys for succeeding at that gambit. All gambits possess the same rake; the warlord only regains a single expended maneuver and suffers a -2 penalty on all d20 rolls for one round. A warlord who succeeds at fulfilling his gambit immediately recovers a number of expended maneuvers equal to his Charisma modifier (minimum 2) and enjoys the unique reward for each gambit. Allies who would receive benefits from a warlord's successful gambit must be within 60-ft. of the warlord and must be able to see him perform the action. Finally, gambits may not be initiated outside of combat due to their reliance upon the stresses of battle to bring out the best of the warlord.

      At 4th level and every four levels thereafter, the warlord selects an additional gambit.

      **Acrobatic Gambit:** *Risk:* The warlord attempts an Acrobatics check to move through an opponent's threatened area. *Reward:* The warlord's brash move allows attacks against the opponent or opponents that the warlord evaded this round to inflict an additional 1d6 + his Charisma modifier points of damage upon a successful hit. This damage is not multiplied on a critical hit.

      **Brave Gambit:** *Risk:* The warlord attempts to make a successful charge attack against an opponent (if the character has the ability to make multiple attacks at the end of a charge, the initial first attack must be successful for this gambit's success). *Reward:* The warlord's actions embolden his allies and sets his spirit alight with courage; the warlord and his allies gain a morale bonus to damage equal to the warlord's Charisma modifier on the next attack they make or until the warlord's next turn.

      **Cavalry Gambit:** *Risk:* The warlord attempts a successful mounted charge attack or mounted overrun maneuver against a target creature. *Reward:* The warlord's opponent's defense is unbalanced; the warlord and his allies gain a morale bonus equal to his Charisma modifier on attacks of opportunity against that foe until the warlord's next turn.

      **Dastardly Gambit:** *Risk:* The warlord attempts a successful dirty trick maneuver against an opponent. *Reward:* The warlord and his allies are filled with malicious glee to attack the warlord's foe, and gain his Charisma modifier as a morale bonus to damage rolls to a single attack against this target until the warlord's next turn.

      **Deadeye Gambit:** *Risk:* The warlord attempts a successful called shot maneuver on a target opponent. *Reward:* The warlord's incredible accuracy livens up his allies and restores to them a measure of spirit; the warlord and his allies gain temporary hit points equal to the warlord's Charisma modifier (persisting until the end of the encounter or until they are used), helping them ignore the pains of their injuries and continue the fight.

      **Duelist's Gambit:** *Risk:* The warlord attempts to successfully use the disarm maneuver against an opponent. *Reward:* The warlord's opponent is disarmed of a weapon and then the warlord may make an immediate attack of opportunity against his foe and gains a morale bonus to damage equal to his Charisma modifier if the attack is successful.

      **Gatecrasher Gambit:** *Risk:* The warlord attempts a successful bull rush maneuver against an opponent. *Reward:* The opponent is so rattled by the warlord's deft bull rush, that he suffers a penalty equal to the warlord's Charisma modifier for one round on all d20 checks.

      **Grappler Gambit:** *Risk:* The warlord attempts a successful grapple maneuver against an opponent. *Reward:* When the warlord has his enemy pinned and he chooses to inflict damage upon him, the warlord adds a morale bonus to damage equal to his Charisma modifier until the foe successfully escapes the grapple.

      **Outrider's Gambit:** *Risk:* The warlord attempts a successful ranged attack while on a moving mount. The mount must move 10 feet or more to use this gambit. *Reward:* The warlord success allows his allies to reap the benefits of his skill; allies who make ranged attacks against this target opponent add the warlord's Charisma modifier as a morale bonus to their next attack roll.

      **Pinhole Gambit:** *Risk:* The warlord attempts to successfully use a ranged attack against an opponent engaged in melee with an ally. *Reward:* The successful and surprising attack against the foe shakes the enemy's confidence and harms its ability to defend itself; the warlord's Charisma modifier is applied as a penalty to its Armor Class until the warlord's next turn.

      **Rascal's Gambit:** *Risk:* The warlord attempts to successfully feint an opponent. *Reward:* The warlord throws off his opponents defenses with his feint, and the foe is considered flat-footed until its next turn.

      **Ravager's Gambit:** *Risk:* The warlord attempts a successful sunder maneuver against an opponent. *Reward:* The warlord's sundering attack ignores a portion of his foe's weapon's hardness equal to his Charisma modifier.

      **Sweeping Gambit:** *Risk:* The warlord attempts a successful trip maneuver against an opponent. *Reward:* The warlord trips his foe and may make an immediate attack of opportunity against that foe, adding his Charisma modifier as a morale bonus to the damage he inflicts if successful.

      **Unbreakable Gambit:** *Risk:* The warlord attempts to succeed on a Fortitude or Will save against an extraordinary ability, maneuver, power, spell, or spell-like or supernatural ability. The effect in question must not be a harmless effect on a failed saving throw. Unlike other gambits, this one can be attempted as an immediate action instead of a swift action. *Reward:* The warlord is emboldened by his ability to resist his opponent's attack, and regains a number of hit points equal to three times his Charisma modifier.

      **Victory Gambit:** *Risk:* The warlord successfully reduces an opponent to 0 or few hit points with a melee or ranged attack on his turn from either a standard attack or full attack action. *Reward:* The warlord and his allies gain a morale bonus on attack rolls equal to his Charisma modifier on their next attack roll.

  - name: bonus feat
    levels: [1, 6, 10, 14, 18]
    levels_text:
      1: 1 feat
      6: 2 feats
      10: 3 feats
      14: 4 feats
      18: 5 feats
    text: At 1st level and at 6th level, and then every four levels after, the warlord gains a bonus combat feat or teamwork feat of his choosing. The warlord must qualify for the feat before selecting it.

  - name: tactical presence
    type: Ex
    levels: [2, 7, 9]
    levels_text:
      7: free action
      9: victorious
    text: |
      At 2nd level, the warlord's innate charisma allows his very presence to aid and assist not only himself but his allies as well, just by his being around. Adopting a presence is a move-equivalent action, and only one presence may be maintained at any given time. At 7th level, the warlord is capable of adopting a presence as a free action.

      *Indomitable Presence:* At 2nd level, the warlord shines as a beacon to his allies on the field of battle, inspiring them to fight with him to their last breath. All allies within 30-ft. of his position gain the benefits of the Die Hard feat, and may add the warlord's Charisma modifier to Fortitude saves versus death effects, fatigue or exhaustion effects, or poison effects as a morale bonus.

      *Rallying Presence:* The sight of a warlord on the battlefield is enough to strengthen the hearts and wills of those who fight beside him in battle. At 5th level, the warlord may add his Charisma modifier as a morale bonus to Will saves versus fear, death effect, or compulsion effects to all allies within 30-ft. of his position. If the warlord maintaining this presence becomes cowed, frightened, panicked or falls prey to a hostile mind-affecting ability (such as one that would stun or daze him), compulsion or death effect, this presence immediately ends.

      *Victorious Presence:* The preternatural skill at arms that a warlord of at this level possesses is enough to win any battle. At 9th level, any foe that the warlord brings to 0 or fewer hit points in battle immediately fuels his hunger for the win, granting him and his allies within 30-ft. of his position the character's class level plus Charisma modifier in temporary hit points. These hit points endure until they are lost or until the end of the encounter, whichever occurs first. Damage inflicted on the warlord is deducted from his temporary hit points first before being deducted from his normal hit point total.

  - name: warleader
    levels: [3]
    text: |
      The warlord excels in the theater of war because he knows how best to work with his allies. At 3rd level, the warlord becomes an ever more capable commander and may share tactics with his allies. First, the warlord gains a teamwork feat as a bonus feat (he must meet the prerequisites for this feat to select it).

      As a standard action that the warlord performs, the warlord and allies within 30 feet of him can share teamwork feats that they possess with each other, acting as if they both possessed the teamwork feat that they are sharing. The warlord can only share one teamwork feat at a time, either one of his own (with all allies within 30-ft. of him) or an ally's (in which case only the warlord receives the ability to use the teamwork feat he does not possess). The warlord and allies retain the use of this feat for 3 + the warlord's Charisma modifier in rounds. The character may use this ability 1 + Charisma modifier times per day at 3rd level (minimum of 1), and one additional time per day for every four warlord levels the character possesses.

  - name: force of personality
    type: Ex
    levels: [3]
    text: At 3rd level, the warlord's forceful personality and bold, headstrong nature assist him in resisting the influence of others. Where others use personal serenity, awareness of the world around them, or plain old sensibility, the warlord gets by with endless nerve. The warlord may add his Charisma modifier in addition to his Wisdom modifier to determine his Will save bonus. If the character is ever able to add his Charisma modifier to his Will save through use of another ability (for example. the paladin's divine grace) he may only add his Charisma modifier once to his Will save.

  - name: tactical flanker
    type: Ex
    levels: [4]
    text: At 4th level, the warlord is exceptionally gifted at working with his allies to bring down opponents and his skills assist any who ally with him. When flanking a target with an allied creature, both the warlord and the ally may use the warlord's Charisma modifier (min +2) for the bonus they receive on flanking their opponent.

  - name: battle prowess
    type: Ex
    levels: [5, 12, 19]
    levels_text:
      5:  "+1, 1 discipline"
      12: "+2, 2 disciplines"
      19: "+3, 3 disciplines"
    text: The warlord is a skilled combatant, mixing traditional fighting skills with the skill of his martial discipline training. Choose a discipline, and when the warlord is in a martial stance from this chosen discipline, the character gets the listed bonus (+1 at 5th level, +2 at 12th level, +3 at 19th level) as a competence bonus to attack and damage rolls, CMB rolls, and to his CMD. He may select another discipline at 12th level, and third discipline at 19th level.

  - name: dual boost
    type: Ex
    levels: [6, 12, 18]
    levels_text:
      6: 1/day
      12: 2/day
      18: 3/day
    text: Knowledgeable in the ways of making the best of any situation through pluck and verve, the warlord is capable of applying multiple martial principles simultaneously. At 6th level, once per day the warlord may initiate two boost type maneuvers as part of the same swift action. He may use this an additional time per day at 12th level, and three times per day at 18th level.

  - name: tactical assistance
    type: Ex
    levels: [8]
    text: At 8th level, the warlord's gift for helping his allies in combat improves. The character may use the Aid Another action for any single ally within 30 feet of his position as a move action, and he uses his Charisma modifier for the bonus he grants to his ally's action (minimum +2).

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
