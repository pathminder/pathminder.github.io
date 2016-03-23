---
title: Paladin (Knight Disciple)
sources:
  - Pathfinder Roleplaying Game Core Rulebook
  - "Path of War: Expanded"
tags:
  - Initiator

max_level: 20
hit_die: 10
prerequisites:
  - Lawful Good
starting_wealth: 5d6 × 10 gp (average 175 gp)

class_skills:
  - Bluff
  - Craft
  - Diplomacy
  - Handle Animal
  - Heal
  - Knowledge (nobility)
  - Knowledge (religion)
  - Perception
  - Profession
  - Ride
  - Sense Motive
  - Spellcraft
skill_ranks_per_level: 4

bab_progression: full
fort_progression: good
ref_progression: poor
will_progression: good

initiating_progression: partial

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

  - name: code of conduct
    levels: [1]
    text: |
      A paladin must be of lawful good alignment and loses all class features except proficiencies if she ever willingly commits an evil act.

      Additionally, a paladin's code requires that she respect legitimate authority, act with honor (not lying, not cheating, not using poison, and so forth), help those in need (provided they do not use the help for evil or chaotic ends), and punish those who harm or threaten innocents.

      **Associates:** While she may adventure with good or neutral allies, a paladin avoids working with evil characters or with anyone who consistently offends her moral code. Under exceptional circumstances, a paladin can ally with evil associates, but only to defeat what she believes to be a greater evil. A paladin should seek an atonement spell periodically during such an unusual alliance, and should end the alliance immediately should she feel it is doing more harm than good. A paladin may accept only henchmen, followers, or cohorts who are lawful good.

  - name: ex-paladins
    levels: [1]
    text: |
      A paladin who ceases to be lawful good, who willfully commits an evil act, or who violates the code of conduct loses all paladin spells and class features (except weapon, armor, and shield proficiencies). She may not progress any further in levels as a paladin. She regains her abilities and advancement potential if she atones for her violations (see *atonement*), as appropriate.

  - name: aura of good
    type: Ex
    levels: [1]
    text: The power of a paladin's aura of good (see the *detect good* spell) is equal to her paladin level.

  - name: "*detect evil*"
    type: Sp
    levels: [1]
    text: At will, a paladin can use *detect evil*, as the spell. A paladin can, as a move action, concentrate on a single item or individual within 60 feet and determine if it is evil, learning the strength of its aura as if having studied it for 3 rounds. While focusing on one individual or object, the paladin does not detect evil in any other object or individual within range.

  - name: maneuvers
    levels: [1]
    text: |
      A knight disciple begins her career with knowledge of three martial maneuvers. The disciplines available to her are Golden Lion, Iron Tortoise, and Silver Crane.

      Once the knight disciple knows a maneuver, she must ready it before she can use it (see Maneuvers Readied, below). A maneuver usable by knight disciples is considered an extraordinary ability unless otherwise noted in it or its discipline's description. A knight disciple's maneuvers are not affected by spell resistance, and she does not provoke attacks of opportunity when she initiates one.

      The knight disciple learns additional maneuvers at higher levels, as indicated on Table: The Paladin. The maximum level of maneuvers gained through knight disciple levels is limited by those listed in that table as well, although this restriction does not apply to maneuvers added to his maneuvers known through other methods, such as prestige classes or the Advanced Study feat. A knight disciple must meet a maneuver's prerequisite to learn it. See the Systems and Use chapter in Path of War for more details on how maneuvers are used.

      Upon reaching 4th level, and at every even numbered initiator level thereafter (6th, 8th, 10th, and so on), the knight disciple can choose to learn a new maneuver in place of one she already knows. In effect, she loses the old maneuver in exchange for the new one. She can choose a new maneuver of any level she likes, as long as she observes the restriction on the highest-level maneuvers she knows; the knight disciple need not replace the old maneuver with a maneuver of the same level. She can swap only a single maneuver at any given level. A knight disciple's initiation modifier is Charisma, and each knight disciple level is counted as a full initiator level.

      *Maneuvers Readied:* A knight disciple can ready all three of her maneuvers known at 1st level, and as she advances in level and learns more maneuvers, she is able to ready more, but must still choose which maneuvers to ready. A knight disciple must always ready her maximum number of maneuvers readied. She readies her maneuvers by performing weapon drills or praying to her deity for ten minutes. The maneuvers she chooses remain readied until she decides to meditate again and change them. The knight disciple does not need to sleep or rest for any long period of time in order to ready her maneuvers; any time she spends ten minutes in prayer and practice, she can change her readied maneuvers.

      A knight disciple begins an encounter with all her readied maneuvers unexpended, regardless of how many times she might have already used them since she chose them. When she initiates a maneuver, she expends it for the current encounter, so each of her readied maneuvers can be used once per encounter (unless she recovers them, as described below).

      In order for the knight disciple to recover maneuvers, she must project her power, protecting her allies from harm as a full-round action. When she does so, she recovers a number of expended maneuvers equal to her knight disciple initiation modifier (minimum 2) and each ally within 30 feet gains a sacred bonus equal to the knight disciple's initiation modifier (minimum 1) to their AC and on saving throws for one round. Alternately, the knight disciple may focus inward and recover a single maneuver as a standard action.

      *Stances Known:* A knight disciple begins play with knowledge of one stance from any discipline open to knight disciples. At 4th, 7th, 11th, and 13th levels, she can select an additional stance to learn. The maximum level of stances gained through knight disciple levels is limited by those listed in Table: The Paladin. Unlike maneuvers, stances are not expended and the knight disciple does not have to ready them. All the stances she knows are available to her at all times, and she can change the stance she is currently maintaining as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance or discipline description.

      Unlike with maneuvers, a knight disciple cannot learn a new stance at higher levels in place of one she already knows.

  - name: crusader's training
    levels: [1, 4, 7, 10, 13, 16, 19]
    levels_text:
      1: 1 ability
      4: 2 abilities
      7: 3 abilities
      10: 4 abilities
      13: 5 abilities
      16: 6 abilities
      19: 7 abilities
    text: |
      At 1st level, a knight disciple begins to express her divine power through her initiating and with effects similar to the spells of other paladins. She selects one of the following abilities to learn at 1st level, and gains another ability at 4th level and every three levels thereafter.

      - *Detect Alignment (Su):* The knight disciple gains the ability to use *detect chaos*, *detect good*, and *detect law* spell-like abilities at-will, with a caster level equal to her class level.
      - *Detect Undead (Su):* The knight disciple can use *detect undead* as a spell-like ability at-will. If she wishes, she can activate and concentrate on this ability at the same time as her detect evil ability.
      - *Divine Interception (Su):* Once per encounter, the knight disciple can move up to her speed as an immediate action, provided she ends her movement in a square adjacent to another ally.
      - *Fiendbane (Su):* The knight disciple can expend one use of her guardian's shield ability as a swift action to enchant her weapon with holy light that banishes evil outsiders. The next time the knight disciple hits with that weapon, if the target is an outsider with the evil and extraplanar subtypes, that creature must succeed at a Will save (DC 10 + 1/2 the knight disciple's class level + the knight disciple's initiation modifier) or be banished back to its home plane. A knight disciple can keep a weapon charged with this ability indefinitely, although she may only have one such weapon charged at any one time.
      - *Ghost Hunter (Su):* The knight disciple's weapons and armor gain the effects of the *ghost touch* weapon special ability in addition to their other properties for as long as she wields or wears them.
      - *Improved Guardian's Shield (Su):* Allies under the effects of the knight disciple's guardian's shield ability also gain the benefits of a *protection from evil* spell for the duration of the shield.
      - *Know Thine Enemy (Ex):* The knight disciple can make untrained Knowledge checks to identify creatures with no limit to the DC, and gains a bonus on Knowledge checks to identify chaotic and/or evil creatures equal to 1/2 her class level.
      - *Righteous Sanctuary (Su):* Once per encounter as an immediate action, the knight disciple can allow a willing ally to move up to their speed. This movement does not provoke attacks of opportunity, and the ally must end their movement adjacent to the knight disciple. If the ally would not be able to reach the knight disciple, they cannot be allowed to move with this ability.
      - *Truthseeker (Su):* The knight disciple can use *discern lies* as a spell-like ability with a caster level equal to her initiator level. She can use this ability for a number of rounds per day equal to her class level, although these rounds need not be consecutive.

  - name: guardian's shield
    type: Su
    levels: [1]
    text: |
      At 1st level, a knight disciple learns to surround her allies in a field of holy protective energy. Whenever she initiates a strike, the knight disciple can apply a guardian's shield to one ally (other than herself) within 60 feet as a free action. This shield lasts for a number of rounds equal to the knight disciple's initiation modifier.

      A guardian's shield grants the affected ally a number of temporary hit points equal to twice the knight disciple's initiator level. These temporary hit points do not stack with other temporary hit points, and vanish when the shield's duration expires. The knight disciple can use her guardian's shield ability a number of times per day equal to 1/2 her class level (minimum 1) + her knight disciple initiation modifier.

      This ability counts as the lay on hands class feature for the purposes of the Extra Lay on Hands feat.

  - name: spell familiarity
    type: Ex
    levels: [1]
    text: Starting at 1st level, a knight disciple can use spell completion and spell triggers items (such as scrolls and wands) as if she possessed the ability to cast paladin spells, using her initiator level as her effective caster level.

  - name: mark of censure
    type: Su
    levels: [1, 4, 7, 10, 11, 13, 16, 19]
    levels_text:
      1: 1/day, 1× modifier
      4: 2/day
      7: 3/day
      10: 4/day
      11: 2× modifier
      13: 5/day
      16: 6/day
      19: 7/day
    text: At 1st level, a knight disciple gains the ability to censure the actions of evil creatures, protecting her allies from the harm they cause. Once per day as a swift action, the knight disciple can apply a mark of censure to any evil creature she can see. The mark lasts for 24 hours or until the creature is slain. While the mark of censure is in effect, the knight disciple's allies (other than herself) gain damage reduction/– equal to her knight disciple initiation modifier against attacks made by the marked creature. At 11th level, this damage reduction increases to equal twice her knight disciple initiation modifier. At 4th level and every three levels thereafter, the knight disciple can use this ability an additional time per day.

  - name: divine grace
    type: Su
    levels: [2]
    text: At 2nd level, a paladin gains a bonus equal to her Charisma bonus (if any) on all saving throws.

  - name: aura of courage
    type: Su
    levels: [3]
    text: At 3rd level, a paladin is immune to fear (magical or otherwise). Each ally within 10 feet of her gains a +4 morale bonus on saving throws against fear effects. This ability functions only while the paladin is conscious, not if she is unconscious or dead.

  - name: divine health
    type: Ex
    levels: [3]
    text: At 3rd level, a paladin is immune to all diseases, including supernatural and magical diseases, including mummy rot.

  - name: merciful shield
    type: Su
    levels: [3, 6, 9, 12, 15, 18]
    levels_text:
      3: 1 condition
      6: 2 conditions
      9: 3 conditions
      12: 4 conditions
      15: 5 conditions
      18: 6 conditions
    text: |
      At 3rd level, a knight disciple's guardian's shield becomes potent enough to protect allies from debilitating effects. The knight disciple selects one condition from the list below that she meets the prerequisites for. Whenever an ally under the effects of her guardian's shield would gain a condition she has selected, that condition is negated and the duration of the guardian's shield affecting them is reduced by one round. This ability can remove a condition caused by a curse, disease, or poison without curing the affliction.

      At 3rd level, the knight disciple can select from the following conditions:

      - Shaken
      - Sickened
      - Fatigued

      At 6th level, the knight disciple adds the following conditions to the list of those that can be selected:

      - Dazed
      - Stunned
      - Diseased: The knight disciple's guardian's shield ability also acts as a *remove disease* spell, using the knight disciple's level as the caster level.
      - Staggered: The target is no longer staggered, unless the target is at exactly 0 hit points.

      At 9th level, the knight disciple adds the following conditions to the list of those that can be selected.

      - Cursed: The knight disciple's guardian's shield ability also acts as a remove curse spell, using the paladin's level as the caster level.
      - Exhausted: The knight disciple must have the fatigue condition before selecting this condition.
      - Frightened: The knight disciple must have the shaken condition before selecting this condition.
      - Nauseated: The knight disciple must have the sickened condition before selecting this condition.
      - Poisoned: The knight disciple's guardian's shield ability also acts as a neutralize poison spell, using the knight disciple's level as the caster level.

      At 12th level, the knight disciple adds the following conditions to the list of those that can be selected:

      - Blinded
      - Deafened
      - Paralyzed

      At 6th level and every three levels thereafter, the knight disciple selects an additional condition from the above lists. The effects of this ability stack; for example, a 12th level knight disciple's guardian's shield could provide 24 temporary hit points and protect against fatigue, exhaustion, diseases, and poisons. Once the knight disciple selects a condition to protect against, that choice cannot be changed.

  - name: empowered healing
    type: Su
    levels: [4]
    text: At 4th level, a the knight disciple healing maneuvers become more potent. Any maneuver she initiates that heals hit point damage (to herself or others) heals an additional 50% points of damage (rounded down).

  - name: aura of resolve
    type: Su
    levels: [8]
    text: |
      At 8th level, a paladin is immune to charm spells and spell-like abilities. Each ally within 10 feet of her gains a +4 morale bonus on saving throws against charm effects.

      This ability functions only while the paladin is conscious, not if she is unconscious or dead.

  - name: guardian's aura
    type: Ex
    levels: [11]
    text: At 11th level, a knight disciple's protective nature allows her to use her counters for the benefit of her allies instead of just herself. Whenever she initiates a counter, she can choose to have that counter affect an ally within 10 feet instead of herself. When determining if the counter can be initiated (for example, if the counter is initiated in response to an attack), she treats that ally as if they were herself. The counter still uses the knight disciple's modifiers to determine its success or failure, and she still makes any rolls or checks for the counter.

  - name: aura of faith
    type: Su
    levels: [14]
    text: |
      At 14th level, a paladin's weapons are treated as good-aligned for the purposes of overcoming damage reduction. Any attack made against an enemy within 10 feet of her is treated as good-aligned for the purposes of overcoming damage reduction.

      This ability functions only while the paladin is conscious, not if she is unconscious or dead.

  - name: aura of righteousness
    type: Su
    levels: [17]
    text: |
      At 17th level, a paladin gains DR 5/evil and immunity to compulsion spells and spell-like abilities. Each ally within 10 feet of her gains a +4 morale bonus on saving throws against compulsion effects.

      This ability functions only while the paladin is conscious, not if she is unconscious or dead.

  - name: holy disciple
    type: Su
    levels: [20]
    text: At 20th level, a knight disciple becomes a paragon of divine martial justice. She gains damage reduction 10/evil, and whenever a creature under the effect of her mark of censure deals damage to one of her allies (not including herself), that creature takes 1/2 the damage it dealt. This damage is the same type as the damage that was dealt to the knight disciple's ally. In addition, the temporary hit points granted by the knight disciple's guardian's shield ability increase by 50% (rounded down).
---

Through a select, worthy few shines the power of the divine. Called paladins, these noble souls dedicate their swords and lives to the battle against evil. Knights, crusaders, and law-bringers, paladins seek not just to spread divine justice but to embody the teachings of the virtuous deities they serve. In pursuit of their lofty goals, they adhere to ironclad laws of morality and discipline. As reward for their righteousness, these holy champions are blessed with boons to aid them in their quests: powers to banish evil, heal the innocent, and inspire the faithful. Although their convictions might lead them into conflict with the very souls they would save, paladins weather endless challenges of faith and dark temptations, risking their lives to do right and fighting to bring about a brighter future.

**Role:** Paladins serve as beacons for their allies within the chaos of battle. While deadly opponents of evil, they can also empower goodly souls to aid in their crusades. Their magic and martial skills also make them well suited to defending others and blessing the fallen with the strength to continue fighting.
