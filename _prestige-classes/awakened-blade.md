---
title: Awakened Blade
sources:
  - Path of War
  - "Path of War: Expanded"
tags:
  - Initiator
  - Psionic

max_level: 10
hit_die: 10
prerequisites:
  - Acrobatics 5 ranks
  - Autohypnosis 4 ranks
  - Knowledge (Martial) 3 ranks
  - Knowledge (Psionics) 3 ranks
  - Psionic Body
  - Psionic Meditation
  - ability to manifest *defensive precognition* and *offensive precognition*
  - ability to initiate 2nd level maneuvers including at least one stance

class_skills:
  - Acrobatics
  - Autohypnosis
  - Diplomacy
  - Intimidate
  - Knowledge (psionics)
  - Spellcraft
  - Stealth
skill_ranks_per_level: 4

bab_progression: full
fort_progression: prestige_poor
ref_progression: prestige_poor
will_progression: prestige_good

initiating_progression: prestige

class_features:
  - name: maneuvers
    levels: [1]
    text: |
      An awakened blade adds either Riven Hourglass or Sleeping Goddess to his list of available disciplines. If he does not have that discipline's associated skill as a class skill, he gains it as a class skill.

      At every even-number level, an awakened blade gains new maneuvers known from any discipline he has access to (whether from a martial disciple class, Awakened Blade, or the [Martial Training](/feats/martial-training/) feat). He must meet a maneuver’s prerequisites to learn it. The character adds his full awakened blade levels to his initiator level to determine his total initiator level and his highest-level maneuvers known.

      At 3rd, 6th, and 9th levels, he gains additional maneuvers readied per day, and and 2nd, 5th, and 8th levels he may exchange a known maneuver for a different maneuver that he qualifies for.

      *Stances Known:* At 3rd level and again at 8th level, the awakened blade learns a new martial stance from his available disciplines. He must meet the stance’s prerequisites to learn it.

  - name: manfesting advancement
    levels: [2, 3, 4, 5, 7, 8, 9, 10]
    levels_text:
      2:  +1 level
      3:  +1 level
      4:  +1 level
      5:  +1 level
      7:  +1 level
      8:  +1 level
      9:  +1 level
      10: +1 level
    text: |
      At every level but 1st and 6th, an awakened blade gains additional power points per day and access to new powers as if he had also gained a level in whatever manifesting class he belonged to before he added the prestige class. He does not, however, gain any other benefit a character of that class would have gained (bonus feats, metapsionic or item creation feats, and so on). This essentially means that he adds the level of awakened blade to the level of whatever manifesting class the character has, and then determines power points per day, powers known, and manifester level accordingly.

      If a character had more than one manifesting class before he became an awakened blade, he must decide to which class he adds the new level of awakened blade for the purpose of determining power points per day, powers known, and manifester level.

  - name: situational awareness
    type: Su
    levels: [1, 3, 4, 6, 8, 9, 10]
    levels_text:
      1: "+1"
      3: uncanny dodge
      4: "+2"
      6: "+3"
      8: "+4"
      9: improved uncanny dodge
      10: "+5"
    text: At 1st level, awakened blades open their minds to the myriad of potential futures that could lead to his victory in battle and to his continued defense. Similar in effect to the danger sense psionic power, the character adds half his class level (rounded down, minimum of +1) to his initiative rolls as an insight bonus. He may also add this bonus to his AC as a dodge bonus or Reflex saves to avoid traps and their attacks. This bonus stacks with bonuses gained from the trap sense class feature. At 3rd level, the character gains the benefits of the uncanny dodge ability. At 9th level, the character gains the improved uncanny dodge ability.

  - name: Deep Focus
    levels: [1]
    text: The character gains the Deep Focus psionic feat as a bonus feat at 1st level.

  - name: path of the warrior
    levels: [1]
    text: The awakened blade’s trip along the Path of War is one of constant devotion, and for those with a focused aptitude in the field of war with the psionic arts, their discipline is rewarded. If the character possesses levels in psychic warrior, then he adds his class level to his psychic warrior level for the purposes of determining the trance and maneuver abilities of his path abilities. If the character possessed levels in the soulknife base class, then the awakened blade counts all levels in this class as +1 to existing manifester level with regards to a soulknife’s mind blade enhancement bonus.

  - name: stance of the inner eye
    levels: [2, 7]
    levesl_text:
      2: +1d6
      7: +2d6
    text: At 2nd level, the awakened blade’s precognitive abilities blend with his martial prowess to unlock an inner eye within his mind, all-seeing and hyper-aware of the dangers that surround him and ways to combat them. This inner sense allows the awakened blade to react to danger quickly, guide his attacks around the defenses of his enemies, and to land fierce blows as his mind traces out the myriad scenarios that could play out between himself and his foes. To enter this stance, as a swift action the awakened blade abandons a martial stance he is currently using. While in this stance, the character gains a +1 insight bonus for every three initiator levels he possesses (minimum +1) to his AC, attack and damage rolls, CMB checks, and to all saving throws. If caught in a situation where the character would be denied his Dexterity bonus, these bonuses do not apply. The character inflicts an additional 1d6 points of damage while in this stance at 2nd level, and this damage bonus improves to 2d6 points of damage at 7th level. This bonus damage is precision based, and creatures not subject to critical hits are immune to this additional damage.

  - name: bonus psionic feat
    levels: [4, 8]
    levels_text:
      4: 1 feat
      8: 2 feats
    text: The awakened blade gains a bonus combat feat or psionic feat of his choice at 4th level. He gains an additional bonus combat feat or psionic feat of his choice at 8th level. The character must meet all prerequisites for this feat to select it.

  - name: precognitive defenses
    type: Su
    levels: [5]
    text: At 5th level, the mind’s eye within the awakened blade’s defensive senses is capable of reacting to multiple dangerous scenarios at the same time. The character may expend his psionic focus as a free action to initiate a readied counter, even if he has already used his immediate or swift action this round. This specifically allows for the use of a free action on another creature’s turn.

  - name: hypercognitive focus
    type: Ex
    levels: [6]
    text: At 6th level, an awakened blade’s mind is able to anticipate his needs and subconsciously works to further his effectiveness. Whenever the character recovers one or more maneuvers, he may regain psionic focus as a free action as part of his maneuver recovery. He may only do this one time in a given round. Alternately, the character may expend his psionic focus when manifesting a psionic power and recover an expended maneuver.

  - name: clairsentient counter
    type: Su
    levels: [7]
    text: By anticipating the attack before the attacker ever considers making it, the awakened blade using this martial technique may act faster than his opponent can even think. At 7th level, to use this ability, the character expends a readied maneuver and his psionic focus as an immediate action; the clairsentient counter is used in response to attack against him of any sort (be it a melee or ranged attack, spell, power, or other spell-like or supernatural effect) and grants the character a standard or move action that he must use as part of this counter. This movement occurs before the attack is resolved but after the attack is made.

  - name: pretercognitive mind
    levels: [10]
    text: At 10th level, the awakened blade’s reactive capabilities are so intense that his subconscious mind must manage them for him as they otherwise would never give him a moment’s rest. While psionically focused, the character is considered to have the benefits of the Stance of the Inner Eye without needing to initiate the stance. He may continue to gain these benefits while he adopts any other martial stance that he knows and gain the benefits of both stances.
---

Some wielders of psychic power seek to extend and stretch the depths of their psionic power to assist their abilities in many different ways. Some small select few, those who are quite gifted in the clairsentient arts, find that they are able to distil certain psionic powers into a fighting style of extreme potency. The style is a deadly mix of precognition abilities coupled with martial techniques that when utilized together, allows for its user to react to danger faster and defend himself while simultaneously mapping out his foe’s defenses for maximum effect. Awakened blades, as they are called, learn to use their precognitive mastery as both offense and defense in pursuit of greater psionic knowledge and personal glory or power.
