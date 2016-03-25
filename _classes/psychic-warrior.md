---
title: Psychic Warrior
sources:
  - Ultimate Psionics

tags:
  - Psionic

max_level: 20
hit_die: 8

class_skills:
  - Acrobatics
  - Autohypnosis
  - Climb
  - Craft
  - Knowledge (psionics)
  - Perception
  - Profession
  - Ride
  - Spellcraft
  - Swim
skill_ranks_per_level: 4

bab_progression: mid
fort_progression: good
ref_progression: poor
will_progression: poor

manifesting_progression: mid

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

  - name: manifesting
    levels: [1]
    text: |
      A psychic warrior's ability to manifest powers is limited by the power points he has available. His base daily allotment of power points is given on Table 2-4: The Psychic Warrior. In addition, he receives bonus power points per day if he has a high Wisdom score (see Table: Ability Modifiers and Bonus Power Points). His race may also provide bonus power points per day, as may certain feats and items.

      *Powers Known:* A psychic warrior begins play knowing one psychic warrior power of your choice. Each time he achieves a new level, he unlocks the knowledge of a new power.

      Choose the powers known from the psychic warrior power list. (Exception: The feat Expanded Knowledge does allow a psychic warrior to learn powers from the lists of other classes.) A psychic warrior can manifest any power that has a power point cost equal to or lower than his manifester level.

      The total number of powers a psychic warrior can manifest in a day is limited only by his daily power points.

      A psychic warrior simply knows his powers; they are ingrained in his mind. He does not need to prepare them (in the way that some spellcasters prepare their spells), though he must get a good night's sleep each day to regain all his spent power points.

      The Difficulty Class for saving throws against psychic warrior powers is 10 + the power's level + the psychic warrior's Wisdom modifier.

      *Maximum Power Level Known:* A psychic warrior begins play with the ability to learn 1st-level powers. As he attains higher levels, he may gain the ability to master more complex powers.

      To learn or manifest a power, a psychic warrior must have a Wisdom score of at least 10 + the power's level.

  - name: bonus feats
    levels: [1, 2, 5, 8, 11, 14, 17, 20]
    levels_text:
      1: 1 feat
      2: 2 feats
      5: 3 feats
      8: 4 feats
      11: 5 feats
      14: 6 feats
      17: 7 feats
      20: 8 feats
    text: |
      At 1st level, a psychic warrior gets a bonus combat-oriented feat in addition to the feat that any 1st level character gets and the bonus feat granted to a human character. The psychic warrior gains an additional bonus feat at 2nd level and every three levels thereafter (5th, 8th, etc.). These bonus feats must be drawn from the feats noted as combat feats or psionic feats. The psychic warrior must still meet all prerequisites for the bonus feat, including ability score and base attack bonus minimums as well as class requirements (like levels in another specific class).

      These bonus feats are in addition to the feats that a character of any class gains every two levels. A psychic warrior is not limited to combat feats and psionic feats when choosing these other feats.

  - name: psionic proficiency
    type: Ex
    levels: [1]
    text: A psychic warrior treats his base attack bonus as equal to his psychic warrior level for the purposes of requirements for psionic feats. Base attack bonuses granted from other classes are unaffected and are added normally.

  - name: talents
    levels: [1]
    text: Each psychic warrior gains two 0 level psionic talents of their choice. These talents do not count against the psychic warrior's powers known.

  - name: warrior's path
    type: Ex
    levels: [1, 3]
    levels_text:
      3: second power
    text: |
      At 1st level, a psychic warrior chooses a path to adhere to (listed below). When first taking a path, the psychic warrior gains one of the two powers associated with that path. Powers gained from a path do not count against his number of powers known. When manifesting this power, called a path power, the psychic warrior can either choose to manifest it for no cost by expending his psionic focus, in which case it cannot be augmented, or he can choose to manifest it normally, in which case his effective manifester level for this power is treated as one higher than normal.

      In addition, the psychic warrior gains one additional class skill, as noted in the path description.

      At 3rd level, the psychic warrior gains the second power from his path. All of the above benefits apply to this additional path power.

      **Archer Path:** Your focus is on ranged combat rather than wading into the thick of things.

      *Powers:* *Force screen*, *psychokinetic cannon*.

      *Skills:* Perception, Ride, Stealth.

      *Bonus Class Skill:* Stealth

      *Trance:* Beginning at 3rd level, while maintaining psionic focus, you gain a +1 competence bonus on attack rolls made with a ranged or thrown weapon (natural weapons do not count for this benefit). This bonus increases by 1 every four psychic warrior levels thereafter.

      *Maneuver:* Beginning at 3rd level, you can expend your psionic focus and make a ranged trip attack as a standard action. If your target is flying, they are instead staggered for one round. At 7th level and every four psychic warrior levels thereafter, you gain a +1 bonus to your CMB when using this maneuver.

      **Ascetic Path:** You have studied with the mystics of the ancient temples, sat silent embracing the solitude and isolation, so as to become more in tune with your body and mind, merging them into a single, dangerous warrior.

      *Powers:* *Defensive precognition*, *offensive precognition*.

      *Skills:* Acrobatics, Autohypnosis, Knowledge (religion).

      *Bonus Class Skill:* Knowledge (religion).

      *Trance:* Beginning at 3rd level, while maintaining psionic focus and wearing no or light armor, you gain gain a +1 competence bonus to your AC or saves, chosen at the time you gain psionic focus. This bonus increases by 1 every four psychic warrior levels thereafter.

      *Maneuver:* Beginning at 3rd level, as an immediate action, you can expend your psionic focus to gain a +2 dodge bonus to your AC until the beginning of your next turn. This bonus increases by +1 for every five psychic warrior levels you have. In addition, if you did this in response to an attack and that attack misses you, you may take a 5-foot step as part of this action.

      **Assassin's Path:** While others prefer to stand boldly in the face of danger, your preferred weapon is stealth and silence. When you attack, your enemy is bound to fall.

      *Powers:* *Distract*, choice of *prevenom* or *prevenom weapon*

      *Skills:* Acrobatics, Perception, Stealth

      *Bonus Class Skill:* Stealth

      *Trance:* Beginning at 3rd level, while maintaining psionic focus, you gain a +2 competence bonus on damage rolls. This bonus increases by 1 every four psychic warrior levels thereafter.

      *Maneuver:* Beginning at 3rd level, any time you strike an enemy with a melee attack and there are no other enemies adjacent to you, you can expend your psionic focus to deal an additional +2d6 damage. For every five psychic warrior levels you gain thereafter, this damage increases by +1d6. This damage is precision-based damage.

      **Brawling Path:** You bring the combat right into the face of your enemy. Your powers allow you to overpower enemies and bring them to bear, either to bring justice to them, or to finish them when they are worn down.

      *Powers:* *Grip of iron*, *hammer*.

      *Skills:* Acrobatics, Autohypnosis, Escape Artist.

      *Bonus Class Skill:* Escape Artist.

      *Trance:* Beginning at 3rd level, while maintaining psionic focus, each time you make a successful grapple check, you can deal damage to that enemy equal to your Wisdom modifier.

      *Maneuver:* Beginning at 3rd level, as a swift action you can expend your psionic focus to cause an enemy you are grappling to take 2d6 non-lethal damage. For every two psychic warrior levels you gain thereafter, the damage increases by 1d6.

      **Dervish Path:** You are a whirlwind in combat. Your blades strike out faster than the eye can perceive, sending enemies reeling from your twin-bladed attacks.

      *Powers:* *Force screen*, *metaphysical weapon*.

      *Skills:* Acrobatics, Bluff, Perform.

      *Bonus Class Skill:* Bluff.

      *Trance:* Beginning at 3rd level, while maintaining psionic focus, you gain a +1 competence bonus on attack rolls made when you wield two weapons. This bonus increases by 1 every four psychic warrior levels thereafter.

      *Maneuver:* Beginning at 3rd level, you can expend your psionic focus as part of a full attack when you fight with two weapons to take a 5-foot step between your attacks, even if you have already taken a 5-foot step, but not if you have moved normally (such as by using hustle). At 8th level and every five psychic warrior levels thereafter, you gain one additional 5-foot step, but each of these 5-foot steps must be made after an attack in your full attack.

      **Feral Warrior Path:** You are the beast incarnate. You channel your rage and power into physically transforming yourself into the likeness of a monster.

      *Powers:* *Bite of the wolf*, *claws of the beast*.

      *Skills:* Acrobatics, Perception, Survival.

      *Bonus Class Skill:* Survival.

      *Trance:* Beginning at 3rd level, while maintaining psionic focus, you gain a +1 competence bonus to your attack rolls on attacks made with natural weapons. This bonus increases by 1 every four psychic warrior levels you gain thereafter.

      *Maneuver:* Beginning at 3rd level, you can expend your psionic focus when use the charge action. If you do, you can make one additional attack at the end of your charge instead of making a single melee attack, but each attack suffers a -2 penalty to the attack roll. In addition, you gain a +1 competence bonus to any damage rolls made as part of this action. This competence bonus increases by +1 for every four psychic warrior levels you gain thereafter. At 20th level, when using the charge action, you can instead make a full attack at the end of the charge.

      **Gladiator Path:** Your tactic is not to simply attack, but to maneuver your enemies into the most optimal position, forcibly if necessary.

      *Powers:* *Grip of iron*, *tactical precognition*.

      *Skills:* Acrobatics, Bluff, Perception

      *Bonus Class Skill:* Bluff

      *Trance:* Beginning at 3rd level, while maintaining psionic focus, you gain a +1 competence bonus to your CMB and a +2 competence bonus to your CMD. These bonuses increase by 1 every four psychic warrior levels thereafter.

      *Maneuver:* Beginning at 3rd level, you can expend your psionic focus when using a combat maneuver to not provoke an attack of opportunity for using that combat maneuver. If you have a feat that already does this, such as Improved Bull Rush, your trance competence bonus on this specific maneuver check increases by 2 or you gain a +2 competence bonus on this check if you do not have the Gladiator trance active. Additionally at 8th level and every four psychic warrior levels thereafter, the bonus you gain on this specific maneuver check increases by 1.

      **Infiltrator Path:** You are adept at changing your form and altering your physiology to meet any situation and strike fear into your enemies.

      *Powers:* *Chameleon*, *minor metamorphosis*.

      *Skills:* Disguise, Escape Artist, Intimidate.

      *Bonus Class Skill:* Disguise.

      *Trance:* Beginning at 3rd level, while maintaining psionic focus, you gain a +2 competence bonus on Disguise checks and a +1 competence bonus on damage rolls made with natural weapons. These bonuses increase by 1 every four psychic warrior levels thereafter.

      *Maneuver:* Beginning at 3rd level, you can expend your psionic focus when manifesting minor metamorphosis, metamorphosis, or major metamorphosis to gain an intimidating visage. For the duration of the manifestation, you may make a free Intimidate check against any creature that comes within 30 ft. of you. You must have line of sight to the creature and you may only make one such check against that creature per manifestation of minor metamorphosis, metamorphosis, or major metamorphosis. At 7th level  and every four psychic warrior levels thereafter, you gain a +1 competence bonus to this Intimidate check.

      **Interceptor Path:** You are adept at engaging enemies, guarding your allies, and blocking interlopers. Speed and maneuverability are not your only tools; you know how stop a foe in his tracks.

      *Powers:* Burst, expansion

      *Skills:* Acrobatics, Intimidate, Perception

      *Bonus Class Skill:* Intimidate

      *Trance:* Beginning at 3rd level, while maintaining psionic focus, you gain a +1 competence bonus on attack and damage rolls made against any opponent that threatens any of your allies. This bonus increases by 1 every four psychic warrior levels thereafter.

      *Maneuver:* Beginning at 3rd level, you can expend your psionic focus as an immediate action when an enemy you threaten attacks one of your allies to make a single melee attack or bull rush attempt against that enemy. Your attack or bull rush attempt is resolved before the enemy's attack. If you made a melee attack and it is successful, the struck enemy takes a penalty equal to the competence bonus of the Interceptor trance on the attack and damage rolls of the attack that triggered this maneuver.

      **Mind Knight Path:** You have sworn an oath to your order, and in exchange you have been trained in mystic techniques that allow you to summon a weapon from beyond time and space, while protecting yourself with the power of your mind.

      *Powers:* *Call weaponry*, *inertial armor*.

      *Skills:* Autohypnosis, Diplomacy, Ride.

      *Bonus Class Skill:* Diplomacy.

      *Trance:* Beginning at 3rd level, while maintaining psionic focus, you gain a +1 competence bonus to your initiative. In addition, when wielding a weapon you gain through *call weaponry*, you gain a +1 bonus to attack and damage rolls with that weapon. All of these bonuses increase by 1 for every four psychic warrior levels you gain thereafter.

      *Maneuver:* Beginning at 3rd level, you can expend your psionic focus as a standard action to make a melee attack against two creatures adjacent to you. For every five psychic warrior levels you gain thereafter, you can make one additional attack against another enemy adjacent to you.

      **Survivor Path:** You are capable of surviving in harsh environments and enduring deadly assaults. You recognize the power of the body's ability to overcome even the most deadly of afflictions.

      *Powers:* *Catfall*, *vigor*.

      *Skills:* Autohypnosis, Heal, Survival.

      *Bonus Class Skill:* Survival.

      *Trance:* Beginning at 3rd level, while maintaining psionic focus, you gain DR 2/---. This damage reduction improves by 1 every four psychic warrior levels thereafter. In addition, you suffer no harm from being in a hot or cold environment. You can exist comfortably in conditions between --50 and 140 degrees Fahrenheit without having to make Fortitude saves. Your equipment is likewise protected. This doesn't provide any protection from fire or cold damage, nor does it protect against other environmental hazards such as smoke, lack of air, and so forth.

      *Maneuver:* Beginning at 3rd level, you can expend your psionic focus as an immediate action to be treated as having the Stalwart ability until the beginning of your next turn. At 7th level and every four psychic warrior levels beyond, you gain a +1 competence bonus to Will saves when using this maneuver. In addition, at 11th level, when using this maneuver, you are treated as having the Improved Stalwart ability.

      **Weaponmaster Path:** You become one with your weapon and wield it with vicious strokes, cleaving enemies as if wheat before a scythe. Your weapon is an extension of your will and thus it is deadly.

      *Powers:* *Empty mind*, *metaphysical weapon*.

      *Skills:* Acrobatics, Craft, Knowledge (nobility).

      *Bonus Class Skill:* Knowledge (nobility).

      *Trance:* Beginning at 3rd level, while maintaining psionic focus, you gain a +1 competence bonus on attack rolls made with a weapon (natural weapons do not count for this benefit). This bonus increases by 1 every four psychic warrior levels thereafter.

      *Maneuver:* Beginning at 3rd level, you can expend your psionic focus as an immediate action when an enemy attacks you to make a single melee attack against that enemy and then take a 5-foot step. The enemy's attack is resolved before you take your action. At 8th level and every five psychic warrior levels thereafter, you gain a +1 competence bonus on the attack and damage rolls made for this attack.

  - name: expanded path
    levels: [3]
    text: |
      At 3rd level, the psychic warrior expands his understanding of his chosen path. From this point on, he can use the trance and maneuver associated with his chosen path.

      Unless otherwise indicated, if the psychic warrior expends psionic focus to activate a maneuver, he still gain the benefit of his trance until the end of his turn.

  - name: path skill
    levels: [4, 7, 10, 13, 16, 19]
    text: At 4th level, the psychic warrior gains a +2 bonus to one skill associated with a path he is on. Every three levels thereafter, he can choose to increase the bonus to one of his path skills by +2 (to a maximum of +6 for any one path skill). This may be a skill he has already chosen or a new skill associated with a path he is on.

  - name: martial power
    levels: [6]
    text: At 6th level, if the psychic warrior makes an attack (but not a ranged touch attack), he can manifest one of his path powers as part of that attack action. The power takes effect immediately after the attack has been finished. Touch range powers are transmitted through the melee attack to the attacked target. The psychic warrior gaing the benefits of the power on the attack made, even if the power is what grants the weapon to make the attack. The psychic warrior may only activate a path power in this fashion once per round.

  - name: secondary path
    type: Ex
    levels: [9, 11]
    levels_text:
      9: power
      11: trance and maneuver
    text: |
      At 9th level, the psychic warrior gets to choose a second warrior's path. He chooses one of the path powers available from his new list. The psychic warrior may only have two path powers in total from a single given path.

      At 11th level, the psychic warrior can choose to use the trance and maneuver from his second warrior's path, but may only benefit from one trance at a time.

      The psychic warrior treats the path skills of his secondary path as class skills and may select them when choosing a path skill.

  - name: twisting path
    type: Ex
    levels: [12]
    text: At 12th level, as a swift action while maintaining psionic focus and using a trance, the psychic warrior can change to the trance of his other path.

  - name: pathweaving
    type: Su
    levels: [15, 18]
    levels_text:
      15: 1/day
      18: 2/day
    text: |
      At 15th level, as long as the psychic warrior maintains psionic focus, once per day he can gain the benefits of both of his trances for up to 5 minutes. Activating this ability is a free action.

      Every third level thereafter, the psychic warrior can use this ability an additional time per day.

  - name: eternal warrior
    type: Su
    levels: [20]
    text: At 20th level, once per day as a free action, the psychic warrior can enter into a very powerful trance. As long as he maintains psionic focus, for up to 5 minutes the psychic warrior adds his Wisdom modifier to his attack rolls, damage rolls, AC, skill checks, ability checks, saves, and initiative, and he increases his speed by +5 feet for every point of his Wisdom modifier. These benefits stack with those that might be granted by his active path's trance (or both paths, if using pathweaving).

---

Where the psion spends his days studying the intricacies of psionic power and unlocking the mysteries of the mind, others choose to use their internal power to augment their physical form. These psychic warriors use their psionic potential as a way to improve their natural abilities, becoming fierce and deadly in their chosen path.

**Role:** The psychic warrior's path determines his strengths and weaknesses within a party. Whether he is the epitome of unleashing the beast within, or a stealthy combatant who strikes from the shadows, the psychic warrior's primary focus is typically battlefield control and dealing or blocking damage.
