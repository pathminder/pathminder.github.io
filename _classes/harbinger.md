---
title: Harbinger
sources:
  - "Path of War: Expanded"

max_level: 20
starting_age: Intuitive
starting_wealth: 4d6 × 10 gp (average 140 gp)
hit_die: 8
class_skills:
  - Acrobatics
  - Bluff
  - Climb
  - Craft
  - Diplomacy
  - Fly
  - Heal
  - Intimidate
  - Knowledge (arcana)
  - Knowledge (local)
  - Knowledge (martial)
  - Knowledge (nobility)
  - Knowledge (religion)
  - Linguistics
  - Profession
  - Sense Motive
  - Spellcraft
  - Stealth
  - Survival
skill_ranks_per_level: 4

bab_progression: mid
fort_progression: good
ref_progression: poor
will_progression: good

initiating_progression: full

weapon_proficiencies:
  - Simple
  - Martial Melee
armor_proficiencies:
  - Light
shield_proficiencies:
  - Shields

class_features:
  - name: maneuvers
    levels: [1]
    text: |
      A harbinger begins her career with knowledge of five martial maneuvers. The disciplines available to her are Cursed Razor, Riven Hourglass, Scarlet Throne, Shattered Mirror, and Veiled Moon.

      Once the harbinger knows a maneuver, she must ready it before she can use it (see Maneuvers Readied, below). A maneuver usable by harbingers is considered an extraordinary ability unless otherwise noted in it or its discipline's description. A harbinger's maneuvers are not affected by spell resistance, and she does not provoke attacks of opportunity when she initiates one.

      The harbinger learns additional maneuvers at higher levels, as indicated on Table: Harbinger. A harbinger must meet a maneuver's prerequisite to learn it. See the Systems and Use chapter in Path of War for more details on how maneuvers are used.

      Upon reaching 4th level, and at every even numbered initiator level thereafter (6th, 8th, 10th, and so on), the harbinger can choose to learn a new maneuver in place of one she already knows. In effect, she loses the old maneuver in exchange for the new one. She can choose a new maneuver of any level she likes, as long as she observes the restriction on the highest-level maneuvers she knows; the harbinger need not replace the old maneuver with a maneuver of the same level. She can swap only a single maneuver at any given level. A harbinger's initiation modifier is Intelligence.

      **Maneuvers Readied:** A harbinger can ready three of her five maneuvers known at 1st level, and as she advances in level and learns more maneuvers, she is able to ready more, but must still choose which maneuvers to ready. A harbinger must always ready her maximum number of maneuvers readied. She readies her maneuvers by meditating over the nature of malevolence, honing her killer instinct, dwelling upon grief and sorrow, or otherwise communing with her negative side for ten minutes. The maneuvers she chooses remain readied until she decides to meditate again and change them. The harbinger does not need to sleep or rest for any long period of time in order to ready her maneuvers; any time she spends ten minutes in communion with her darker urges, she can change her readied maneuvers.

      A harbinger begins an encounter with all her readied maneuvers unexpended, regardless of how many times she might have already used them since she chose them. When she initiates a maneuver, she expends it for the current encounter, so each of her readied maneuvers can be used once per encounter (unless she recovers them, as described below).

      In order for the harbinger to recover maneuvers, she must tap into her sorcerous malice by activating her dark claim class feature; the harbinger recovers a single expended maneuver whenever she Claims a creature, and she recovers a number of expended maneuvers equal to her harbinger initiation modifier (minimum 2) whenever a creature she has Claimed is reduced to 0 or less hit points. Alternately, the harbinger may concentrate on her inner negativity and recover a single maneuver as a standard action.

      **Stances Known:** A harbinger begins her career with knowledge of one stance from any discipline open to harbingers. At 2nd, 5th, 9th, 11th, 15th, and 18th levels, she can select an additional stance to learn. Unlike maneuvers, stances are not expended and the harbinger does not have to ready them. All the stances she knows are available to her at all times, and she can change the stance she is currently maintaining as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance or discipline description.

      Unlike with maneuvers, a harbinger cannot learn a new stance at higher levels in place of one she already knows.

  - name: dark claim
    type: Su
    levels: [1]
    text: |
      Starting at 1st level, a harbinger gains the ability to reach out with her sorcerous malice, marking foes as her own. As a swift action, the harbinger may Claim an opponent that she can see (including with special senses such as blindsense or tremorsense) within close range (25 feet + 5 feet per 2 harbinger levels) for a number of rounds equal to 1/2 her class level (minimum 1 round). A harbinger can have a maximum number of creatures Claimed equal to her harbinger initiation modifier (minimum 1), and may not Claim a creature she has already Claimed until or unless the Claim expires. Claimed creatures using the Withdraw action to leave a square threatened by the harbinger provoke attacks of opportunity from her.

      In addition, the harbinger automatically knows the position of creatures she has Claimed. Any opponent the harbinger cannot see still has total concealment (50% miss chance) against her, and the harbinger still suffers the normal miss chance when attacking creatures that have concealment. The harbinger is still denied her Dexterity bonus to her AC against attacks from Claimed creatures she cannot see.

  - name: accursed will
    type: Ex
    levels: [1, 10]
    levels_text:
      1: half
      2: full      
    text: A harbinger is not an entirely physical being; the darkness within her supplements her body, impelling her to acts of stunning violence. Starting at 1st level, the harbinger gains an insight bonus on attack rolls equal to 1/2 her harbinger initiation modifier (minimum +1). At 10th level, she gains an insight bonus on damage rolls equal to her harbinger initiation modifier.

  - name: ill tidings
    type: Ex
    levels: [1, 10]
    levels_text:
      1: +10
      10: +20
    text: Like unwanted news, the harbinger travels swiftly. At 1st level, a harbinger gains a +10-foot competence bonus to her movement speeds. At 10th level, this bonus increases by +10 feet. Apply this bonus before modifying the harbinger's movement speeds because of any load carried or armor worn.

  - name: dark focus
    type: Ex
    levels: [2, 5, 6, 10, 14, 20]
    levels_text:
      2: +1, 1 discipline, bonus feat
      5: +2
      10: +3, 2 disciplines
      14: adaptation
      15: +4
      20: +5, supremacy
    text: |
      Though all Harbingers tap into violence and sorrow, they inevitably specialize in a method of combat that calls to them deep within themselves. At 2nd level, a harbinger selects one discipline she has access to from her harbinger levels to be her dark focus. She gains a +1 insight to attack and damage rolls when initiating strikes and counters from her dark focus discipline. The bonus to attack and damage rolls increases by +1 at 5th level and every four levels thereafter. In addition, she gains a +1 insight bonus to the save DCs of maneuvers from her dark focus discipline.

      At 6th level, the harbinger gains either Advanced Study or Discipline Focus in her dark focus discipline as a bonus feat, even if she does not meet the prerequisites. In the case of Advanced Study, both maneuvers selected must be from her dark focus discipline.

      At 10th level, the harbinger selects a second discipline as her dark focus in addition to her original dark focus discipline. She does not gain an additional bonus feat, although the other bonuses from her dark focus class feature apply to the second discipline as well.

      At 14th level, the harbinger's dedication bears violent fruit. She may expend a readied maneuver to spontaneously initiate any maneuver she knows from her dark focus disciplines that is one or more levels lower than the expended maneuver, regardless of whether or not she has the dark focus maneuver readied. The initiation action of the spontaneously initiated maneuver is unchanged.

      At 20th level, the harbinger treats all maneuvers from her dark focus disciplines as being readied at the beginning of each encounter, in addition to her normal pool of readied maneuvers.

  - name: grim news
    type: Su
    levels: [3, 9, 15]
    levels_text:
      3: 1/encounter
      9: 2/encounter, 1 movement mode
      15: 3/encounter, 2 movement modes
    text: |
      Like a ghost or a rumor, the harbinger moves with supernatural acumen. Starting at 3rd level, a harbinger can move up to her speed as a swift action once per encounter. She can use this ability twice per encounter at 9th level, and three times per encounter at 15th level.

      At 9th level and again at 15th level, the harbinger selects one of the following abilities. One made, her choice is permanent and cannot be changed.

      - *Dark Wings:* The harbinger gains a fly speed equal to her base land speed, with good maneuverability. This flight is supernatural in nature; though the harbinger may develop wings or another form of evident propulsion, she flies through supernatural acumen alone.
      - *Omenwalk:* The harbinger gains the ability to teleport up to her speed as a move action. The harbinger does not need line of effect or line of sight to her destination, although she still provokes attacks of opportunity for leaving a threatened square when using this ability.
      - *Spider's Boon:* The harbinger gains a climb speed equal to her base land speed. In addition, she develops a sticky grip that aids her in battle, granting her a +4 racial bonus on grapple checks and to her CMD.
      - *Water Dweller:* The harbinger gains a swim speed equal to her base land speed. In addition, the harbinger no longer needs to breathe and becomes immune to inhaled poisons.

  - name: massacre
    type: Ex
    levels: [4, 10, 16]
    levels_text:
      4: 1/encounter
      10: 2/encounter
      16: 3/encounter
    text: The scent of blood in the air and the gentle throb of fading life force impels the Harbinger to further heights of violence. Starting at 4th level, a harbinger can initiate one of her readied strikes against an adjacent creature as an immediate action when she reduces an opponent to 0 or fewer hit points. She can only initiate strikes with an initiation action of one standard action with this ability. The harbinger can use this ability once per encounter at 4th level, twice per encounter at 10th level, and three times per encounter at 16th level.

  - name: elusive shadow
    type: Ex
    levels: [5]
    text: The harbinger's unnatural alacrity protects her from harm as she shies away from whirling blades and streaking spells alike. Starting at 5th level, a harbinger gains a +2 dodge bonus to her AC and Reflex saves during any round in which she has moved at least 10 feet (including by teleportation effects such as omenwalk).

  - name: sorcerous deception
    type: Sp
    levels: [7]
    text: Having become adept at concealing the malice within, the harbinger develops the ability to allay the suspicions of those who investigate her with magic. At 7th level, a harbinger can use *magic aura* as a spell-like ability at will, with a caster level equal to her harbinger level. She may only target items and objects she is attending, carrying, wearing, or wielding.

  - name: ill intentions
    type: Su
    levels: [8]
    text: Those cornered by the harbinger and her allies feel the weight of her malice pressing down against them. Starting at 8th level, whenever a harbinger and one or more of her allies flank a creature, that creature suffers a –2 penalty on saving throws and skill checks.

  - name: black omen
    type: Su
    levels: [11]
    text: Like misfortune, the harbinger does not seem to move so much as simply arrive. Starting at 11th level, a harbinger may move up to half her speed as an immediate action once per encounter.

  - name: bleak prophecy
    type: Su
    levels: [12]
    text: Those claimed by the harbinger are filled with dreadful visions of their own demise. Starting at 12th level, creatures Claimed by a harbinger become shaken while the Claim persists.

  - name: dark murmur
    type: Su
    levels: [13]
    text: Those claimed by the harbinger find her as hard to catch as rumor itself. Starting at 13th level, the harbinger's movement no longer provokes attacks of opportunity from creatures she has Claimed.

  - name: rumors of war
    type: Ex
    levels: [17]
    text: The harbinger sweeps through her enemies, spreading pain and woe wherever she steps. Starting at 17th level, a harbinger may move up to her speed and initiate a single strike at any point in the movement as a full-round action.

  - name: voices in the dark
    type: Ex
    levels: [18]
    text: Like a dark voice on the edge of hearing, the harbinger persecutes her enemies. Starting at 18th level, a harbinger can initiate a strike whenever she would normally be able to make an attack of opportunity (she still expends the attack of opportunity). She can only initiate strikes with an initiation action of one standard action with this ability.

  - name: whispers of atrocity
    type: Su
    levels: [19]
    text: There is no resisting the harbinger's malice. Starting at 19th level, maneuvers initiated by a harbinger ignore all immunities possessed by their targets.
