---
title: Alchemist (Polymath, Vivisectionist)
sources:
  - Pathfinder Roleplaying Game Advanced Class Guide
  - Pathfinder Roleplaying Game Advanced Player's Guide
  - Pathfinder Roleplaying Game Advanced Race Guide
  - Pathfinder Roleplaying Game Ultimate Magic
  - "Path of War: Expanded"
tags:
  - Alchemy
  - Sneak Attack

max_level: 20
prerequisites:
hit_die: 8
starting_wealth: 3d6 × 10 gp (average 105 gp)

class_skills:
  - Appraise
  - Craft
  - Disable Device
  - Fly
  - Heal
  - Knowledge (arcana)
  - Knowledge (nature)
  - Perception
  - Profession
  - Sleight of Hand
  - Spellcraft
  - Survival
  - Use Magic Device
skill_ranks_per_level: 4

bab_progression: mid
fort_progression: good
ref_progression: good
will_progression: poor

extract_progression: mid_minus_one
spell_list: alchemist
spell_list_levels: 6

initiating_progression: half

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
      A polymath begins his career with knowledge of three martial maneuvers. If the polymath does not have these discipline’s associated skills as class skills, he gains them as class skills. The disciplines available to him are Primal Fury, Solar Wind, and Steel Serpent.

      Once the polymath knows a maneuver, he must ready it before he can use it (see Maneuvers Readied, below). A maneuver usable by polymaths is considered an extraordinary ability unless otherwise noted in it or its discipline’s description. A polymath’s maneuvers are not affected by spell resistance, and he does not provoke attacks of opportunity when he initiates one.

      The polymath learns additional maneuvers at higher levels, as indicated on the class table. The maximum level of maneuvers gained through polymath levels is limited by those listed in that table as well, although this restriction does not apply to maneuvers added to his maneuvers known through other methods, such as prestige classes or the Advanced Study feat. A polymath must meet a maneuver’s prerequisite to learn it. See the Systems and Use chapter in Path of War for more details on how maneuvers are used.

      Upon reaching 4th level, and at every even numbered initiator level thereafter (6th, 8th, 10th, and so on), the polymath can choose to learn a new maneuver in place of one he already knows. In effect, he loses the old maneuver in exchange for the new one. He can choose a new maneuver of any level he likes, as long as he observes the restriction on the highest-level maneuvers he knows; the polymath need not replace the old maneuver with a maneuver of the same level. He can swap only a single maneuver at any given level. A polymath’s initiation modifier is Intelligence, and each polymath level is counted as a full initiator level.

      *Maneuvers Readied:* A polymath can ready all three of his maneuvers known at 1st level, and as he advances in level and learns more maneuvers, he is able to ready more, but must still choose which maneuvers to ready. A polymath must always ready his maximum number of maneuvers readied. He readies his maneuvers by meditating or performing martial katas for ten minutes. The maneuvers he chooses remain readied until he decides to practice again and change them. The polymath does not need to sleep or rest for any long period of time in order to ready his maneuvers; any time he spends ten minutes study or meditation, he can change his readied maneuvers.

      A polymath begins an encounter with all his readied maneuvers unexpended, regardless of how many times he might have already used them since he chose them. When he initiates a maneuver, he expends it for the current encounter, so each of his readied maneuvers can be used once per encounter (unless he recovers them, as described below).

      In order for the polymath to recover maneuvers, he must re-evaluate his opponents and their abilities as a full-round action. When he does, he replaces a number of expended maneuvers equal to his polymath initiation modifier (minimum 2) with new readied polymath maneuvers he knows. If he wishes, he may replace these maneuvers with themselves, effectively recovering them. In addition, whenever the polymath recovers maneuvers in this way, he may drink one extract he has prepared as a swift action. Alternately, the polymath may take a brief moment to collect his thoughts to recover a single maneuver as a standard action.

      *Stances Known:* A polymath begins his career with knowledge of one stance from any discipline open to polymaths. At 4th, 7th, 11th, and 13th levels, he can select an additional stance to learn. The maximum level of stances gained through polymath levels is limited by those listed in the class table. Unlike maneuvers, stances are not expended and the polymath does not have to ready them. All the stances he knows are available to his at all times, and he can change the stance he is currently maintaining as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance or discipline description.

      Unlike with maneuvers, a polymath cannot learn a new stance at higher levels in place of one he already knows.

  - name: alchemy
    type: Su
    levels: [1]
    text: |
      Alchemists are not only masters of creating mundane alchemical substances such as alchemist's fire and smokesticks, but also of fashioning magical potion-like extracts in which they can store spell effects. In effect, an alchemist prepares his spells by mixing ingredients into a number of extracts, and then "casts" his spells by drinking the extract. When an alchemist creates an extract or bomb, he infuses the concoction with a tiny fraction of his own magical power---this enables the creation of powerful effects, but also binds the effects to the creator.

      When using Craft (alchemy) to create an alchemical item, an alchemist gains a competence bonus equal to his class level on the Craft (alchemy) check. In addition, an alchemist can use Craft (alchemy) to identify potions as if using detect magic. He must hold the potion for 1 round to make such a check.

      An alchemist can create two special types of magical items---extracts,and mutagens are transformative elixirs that the alchemist drinks to enhance his physical abilities---both of these are detailed in their own sections below.

      Extracts are the most varied of the two. In many ways, they behave like spells in potion form, and as such their effects can be dispelled by effects like dispel magic using the alchemist's level as the caster level. Unlike potions, though, extracts can have powerful effects and duplicate spells that a potion normally could not.

      An alchemist can create only a certain number of extracts of each level per day. His base daily allotment of extracts is given on Table: Alchemist. In addition, he receives bonus extracts per day if he has a high Intelligence score, in the same way a wizard receives bonus spells per day.

      When an alchemist mixes an extract, he infuses the chemicals and reagents in the extract with magic siphoned from his own magical aura. An extract immediately becomes inert if it leaves the alchemist's possession, reactivating as soon as it returns to his keeping---an alchemist cannot normally pass out his extracts for allies to use (but see the “infusion” discovery below). An extract, once created, remains potent for 1 day before becoming inert, so an alchemist must re-prepare his extracts every day. Mixing an extract takes 1 minute of work---most alchemists prepare many extracts at the start of the day or just before going on an adventure, but it's not uncommon for an alchemist to keep some (or even all) of his daily extract slots open so that he can prepare extracts in the field as needed.

      Although the alchemist doesn't actually cast spells, he does have a formulae list that determines what extracts he can create. An alchemist can utilize spell-trigger items if the spell appears on his formulae list, but not spell-completion items (unless he uses Use Magic Device to do so). An extract is "cast" by drinking it, as if imbibing a potion---the effects of an extract exactly duplicate the spell upon which its formula is based, save that the spell always affects only the drinking alchemist. An alchemist can draw and drink an extract as a standard action. The alchemist uses his level as the caster level to determine any effect based on caster level.

      Creating extracts consumes raw materials, but the cost of these materials is insignificant---comparable to the valueless material components of most spells. If a spell normally has a costly material component, that component is expended during the consumption of that particular extract. Extracts cannot be made from spells that have focus requirements (alchemist extracts that duplicate divine spells never have a divine focus requirement). An alchemist can prepare an extract of any formula he knows. To learn or use an extract, an alchemist must have an Intelligence score equal to at least 10 + the extract's level. The Difficulty Class for a saving throw against an alchemist's extract is 10 + the extract level + the alchemist's Intelligence modifier.

      An alchemist may know any number of formulae. He stores his formulae in a special tome called a formula book. He must refer to this book whenever he prepares an extract but not when he consumes it. An alchemist begins play with two 1st level formulae of his choice, plus a number of additional forumlae equal to his Intelligence modifier. At each new alchemist level, he gains one new formula of any level that he can create. An alchemist can also add formulae to his book just like a wizard adds spells to his spellbook, using the same costs and time requirements. An alchemist can study a wizard's spellbook to learn any formula that is equivalent to a spell the spellbook contains. A wizard, however, cannot learn spells from a formula book. An alchemist does not need to decipher arcane writings before copying them.

  - name: sneak attack
    type: Ex
    levels: [1, 3, 5, 7, 9, 11, 13, 15, 17, 19]
    levels_text:
      1:  +1d6
      3:  +2d6
      5:  +3d6
      7:  +4d6
      9:  +5d6
      11: +6d6
      13: +7d6
      15: +8d6
      17: +9d6
      19: +10d6
    text: At 1st level, a vivisectionist gains the sneak attack ability as a rogue of the same level. If a character already has sneak attack from another class, the levels from the classes that grant sneak attack stack to determine the effective rogue level for the sneak attack's extra damage dice (so an alchemist 1/rogue 1 has a +1d6 sneak attack like a 2nd-level rogue, an alchemist 2/rogue 1 has a +2d6 sneak attack like a 3rd-level rogue, and so on).

  - name: brew potion
    type: Ex
    levels: [1]
    text: At 1st level, alchemists receive Brew Potion as a bonus feat. An alchemist can brew potions of any formulae he knows (up to 3rd level), using his alchemist level as his caster level. The spell must be one that can be made into a potion. The alchemist does not need to meet the prerequisites for this feat.

  - name: mutagen
    type: Su
    levels: [1]
    text: |
      At 1st level, an alchemist discovers how to create a mutagen that he can imbibe in order to heighten his physical prowess at the cost of his personality. It takes 1 hour to brew a dose of mutagen, and once brewed, it remains potent until used. An alchemist can only maintain one dose of mutagen at a time---if he brews a second dose, any existing mutagen becomes inert. As with an extract or bomb, a mutagen that is not in an alchemist's possession becomes inert until an alchemist picks it up again.

      When an alchemist brews a mutagen, he selects one physical ability score---either Strength, Dexterity, or Constitution. It's a standard action to drink a mutagen. Upon being imbibed, the mutagen causes the alchemist to grow bulkier and more bestial, granting him a +2 natural armor bonus and a +4 alchemical bonus to the selected ability score for 10 minutes per alchemist level. In addition, while the mutagen is in effect, the alchemist takes a --2 penalty to one of his mental ability scores. If the mutagen enhances his Strength, it applies a penalty to his Intelligence. If it enhances his Dexterity, it applies a penalty to his Wisdom. If it enhances his Constitution, it applies a penalty to his Charisma.

      A non-alchemist who drinks a mutagen must make a Fortitude save (DC 10 + 1/2 the alchemist's level + the alchemist's Intelligence modifier) or become nauseated for 1 hour---a non-alchemist can never gain the benefit of a mutagen, but an alchemist can gain the effects of another alchemist's mutagen if he drinks it. (Although if the other alchemist creates a different mutagen, the effects of the “stolen” mutagen immediately cease.) The effects of a mutagen do not stack. Whenever an alchemist drinks a mutagen, the effects of any previous mutagen immediately end.

  - name: throw anything
    type: Ex
    levels: [1]
    text: All alchemists gain the Throw Anything feat as a bonus feat at 1st level. An alchemist adds his Intelligence modifier to damage done with splash weapons, including the splash damage if any. This bonus damage is already included in the bomb class feature.

  - name: discovery
    type: Su
    levels: [2, 4, 6, 8, 10, 12, 14, 16, 18]
    levels_text:
      2: 1 discovery
      4: 2 discoveries
      6: 3 discoveries
      8: 4 discoveries
      10: 5 discoveries
      12: 6 discoveries
      14: 7 discoveries
      16: 8 discoveries
    text: |
      At 2nd level, and then again every 2 levels thereafter (up to 18th level), an alchemist makes an incredible alchemical discovery. Unless otherwise noted, an alchemist cannot select an individual discovery more than once. Some discoveries can only be made if the alchemist has met certain prerequisites first, such as uncovering other discoveries. Discoveries that modify bombs that are marked with an asterisk (*) do not stack. Only one such discovery can be applied to an individual bomb. The DC of any saving throw called for by a discovery is equal to 10 + 1/2 the alchemist's level + the alchemist's Intelligence modifier.

      A vivisectionist may select the bleeding attack rogue talent in place of a discovery. At 10th level or later, a vivisectionist may select the crippling strike rogue talent in place of a discovery.

  - name: torturer's eye
    levels: [2]
    text: At 2nd level, a vivisectionist adds *deathwatch* to his formula book as a 1st-level extract.

  - name: cruel anatomist
    levels: [3]
    text: At 3rd level, a vivisectionist may use his Knowledge (nature) skill bonus in place of his Heal skill bonus.

  - name: swift alchemy
    type: Ex
    levels: [3]
    text: At 3rd level, an alchemist can create alchemical items with astounding speed. It takes an alchemist half the normal amount of time to create alchemical items, and he can apply poison to a weapon as a move action.

  - name: swift poisoning
    type: Ex
    levels: [6]
    text: At 6th level, an alchemist can apply a dose of poison to a weapon as a swift action.

  - name: tortorous transformation
    levels: [7, 9, 15]
    levels_text:
      7: "*anthropomorphic animal*"
      9: "*awaken*, *baleful polymorph*"
      15: "*regenerate*"
    text: |
      At 7th level, a vivisectionist adds *anthropomorphic animal* to his formula book as a 2nd-level extract. When he uses this extract, he injects it into an animal as part of a 2-hour surgical procedure. By using multiple doses of this extract as part of the surgery, he multiplies the duration by the number of extracts used.

      At 9th level, a vivisectionist adds *awaken* and *baleful polymorph* to his formula book as 3rd-level extracts. When he uses the awaken or baleful polymorph extract, he injects it into the target (not a plant) as part of a 24-hour surgical procedure. He can make *anthropomorphic animal* permanent on a creature by spending 7,500 gp.

      At 15th level, a vivisectionist adds *regenerate* to his formula book as a 5th-level extract.

  - name: persistent mutagen
    type: Su
    levels: [14]
    text: At 14th level, the effects of a mutagen last for 1 hour per level.

  - name: instant alchemy
    type: Ex
    levels: [18]
    text: At 18th level, an alchemist can create alchemical items with almost supernatural speed. He can create any alchemical item as a full-round action if he succeeds at the Craft (alchemy) check and has the appropriate resources at hand to fund the creation. He can apply poison to a weapon as an immediate action.

  - name: grand discovery
    type: Su
    levels: [20]
    text: |
      At 20th level, the alchemist makes a grand discovery. He immediately learns two normal discoveries, but also learns a third discovery chosen from the  list below, representing a truly astounding alchemical breakthrough of significant import. For many alchemists, the promise of one of these grand discoveries is the primary goal of their experiments and hard work.

      - *Awakened Intellect:* The alchemist's constant exposure to strange chemicals has expanded his mind. His Intelligence score permanently increases by 2 points.
      - *Eternal Youth:* The alchemist has discovered a cure for aging, and from this point forward he takes no penalty to his physical ability scores from advanced age. If the alchemist is already taking such penalties, they are removed at this time.
      - *Fast Healing:* The alchemist's flesh responds to damage with shocking speed---he gains fast healing 5.
      - *Greater Change Alignment (Su):* The effects of the alchemist's change alignment infusion become permanent and can only be reversed by a *wish* or *miracle*. A permanent, forced change of alignment may be devastating, and some believe it is little better than zealous slavery or mind control. Others consider a good alignment brought about by any means but purity of heart an affront to freedom. This discovery remains controversial at best. *Prerequisites:* change alignment discovery, infusion discovery.
      - *Philosopher's Stone:* The alchemist learns how to create a *philosopher's stone*, and can do so once per month at no cost. Creating a *philosopher's stone* takes 1 day of work.
      - *Poison Touch:* The alchemist gains a poisonous touch, as if under the effects of a *poison* spell. He can suppress or activate this ability as a free action. The physical appearance of how the alchemist generates and delivers his poisonous touch varies from alchemist to alchemist.
      - *True Mutagen:* The alchemist's mutagen now grants a +8 natural armor bonus and a +8 alchemical bonus to Strength, Dexterity, and Constitution. The alchemist takes a --2 penalty to his Intelligence, Wisdom, and Charisma as long as the mutagen persists.

