---
title: Bard (Rubato)
sources:
  - Pathfinder Roleplaying Game Core Rulebook

tags:
  - Base
  - Initiator

max_level: 20
hit_die: 8

class_skills:
  - Acrobatics
  - Appraise
  - Bluff
  - Climb
  - Craft
  - Diplomacy
  - Disguise
  - Escape Artist
  - Intimidate
  - Knowledge
  - Linguistics
  - Perception
  - Perform
  - Profession
  - Sense Motive
  - Sleight of Hand
  - Spellcraft
  - Stealth
  - Use Magic Device
skill_ranks_per_level: 6

bab_progression: mid
fort_progression: poor
ref_progression: good
will_progression: good

initiating_progression: half

weapon_proficiencies:
  - Simple
  - longsword
  - rapier
  - sap
  - shortsword
  - shortbow
  - whip
armor_proficiencies:
  - Light
shield_proficiencies:
  - Shields

class_features:

  - name: maneuvers
    levels: [1]
    text: |
      A rubato begins his career with knowledge of three martial maneuvers. The disciplines available to him are Elemental Flux, Golden Lion, and Mithral Current.

      Once the rubato knows a maneuver, he must ready it before he can use it (see Maneuvers Readied, below). A maneuver usable by rubati is considered an extraordinary ability unless otherwise noted in it or its discipline's description. A rubato's maneuvers are not affected by spell resistance, and he does not provoke attacks of opportunity when he initiates one.

      The rubato learns additional maneuvers at higher levels, as indicated on Table: The Bard. The maximum level of maneuvers gained through rubato levels is limited by those listed in that table as well, although this restriction does not apply to maneuvers added to his maneuvers known through other methods, such as prestige classes or the Advanced Study feat. A rubato must meet a maneuver's prerequisite to learn it. See the Systems and Use chapter in Path of War for more details on how maneuvers are used.

      Upon reaching 4th level, and at every even numbered initiator level thereafter (6th, 8th, 10th, and so on), the rubato can choose to learn a new maneuver in place of one he already knows. In effect, he loses the old maneuver in exchange for the new one. He can choose a new maneuver of any level he likes, as long as he observes the restriction on the highest-level maneuvers he knows; the rubato need not replace the old maneuver with a maneuver of the same level. He can swap only a single maneuver at any given level. A rubato's initiation modifier is Charisma, and each rubato level is counted as a full initiator level.

      *Maneuvers Readied:* A rubato can ready all three of his maneuvers known at 1st level, and as he advances in level and learns more maneuvers, he is able to ready more, but must still choose which maneuvers to ready. A rubato must always ready his maximum number of maneuvers readied. He readies his maneuvers by practicing weapon drills or communing with the primal rhythm for ten minutes. The maneuvers he chooses remain readied until he decides to practice again and change them. The rubato does not need to sleep or rest for any long period of time in order to ready his maneuvers; any time he spends ten minutes practicing, he can change his readied maneuvers.

      A rubato begins an encounter with all his readied maneuvers unexpended, regardless of how many times he might have already used them since he chose them. When he initiates a maneuver, he expends it for the current encounter, so each of his readied maneuvers can be used once per encounter (unless he recovers them, as described below).

      In order for the rubato to recover maneuvers, he must expend tempo. A rubato can recover a single expended maneuver as a swift action by spending 2 points of tempo, or as a free action by spending 3 points of tempo. A rubato may not recover a maneuver by spending tempo in the same round that he initiated it, though he might be able to recover it in another way.

      *Stances Known:* A rubato begins his career with knowledge of one stance from any discipline open to rubati. At 4th, 7th, 11th, and 13th levels, he can select an additional stance to learn. The maximum level of stances gained through rubato levels is limited by those listed in Table: The Bard. Unlike maneuvers, stances are not expended and the rubato does not have to ready them. All the stances he knows are available to his at all times, and he can change the stance he is currently maintaining as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance or discipline description.

      Unlike with maneuvers, a rubato cannot learn a new stance at higher levels in place of one he already knows.

  - name: bardic knowledge
    type: Ex
    levels: [1, 4, 6, 8, 10, 12, 14, 16, 18, 20]
    levels_text:
      1:  "+1"
      4:  "+2"
      6:  "+3"
      8:  "+4"
      10: "+5"
      12: "+6"
      14: "+7"
      16: "+8"
      18: "+9"
      20: "+10"
    text: A bard adds half his class level (minimum 1) to all Knowledge skill checks and may make all Knowledge skill checks untrained.

  - name: bardic performance
    levels: [1, 3, 5, 6, 7, 13]
    levels_text:
      7: move action
      13: swift action
    text: |
      A bard is trained to use the Perform skill to create magical effects on those around him, including himself if desired. He can use this ability for a number of rounds per day equal to 4 + his Charisma modifier. At each level after 1st a bard can use bardic performance for 2 additional rounds per day. Each round, the bard can produce any one of the types of bardic performance that he has mastered, as indicated by his level.

      Starting a bardic performance is a standard action, but it can be maintained each round as a free action. Changing a bardic performance from one effect to another requires the bard to stop the previous performance and start a new one as a standard action. A bardic performance cannot be disrupted, but it ends immediately if the bard is killed, paralyzed, stunned, knocked unconscious, or otherwise prevented from taking a free action to maintain it each round. A bard cannot have more than one bardic performance in effect at one time.

      At 7th level, a bard can start a bardic performance as a move action instead of a standard action. At 13th level, a bard can start a bardic performance as a swift action.

      Once per round as a free action, a rubato can expend one round of his bardic performance to add 2 points of tempo to his tempo pool. Alternatively, he can spend 2 points of tempo to regain one round of his bardic performance. He may only use one of these abilities in a given round. In addition, a rubato can start a bardic performance in the same action as initiating a strike by spending one additional round of his bardic performance ability.

      Each bardic performance has audible components, visual components, or both.

      If a bardic performance has audible components, the targets must be able to hear the bard for the performance to have any effect, and many such performances are language dependent (as noted in the description). A deaf bard has a 20% chance to fail when attempting to use a bardic performance with an audible component. If he fails this check, the attempt still counts against his daily limit. Deaf creatures are immune to bardic performances with audible components.

      If a bardic performance has a visual component, the targets must have line of sight to the bard for the performance to have any effect. A blind bard has a 50% chance to fail when attempting to use a bardic performance with a visual component. If he fails this check, the attempt still counts against his daily limit. Blind creatures are immune to bardic performances with visual components.

  - name: counterpoint
    type: Ex
    levels: [1, 4, 6, 8, 10, 12, 14, 16, 18, 20]
    levels_text:
      1:  "+1"
      4:  "+2"
      6:  "+3"
      8:  "+4"
      10: "+5"
      12: "+6"
      14: "+7"
      16: "+8"
      18: "+9"
      20: "+10"
    text: |
      *This is a bardic performance ability.* At 1st level, a rubato learns how to lead his allies in a defensive rhythm. An ally must be able to perceive the rubato's performance to be affected. Affected allies gain a bonus equal to 1/2 the rubato's class level (minimum one) on all non-damage rolls made as part of initiating counters.

  - name: metronome
    type: Ex
    levels: [1, 5, 10, 15, 20]
    levels_text:
      1: 1 tempo
      5: 2 tempo
      10: 3 tempo
      15: 4 tempo
      20: 5 tempo
    text: |
      *This is a bardic performance ability.* At 1st level, a rubato learns how to create a stronger, faster connection to the Primal Song. While maintaining this performance, he adds one point of tempo to his tempo pool at the beginning of each of his turns. At 5th level and every five levels thereafter, the amount of tempo gained by this ability increases by 1.

  - name: dissonance
    type: Ex
    levels: [1, 5, 10, 15, 20]
    levels_text:
      1:  --1
      5:  --2
      10: --3
      15: --4
      20: --5
    text: |
      *This is a bardic performance ability.* At 1st level, a rubato learns how to create a subtly hypnotic, discordant performance that jars his enemies and disturbs their patterns. Enemies within 30 feet that can perceive the rubato's performance must succeed at a Will save (DC 10 + 1/2 the rubato's class level + his rubato initiation modifier) or take a --1 penalty on all non-damage rolls made as part of their attacks or strikes while the rubato maintains this performance. A creature that successfully saves cannot be affected by the same rubato's dissonance performance until the end of the encounter. This penalty increases by --1 at 5th level and every five levels thereafter.

  - name: inspire courage
    type: Su
    levels: [1, 5, 11, 17]
    levels_text:
      1:  "+1"
      5:  "+2"
      11: "+3"
      17: "+4"
    text: |
      *This is a bardic performance ability.* A 1st level bard can use his performance to inspire courage in his allies (including himself), bolstering them against fear and improving their combat abilities. To be affected, an ally must be able to perceive the bard's performance. An affected ally receives a +1 morale bonus on saving throws against charm and fear effects and a +1 competence bonus on attack and weapon damage rolls. At 5th level, and every six bard levels thereafter, this bonus increases by +1, to a maximum of +4 at 17th level. Inspire courage is a mind-affecting ability. inspire courage can use audible or visual components. The bard must choose which component to use when starting his performance.

  - name: inspire competence
    type: Su
    levels: [3, 7, 11, 15, 19]
    levels_text:
      3:  "+1"
      7:  "+2"
      11: "+3"
      15: "+4"
      19: "+5"
    text: |
      *This is a bardic performance ability.* A bard of 3rd level or higher can use his performance to help an ally succeed at a task. The ally must be within 30 feet and able to see and hear the bard. The ally gets a +2 competence bonus on skill checks with a particular skill as long as she continues to hear the bard's performance. This bonus increases by +1 for every four levels the bard has attained beyond 3rd (+3 at 7th, +4 at 11th, +5 at 15th, and +6 at 19th).

      Certain uses of this ability are infeasible, such as stealth, and may be disallowed at the GM's discretion. A bard can't inspire competence in himself. inspire competence relies on audible components.

  - name: fortissimo
    type: Su
    levels: [6]
    text: |
      *This is a bardic performance ability.* At 6th level, a rubato learns to empower his maneuvers with tempo. Unlike other bardic performances, he may activate this performance while maintaining another performance. When the rubato initiates a strike with an initiation action of 1 standard action, he can expend 3 rounds of bardic performance and 2 points of tempo to increase the damage (including ability damage, if appropriate) dealt by that strike by 50%. He can activate this performance after rolling his attack roll and determining if it hit or missed, but must activate it before damage is rolled. The rubato must wait 3 rounds after performing a fortissimo before he may perform it again.

  - name: canon
    type: Su
    levels: [8]
    text: |
      *This is a bardic performance ability.* At 8th level, a rubato learns to lead his allies in a martial rhythm. An ally must be able to perceive the rubato's performance to be affected. Whenever an affected ally initiates a maneuver, they can recover an expended maneuver of different type (for example, an ally that initiates a strike may recover a boost or a counter). Each affected ally may only recover up to one maneuver per round in this fashion.

  - name: accelerando
    type: Su
    levels: [9]
    text: |
      *This is a bardic performance ability.* At 9th level, a rubato learns to charge his allies with his tempo, infusing them with the Primal Song. An ally must be able to perceive the rubato's performance to be affected. Affected allies gain the benefits of a *haste* spell as if cast by a bard of the rubato's class level. Starting and maintaining this performance costs two performance rounds for each round the rubato performs, rather than one.

  - name: soothing performance
    type: Su
    levels: [12]
    text: |
      *This is a bardic performance ability.* A bard of 12th level or higher can use his performance to create an effect equivalent to the *mass cure serious wounds*, using the bard's level as the caster level. In addition, this performance removes the fatigued, sickened, and shaken condition from all those affected. Using this ability requires 4 continuous performance, and the targets must be able to see and hear the bard throughout the performance. Soothing performance relies on audible and visual components.

  - name: crescendo
    type: Su
    levels: [14]
    text: |
      *This is a bardic performance ability.* At 14th level, a rubato can maximize his strikes with tempo, smiting his enemies with the triumphant rise of the Primal Song. Unlike other bardic performances, he may activate this performance while maintaining another performance. When the rubato initiates a strike with an initiation action of 1 standard action, he can expend 4 rounds of bardic performance and 4 points of tempo to maximize the damage (including ability damage, if appropriate) dealt by that strike. Treat all damage dice rolled as part of the strike as though they had achieved the maximum result. This does not affect any other part of the strike, such as attack rolls or rolls to determine the duration of its effects.

  - name: harmonize
    type: Su
    levels: [15]
    text: |
      *This is a bardic performance ability.* At 15th level, a rubato learns to harmonize his allies' movements with the rhythm of the Primal Song. Unlike other bardic performances, this performance costs 2 tempo per round to maintain rather than costing bardic performance rounds. An ally must be able to perceive the rubato's performance to be affected. Affected allies gain an insight bonus equal to the rubato's initiation modifier to their AC, on saving throws, and on skill checks made as part of initiating maneuvers. This bonus increases by +2 during any round in which the rubato recovers one or more maneuvers.

  - name: con moto
    type: Su
    levels: [18]
    text: |
      *This is a bardic performance ability.* At 18th level, a rubato gains the ability to enhance the maneuvers of his allies with his tempo. An ally must be able to perceive the rubato's performance to be affected. Whenever an affected ally initiates a maneuver, the rubato can spend 2 tempo as a free action, even if it isn't his turn. If he does, that ally may move up to 15 feet as part of the maneuver (resolve this movement either immediately before, or immediately after initiating the maneuver) or if the maneuver already involves movement, they may increase the distance moved by 15 feet. This movement provokes attacks of opportunity as normal, unless another ability would prevent such attacks. In addition, the save DC of that ally's maneuver (if any) increases by 2.

  - name: fugue
    type: Ex
    levels: [20]
    text: |
     At 20th level, the rubato learns to maintain two bardic performances at the same time. He can activate two bardic performances with the same action, paying any associated costs for each separately. Performances noted as being able to be used while maintaining other performances (such as fortissimo) do not count against this limit.

  - name: tempo
    type: Su
    levels: [1]
    text: As the rubato fights and draws on the Primal Song, he builds a supernatural energy known as tempo. Outside combat, a rubato has no tempo to spend. When a rubato enters combat, he gains a tempo pool equal to 1/2 his class level (minimum 1) + his rubato initiation modifier at the start of his first turn, and adds one point of tempo to his tempo pool at the start of each of his turns thereafter. His tempo pool persists for one minute after the last enemy combatant is defeated or the encounter otherwise ends. The rubato may not gain tempo out of combat, even if another ability would normally permit him to. A rubato can spend tempo as if it were animus when augmenting maneuvers from the Elemental Flux discipline.

  - name: martial performer
    type: Ex
    levels: [2]
    text: Starting at 2nd level, a rubato can make Perform checks in place of checks with his disciplines' associated skills. He may only substitute Perform checks for skills associated with disciplines he has access to from his rubato levels (including disciplines acquired through traits or martial traditions).

  - name: well-versed
    type: Ex
    levels: [2]
    text: At 2nd level, the bard becomes resistant to the bardic performance of others, and to sonic effects in general. The bard gains a +4 bonus on saving throws made against bardic performance, sonic, and language-dependent effects.

  - name: lore master
    type: Ex
    levels: [5, 11, 17]
    levels_text:
      5: 1/day
      11: 2/day
      17: 3/day
    text: At 5th level, the bard becomes a master of lore and can take 10 on any Knowledge skill check that he has ranks in. A bard can choose not to take 10 and can instead roll normally. In addition, once per day, the bard can take 20 on any Knowledge skill check as a standard action. He can use this ability one additional time per day for every six levels he possesses beyond 5th, to a maximum of three times per day at 17th level.

  - name: jack of all trades
    type: Ex
    levels: [10, 16, 19]
    levels_text:
      10: untrained
      16: class skills
      19: take 10
    text: At 10th level, the bard can use any skill, even if the skill normally requires him to be trained. At 16th level, the bard considers all skills to be class skills. At 19th level, the bard can take 10 on any skill check, even if it is not normally allowed.

---

Untold wonders and secrets exist for those skillful enough to discover them. Through cleverness, talent, and magic, these cunning few unravel the wiles of the world, becoming adept in the arts of persuasion, manipulation, and inspiration. Typically masters of one or many forms of artistry, bards possess an uncanny ability to know more than they should and use what they learn to keep themselves and their allies ever one step ahead of danger. Bards are quick-witted and captivating, and their skills might lead them down many paths, be they gamblers or jacks-of-all-trades, scholars or performers, leaders or scoundrels, or even all of the above. For bards, every day brings its own opportunities, adventures, and challenges, and only by bucking the odds, knowing the most, and being the best might they claim the treasures of each.

A rubato (plural rubati) is a bard who taps into the Primal Song and channels it in both life and war. Theories abound about the Primal Song, though most accept that it is an echo, a shard, of something even more ancient and fundamental, but its power fuels these war singers and propels them to acts of incredible valor.

**Role:** Bards capably confuse and confound their foes while inspiring their allies to ever-greater daring. While accomplished with both weapons and magic, the true strength of bards lies outside melee, where they can support their companions and undermine their foes without fear of interruptions to their performances.