---

Like rumors of war or plague-ridden winds, harbingers move through battlefields and leave only ruin and sorrow in their wake. empowered from within by a deep connection to sorrow, grief, and wrath, harbingers channel their negative emotions into a supernatural fighting style that is strange and terrifying to behold. Some accept the darker urges within themselves but leash them, making their wrath serve as a hound might---and others embrace the violence within, becoming killers without restraint or pity.

**Adventures:** Harbingers adventure for many and sundry reasons, ranging from simple greed to revenge to genuine altruism. Many harbingers learn their trade from a mentor or master who sometimes imparts a mission or task to them, or initiates them into an organization that retains the harbinger as its agent. Harbingers aren't any less likely to take to the adventuring life out of friendship than anyone else and may be found in the company of mercenaries they've grown to love, or at least no longer feel like they can live without.

**Characteristics:** Regardless of their alignment, religion, culture of origin, or beliefs, all harbingers have one thing in common: violence. For some anger and sorrow are tools they use to do their jobs, an acknowledgement that all sapients have both good and evil within. For others violence marks and defines their lives, with angry scars and psychological wounds. Some crumble before the anger within, becoming little more than puppets for their hate, and others refuse to give in and display a level of self-control that can only be called saintlike. However, all harbingers live their lives coming to---or failing to come to---terms with the darkness within.

