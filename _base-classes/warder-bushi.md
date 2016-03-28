---
title: Warder (Bushi)
sources:
  - Path of War
  - "Path of War: Expanded"
tags:
  - Initiator

max_level: 20
hit_die: 12
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
  - Knowledge (history)
  - Knowledge (martial)
  - Knowledge (nobility and royalty)
  - Perform
  - Profession
  - Ride
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
  - Tower Shields

class_features:

  - name: maneuvers
    levels: [1]
    text: |
      A warder begins her career with knowledge of five martial maneuvers. The disciplines available to her are Broken Blade, Golden Lion, Iron Tortoise, and Primal Fury, and the choice of either Eternal Guardian or Piercing Thunder. She must choose one of her martial disciplines to exchange for the Mithral Current discipline. She gains the associated skill of each of her disciplines as a class skill.

      Once she knows a maneuver, she must ready it before she can use it (see Maneuvers Readied, below). A maneuver usable by warders is considered an extraordinary ability unless otherwise noted in its description. Her maneuvers are not affected by spell resistance, and she does not provoke attacks of opportunity when she initiates one. She learns additional maneuvers at higher levels, as shown on Table: The Warder. The warder must meet a maneuver's prerequisites to learn it.

      Upon reaching 4th level, and at every even numbered warder level after that, she can choose to learn a new maneuver in place of one she already knows. In effect, the warder loses the old maneuver in exchange for the new one. The warder need not replace the old maneuver with a maneuver of the same level. She can choose a new maneuver of any level she likes, as long as she observes her restriction on the highest-level maneuvers she knows. The warder can swap only a single maneuver at any given level. A warder's initiation modifier is Intelligence.

      *Maneuvers Readied:* A warder can ready three of her five starting maneuvers, but as she advances in level and learns more maneuvers, she must choose which maneuvers to ready. She readies her maneuvers by going over battle tactics, through weapon drills, or spending time meditating in prayer for 10 minutes. The maneuvers she chooses remain readied until she decides to repeat this again and change them. Any given maneuver may only be readied once. Warders do not need to sleep or be well rested to ready their maneuvers; any time they spend 10 minutes in practice or meditation, they can change their readied maneuvers. She begins an encounter with all readied maneuvers unexpended, regardless of how many times she may have already used them since she chose them. When the warder initiates a maneuver, she expends it for the current encounter, so each of her readied maneuver can be used once per encounter (until they are recovered, see below).

      For a warder bushi to recover expended maneuvers, she must take stock of her situation to plan for her next movement. By focusing entirely on a defensive position to prepare her next move, she is able to regain maneuvers expended to assist her to victory. By taking a full round action to plan her next move (activating her defensive focus class feature, see below), she recovers a number of expended maneuvers equal to her Intelligence modifier (minimum of 2).

      *Stances Known:* Warders begin play with knowledge of one stance from any discipline open to warders. At the indicated levels (see class table), the warder selects an additional new stance. Unlike maneuvers, stances are not expended, and she does not have to ready them. All the stances she knows are available to her at all times, and she can change the stance she is currently using as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance description. Unlike with maneuvers, the warder cannot learn a new stance at higher levels in place of one she already knows.


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

  - name: defensive focus
    type: Ex
    levels: [1, 10]
    levels_text:
      10: improved
    text: |
      At 1st level, the defensive prowess of the warder is second to none, allowing her to focus her actions purely on defending himself and her allies in ways that cannot be replicated. The warder gains the Combat Reflexes feat as a bonus feat, using her Intelligence modifier in place of her Dexterity modifier to determine the number of additional attacks of opportunity she may make each round.

      When recovering maneuvers as a full round action, the warder sets up a defensive perimeter around himself to defend her allies, increasing her threatened area by 5 ft. for every 5 initiator levels she possesses. Until the beginning of her next turn, she may make attacks of opportunity against any opponent in this threatened area that provokes attacks of opportunity. She may move as part of these attacks of opportunity, provided her total movement before her next turn does not exceed her speed (his movement provokes attacks of opportunity as normal). Additionally, while using defensive focus, the warder adds her Intelligence modifier plus her class level to her CMD for the purposes of defending against enemies trying to use the Acrobatics skill to prevent her from getting attacks of opportunity against them.

      At 10th level, her defensive focus improves further, causing the ground within her melee reach to be treated as if it were difficult terrain, hampering her foes' movement around him. If a foe tries to move through a space within her reach, the movement through those squares costs double (x2). Additionally, while using her defensive focus to make an attack of opportunity, her movement does not provoke attacks of opportunity.

  - name: aegis
    type: Ex
    levels: [1, 5, 6, 9, 12, 13, 17]
    levesl_text:
      1:  "+1, 10 ft."
      5:  "+2"
      6:  "20 ft."
      9:  "+3"
      12: "30 ft."
      13: "+4"
      15: "+5"
    text: |
      At 1st level, the warder's defensive prowess extends to those who choose to stay near to him. Allies who are within 10 ft. of the warder's position gain a +1 morale bonus to Armor Class and to Will saves under the warder's defensive aegis, her presence bolstering and shepherding the defenses of her allies. This bonus improves to +2 at 5th level (+3 at 9th level, +4 at 13th level, and +5 at 17th level). The warder does not receive this bonus, but may receive the benefits of this ability from another warder. If the ally cannot see or hear the warder, then the ally does not gain the benefits of this ability (such as if the warder is concealed or invisible).

      At 6th level, her aegis' range increases its effective area, growing to a 20 ft. radius. At 12th level, this increases again to 30 ft.

  - name: armiger's mark
    type: Ex
    levels: [2, 8, 9, 16]
    levels_text:
      2: --4
      8: --6
      9: grand challenge
      16: --8, recovery
    text: |
      At 2nd level, a warder is trained in how best to control her enemies and how they behave in battle, urging them to throw their all against the warder's indomitable armor and unyielding shield. With a sharp blade, a clever taunt, or something that otherwise attracts her foe, the warder can direct the attention of enemies towards himself. Whenever the warder attacks a foe in combat and inflict at least 1 point of damage, as a free action she may mark them as her foe and attempt to continue to force them to engage the warder only. The warder may even mark a foe during an attack of opportunity and may make the free action to do so, even though it is not her turn. The warder may only maintain a number of marks equal to 3 + her Intelligence modifier at a time, and she may make a number of marks per day equal to 1⁄2 warder level + Intelligence modifier.

      The target is aware of being marked, and the mark remains for a number of rounds equal to the warder's Intelligence modifier (minimum of 1). Marked targets suffer a --4 penalty to attack rolls against foes that are not the warder, and arcane spellcasters suffer an increase in arcane spell failure of 10% + 1% per two warder levels until the mark expires.  At 8th level, this penalty increases to --6, and it increases again to --8 at 16th level.

      This ability functions on creatures with an Intelligence score of 1 or more, allowing her to mark animals and other beasts as well as sentient beings, but not mindless creatures such as skeletons. Multiple armiger's marks overlap rather than stacking.

      At 9th level, the warder may expend two uses of her armiger's mark to make a grand challenge to all enemies within a 30 ft. radius and mark them with her words alone. Creatures affected must make a Will save (DC 10 + 1⁄2 warder level + Intelligence modifier) against the warder's mark ability or suffer the penalties of being marked for a number of rounds equal to the warder's Intelligence modifier. This does not count against her normal marking limit. This is a language-dependent ability and does not effect creatures of less than 1 Intelligence.

      At 16th level, the armiger's mark improves to allow her to recover an expended maneuver whenever she reduces a marked opponent's hit points to 0 or less (this can only trigger once per marked opponent).

  - name: bushido
    type: Su
    levels: [3, 6, 8, 13, 15, 19]
    levels_text:
      3:  1 bushido
      6:  2 bushido
      8:  3 bushido
      13: 4 bushido
      15: 5 bushido
      19: 6 bushido
    text: As a bushi grows in power, he gains access to abilities through the refinement of his spirit and his weapon by adhering to the principles of bushido. A warder bushi selects a [bushido](/bushido/) to gain at 3rd, 6th, 8th, 13th, 15th, and 19th levels.

  - name: Mixed Combat
    type: Ex
    levels: [6]
    text: At 6th level, a bushi gains Mixed Combat as a bonus feat, even if he does not meet the prerequisites. In addition, the bushi is considered to be threatening all adjacent squares even if his weapon is sheathed, and can draw his weapon when making any attack (including attacks of opportunity).

  - name: bonus feat
    levels: [13, 18]
    levels_text:
      13: 1 feat
      18: 2 feats
    text: At 13th level and at 18th level, a warder receives a bonus combat or teamwork feat. She must meet all prerequisites for these feats.

  - name: tactical acumen
    type: Ex
    levels: [4]
    text: At 4th level, the combat training that the warder has received hones her reflexes. Through her knowledge of tactics, training manuals, and lessons in the histories of war, her wits aid her when her agility may be impaired by her heavy armor. The warder may add her Intelligence modifier to her Reflex saves and to her initiative in place of her Dexterity modifier (using the higher of the two bonuses).

  - name: extended defense
    type: Ex
    levels: [5, 8, 11, 14, 17]
    levels_text:
      5: 1/day
      8: 2/day
      11: 3/day
      14: 4/day
      17: 5/day
    text: Upon reaching 5th level, the warder becomes ever more skilled at adapting to the flow of combat. Once per day, the warder may activate Extended Defense as an immediate action. When she does, the character chooses a counter she has readied; she may initiate that counter as a free action (even on another's turn) at will until the beginning of her next turn. At the beginning of her next turn, the chosen counter is expended. Every three levels beyond this (8th, 11th, 14th, and 17th levels), she may use this ability an additional time per day.

  - name: adaptive tactics
    type: Ex
    levels: [7]
    text: A warrior can attempt to plan for everything, but no plan stands against the heat of battle if there is no room for adaptation. At 7th level, the warder can expend one use of her armiger's mark ability as a full-round action to expend up to her Intelligence modifier in readied maneuvers, then instantly ready an equal amount of maneuvers. The warder may not replace expended maneuvers using this ability; any maneuver she is re-preparing with this ability must be unexpended to be exchanged. She may choose from any of her known maneuvers.

  - name: stalwart
    type: Ex
    levels: [12]
    text: At 12th level, a warder can use mental and physical resiliency to avoid certain attacks. If she makes a successful Fortitude or Will saving throw against an attack that has a reduced effect on a successful save, she instead avoids the effect entirely. A helpless warder does not gain the benefit of the stalwart ability.

  - name: deathless defenses
    type: Ex
    levels: [20]
    text: At 20th level, the warder can indefinitely hold a position to protect her allies, even if it may cost her her life. The warder must expend two uses of her armiger's mark ability as an immediate action to activate her deathless defenses. While this ability is active, the warder is capable of maintaining her defensive focus as a move action (but recovers no maneuvers unless she spends a full round to recover) but gains the full bonuses of her defensive focus. Additionally, she receives the benefits of her aegis ability as well. She is unable to die from hit point damage while this effect is in use. She may maintain the use of this ability each round at the cost of one use of her armiger's mark ability, or she may end it as a free action. Abilities or effects that don't inflict hit point damage, such as energy drain or ability damage, can still kill the warder. While this effect is in use, she is immune to mind-affecting abilities, as her focus prevents any from tampering with her mind. Once this ability ends, either voluntarily or if the character runs out uses of armiger's mark (assuming she is not dead), the warder is exhausted and must rest a full 8 hours to recover.
---

Protective and disciplined warriors, warders are fighting men and women who use their knowledge of warfare, tactics, and strategy combined with superior combat training to accomplish their goals in defending others. Their intellect guides them through battle, and their skill at arms achieves their success.

Bushi are honorable and noble warriors who specialize in Iaijutsu, the art of the draw cut. With a single swing of his katana, a bushi can cleave through armor, bones and organs as easily as straw. Bushi follow the code of bushido and exemplify the virtues of righteousness, courage, benevolence, respect, honesty, honor and loyalty.

**Adventures:** Warders adventure to further their employer's missions, to serve on battlefields as protectors and champions, or to protect those that they care about. Some warders adventure to forge kingdoms of their own, battle tyranny, fight others of their kind for honor, or to live simply and by their own code.

**Characteristics:** Warders are always protective of people they deem in their care, be it a superior, their friends, or fellow soldiers of fortune. Many warders are proud, intelligent individuals who study tactics and maps as well while training daily with their associates to better suit their style towards their defense.

**Alignment:** Any, but most are lawful; the moral portion of their alignment is either up to them or their inclusion in their sect.

**Religion:** Many warders are religious, often following gods of war, chivalry, and sacrifice. Some follow gods of tyranny or justice, and others follow gods that stand for the good of their race.

**Background:** Warders find their place in their society based upon their line of adventuring. Some warders are regarded with great respect as leaders and guardians while others are feared and hated for their tyrannical ways. Many are respected and treated well in the hopes that if trouble comes, the warder will come to help those who showed them kindness.

**Races:** Nearly all humanoid races have warders amongst them. Dwarves, half-orcs, and humans make up the larger majority of warders in more civilized society, but there are a minority of halflings and gnomes that guard their kind from harm. While elves possess the tactical prowess to make great warders, their fragile bodies are often not enough for the physical rigors of the profession. While some warders are restrictive to whom they'll share their secrets, it's largely agreed that the more monstrous races tend to be excluded. Hobgoblins, of the monstrous races, are by far the largest exception to that stereotype.

**Other Classes:** Warders get on well with those of a more orderly and martial bent, naturally befriending paladins, monks, and fighters. Rogues and warders don't exactly see eye to eye, while rangers and sorcerers might find a warder's presence restrictive. Wizards and warders appreciate many of their shared facets in learning, and warders widely recognize the importance of clerics in both martial and spiritual matters.

**Role:** Defender. Warders are natural guardians and protectors of the weaker members of the party, and are the ones who can take the most damage on the front line. They also double as being coordinators on the battlefield, helping their teammates and providing support for them both defensively and offensively.

**Abilities:** Strength and Constitution are prime attributes for warders, ruling over the majority of their combat prowess. Intelligence also plays a big role in their day to day life, as it is both their primary initiation attribute and aids in their more mundane skills.