favored_class_bonuses:

  - race: Dwarf
    bonus: Add +1/4 to the alchemist's natural armor bonus when using the character's mutagen.

  - race: Elf
    bonus: Add one extract formula from the alchemist's list to the character's formulae book. This formula must be at least one level lower than the highest-level formula the alchemist can create.

  - race: Gnome
    bonus: Add +1/2 to the number of bombs per day the alchemist can create.

  - race: Half-Elf
    bonus: Add +1 foot to the range increment of the alchemist's thrown splash weapons (including the alchemist's bombs). This option has no effect unless the alchemist has selected it 5 times (or another increment of 5).

  - race: Half-Orc
    bonus: Add +1/2 to bomb damage.

  - race: Halfling
    bonus: Add one extract formula from the alchemist's list to the character's formulae book. This formula must be at least one level lower than the highest-level formula the alchemist can create.

  - race: Human
    bonus: Add one extract formula from the alchemist's list to the character's formulae book. This formula must be at least one level below the highest formulae level the alchemist can create.

  - race: Dhampir
    bonus: Add +10 minutes to the duration of the alchemist's mutagens.

  - race: Drow
    bonus: Add +10 minutes to the duration of the alchemist's mutagens.

  - race: Goblin
    bonus: The alchemist gains fire resistance 1. Each time this reward is selected, increase fire resistance by +1. This fire resistance does not stack with fire resistance gained from other sources.

  - race: Grippli
    bonus: Add +1/4 to the number of toxic skin uses per day.

  - race: Hobgoblin
    bonus: Add +1/2 to the number of bombs per day the alchemist can create.

  - race: Ifrit
    bonus: Add +1/2 to the alchemist's bomb damage.

  - race: Kobold
    bonus: Add +1/2 to the number of bombs per day the alchemist can create.

  - race: Nagaji
    bonus: Add +1 on Craft (alchemy) checks to craft poison and +1/3 on the DCs of poisons the alchemist creates.

  - race: Orc
    bonus: Add +10 minutes to the duration of the alchemist's mutagens.

  - race: Ratfolk
    bonus: The alchemist gains +1/6 of a new discovery.

  - race: Svirfneblin
    bonus: Add one extract formula from the alchemist's list to the character's formulae book. This formula must be at least one level below the highest formulae level the alchemist can create.

  - race: Tiefling
    bonus: Add +1/2 to the alchemist's bomb damage.

  - race: Vanara
    bonus: Add +1/2 to the alchemist's bomb damage.

---

Whether secreted away in a smoky basement laboratory or gleefully experimenting in a well-respected school of magic, the alchemist is often regarded as being just as unstable, unpredictable, and dangerous as the concoctions he brews. While some creators of alchemical items content themselves with sedentary lives as merchants, providing tindertwigs and smokesticks, the true alchemist answers a deeper calling. Rather than cast magic like a spellcaster, the alchemist captures his own magic potential within liquids and extracts he creates, infusing his chemicals with virulent power to grant him impressive skill with poisons, explosives, and all manner of self-transformative magic.

A vivisectionist studies bodies to better understand their function. Unlike a chirurgeon, a vivisectionist’s goals are not related to healing, but rather to experimentation and knowledge that most people would consider evil.

**Role:** The alchemist's reputation is not softened by his exuberance (some would say dangerous recklessness) in perfecting his magical extracts and potion-like creations, infusing these substances with magic siphoned from his aura and using his own body as experimental stock. Nor is it mollified by the alchemist's almost gleeful passion for building explosive bombs and discovering strange new poisons and methods for their use. These traits, while making him a liability and risk for most civilized organizations and institutions of higher learning, seem to fit quite well with most adventuring groups.
