---
title: Stalker (Soul Hunter)
sources:
  - Path of War
  - "Path of War: Expanded"
tags:
  - Initiator
  - Ki

max_level: 20
hit_die: 8
prerequisites:
starting_age: Trained
starting_wealth: ???

class_skills:
  - Acrobatics
  - Appraise
  - Bluff
  - Climb
  - Craft
  - Disable Device
  - Disguise
  - Escape Artist
  - Heal
  - Intimidate
  - Knowledge (local)
  - Knowledge (martial)
  - Knowledge (nature)
  - Knowledge (religion)
  - Perception
  - Profession
  - Sense Motive
  - Spellcraft
  - Stealth
skill_ranks_per_level: 6

bab_progression: mid
fort_progression: poor
ref_progression: poor
will_progression: good

initiating_progression: stalker

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
      A stalker begins his career with knowledge of six martial maneuvers. The disciplines available to him are Broken Blade, Cursed Razor, Solar Wind, Steel Serpent, Thrashing Dragon, and Veiled Moon. The stalker may also exchange access to one of his martial disciplines for the Unquiet Grave discipline. He gains the associated skill of each of his disciplines as a class skill.

      Once he knows a maneuver, he must ready it before he can use it (see Maneuvers Readied, below). A maneuver usable by stalkers is considered an extraordinary ability unless otherwise noted in its description. His maneuvers are not affected by spell resistance, and he does not provoke attacks of opportunity when he initiates one. He learns additional maneuvers at higher levels, as shown above. The stalker must meet a maneuver's prerequisite to learn it.

      Upon reaching 4th level, and at every even numbered stalker level after that, he can choose to learn a new maneuver in place of one he already knows. In effect, the stalker loses the old maneuver in exchange for the new one. The stalker need not replace the old maneuver with a maneuver of the same level. He can choose a new maneuver of any level he likes, as long as he observes his restriction on the highest-level maneuvers he knows. The stalker can swap only a single maneuver at any given level. A stalker's initiator modifier is Wisdom.

      *Maneuvers Readied:* A stalker can ready four of his six starting maneuvers, but as he advances in level and learns more maneuvers, he must choose which maneuvers to ready. He readies his maneuvers by meditating and focusing his *ki* for 10 minutes. The maneuvers he chooses remain readied until he decides to repeat this again and change them. Stalkers do not need to sleep or be well rested to ready their maneuvers; any time he spends 10 minutes in meditation, he can change his readied maneuvers. He may not ready any individual maneuver more than once. He begins an encounter with all readied maneuvers unexpended, regardless of how many times he may have already used them since he chose them. When the stalker initiates a maneuver, he expends it for the current encounter, so each of his readied maneuvers can be used once per encounter (until they are recovered, see below).

      Stalkers may recover their maneuvers in one of two ways. In order for a soul hunter to recover maneuvers, he must either focus on the hunt of his prey or on the memories of past kills as a standard action and recover one expended maneuver. Alternately, the soul hunter may tap into the escaping energy of a soul by using his Soul Claiming ability, and recover a number of expended maneuvers equal to his Wisdom modifier.

      *Stances Known:* Stalkers begin play with knowledge of one stance from any discipline open to stalkers. At the indicated levels (see class table), the stalker selects an additional new stance. Unlike maneuvers, stances are not expended and he does not have to ready them. All the stances he knows are available to him at all times, and he can change the stance he is currently using as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance description. Unlike with maneuvers, the stalker cannot learn a new stance at higher levels in place of one he already knows.

  - name: "*ki* pool"
    type: Su
    levels: [1, 5]
    levesl_text:
      1: sense
      5: soulburning
      7: insight
      9: readiness
    text: |
      At 1st level, a stalker gains a pool of *ki* points, supernatural energy he can use to accomplish amazing feats. The number of points in the stalker's *ki* pool is equal to 1/2 her stalker level + his Wisdom modifier (minimum of 1) + 2.

      At 1st level, the stalker may spend 1 point of *ki* to grant himself a +4 insight bonus to a single Perception or Sense Motive check as an immediate action, as he uses his *ki* to feel out the vibrations of others and their hidden motives.

      At 5th level, the soul hunter may use his soulburning class feature on Claimed targets within 30 ft. of his position. The stalker spends 1 point of *ki* as a move action and all Claimed targets suffer his soulburning damage.

      At 7th level, the stalker may spend 1 point from his *ki* pool to gain a +4 insight bonus on a saving throw as an immediate action.

      At 9th level, the stalker can delve into his subconscious in battle and remember key lessons from his training. The stalker envisions potential scenarios where martial abilities he has not readied come into play and gains a momentary burst of martial insight. A number of times per day equal to his Wisdom modifier, the stalker can spend one *ki* point as a swift action and trade one readied maneuver for another maneuver known of the same level or lower. The new maneuver is immediately readied and accessible for use. The character may initiate this maneuver and recover it as if he had prepared at the beginning of the day (or when ever the stalker readied his maneuvers last) until the end of the combat encounter.

      The *ki* pool is replenished each day after 8 hours of rest and meditation; these hours do not need to be consecutive. If the stalker possesses levels in another class that grants points to a *ki* pool, stalker levels stack with the levels of that class to determine the total number of *ki* points in the combined pool, but only one ability score modifier is added to the total. The choice of which score to use is made when the second class ability is gained, and once made, the choice is set. The stalker can now use *ki* points from this pool to power the abilities of every class he possesses that grants a *ki* pool.

  - name: soul claiming
    type: Su
    levels: [1]
    text: |
      A soul hunter is capable of attuning his own *ki* to a foe’s vital energies, making it difficult for quarry to elude or escape him. As a swift action, the soul hunter stalker may Claim a target creature that he has inflicted damage upon. A Claimed target’s position is known to the soul hunter, even if they have total concealment against him (though he still suffers the normal miss chance if his target is concealed, and is denied his Dexterity bonus if the Claimed target attacks him). Additionally, the target of his Claiming provokes attacks of opportunity from the soul hunter when using the withdraw action to escape him.

      A soul hunter may not Claim more than his Wisdom modifier in creatures at any given time; a creature remains Claimed until the soul hunter withdraws his Claim (a free action) or until the target is slain. If the Claimed target is slain (reduced to 0 or fewer hit points) by the Claiming soul hunter, then he may recover his Wisdom modifier in expended maneuvers. A soul hunter may not Claim a target creature with fewer than 1⁄2 HD.

  - name: soulburning
    type: Su
    text: |
      When combating his target, the soul hunter can use his *ki* to cause disharmony within a Claimed creature’s very life energy, causing the foe’s own *ki* to erupt into life-destroying energy. Some describe the pain experienced as being the worst that any could endure, like something was inside their very spirit and devouring it whole. When making an attack or initiating a martial maneuver against his Claimed target, the soul hunter may force this subtle disharmony to become a geyser of agony, as the soul hunter’s *ki* causes the target’s life energies to ignite. This inflicts an additional 1d6 points of damage at 1st level upon a successful attack, and this damage increases by an additional 1d6 points of damage every four soul hunter levels.

      Stalker arts that utilize deadly strikes use soulburning instead, and function as written with the following caveat: Soulburning cannot be used against targets that do not have vital forces. This includes constructs, oozes, and undead with an Intelligence score of 0.

  - name: combat insight
    type: Su
    levels: [2, 4, 8, 12, 18]
    levels_text:
      2: scent
      4: uncanny dodge
      8: critical hits
      12: Claimed recovery
      18: blindsight
    text: |
      At 2nd level, the soul hunter gains the scent special ability, and gains a +4 insight bonus to track targets that the he has Claimed.

      At 4th level, the heightened perceptions of the stalker allow him to know when his prey could get the jump on him, granting him the uncanny dodge class feature, as per the rogue class.

      At 8th level, the killer's instinct in the stalker is honed to a razor's fine edge, allowing him to add his Wisdom modifier as a competence bonus to confirm critical hits. This ability counts as if the character possessed the Critical Focus feat, and for the purposes of taking critical feats that the character qualifies for. The character may not select the Critical Focus feat once he has this ability, and should he have it before he gains this ability, he loses the Critical Focus feat and may select a critical feat in its place.

      At 12th level, whenever the judge reduces a Claimed target to 0 hit points or less, he may recover an expended maneuver.

      At 18th level, the heightened precognitive abilities of the stalker manifest in his ability to sense things around him that others cannot, granting him blindsight with a range of 30 feet. This is a supernatural ability.

  - name: dodge bonus
    type: Ex
    levels: [2, 6, 10, 14, 18]
    levesl_text:
      2:  "+1"
      6:  "+2"
      10: "+3"
      14: "+4"
      18: "+5"
    text: The stalker's heightened perception of danger allows him to defend himself from attacks as they are made against him, anticipating the attacks as they come. A stalker gains a +1 dodge bonus to his Armor Class at 2nd level, which improves by an additional +1 every four stalker levels thereafter. When recovering maneuvers as a full round action, the character may add his Wisdom modifier to his AC as an additional dodge bonus; his defensive precognition being heightened by centering his *ki* through maneuver recovery.

  - name: stalker arts
    levels: [1, 3, 7, 11, 15, 19]
    levels_text:
      1:  1 art
      3:  2 arts
      7:  3 arts
      11: 4 arts
      15: 5 arts
      19: 6 arts
    text: |
      As a stalker gains experience, he learns a number of arts that aid him and confound his foes. Starting at 1st level, a stalker gains one [stalker art](/stalker-arts/); he gains an additional art at 3rd level and new arts every four class levels attained after 3rd level. A stalker cannot select an individual art more than once (unless noted).

  - name: "*sight of the hunter*"
    type: Sp
    levels: [6, 16]
    levels_text:
      6: "*clairaudience/clairvoyance*"
      16: "*scrying* and *locate creature*"
    text: |
      The soul hunter learns ways to be able to hunt his prey with his extrasensory abilities. At 6th level, the soul hunter may spend 1 *ki* and use the spell *clairaudience/clairvoyance* (clairvoyance only) as a spell-like ability, using his stalker level as his caster level for the effect. He may spend an additional *ki* point to Claim a target seen in such a way.

      At 16th level, he may spend a *ki* point to use *scrying* and *locate creature* as spell-like abilities, and Claim targets spied upon in such a manner. The soul hunter must have either visited the location first, or have a clear picture of the target within his mind to use these abilities (as per the spells' specific requirements).

  - name: dual strike
    type: Ex
    levels: [10, 14, 18]
    levels_text:
      10: 1/day
      14: 2/day
      18: 3/day
    text: Once per day at 10th level, the stalker's deadly skill in combat improves, allowing him to initiate two martial strikes as a full round action. The strikes the stalker initiates must have an initiation action of one standard action, and he must have both strikes readied. Boosts may not be applied to a dual strike due to the need to concentrate on two separate martial movements. When a dual strike is used, the action must be declared beforehand and when used, both strikes are resolved separately and are expended. At 14th level the character may use dual strike twice per day, and three times per day at 18th level.

  - name: retributive *ki*
    type: Su
    levels: [20]
    text: At 20th level, the stalker's mystical *ki* power allows for him to generate a powerful burst of energy to gain retribution on those who would injure him. When the stalker is harmed by an attack, spell, or ability of an enemy, as an immediate action he may spend two *ki* points to initiate a martial strike that he has readied (with an initiation action of one standard action) in retaliation against that attack. He uses the range of the attacker's ability as the range of his strike, creating a phantom echo of himself with his *ki* (as with the phantom reach art) that rushes out and strikes his attacker if they are outside of the stalker's normal reach. Use of this ability expends his strike as normal, and the strike functions as normal otherwise.
---

An effective warrior wielding both skill and stealth, the stalker is a martial disciple who battles in the deep shadows and the hidden underworld of night. Through rigorous training and deep, intuitive instincts, the stalker is a trained killer whose very art is considered illegal in some places. Part mystic, part warrior, and part assassin, the stalker's arts are varied, but always deadly.

Some stalkers learn that through the practice of more esoteric *ki* arts, that they are able to track the very essence of a foe, see through the fog of reality and hunt the soul of their targets. These stalkers, known as soul hunters, are well-versed in the methods of hunting and killing their intended targets. By honing their senses farther than any other stalker could, and emulating the hunting methods of hungry spirits and dragons, the soul hunter becomes a foe that is nigh- inescapable.

**Adventures:** Stalkers adventure for many reasons, but most do so either as part of a guild of fellow stalkers on a mission, for money and profit, or for deeper, often darker purposes of the heart. Some adventure for the test of their skill, but this is slightly rarer; whatever the reason, the path of the stalker is often a self-absorbed one.

**Characteristics:** Stalkers universally are very introspective people, they rely so heavily upon their intuitive reactions to situations and their heightened reflexes through athletic skill that they usually have an air of detachment. Some are braggarts, but many are quiet and calm, paying close attention to their surroundings should they need to use their lethal skills.

**Alignment:** Any. Stalkers do not lean to any particular alignment trend, running the gamut of all walks of life.

**Religion:** Some stalkers are deeply religious, finding solace in their meditations to gods of night, death, travels, or revelry. Other stalkers find no use for gods, for if the gods protected and cared for their flock, then they wouldn't make their followers so easy to kill.

**Background:** Stalkers often arise from the poor and underprivileged who live in city slums, trained from their youth to be unfeeling killers. Others are trained in remote areas in a more monastic fashion, taught to be warriors who strike from the shadows. The training of stalkers can also be an individual thing, each master teaching a student in their own way, the way they were taught.

**Races:** Humans and outcast races tend to be drawn to the path of the stalker. Half-orcs and half-elves make up a majority of the non-human stalkers, with goblinoids coming in next.

**Other Classes:** Stalkers get on well with rogues and rangers due to having complementary roles. Paladins and clerics often chafe when partied with stalkers, as their reputation as killers (rightly or wrongly) often sours opinions of them. Other classes generally have a neutral opinion of stalkers, unless that stalker has come for them.

**Role:** Striker. In the party, the stalker follows the heavily armored fighter into combat, using them as shields and distractions so they can inflict maximum damage on their foes. In addition, the stalker can serve quite well as the party scout, finding danger and warning the party before they stumble upon it.

**Abilities:** Dexterity and Wisdom are prime attributes for stalkers, as many of their skills are governed by these abilities and their combat capabilities are augmented by them as well. Wisdom is the primary initiating attribute for stalker. Strength is valuable for damage, but can fall behind Constitution for endurance in battle.
