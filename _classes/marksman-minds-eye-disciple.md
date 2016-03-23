---
title: Marksman (Mind's Eye Disciple)
sources:
  - Ultimate Psionics
  - "Path of War: Expanded"

max_level: 20
hit_die: 10

class_skills:
  - Acrobatics
  - Autohypnosis
  - Climb
  - Craft
  - Escape Artist
  - Intimidate
  - Knowledge (psionics)
  - Perception
  - Perform
  - Profession
  - Sense Motive
  - Sleight of Hand
  - Stealth
  - Survival
  - Use Magic Device
skill_ranks_per_level: 4

bab_progression: full
fort_progression: poor
ref_progression: good
will_progression: good

manifesting_progression: marksman
initiating_progression: partial

weapon_proficiencies:
  - Simple
  - Light Martial
  - Projectile Martial
  - Thrown Martial
armor_proficiencies:
  - Light
shield_proficiencies:
  - buckler

class_features:

  - name: manifesting
    levels: [1]
    text: |
      A marksman's ability to manifest powers is limited by the power points she has available. Her base daily allotment of power points is given on Table: The Marksman. In addition, she receives bonus power points per day if she has a high Wisdom score. Her race may also provide bonus power points per day, as may certain feats and items.

      *Powers Known*: A marksman begins play knowing no marksman powers (although she can manifest powers from power completion or power trigger items as normal). At each level indicated on Table: The Marksman, she unlocks the knowledge of a new power.

      Choose the powers known from the marksman power list. (Exception: The feat Expanded Knowledge does allow a marksman to learn powers from the lists of other classes.) A marksman can manifest any power that has a power point cost equal to or lower than her manifester level.

      The total number of powers a marksman can manifest in a day is limited only by her daily power points.

      A marksman simply knows her powers; they are ingrained in her mind. She does not need to prepare them (in the way that some spellcasters prepare their spells), though she must get a good night's sleep each day to regain all her spent power points.

      The Difficulty Class for saving throws against marksman powers is 10 + the power's level + the marksman's Wisdom modifier.

      *Maximum Power Level Known:* A marksman begins play with the ability to learn 1st-level powers. As she attains higher levels, she may gain the ability to master more complex powers. To learn or manifest a power, a marksman must have a wisdom score of at least 10 + the power's level.

  - name: maneuvers
    levels: [1]
    text: |
      A mind's eye disciple begins her career with knowledge of three martial maneuvers. The disciplines available to her are Sleeping Goddess, Solar Wind, and Tempest Gale.

      Once the mind's eye disciple knows a maneuver, she must ready it before she can use it (see Maneuvers Readied, below). A maneuver usable by mind's eye disciples is considered an extraordinary ability unless otherwise noted in it or its discipline's description. A mind's eye disciple's maneuvers are not affected by spell resistance, and she does not provoke attacks of opportunity when she initiates one.

      The mind's eye disciple learns additional maneuvers at higher levels, as indicated on Table: The Marksman. The maximum level of maneuvers gained through mind's eye disciple levels is limited by those listed in that table as well, although this restriction does not apply to maneuvers added to his maneuvers known through other methods, such as prestige classes or the Advanced Study feat. A mind's eye disciple must meet a maneuver's prerequisite to learn it. See the Systems and Use chapter in Path of War for more details on how maneuvers are used.

      Upon reaching 4th level, and at every even numbered initiator level thereafter (6th, 8th, 10th, and so on), the mind's eye disciple can choose to learn a new maneuver in place of one she already knows. In effect, she loses the old maneuver in exchange for the new one. She can choose a new maneuver of any level she likes, as long as she observes the restriction on the highest-level maneuvers she knows; the mind's eye disciple need not replace the old maneuver with a maneuver of the same level. She can swap only a single maneuver at any given level. A mind's eye disciple initiation modifier is Wisdom, and each mind's eye disciple level is counted as a full initiator level.

      *Maneuvers Readied:* A mind's eye disciple can ready all three of her maneuvers known at 1st level, and as she advances in level and learns more maneuvers, she is able to ready more, but must still choose which maneuvers to ready. A mind's eye disciple must always ready her maximum number of maneuvers readied. She readies her maneuvers by opening her mind's eye and meditating on what it sees for ten minutes. The maneuvers she chooses remain readied until she decides to meditate again and change them. The mind's eye disciple does not need to sleep or rest for any long period of time in order to ready her maneuvers; any time she spends ten minutes focusing, she can change her readied maneuvers.

      A mind's eye disciple begins an encounter with all her readied maneuvers unexpended, regardless of how many times she might have already used them since she chose them. When she initiates a maneuver, she expends it for the current encounter, so each of her readied maneuvers can be used once per encounter (unless she recovers them, as described below).

      In order for the mind's eye disciple to recover maneuvers, she must focus her mind's eye on a target. As a full-round action, she selects one creature she can see, recovering a number of expended maneuvers equal to her mind's eye disciple initiation modifier (minimum 2). Her next ranged attack against that creature ignores any miss chance possessed by the target (including that of total concealment) and does not take penalties on attack rolls from attacking that creature from beyond her weapon's first range increment. In addition, she gains an insight bonus on that attack roll equal to her mind's eye disciple initiation modifier. Alternately, the mind's eye disciple may focus inward and recover a single maneuver as a standard action.

      *Stances Known:* A mind's eye disciple begins his career with knowledge of one stance from any discipline open to mind's eye disciples. At 4th, 7th, 11th, and 13th levels, she can select an additional stance to learn. The maximum level of stances gained through mind's eye disciple levels is limited by those listed in Table: The Marksman. Unlike maneuvers, stances are not expended and the mind's eye disciple does not have to ready them. All the stances she knows are available to her at all times, and she can change the stance she is currently maintaining as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance or discipline description.

      Unlike with maneuvers, a mind's eye disciple cannot learn a new stance at higher levels in place of one she already knows.

  - name: opened eye
    type: Su
    levels: [1]
    text: At 1st level, the mind's eye disciple's power allows her to wield weapons more freely. She treats all ranged and thrown weapons she wields as Sleeping Goddess discipline weapons.

  - name: Point-Blank Shot
    levels: [1]
    text: At 1st level, a marksman gains the Point-Blank Shot feat as a bonus feat.

  - name: wind reader
    type: Su
    levels: [1]
    text: A marksman can use her heightened senses and awareness of her surroundings to read the wind and environment, allowing her to drastically improve her accuracy. While maintaining psionic focus, she can spend a swift action to gain a competence bonus equal to her Wisdom modifier on ranged attacks until the end of the round. She can do this a number of times per day equal to 3 + her class level.

  - name: evade arrows
    type: Ex
    levels: [2, 6, 10, 14, 18]
    levels_text:
      2: +1
      6: +2
      10: +3
      14: +4
      18: +5
    text: At 2nd level, a marksman's familiarity with ranged attacks and her natural intuition alerts her to danger from mundane ranged attacks. She gains a +1 Dodge bonus to Armor Class against ranged attacks (but not ranged touch attacks). At 6th level and every four marksman levels thereafter, this Dodge bonus increases by 1.

  - name: favored weapon
    levels: [2, 6, 10, 14, 18]
    levels_text:
      2: +1
      6: +2
      10: +3
      14: +4
      18: +5
    text: |
      Marksmen of 2nd level select a group of ranged weapons from the list below as their preferred weapons and gain a +1 competence bonus to ranged attack rolls made with any weapon of that group. Every four marksman levels thereafter, this bonus increases by 1.

      - *Bows:* composite longbow, composite shortbow, longbow, and shortbow.
      - *Crossbows:* double crossbow, hand crossbow, heavy crossbow, light crossbow, repeating heavy crossbow, and repeating light crossbow.
      - *Spears:* javelin, lance, longspear, pilum, shortspear, spear, and trident.
      - *Thrown:* blowgun, bolas, boomerang, chakram, club, dagger, dart, halfling sling staff, javelin, light hammer, net, shortspear, shuriken, sling, spear, starknife, throwing axe, trident, wooden stake.

      *Note:* Additional weapons can be added to these groups or additional weapon groups can be created at your GM's discretion. Some weapons may belong to multiple weapon groups at your GM's discretion.

  - name: discipline skill
    type: Ex
    levels: [3, 6, 9, 12, 15, 18]
    levels_text:
      3: +1
      6: +2
      9: +3
      12: +4
      15: +5
      18: +6
    text: At 3rd level, a mind's eye disciple selects a discipline she has access to. She gains a +1 bonus on checks with that discipline's associated skill. This bonus increases by +1 at 6th level and every three levels thereafter.

  - name: focused eye
    type: Su
    levels: [3, 7, 11, 15, 19]
    levels_text:
      3: +2
      7: +3
      11: +4
      15: +5
      19: +6
    text: Starting at 3rd level, as long as the mind's eye disciple maintains psionic focus, she gains a +2 competence bonus on damage rolls for when initiating strikes with ranged or thrown weapons. At 7th level and every four levels thereafter, this bonus increases by +1.

  - name: cover fire
    type: Ex
    levels: [4]
    text: |
      Beginning at 4th level, the marksman knows not only how to directly engage her enemies, but also how to protect her allies. As an attack action, she may choose to fire a ranged or thrown weapon at an opponent within 30 feet to distract that opponent rather than to deal damage. Make an attack roll against the space a target occupies (AC 10). When a mind's eye disciple uses her cover fire class feature, any boosts she is affected by also affect the cover fire attack. If successful, the targeted enemy must make a Reflex save (DC 10 + one-half the marksman's class level + the marksman's Dexterity modifier), or be staggered for one round. If the target fails its saving throw, it is also affected by any additional damage or effects that the boost would normally apply to an attack. The marksman still expends ammunition as normal for this attack.

      If the attack roll would indicate a critical threat and the result would hit the opponent's AC, roll to confirm: if the critical hit is confirmed against the opponent's AC, the attack does normal damage as well. A marksman cannot use cover fire if her opponent or the square she targets would be subject to a miss chance (such as from a concealed target).

  - name: bonus feat
    levels: [5, 11, 14, 17, 20]
    levels_text:
      5: 1 feat
      11: 2 feats
      14: 3 feats
      17: 4 feats
      20: 5 feats
    text: |
      A marksman of 5th level gains a bonus feat chosen from the following list: Advanced Study, Crossbow Mastery, Deadly Aim, Discipline Focus, Discipline Mastery, Expanded Knowledge, Extra Readied Maneuver, Far Shot, Fell Shot, Greater Psionic Shot, Parting Shot, Precise Shot, Psionic Meditation, Psionic Shot, Quick Draw, Rapid Reload, Return Shot, Returning Throw, or a feat that requires a particular weapon when it is selected, such as Weapon Focus or Improved Critical. If the marksman chooses a feat that requires a particular weapon, she must select a weapon from her selected ranged weapon group. The marksman must still meet all prerequisites for the feat to select it.

      At 11th level and every three marksman levels thereafter, the marksman gains another bonus feat from the same list.

  - name: disengage
    type: Ex
    levels: [7]
    text: Once a marksman has reached 7th level, she learns how to effectively distance herself from enemies. When the marksman would provoke an attack of opportunity for moving out of a threatened space, she may expend her psionic focus to add her Wisdom modifier to her Acrobatics rolls to avoid attacks of opportunity for the round and can move at full speed without increasing the Acrobatics DC.

  - name: augmented eye
    type: Su
    levels: [8, 12, 16, 20]
    levels_text:
      8: 3 PP
      12: 4 PP
      16: 5 PP
      20: 6 PP
    text: |
      Starting at 8th level, a the mind's eye disciple gains the ability to augment her maneuvers by spending power points. A the mind's eye disciple can spend a maximum number of power points augmenting a maneuver equal to one plus one additional power point for every four initiator levels she possesses (to a maximum of 6 at 20th level). If the mind's eye disciple has the ability to augment her maneuvers in other ways, such as from another class feature or the maneuver itself, this cannot be combined with the augments granted by this ability; she must choose which augmentation type to use when initiating the maneuver. These augments can only be used on maneuvers that involve attack rolls.

      - For every power point the mind's eye disciple spends, this maneuver deals an additional 1d8 points of damage of the mind's eye disciple's active energy type. For every 2d8 she increases the damage by, the save DC of this maneuver (if any) increases by +1. If a maneuver involves multiple attacks, this additional damage only applies to the first attack that hits.
      - For every power point the mind's eye disciple spends, attacks made as part of this maneuver ignore 5% of miss chance possessed by the target (such as from concealment or the displacement spell). Miss chances cannot be reduced below 0% with this augment.

  - name: defensive shot
    type: Ex
    levels: [13]
    text: At 13th level, a marksman no longer provokes attacks of opportunity when making ranged attacks with a ranged or thrown weapon.

  - name: ranged specialist
    type: Su
    levels: [19]
    text: At 19th level, a marksman's ranged and thrown attacks have their critical multiplier increased by 1 (x2 becomes x3, for example) and her penalties for range increments are halved. If the marksman has the Far Shot feat, she instead suffers no penalties for range increments.
---

Masters of ranged weapons, marksmen are the elite wielders of any weapon that can be shot, fired, or thrown. Unlike rangers, who are more focused on tracking down their chosen enemies, marksmen focus their attention on harnessing their ranged combat abilities, learning to use their weapon in ways others could only dream of. Their psionic ability improves their attacks and augments their otherwise limited defensive abilities.

Role: As light armor wielders, marksmen are not intended to be front-line combatants. They excel when they have a safe distance from which to unleash their deadly attacks.
