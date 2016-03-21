---
title: Zealot
sources:
  - "Path of War: Expanded"

max_level: 20
starting_age: Self-Taught
starting_wealth: 5d6 × 10 gp (average 175 gp)
hit_die: 10

class_skills:
  - Autohypnosis
  - Bluff
  - Craft
  - Diplomacy
  - Heal
  - Intimidate
  - Knowledge (history)
  - Knowledge (martial)
  - Knowledge (nobility)
  - Knowledge (psionics)
  - Knowledge (religion)
  - Perception
  - Profession
  - Sense Motive
skill_ranks_per_level: 4

bab_multiplier: 1

fort_adder: 4
fort_multiplier: 0.5

ref_adder: 1
ref_multiplier: 0.3333

will_adder: 4
will_multiplier: 0.5

initiating_progression: full
manifesting_progression: zealot

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
      A zealot begins his career with knowledge of five martial maneuvers. The disciplines available to him are Eternal Guardian, Golden Lion, Piercing Thunder, Sleeping Goddess, and Solar Wind.

      Once the zealot knows a maneuver, he must ready it before he can use it (see Maneuvers Readied, below). A maneuver usable by zealot is considered an extraordinary ability unless otherwise noted in it or its discipline's description. A zealot's maneuvers are not affected by spell resistance, and he does not provoke attacks of opportunity when he initiates one.

      The zealot learns additional maneuvers at higher levels, as indicated on Table 1-3: Zealot. A zealot must meet a maneuver's prerequisite to learn it. See the Systems and Use chapter in Path of War for more details on how maneuvers are used.

      Upon reaching 4th level, and at every even numbered initiator level thereafter (6th, 8th, 10th, and so on), the zealot can choose to learn a new maneuver in place of one he already knows. In effect, he loses the old maneuver in exchange for the new one. He can choose a new maneuver of any level he likes, as long as he observes the restriction on the highest-level maneuvers he knows; the zealot need not replace the old maneuver with a maneuver of the same level. He can swap only a single maneuver at any given level. A zealot's initiation modifier is Charisma.

      **Maneuvers Readied:** A zealot can ready three of his five maneuvers known at 1st level, and as he advances in level and learns more maneuvers, he is able to ready more, but must still choose which maneuvers to ready. A zealot must always ready his maximum number of maneuvers readied. He readies his maneuvers by meditating for ten minutes. The maneuvers he chooses remain readied until he decides to meditate again and change them. The zealot does not need to sleep or rest for any long period of time in order to ready his maneuvers; any time he spends ten minutes in contemplation, he can change his readied maneuvers.

      A zealot begins an encounter with all his readied maneuvers unexpended, regardless of how many times he might have already used them since he chose them. When he initiates a maneuver, he expends it for the current encounter, so each of his readied maneuvers can be used once per encounter (unless he recovers them, as described below).

      In order for the zealot to recover maneuvers, he must activate his zeal class feature by using the Aid Another action. Using the Aid Another action in this way is a move action, and when he does so, he recovers a number of expended maneuvers equal to his zealot initiation modifier (minimum 2), regardless of whether or not the Aid Another attempt was successful. Maneuvers initiated during the zealot's current turn cannot be recovered in this way. Using the Aid Another action as any other action (such as with the Bodyguard feat or the *battlesense* power) does not allow the zealot to recover maneuvers. Alternately, the zealot may focus inwards, meditating and recovering a single maneuver as a standard action.

      **Stances Known:** A zealot begins his career with knowledge of one stance from any discipline open to zealots. At 2nd, 5th, 9th, 11th, 15th, and 18th levels, he can select an additional stance to learn. Unlike maneuvers, stances are not expended and the zealot does not have to ready them. All the stances he knows are available to him at all times, and he can change the stance he is currently maintaining as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance or discipline description.

      Unlike with maneuvers, a zealot cannot learn a new stance at higher levels in place of one he already knows.

  - name: power points
    levels: [1]
    text: |
      A zealot's ability to augment some of his abilities is limited by the power points he has available. His base daily allotment of power points is given on Table: The Zealot. In addition, he receives bonus power points per day if he has a high Charisma score (see Table 2-1: Ability Modifiers and Bonus Power Points, in Chapter 2 of Ultimate Psionics), treating his class level as his effective manifester level for the purposes of bonus power points. His race may also provide bonus power points per day, as may certain feats and items. This effective manifester level does not make a zealot eligible for feats and prestige classes requiring a manifester level.

  - name: collective
    type: Su
    levels: [1, 15, 19]
    levels_text:
      15: unlimited range
      19: planar
    text: |
      A zealot learns to use psionic power to connect willing minds through an internal network that strengthens their psychic bonds. As a standard action, a zealot can join any number of willing targets into his collective (up to his limit, see below). The zealot must have line of sight to each target, each target must have a Wisdom score of at least 1, and all targets must be within medium range (100 feet + 10 feet per zealot level). The collective can contain up to his zealot initiation modifier or half his zealot level (minimum 1), whichever is higher, plus the intensity of his zeal (see zeal, below). The zealot is always considered a member of his own collective, and does not count against the maximum number of creatures in the collective.

      The zealot can choose to remove a member as a free action on his turn, and any member can voluntarily leave the collective as a free action on their turn. Any member whose Wisdom drops to zero or who moves out of range of the collective is automatically removed. If a member enters a null psionics field, the connection to the collective is suppressed until the member leaves the field. A member who leaves the collective for any reason immediately loses any and all benefits they may have gained from being a member. A zealot is aware of the status of his collective and can, roughly, sense the presence of each member, although beyond telling if such a creature is still a member, this has no mechanical benefit until higher levels (see telepathy below).

      A zealot can initiate certain maneuvers through his collective. If a zealot maneuver specifies one or more willing targets (or is harmless) and has a range greater than personal, he can initiate this maneuver on a member of his collective regardless of the range of the actual maneuver. All other non-range restrictions still apply.

      If he is capable of manifesting powers, casting spells, or initiating maneuvers from a different class (as is the case for a multiclass zealot), any compatible spell, power, or maneuver with a range greater than touch can also be used through the collective. He may manifest any power with the Network descriptor this way, regardless of their actual ranges or targets.

      If a member of the collective dies, the member is removed from the collective and the zealot must make a Fortitude save (DC 15) or lose 1 power point for every Hit Die of the fallen member or be sickened for an equal number of rounds.

      At 15th level, a zealot's collective range is limitless on the same plane as the zealot

      At 19th level, a zealot's range reaches even across other planes and dimensions.

  - name: zeal
    type: Su
    levels: [1, 5, 10, 15, 20]
    levels_text:
      1: +1
      5: +2
      10: +3
      15: +4
      20: +5
    text: |
      The zealot's martial competence and inspiring exhortations give his collective the courage to fight no matter the odds. Whenever a zealot successfully hits an opponent with a strike maneuver, all allies in his collective (including him) gain a +1 morale bonus on attack rolls for one round. This bonus increases by +1 at 5th level and every five levels thereafter.

      A zealot's zeal is also activated when he uses the Aid Another action as to recover maneuvers (regardless of whether or not the Aid Another attempt was successful). In addition, when he uses the Aid Another action to grant an ally a bonus on a skill check or to their AC, he adds the intensity of his zeal to the bonus granted.

      In addition, the zealot's ardor for his beliefs draws others to follow and support him. The zealot adds the intensity of his zeal to the maximum number of creatures he may have in his collective.

  - name: compartmentalized aid
    type: Ex
    levels: [1]
    text: A zealot can mentally divide a fraction of himself to objectively analyze his actions, allowing him to use the Aid Another action on himself to grant himself a bonus to an attack roll or AC and recover maneuvers (and activating the zealot's zeal class feature). When he does so, the bonus applies to an attack that comes before the end of his next turn. In addition, he can use the Aid Another action with a ranged attack as long as he is within his weapon's first range increment.

  - name: burning contemplation
    type: Ex
    levels: [2]
    text: Starting at 2nd level, a zealot's inner fire allows him to unlock latent psionic potential within himself. For the purpose of qualifying for psionic feats, he may use his Charisma score instead of his Wisdom score.

  - name: conviction
    levels: [2, 6, 10, 14, 18]
    text: |
      In addition to his purpose and plans, a zealot champions minor beliefs and practices. At 2nd level and every four levels thereafter, a zealot gains a conviction from the following list. Unless otherwise noted, a zealot cannot select an individual conviction more than once. Some convictions can only be taken if the zealot meets certain prerequisites first, as noted in the individual conviction's description.

      - *Combat Conviction:* The zealot gains a combat feat he qualifies for as a bonus feat. After the zealot reaches 10th level, he can gain this conviction a second time.
      - *Enduring Zeal (Su):* When the zealot activates his zeal class feature, he can spend up to 1 power point per zealot level to extend the duration of his zeal by a number of rounds equal to the power points spent.
      - *Hearten the Mindless (Su):* Creatures in the zealot's collective that are mindless or immune to mind-affecting effects still benefit from his zeal class feature, gaining morale bonuses as if they were not mindless or immune to mind-affecting effects.
      - *Improved Zeal (Su):* Whenever the zealot activates his zeal class feature, he can choose to pay 2 power points. If he does so, the intensity of his zeal increases by 1 for that use of his zeal class feature. A zealot must be at least 6th level before selecting this conviction.
      - *Impulsive Reactions (Ex):* The zealot gains Combat Reflexes as a bonus feat, even if he does not meet the prerequisites. He uses his zealot initiation modifier instead of his Dexterity modifier to determine the number of additional attacks of opportunity he can make each round.
      - *Path of Dedication (Su):* As a move action, the zealot can grant one willing member of his collective a move action to move (even if it isn't their turn). This movement must be taken immediately, and provokes attacks of opportunity as normal. The zealot can use this ability only once per round.
      - *Path of Dedication, Improved (Su):* Whenever the zealot initiates a boost or counter, the zealot can pay 3 power points to activate his Path of Dedication conviction as a free action, even if it isn't his turn. This is not considered an augment and does not count against the maximum amount of power points the zealot can spend on the maneuver. In addition, he can expend psionic focus when using the Path of Dedication conviction to grant its effects to all willing members of his collective, including himself. The zealot may still only use this ability once per round. A zealot must be at least 10th level and possess the Path of Dedication conviction before selecting this conviction.
      - *Personality Fragment (Ex):* The zealot gains Psicrystal Affinity as a bonus feat, even if he does not meet the prerequisites. He uses his initiator level in place of his manifester level for the purpose of determining the power of his psicrystal and for qualifying for the Psicrystal Containment feat. The zealot's psicrystal is always a member of his collective, and does not count towards the maximum number of creatures in his collective.
      - *Psionic Conviction:* The zealot gains a psionic feat he qualifies for as a bonus feat. After the zealot reaches 10th level, he can gain this conviction a second time.
      - *Strike of Unity (Su):* The zealot can spend 5 power points when initiating a strike to initiate that maneuver through a member of the zealot's collective. The strike is resolved in all ways as if the zealot's ally had initiated it (in terms of base attack bonus, weapons, feats, line of sight, reach, cover, etc.). This is not considered an augment and does not count against the maximum amount of power points the zealot can spend on the maneuver. A zealot must be at least 10th level before selecting this conviction.
      - *Tempered Body (Ex):* The zealot's incredible dedication allows him to weather serious and even fatal attacks. When a critical hit or sneak attack is scored on the zealot, there is a 25% chance that the critical hit or sneak attack is negated and damage is instead rolled normally. This does not stack with similar abilities that negate critical hits and sneak attacks (such as the fortification armor special ability). The zealot can take this conviction up to three times; its effects stack, increasing the chance of negation by 25% each time he takes it.

  - name: martyrdom
    type: Su
    levels: [2, 7, 12, 17]
    levels_text:
      3: 3
      7: 4
      12: 5
      17: 6
    text: |
      At 2nd level, the zealot learns to share the immense pain and suffering his allies must face to fulfill their calling. Once per round, when a willing member of the zealot's collective other than himself takes hit point damage from an opponent, the zealot can redirect up to 5 points of damage per zealot level to himself as a free action, even if it isn't his turn. Effects other than hit point damage (such as poison, stunning, or ability damage) are not reduced or transferred. Damage the zealot redirects to himself with this ability ignores any form of damage reduction, resistance, immunity or regeneration the zealot may possess. When the zealot activates this ability, he can pay up to 1 power point per zealot level to negate 3 points of the damage redirected to him per power point spent (to a minimum of 1 point of damage taken).

      Starting at 7th level, if one of the zealot's allies takes ability damage, the zealot may choose to take up to 1 point of that ability damage per three zealot levels in place of the ally. When the zealot activates this ability, he can pay up to 1 power point per zealot level to negate 1 point of this ability damage redirected to him per 2 power points spent. In addition, he now negates 4 points of redirected hit point damage per power point spent.

      Starting at 12th level, the zealot can use his martyrdom ability on each creature in his collective once per round, and he now negates 5 points of redirected hit point damage per power point spent.

      Starting at 17th level, the zealot automatically negates the first 10 points of damage redirected each time he uses this ability (to a minimum of 1 point of damage taken), and negates 6 points of redirected hit point damage per power point spent.

  - name: commitment
    type: Su
    levels: [3]
    text: The fervor a zealot ignites in his allies does not end at the limits of his physical body. As his allies internalize his beliefs, they increasingly feel the zealot's presence beside them even in the harshest circumstances. Starting at 3rd level, a zealot can use the Aid Another action on any member of his collective, regardless of distance.

  - name: telepathy
    type: Su
    levels: [3]
    text: When a zealot reaches 3rd level, all willing members of his collective (including the zealot himself ) can communicate with each other telepathically, even if they do not share a common language. Psionic creatures who are willing members in a zealot's collective (including the zealot himself) may manifest unknown powers from powers known by another willing psionic creature in the collective as if they were making physical contact.

  - name: echoes of steel
    type: Su
    levels: [4, 11]
    levels_text:
      4: 1
      11: 2
    text: |
      As a zealot continues to mold the hearts and minds of those around them, his collective begins to copy his words and his deeds, working to advance his cause. At 4th level, this manifests in the ability to temporarily psychically transfer the zealot's techniques.

      When the zealot initiates a maneuver at least one level below his maximum maneuver level known, he can spend 1 power point per maneuver level to grant a member of his collective the ability to initiate that maneuver one time within 1 minute or until the zealot chooses to recover the maneuver. This is not considered an augment and does not count against the maximum amount of power points the zealot can spend on the maneuver.

      The maneuver becomes a known and readied maneuver for that ally, using the zealot's initiator level and initiation modifier. After the zealot's ally initiates the maneuver or 1 minute passes, it is expended and the echo ends. This does not cause the creature to unlearn a maneuver it knows from other sources.

      If the zealot recovers the granted maneuver, this ability ends immediately and the maneuver is removed from the ally. This ability does not allow a creature to have two of the same maneuver readied. The zealot can only have one echoed maneuver at a time; using this ability ends any previous use. A creature can only have an echoed maneuver from one zealot at a time, but a creature may end any echoed maneuver on them as a free action (even if it isn't their turn).

      At 11th level, the zealot can grant up to two echoed maneuvers at a time. Any given creature may still only know one echoed maneuver at one time. Granting another echoed maneuver while the zealot already has two maneuvers echoed causes the oldest echoed maneuver to be expended and removed from the creature benefiting from it.

  - name: mission
    type: Su
    levels: [4, 8]
    levels_text:
      4: focus
      8: augments
    text: |
      The zealot is defined by his cause. Zealots might pray for guidance on what mission to choose, receive orders through dark, mysterious whispers, decide for themselves after careful analysis, or simply pursue the task that fate puts before them. At 4th level, the zealot chooses a mission, granting him a benefit when he is psionically focused and an ability that can be used by expending his psionic focus.

      Starting at 8th level, a zealot's mission grants him the ability to augment his maneuvers by spending power points. A zealot can spend a maximum number of power points augmenting a maneuver equal to one plus one additional power point for every four initiator levels he possesses (up to a maximum of 6 at 20th level). If the zealot has the ability to augment his maneuvers in other ways, such as from another class feature or the maneuver itself, this cannot be combined with the augments granted by his mission; he must choose which augmentation type to use when initiating the maneuver.

      **Creation:**

      *Eternal Rebirth (Su):* The zealot's psyche resists the death of those in his collective, giving them a chance to be reborn after a fatal blow. At 4th level, as long as the zealot maintains psionic focus, creatures in his collective that have died within 1 round can still benefit from healing and remain in the collective for 1 round (though the zealot must still make a Fortitude save a normal for a creature in his collective dying). If the dead creature is healed so that the creature's hit point total is at a negative amount less than its Constitution score, it comes back to life and stabilizes at its new hit point total without leaving the zealot's collective. Creatures brought back to life through this effect gain a temporary negative level that lasts for 1 day. Creatures slain by death effects cannot be saved by this effect. In addition, the zealot can expend psionic focus as a free action and pay any amount of power points up to his zealot level to heal a member of his collective for 4 hit points for every power point spent; a creature cannot benefit from this ability more than once per round.

      *Impossible Epiphany (Su):* The zealot's strikes draw out the bounty of the universe, causing existence itself to bring forth matter to bind and control his foes. At 8th level, the zealot gains the ability to augment his strikes in one or more of the following ways:

      - For every 2 power points the zealot spends, a 10-foot-square wall of ectoplasm that lasts for 1 minute appears within 30 feet of one member of the zealot's collective, using his zealot level as his manifester level. Creatures benefiting from the zealot's zeal ability can walk through the wall unimpeded, although the wall still blocks line of sight and line of effect.
      - For every 3 power points the zealot spends, he may temporarily suppress one of the following harmful conditions affecting a member of his collective for a number of rounds equal to his initiator level. This does not end the effect causing the condition; it just suspends that condition's effect for the duration. Spells or effects with durations expire normally, even while suppressed. A spell or effect with a duration greater than that of the suppression effect resumes functioning normally when the suppression ends. The zealot can suppress any one of the following conditions: blinded, confused, dazed, dazzled, deafened, fatigued, frightened, paralyzed, shaken, or sickened.

      **Destruction:**

      *Crushing Blows (Su):* By striking at the fundamental nature of the objects and creatures he wishes to destroy, the zealot can shatter them as easily as brittle vessels. At 4th level, as long as the zealot is psionically focused, his attacks ignore hardness and damage reduction up to double the intensity of his zeal. In addition, the zealot can expend psionic focus as a free action, allowing each member of his collective's attacks to ignore hardness and automatically overcome damage reduction for one round.

      *Storm of Steel (Su):* The zealot's attacks strain and crack the bounds of reality, allowing him to strike once to cause a whole wave of foes to fall. At 8th level, the zealot gains the ability to augment his strikes in one or more of the following ways:

      - For every power point the zealot spends, this strike deals an additional 1d8 points of damage of the zealot's active energy type. For every 2d8 he increases the damage by, the save DC of this strike increases by +1. If the strike involves multiple attacks, this additional damage is only added to the first attack that hits.
      - If the zealot spends power points equal to the maximum number of power points he can spend to augment a maneuver (3 at 8th level, 4 at 12th level, and so on), his strike affects all opponents within a 15-foot cone or 20-foot line. Ranged attacks affect opponents extending from the initiator's location. The zealot makes a single attack roll and compares it to the AC of each creature within the area. If the strike allows a saving throw, each target may make one. Only strikes with an initiation action of 1 standard action may be augmented in this fashion, and this augment replaces the strike's normal targets and affected area.

      **Protection:**

      *Living Bastion (Su):* When a zealot's allies are wounded from battle, they can find a refuge at his side. At 4th level, as long as the zealot is psionically focused, his reach increases by 5 feet. In addition, whenever an ally within his reach takes hit point damage, the zealot can expend psionic focus as a free action (even if it isn't his turn) to surround the ally with a telekinetic shield which reduces the damage they take by half (after applying damage reduction and energy resistance). A creature can only benefit from this ability once per round.

      *Unbreakable Fortress (Su):* The zealot is a bastion of defense, every blow he strikes not only harms his enemies, but it also protects his allies. At 8th level, the zealot gains the ability to augment his counters in one or more of the following ways:

      - The zealot can spend power points to grant each member of his collective damage reduction/– equal to the level of the maneuver initiated for one round per power point spent.
      - If the zealot spends 1 power point per level of the maneuver, he can initiate the counter as a free action instead of an immediate action, even if it isn't his turn. The zealot may use this augment only once per round, and he cannot augment a counter of higher than 6th level with this ability.

  - name: defiance
    type: Su
    levels: [5]
    text: At 5th level, the zealot learns to continue supporting his allies while hanging on to his last breath. The zealot gains Diehard as a bonus feat (even if he do not meet the prerequisites), and does not take damage for using the Aid Another action while at or below 0 hit points. In addition, the zealot does not die until he reaches negative hit points equal to his zealot level plus his constitution score.

  - name: unshakable will
    type: Su
    levels: [9]
    text: At 9th level, the zealot is able to maintain his concentration even after dire setbacks. The zealot automatically succeed on the Fortitude save when a member of his collective dies, and automatically succeeds on Aid Another checks to grant a member of his collective a bonus to attack rolls or AC.

  - name: stalwart
    type: Ex
    levels: [13]
    text: Starting at 13th level, a zealot can use mental and physical resiliency to avoid certain attacks. If he makes a successful Fortitude or Will saving throw against an attack that has a reduced effect on a successful save, he instead avoids the effect entirely. A helpless zealot does not gain the benefit of the stalwart ability.

  - name: metaphysical transcendence
    type: Su
    levels: [16, 20]
    levels_text:
      16: allies
      20: self
    text: |
      At 16th level, the zealot breaks the limitations between ideals and existence; as a word lasts beyond the life the one who spoke it, so the zealot and his allies persist beyond their own mortality. As long as their visions are still carried out, the zealot and his collective can not truly be destroyed. When a member of his collective dies, the creature's soul merges with his collective for up to one day per zealot level. During this time, it can be affected by *psionic revivify*, raise dead and similar abilities as if it died within 1 round, without need for the creature's corpse. The creature still counts towards the maximum number of creatures in his collective while merged. If the zealot dies, the creature's soul departs, killing it.

      At 20th level, when the zealot dies, he can choose to merge with his own collective. While he is merged with his collective, his collective continues to function and he can continue to use the Aid Another action, add creatures to his collective, remove creatures from his collective, and merge souls with his collective. Only if all other members of the zealot's collective die does the zealot die.
---

A warhawk politician grimly but eloquently calls for the destruction of a hated enemy. A loyal guard lays down his life for his homeland without hesitation. A cultist is driven to greater and greater ecstasies of blood to satisfy the wicked whispers that fill his mind day and night. All believe that if they sacrifice enough for their dreams, even the impossible can be realized. These dreams are enough to shape those around them---and, if realized---the world.

**Adventures:** Zealots live in pursuit of a passion or cause. Each zealot has a purpose they intimately understand, from protecting their country, to spreading their religion, to hunting down every last one of the assassins who murdered their master.
Characteristics: Zealots typically have intense personalities---despite their commitment to one cause, if one fire cools, another will ignite. This fervency is what draws in their allies and sets them apart: What some might believe on an intellectual level in a vague, apathetic way, the zealot embraces and knows like a lover.

**Alignment:** Any. Zealots have a strict devotion to an ideal that they follow with reckless abandon. While zealots often allow the ends to justify the means, they also put the needs of something greater than themselves beyond their own needs. These conflicting motivations create zealots of every conceivable stripe. Though zealots do not change alignment more frequently than other classes, a zealot who changes alignments fights for his new ideals with the same intensity as the one he left behind.

**Religion:** Many zealots are religious, but their personal beliefs often clash with established dogma. Zealots often live at the extremes of a given religion---its most brutal enforcers, its most devout preachers, its first followers, its greatest defenders, and its most despised heretics. This purity of drive leads zealots to frequently found their own religions, philosophies, and cults.

**Background:** Zealots are found most frequently in times of uncertainty and places of conflict, though whether this is because these situations are ideal for creating zealots, zealots are drawn to these areas, or zealots create these situations is uncertain.

**Races:** Zealots are most commonly found in humans and other shorter-lived races, because zealots often live short and burn bright. Sadly, there may be just as many dwarven patriots as goblin fanatics, but the dwarves who follow less impassioned lives will typically live much longer ones. Half-breeds like half-orcs, half-giants, and tieflings are common zealots, as they are often born in areas of conflict and are forced into allying with one side of their heritage or another. Dromites and other highly-organized races can produce excellent zealots, as their culture helps instill them with a unique sense of purpose.

**Other Classes:** Zealots often mesh best with others who will fight for their cause, regardless of their allies' motivations, a pragmatic stalker who can be counted on to perform a task for a few coins might be a more trusted ally than a pious cleric who is always raising moral arguments to the zealot's methods. Zealots sometimes clash with sorcerers, paladins, and others with strong personalities (a natural consequence of too many leaders and not enough followers), but thoughtful classes like inquisitors, oracles, and rangers can channel the zealot's ardor against the proper targets. Zealots do not inherently get along well, and there are often zealots on all sides of a conflict.

**Role:** Leader. A zealot inspires the hearts and minds of those he fights alongside through pure passion, bringing his allies to heights they never thought possible. With proper feat and maneuver choices, zealots can also become masters of battlefield control.
