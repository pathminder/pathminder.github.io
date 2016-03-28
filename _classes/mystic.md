---
title: Mystic
sources:
  - "Path of War: Expanded"
tags:
  - Base
  - Initiator

max_level: 20
hit_die: 8
prerequisites:
starting_age: Intuitive
starting_wealth: 4d6 × 10 gp (average 140 gp)

class_skills:
  - Acrobatics
  - Autohypnosis
  - Craft
  - Intimidate
  - Knowledge
  - Perception
  - Perform
  - Profession
  - Sense Motive
  - Spellcraft
  - Stealth
  - Use Magical Device
skill_ranks_per_level: 4

bab_progression: mid
fort_progression: poor
ref_progression: poor
will_progression: good

initiating_progression: mystic

weapon_proficiencies:
  - Simple
  - Martial
  - katana
  - wakizashi
armor_proficiencies:
  - Light
shield_proficiencies:
  - Shields

class_features:

  - name: maneuvers
    levels: [1]
    text: |
      A mystic begins her career with knowledge of seven martial maneuvers. The disciplines available to her are Elemental Flux, Mithral Current, Riven Hourglass, Shattered Mirror, Solar Wind, and Veiled Moon. The mystic may also exchange access to one of her martial disciplines for the Unquiet Grave discipline. She gains the associated skill of each of her disciplines as a class skill.

      Once the mystic knows a maneuver, she must ready it before she can use it (see Maneuvers Readied, below). A maneuver usable by mystics is considered an extraordinary ability unless otherwise noted in it or its discipline's description. A mystic's maneuvers are not affected by spell resistance, and she does not provoke attacks of opportunity when she initiates one.

      The mystic learns additional maneuvers at higher levels, as indicated on Table: Mystic. A mystic must meet a maneuver's prerequisite to learn it. See the Systems and Use chapter in Path of War for more details on how maneuvers are used.

      Upon reaching 4th level, and at every even numbered initiator level thereafter (6th, 8th, 10th, and so on), the mystic can choose to learn a new maneuver in place of one she already knows. In effect, she loses the old maneuver in exchange for the new one. She can choose a new maneuver of any level she likes, as long as she observes the restriction on the highest-level maneuvers she knows; the mystic need not replace the old maneuver with a maneuver of the same level. She can swap only a single maneuver at any given level. A mystic's initiation modifier is Wisdom.

      *Maneuvers Readied:* A mystic can ready five of her seven maneuvers known at 1st level, and as she advances in level and learns more maneuvers, she is able to ready more, but must still choose which maneuvers to ready. A mystic must always ready her maximum number of maneuvers readied. She readies her maneuvers by meditating for ten minutes. The maneuvers she chooses remain readied until she decides to meditate again and change them. The mystic does not need to sleep or rest for any long period of time in order to ready her maneuvers; any time she spends ten minutes in meditation, she can change her readied maneuvers.

      A mystic begins an encounter with all her readied maneuvers unexpended, regardless of how many times she might have already used them since she chose them. When she initiates a maneuver, she expends it for the current encounter, so each of her readied maneuvers can be used once per encounter (unless she recovers them, as described below).

      Mystics are unique among martial disciples in that they rely on surging, primal arcane forces within their being to fuel their martial maneuvers. Because of this, they do not have full control over their readied maneuvers; when a mystic readies her maneuvers, she selects two of her readied maneuvers to be immediately granted to her for use at any time (when these two maneuvers are used outside of combat, they recover on their own in the following round), with the rest of her initially randomized maneuvers waiting to be granted in combat. The remainder of her readied maneuvers are withheld and currently inaccessible until combat begins. If she is able to act in a surprise round when combat begins, she is granted her maneuvers then as normal, but if she is caught unaware, she must wait until her initiative before her maneuvers are granted (beyond the initial two). At the end of each of her combat turns, one previously withheld maneuver (randomly determined) is granted to her, and thus becomes accessible for her next turn and subsequent turns. She can freely choose to initiate any maneuver that is currently granted when her turn begins, but she cannot initiate a withheld maneuver. If the mystic chooses not to employ a maneuver in a given round, her currently granted maneuvers remain available, and a previously withheld maneuver is granted, as described above. In other words, it doesn't matter if she uses her maneuvers or not---at the end of each of her turns, one withheld maneuver from her selection of readied maneuvers is granted to her. Over the course of a few rounds, all the mystic's maneuvers will eventually be granted.

      A mystic can change the two readied maneuvers she has chosen to be immediately granted for use at any time by spending one minute meditating.

      If, at the end of the mystic's turn, she cannot be granted a maneuver because she has no withheld maneuvers remaining, she recovers all expended maneuvers, and a new group of readied maneuvers is granted to her, replacing her previously granted maneuvers if any remain unspent. She selects two of her choice (and gains the remainder of granted maneuvers as randomized selections, see below). At the end of her next turn, a withheld maneuver is granted to the mystic, and the process of surging power begins again.

      At 3rd level and again at 6th, 9th, 12th, 18th, and 20th levels, the number of maneuvers granted to the mystic at the beginning of an encounter and when she recovers her maneuvers increases by one. Unlike the mystic's initial granted maneuvers, these additional maneuvers are randomly determined (for example, at the beginning of an encounter, a 6th level mystic would choose two maneuvers to have access to, then randomly be granted two more).

      If a mystic uses the Lightning Recovery or Victorious Recovery feat (or a similar method) to recover a maneuver, it is immediately added to her currently granted maneuvers.

      *Stances Known:* A mystic begins her career with knowledge of one stance from any discipline open to mystics. At 2nd, 5th, 9th, 11th, 15th, and 18th levels, she can select an additional stance to learn. Unlike maneuvers, stances are not expended and the mystic does not have to ready them. All the stances she knows are available to her at all times, and she can change the stance she is currently maintaining as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance or discipline description.

      Unlike with maneuvers, a mystic cannot learn a new stance at higher levels in place of one she already knows.

  - name: animus
    type: Su
    levels: [1]
    text: |
      A mystic's martial prowess is in part fueled by a reservoir of roiling, turbulent energy within her soul, and the passion and danger of combat causes this arcane energy to overflow outwards. This power, called animus, waxes and wanes with a mystic's use of her maneuvers in battle. Outside combat, a mystic has no animus to spend, but her inner power can still be used for more subtle arcane arts. Her levels in mystic count as arcane spellcaster levels for the purposes of qualifying for prerequisites (such as those of item creation feats or the Arcane Strike feat), and if a mystic ever develops arcane spellcasting from another class, she may add her mystic level to her levels in that class to determine her overall caster level for the purposes of item creation feats.

      When a mystic enters combat, she gains an animus pool equal to 1 + her mystic initiation modifier (minimum 1) at the start of her first turn, and adds one point of animus to her animus pool at the start of each of her turns thereafter. Her animus pool persists for one minute after the last enemy combatant is defeated or the encounter otherwise ends. At the end of any round in which the mystic initiates a maneuver (a strike, boost, or counter), she adds an additional point of animus to her pool. Certain abilities, such as some class features, maneuvers, and feats, require the mystic to expend points of animus to use.

      The primal power of animus can be used in several ways---the foremost of which is the augmentation of maneuvers. A mystic can spend points of animus to augment her maneuvers in the following ways, depending on her class level. If the mystic has the ability to augment her maneuvers in other ways, such as from another class feature or the maneuver itself, this cannot be combined with the augments granted by her animus class feature; she must choose which augmentation type to use when initiating the maneuver.

      Starting at 1st level, a mystic can spend a single point of animus to augment a maneuver as part of that maneuver's initiation action to apply one of the following effects to it (if applicable):

      - *Enhance Maneuver:* For each point of animus spent, the mystic adds a cumulative +2 insight bonus to all d20 rolls made (including attack rolls, combat maneuver checks, and skill checks) when initiating that maneuver (maximum of three animus may be spent on this augmentation); if the maneuver allows the user to make multiple attacks, then this bonus only applies to the first attack.
      - *Increase DC:* For each point of animus spent, the save DC of that maneuver increases by 1.

        When the mystic reaches 4th level, she can spend up to two points of animus on maneuver augmentations, rather than one, and she gains access to the following additional augmentations:
      - *Anima Burn:* The mystic adds 1/2 her class level to damage rolls made during that maneuver. This augment costs two points of animus, and can only be applied once to a given maneuver.
      - *Increase Potency:* For each point of animus spent, the mystic may ignore 10 points of energy resistance or 5 points of damage reduction.

        When the mystic reaches 9th level, she may now spend up to three points of animus on maneuver augmentations, and gains access to the following additional augmentation:
      - *Animus Rush*: The mystic make move up to her base movement speed as part of the initiation action for the maneuver before initiating the strike. This is a teleportation effect and the mystic must clearly see her destination. This augmentation costs three points of animus.
      - *Increase Range:* The mystic may target a creature within 30 feet with a strike that normally uses a melee attack. Resolve the strike normally, as if the targeted creature was within the mystic's melee reach. This augmentation costs two points of animus.

      At 13th level, a mystic can spend up to four points of animus on maneuver augmentation, and at 19th level, she can spend up to five points of animus per augmentation.

  - name: elemental attunement
    type: Su
    levels: [1]
    text: |
      A mystic contains incredible elemental power within her body, surging energies that constantly flow through her blood and muscle. Bringing these energies to bear is as easy as breathing for a mystic, shifting the flow of power with the subtle movements of her martial stances. When a mystic readies her maneuvers, she may select one of the following elements (and associated energy type) to be her active element: air (electricity), earth (acid), fire (fire), and water (cold).

      After readying maneuvers, a mystic can change her active element by taking a standard action to focus inwards, or by expending one point of animus as a free action while assuming a new stance. Whenever she initiates a maneuver that deals damage, she may spend one point of animus as part of its initiation action to change all damage the maneuver deals to her active element's associated energy type. For example, if a mystic whose active element is currently Air initiated the Cursed Fate Veiled Moon strike, she could spend one point of animus to change her attack's damage (including the strike's bonus damage) to from her weapon's normal damage type to electricity damage.

      If the mystic has access to the Elemental Flux discipline, then her active element from this class feature is the same as her active element for Elemental Flux maneuvers. If she is psionic, she can change her active energy type whenever she changes her active element, and vice versa. Her active energy type need not match her active element.

  - name: blade meditation
    type: Su
    levels: [1]
    text: |
      When a mystic finds that her martial power is beginning to wane or that few options remain available for use, she can pause in battle, drawing on her inner well of animus to reinvigorate her body and mind. As a full-round action, a mystic can spend one point of animus to grant herself all her remaining withheld maneuvers, then immediately expend them in a raging cadence of arcane power. As there are no remaining maneuvers to be granted, a new set of maneuvers is granted to the mystic at the end of her turn, as normal.

      In addition, until the start of her next turn, creatures that target the mystic with melee attacks are engulfed in the explosion of energy, taking 1d6 points of damage of her active element's associated energy type, plus an additional 1d6 points of damage for every two points of animus remaining in the mystic's animus pool.

  - name: bonus feat
    levels: [2, 7, 12, 17]
    text: At 2nd level and every five levels thereafter, a mystic gain a bonus combat or item creation feat. She must meet the prerequisites for these feats as normal.

  - name: arcane defense
    type: Ex
    levels: [2, 6, 11, 16, 20]
    levels_text:
      2:  "+1"
      6:  "+2"
      11: "+3"
      16: "+4"
      20: "+5"
    text: Starting at 2nd level, the sorcerous power within her body makes her resilient to the supernatural. These energies defend her from magical and psionic powers, granting her a +1 insight bonus to her AC and saving throws against psionic powers, psi-like abilities, spells, and spell-like abilities. This bonus increases by +1 at 6th level, and again at 11th level, 16th level, and 20th level.

  - name: elemental glyph
    type: Su
    levels: [3, 8, 13, 19]
    levels_text:
      3: I
      8: II
      13: III
      19: IV
    text: |
      Starting at 3rd level, a mystic learns to aid her friends with the arcane power of the elements. Although at first this surging energy was raw and unformed, she has begun to master this ability, and can use it to empower her allies, granting them benefits in combat. As a move action, the mystic can spend one point of animus to apply an elemental glyph to a number of allies equal to her mystic initiation modifier modifier within her sight. The effect of this glyph depends on the element it is associated with, but all glyphs last for a number of rounds equal to 1 + the mystic's initiation modifier. A mystic is not limited to casting glyphs of her active element (as darkness, illumination, and metal have no elemental type). Allies may only be affected by one of her glyphs at a time, with new glyphs ending the current glyph in effect and replacing it on the affected ally. The benefits of these glyphs are cumulative (for example, an 8th level mystic grants both the 3rd level and 8th level benefits to her allies). Different glyphs from different mystics may apply to the same target. Glyphs are supernatural abilities and not subject to spells or effects like dispel magic but do not function within an antimagic field or similar effect.

      *Air:* The glyph of air fills the mystic's allies with energy and speed.

      - At 3rd level, all movement speeds possessed by each ally under the effect of the glyph gain a +10-foot enhancement bonus to speed. In addition allies may choose to make one turn of up to 90 degrees while making charge attacks.
      - At 8th level, this enhancement bonus to movement speed increases to 30 feet, and they may make Acrobatics checks to jump as if they had a running start.
      - At 13th level, allies affected by the glyph of air gain the ability to move up to 30 feet as a swift action. This movement provokes attacks of opportunity as normal.
      - At 19th level, whenever one of the mystic's allies uses the glyph of air's swift action movement ability, they can make a single attack with a weapon they are wielding at their highest base attack bonus at any point during this movement.

      *Darkness:* Though darkness often connotates evil, for the mystic its shroud offers both protection and insight, allowing the mystic's allies tactical avenues that they would otherwise be unable to access.

      - At 3rd level, allies affected by the glyph of darkness gain concealment (20% miss chance).
      - At 8th level, affected allies gain darkvision and the effects of a see invisibility spell out to a range of 60 feet.
      - At 13th level, affected allies are shrouded in a pitch- black veil, gaining total concealment (50% miss chance).
      - At 19th level, affected allies gain the blindsight trait with a range of 30 feet.

      *Earth:* The dour, steadfast nature of earth allows the mystic's allies to better stand their ground and weather assaults.

      - At 3rd level, this glyph makes allies more difficult to move against their will. Affected allies gain a bonus to their CMD equal to the mystic's Wisdom modifier.
      - At 8th level, affected allies gain DR/adamantine equal to the mystic's Wisdom modifier.
      - At 13th level, affected allies gain resistance to all energy types equal to the mystic's class level.
      - At 19th level, the first time during the encounter that an affected ally is reduced to 0 or fewer hit points, they are instead reduced to 0 hit points and automatically stabilize. Their hit points cannot be reduced below 0 for the rest of the round. Once this effect triggers on an ally, that ally cannot gain its effect again until the end of the encounter. In addition, affected are allies are immune to bleed damage.

      *Fire:* The unquenchable flames of passion drive the mystic's allies to feats of glory.

      - At 3rd level, affected allies gain a circumstance bonus to attack rolls equal to 1/4 the mystic's class level (minimum +1).
      - At 8th level, affected allies add 1/2 the mystic's class level as fire damage to attacks they make.
      - At 13th level, affected allies' attacks ignore a number of points of energy resistance equal to the mystic's class level.
      - At 19th level, whenever an affected ally is targeted by a melee attack, the attacker takes fire damage equal to the mystic's class level, regardless of whether or not the attack hits.

      *Illumination:* The light of the universe reveals truth wherever it hides.

      - At 3rd level, affected allies' attacks ignore the miss chance from concealment granted to targets by anything less than total concealment.
      - At 8th level, affected allies gain a circumstance bonus to Will saving throws against illusion spells and effects equal to the mystic's Wisdom modifier.
      - At 13th level, affected allies gain the effects of a true seeing spell out to a range of 30 feet.
      - At 19th level, affected allies are protected from any falsehood, gaining the effects of a mind blank spell.

      *Metal:* Sturdy and unyielding like the forged iron from which it takes its name, the glyph of metal imparts resolute strength to the mystic's allies.

      - At 3rd level, affected allies increase their natural armor bonus to AC equal to 1⁄4 the mystic's class level (minimum +1).
      - At 8th level, affected allies gain a circumstance bonus to Fortitude saves equal to 1⁄4 the mystic's class level (minimum +1).
      - At 13th level, affected allies' attacks ignore a number of points of damage reduction and hardness equal to the mystic's Wisdom modifier.
      - At 19th level, affected allies gain damage reduction/– equal to the mystic's Wisdom modifier and gain spell resistance equal to 15 + the mystic's class level.

      *Water:* Fluid and changeable, the glyph of water grants allies flexibility in both their movement and their thinking.

      - At 3rd level, affected allies gain a circumstance bonus to their CMB and to Swim checks equal to the mystic's Wisdom modifier.
      - At 8th level, affected allies ignore difficult terrain when they move.
      - At 13th level, affected allies gain the effects of a freedom of movement spell.
      - At 19th level, affected allies gain fast healing of 10 while under the effects of this glyph.

  - name: mystic artifice
    type: Su
    levels: [4]
    text: Starting at 4th level, a mystic is able to channel her animus into her craft, substituting primal arcane energies in place of more ordinary spells. When crafting an item, the mystic uses her initiator level as her caster level to determine how potent a creation she can make. If her initiator level does not equal the minimum caster level to make the item, then she cannot create the item. When attempting to create a magical item for which she does not possess a prerequisite spell, the mystic can attempt to replicate the spell through her innate power with a Spellcraft check (DC 15 + the level of the spell being replicated). If successful, she can create the item as if she had cast the prerequisite spell. The mystic must possess any material components necessary for casting the spell that she is replicating. If the item being created requires multiple spells, she must make this check for each spell she intends to replicate. If she fails the skill check, she may not try again for that spell while creating that item---the item creation DC increases as normal for the creation of an item without a prerequisite spell in such a case.

  - name: withstand spell
    type: Su
    levels: [5]
    text: |
      Starting at 5th level, the mystic's natural instincts with magic work to protect her, guiding her reactions against offensive spells cast by her enemies and allowing her to siphon off a small amount of that energy for her own use. If the mystic is targeted by a spell, spell-like ability, or psionic power that normally would have a lesser effect (such as a partial effect) on a successful Fortitude or Reflex saving throw, she may make a Will saving throw instead of the effect's normal save. If that Will saving throw is successful, she is completely unaffected by the spell or power, taking no damage and suffering no ill-effects. If she fails the saving throw, she suffers the effect as normal, and adds one point of animus to her animus pool.

      The mystic must be unencumbered and wearing light or no armor to use this ability. This ability does not protect the mystic from traps, extraordinary or supernatural abilities, or any other effects that require a Fortitude or Reflex save. A helpless mystic does not gain the benefit of withstand spell.

  - name: instant enlightenment
    type: Ex
    levels: [6, 10, 14, 18]
    levels_text:
      6: 1/day
      10: 2/day
      14: 3/day
      18: 4/day
    text: Starting at 6th level, a mystic is capable of drawing deep on her training to channel the untapped energies within her, granting her an infinitesimal moment perfect clarity. Once per day as a free action, the mystic may expend one granted maneuver and instantly replace it with another maneuver she knows. This maneuver is added to her currently granted maneuvers and readied for use, replacing the previous maneuver. At 10th level and every four levels thereafter, the mystic can use this ability one additional time per day.

  - name: quell magic
    type: Su
    levels: [9]
    text: Starting at 9th level, a mystic can channel her animus to act as a sort of null-magic energy, smothering active magical effects with its flow. In order to use this ability, the mystic must have identified an ongoing spell or power through a Spellcraft check or other method. As a standard action, she can spend a number of points of animus equal to that spell or power's level to suppress (as if by an antimagic field spell) that spell or power for a number of rounds equal to her Wisdom modifier. Time spent suppressed counts against the suppressed spell or power's duration. This ability can only be used on effects within 30 feet, although the mystic does not need to identify the effect while it is within that range, and it remains suppressed even if it leaves that range.

  - name: font of animus
    type: Su
    levels: [15]
    text: At 15th level, a mystic gains the ability to draw in energy from the world around her, converting it into animus to fuel her own primal power. As a move action, the mystic can add a number of points of animus to her animus pool equal to 1d6 + her Wisdom modifier. Unlike other animus abilities, this may be used outside of combat to generate a small pool of animus that persists for one minute outside of combat. A mystic cannot use this ability multiple times to accumulate animus, additional attempts simply reset the amount of animus from the previous use of this ability. The mystic may use this a number of times per day equal to her Wisdom modifier + 1 (minimum of 1).

  - name: glyph mastery
    type: Su
    levels: [20]
    text: At 20th level, a mystic's control over her elemental powers are strong enough that she can manifest two elemental glyphs at the same time. As a move action, the mystic may spend two points of animus and manifest an elemental glyph of any two elements, regardless of her active element.
---

Born with an untamed magical power buried deep within his soul, the mystic is a warrior who, much like a sorcerer, is filled with untapped energies. This power however, is too primal and unstable, and is difficult to be formed effectively into a spell. By following a martial medium to tame this energy, the mystic is able to shape his wild power into martial maneuvers and this allows him to discover the deeper mysteries of his own inborn power.

**Adventures:** Most mystics adventure to stretch the limits of their powers, learning to master the mysteries within their souls. Some do it to express their power in ways that suit their ethics, for good or for ill, and others travel to find others like themselves, to study and train with and hope to eventually learn more about why they are the way they are.

**Characteristics:** Mystics tend to be a very introspective lot, wielding a power so foreign to most with an intuitive sense of understanding. Many mystics follow ascetic lifestyles, hoping that the order and abstaining of life's vices will help them control their power. Others embrace their wild energies and move with the moment, pausing to reflect at the end of the day as to what drives their motivations.

**Alignment:** Any. Mystics do not follow any ethical or moral path, and choose their own destiny. Some cling to lawful alignments to master their powers, and others embrace chaotic alignments to freely express their talents.

**Religion:** Mystics who follow religion often find their faith with gods of battle, nature, magic, or freedom.

**Background:** Mystics universally have one thing in common, and that's a magical creature or magic-using being in their near family history. This power is an inherited consequence of such relation, and while it is not widely understood why it has chosen to manifest in such a way, the mystic's wild power is usually an expression of this relation's own power. Mystics are born, and must train to master their energies.

**Races:** Any member of any race could be a mystic, provided they had the ancestry and proper training available. Most commonly they are of the human, elven, and gnome races. Among monster races, kobolds and their draconic bloodlines are among the first and foremost experts in the realm of mysticism, and many fey or elemental blooded creatures as well.

**Other Classes:** Mystics tend to chafe with sorcerers around, as they see each other as failed expressions of the other. Otherwise, mystics find the most in common with rangers and monks for either their freedom or their discipline. Wizards find them interesting and enjoy studying their powers, and martially inclined characters find them to be steady and useful allies.

**Role:** A mystic will often find themselves in the role of both striker and party supporter. The glyphs they manifest will aid themselves and their allies, as their animus builds power and strength. Not as hardy as other warriors, however, mystics will find themselves needing the protection of their more robust allies from time to time.

## Keeping Track of it All

To help with maneuvers and randomization, the authors of the Mystic suggest you write the maneuvers down on 3x5 note cards found at any office supply or big box store, then shuffle them together for easy randomization of maneuvers. Simply lay down your two chosen granted maneuvers, shuffle the rest, flip the rest of your granted maneuvers where applicable, and the rest are flipped into granted status on a one per round basis until all are granted to you. The following round, reset the process and start from step one! For online play, there are many different apps or websites that can assist with this randomization process for the same effect.

To maintain an easy way to calculate an animus pool, keep a spare d12 or d20 handy to designate as your animus die, or a small cup with beads that you can add or subtract from.