**Alignment:** Any. Though harbingers are marked by their darker urges they are not utterly defined by them, and many brave and noble souls succeed in staring into the abyss until the abyss averts its gaze. It is true that many Harbingers skew towards evil and/or chaos, but nothing stops a harbinger from turning their power to altruistic ends.

**Religion:** Harbingers tend to be on one side or the other of the line between piety and indifference when it comes to religion. Many harbingers that have been scarred by violence or evil shy away from faith, unable to believe that higher powers truly influence their lives. Others embrace gods of violence, vengeance, tyranny or destruction out of a feeling of common sympathy or even obligation. Good-aligned harbingers tend to worship gods of justice or retribution, taking on the role of those who dispense justice to the wicked, or to gravitate towards gods they seek to emulate---gods of peace, love, or beauty that remind the harbingers of the things they choose to defend.

**Background:** At some point in their lives, all harbingers encountered the violence within. Some come from cursed or tainted backgrounds, dragged towards power by fiendish blood or maledictions laid down upon their ancestors. Others have inherent but untapped magical potential that erupts in a moment of wrath or panic, and many harbingers have started on their path with blood dripping from their fingers and a look of shocked panic on their face. Harbingers tend to be from places marked or scarred by strife, and the majority emerge from lands wracked by civil war, military conflict, massive social change, crushing poverty or endemic crime, though this may be because the circumstances that awaken their power are so much more common in such places.

It is possible to deliberately train an harbinger, though magical potential must be present. Such master-student relationships are less common than 'wild' harbingers but can often end up with an harbinger that understands her own power much better. Some teachers use cruel and sadistic training methods to force their student to confront the anger inside of them, while others ask that their pupils meditate on the nature of evil and its role in the multiverse. Both approaches are effective, and produce very different students.

**Races:** Any race capable of feeling anger, sorrow, or grief can potentially become an harbinger. That said, some are certainly more common than others. Savage humanoids such as orcs and gnolls produce a large number of harbingers; their day-to-day lives are marked with violence and maliciousness. Humans and part-humans (but especially tieflings) also make up a large part of harbinger membership, both because of the significant role negative emotions play in their lives and the endemic poverty and crime rates found in their cities. In contrast, races with gentle day-to-day lives such as elves or dwarves produce harbingers more rarely, and even then usually as part of a master-student relationship.

**Other Classes:** Harbingers can often have difficulty around divinely empowered classes such as clerics and paladins, most often because of the ultimate source of their power. Paladins in particular tend to disapprove of harbingers utilizing evil urges, even for good ends, and the conflicts between the two can run long and deep.

**Role:** Control. Harbingers command the battlefield with a combination of superior mobility and debilitating strikes, determining when and how they want to engage and targeting weak enemies while shutting stronger ones out of the battle. Their spread of supernatural maneuvers gives harbingers access to magical and unusual abilities that can shift the tide of battle in their favor.
