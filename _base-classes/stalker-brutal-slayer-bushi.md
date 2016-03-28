---
title: Stalker (Brutal Slayer, Bushi)
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
  - Perform
  - Profession
  - Sense Motive
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
      A stalker begins his career with knowledge of six martial maneuvers. The disciplines available to him are Broken Blade, Solar Wind, Steel Serpent, Thrashing Dragon, and Veiled Moon, and the choice of either Riven Hourglass or Tempest Gale. The stalker may also exchange access to one of his martial disciplines for the Unquiet Grave discipline, and must choose one of his martial disciplines to exchange for the Mithral Current discipline. He gains the associated skill of each of his disciplines as a class skill.

      Once he knows a maneuver, he must ready it before he can use it (see Maneuvers Readied, below). A maneuver usable by stalkers is considered an extraordinary ability unless otherwise noted in its description. His maneuvers are not affected by spell resistance, and he does not provoke attacks of opportunity when he initiates one. He learns additional maneuvers at higher levels, as shown above. The stalker must meet a maneuver's prerequisite to learn it.

      Upon reaching 4th level, and at every even numbered stalker level after that, he can choose to learn a new maneuver in place of one he already knows. In effect, the stalker loses the old maneuver in exchange for the new one. The stalker need not replace the old maneuver with a maneuver of the same level. He can choose a new maneuver of any level he likes, as long as he observes his restriction on the highest-level maneuvers he knows. The stalker can swap only a single maneuver at any given level. A stalker's initiator modifier is Wisdom.

      *Maneuvers Readied:* A stalker can ready four of his six starting maneuvers, but as he advances in level and learns more maneuvers, he must choose which maneuvers to ready. He readies his maneuvers by meditating and focusing his *ki* for 10 minutes. The maneuvers he chooses remain readied until he decides to repeat this again and change them. Stalkers do not need to sleep or be well rested to ready their maneuvers; any time he spends 10 minutes in meditation, he can change his readied maneuvers. He may not ready any individual maneuver more than once. He begins an encounter with all readied maneuvers unexpended, regardless of how many times he may have already used them since he chose them. When the stalker initiates a maneuver, he expends it for the current encounter, so each of his readied maneuvers can be used once per encounter (until they are recovered, see below).

      To recover his maneuvers, a brutal slayer uses his *ki* to reinforce his body as a full-round action. When he does so, he recovers a number of expended maneuvers equal to his brutal slayer initiation modifier (minimum 2) and gains temporary hit points equal to twice his initiator level and DR/-- equal to his brutal slayer initiation modifier (minimum 0). These temporary hit points and damage reduction last for one round, and stack with any other sources of temporary hit points or damage reduction he may have. In addition, the next strike he initiates this encounter deals additional bleed damage equal to his brutal stalker initiation modifier. The target continues to bleed until the bleeding is stopped via magical healing or a successful DC 15 Heal check.

      *Stances Known:* Stalkers begin play with knowledge of one stance from any discipline open to stalkers. At the indicated levels (see class table), the stalker selects an additional new stance. Unlike maneuvers, stances are not expended and he does not have to ready them. All the stances he knows are available to him at all times, and he can change the stance he is currently using as a swift action. A stance is an extraordinary ability unless otherwise stated in the stance description. Unlike with maneuvers, the stalker cannot learn a new stance at higher levels in place of one he already knows.

  - name: "*ki* pool"
    type: Su
    levels: [1, 5]
    levesl_text:
      1: sense
      5: combat reading
      7: insight
      9: readiness
    text: |
      At 1st level, a stalker gains a pool of *ki* points, supernatural energy he can use to accomplish amazing feats. The number of points in the stalker's *ki* pool is equal to 1/2 her stalker level + his Wisdom modifier (minimum of 1).

      At 1st level, the stalker may spend 1 point of *ki* to grant himself a +4 insight bonus to a single Perception or Sense Motive check as an immediate action, as he uses his *ki* to feel out the vibrations of others and their hidden motives.

      At 5th level, the stalker may use his deadly strikes in conjunction with his combat insight to "read" his opponent's defenses and deliver devastating blows beyond his foe's guard. The stalker spends one point of *ki* as a swift action to read his target opponent, and may apply his deadly strike to all martial strikes initiated by the stalker for a number of rounds equal to his Wisdom modifier against this target. If the stalker scores a successful critical hit against the target while this ability is active, then he activates deadly strike as normal.

      At 7th level, the stalker may spend 1 point from his *ki* pool to gain a +4 insight bonus on a saving throw as an immediate action.

      At 9th level, the stalker can delve into his subconscious in battle and remember key lessons from his training. The stalker envisions potential scenarios where martial abilities he has not readied come into play and gains a momentary burst of martial insight. A number of times per day equal to his Wisdom modifier, the stalker can spend one *ki* point as a swift action and trade one readied maneuver for another maneuver known of the same level or lower. The new maneuver is immediately readied and accessible for use. The character may initiate this maneuver and recover it as if he had prepared at the beginning of the day (or when ever the stalker readied his maneuvers last) until the end of the combat encounter.

      The *ki* pool is replenished each day after 8 hours of rest and meditation; these hours do not need to be consecutive. If the stalker possesses levels in another class that grants points to a *ki* pool, stalker levels stack with the levels of that class to determine the total number of *ki* points in the combined pool, but only one ability score modifier is added to the total. The choice of which score to use is made when the second class ability is gained, and once made, the choice is set. The stalker can now use *ki* points from this pool to power the abilities of every class he possesses that grants a *ki* pool.

  - name: brutal strikes
    type: Ex
    levels: [1, 6, 16]
    levels_text:
      1:  "+4"
      6:  "+6"
      16: "+8"
    text: Starting at 1st level, whenever a brutal slayer confirms a critical hit against a creature, he gains a +4 profane bonus Strength for a number of rounds equal to his brutal slayer initiation modifier. This bonus increases to +6 at 8th level and to +8 at 16th level.

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

  - name: combat insight
    type: Su
    levels: [2, 4, 8, 12, 18]
    levels_text:
      2: defensive reflexes
      4: uncanny dodge
      8: critical hits
      12: critical recovery
      18: blindsight
    text: |
      At 2nd level, the keen senses and awareness of the stalker delivers him a sort of sixth sense. This insight performs as an intuitive alarm, alerting him of danger. Through his rigorous practice and learning to trust his instincts and intuition to an unearthly level, the senses of the stalker are unusually sharp.

      At 2nd level, the stalker's combat sense opens his third eye, granting him defensive reflexes that protect him in combat. The stalker may add his Wisdom modifier to his initiative score and to Reflex saving throws as an insight bonus.

      At 4th level, the heightened perceptions of the stalker allow him to know when his prey could get the jump on him, granting him the uncanny dodge class feature, as per the rogue class.

      At 8th level, the killer's instinct in the stalker is honed to a razor's fine edge, allowing him to add his Wisdom modifier as a competence bonus to confirm critical hits. This ability counts as if the character possessed the Critical Focus feat, and for the purposes of taking critical feats that the character qualifies for. The character may not select the Critical Focus feat once he has this ability, and should he have it before he gains this ability, he loses the Critical Focus feat and may select a critical feat in its place.

      At 12th level, the stalker's insight allows him to funnel the *ki* of his foes into his form with his deadly attacks. The character can recover a single expended maneuver when he scores a successful critical hit against a living creature. This ability does not function against constructs, undead, or creatures with under 1⁄2 HD.

      At 18th level, the heightened precognitive abilities of the stalker manifest in his ability to sense things around him that others cannot, granting him blindsight with a range of 30 feet. This is a supernatural ability.

  - name: armor of scars
    type: Ex
    levels: [1, 4, 8, 12, 16, 20]
    levels_text:
      1:  "+1"
      4:  "+2"
      8:  "+3"
      12: "+4"
      16: "+5"
      20: "+6"
    text: The brutal slayer takes as well as he gives, becoming protected by the scars of wounds he has already survived. Starting at 1st level, a brutal slayer gains a +1 bonus to his natural armor. At 4th level and every four levels thereafter, this bonus increases by +1. In addition, the brutal slayer's instincts enable him to better dodge incoming blows; whenever he spends a full-round action to recover maneuvers, he gains a dodge bonus to AC equal to his brutal slayer initiation modifier.

  - name: muscle memory
    type: Ex
    levels: [2, 6]
    levels_text:
      2: half
      6: full
    text: The muscles of a brutal slayer are honed to deadly efficiency, just like his blades. Starting at 2nd level, a brutal slayer may add 1/2 his Strength modifier to his AC and to Reflex saves instead of his Dexterity modifier. At 6th level, the brutal slayer may add his full Strength modifier instead of his Dexterity modifier, rather than 1/2. The brutal slayer's Strength bonus to his AC is still limited by his armor's maximum Dexterity bonus.

  - name: stalker arts
    levels: [3, 7, 11, 15, 19]
    levels_text:
      3:  1 art
      7:  2 arts
      11: 3 arts
      15: 4 arts
      19: 5 arts
    text: |
      As a stalker gains experience, he learns a number of arts that aid him and confound his foes. Starting at 3rd level, a stalker gains one [stalker art](/stalker-arts/); he gains an additional art every four class levels attained after 3rd level. A stalker cannot select an individual art more than once (unless noted).

  - name: bushido
    type: Su
    levels: [3]
    text: As a bushi grows in power, he gains access to abilities through the refinement of his spirit and his weapon by adhering to the principles of bushido. Beginning at 3rd level, a stalker bushi can choose to take a [bushido](/bushido/) in place of a stalker art he would gain.

  - name: Mixed Combat
    type: Ex
    levels: [6]
    text: At 6th level, a bushi gains Mixed Combat as a bonus feat, even if he does not meet the prerequisites. In addition, the bushi is considered to be threatening all adjacent squares even if his weapon is sheathed, and can draw his weapon when making any attack (including attacks of opportunity).

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

Bushi are honorable and noble warriors who specialize in Iaijutsu, the art of the draw cut. With a single swing of his katana, a bushi can cleave through armor, bones and organs as easily as straw. Bushi follow the code of bushido and exemplify the virtues of righteousness, courage, benevolence, respect, honesty, honor and loyalty.

**Adventures:** Stalkers adventure for many reasons, but most do so either as part of a guild of fellow stalkers on a mission, for money and profit, or for deeper, often darker purposes of the heart. Some adventure for the test of their skill, but this is slightly rarer; whatever the reason, the path of the stalker is often a self-absorbed one.

**Characteristics:** Stalkers universally are very introspective people, they rely so heavily upon their intuitive reactions to situations and their heightened reflexes through athletic skill that they usually have an air of detachment. Some are braggarts, but many are quiet and calm, paying close attention to their surroundings should they need to use their lethal skills.

**Alignment:** Any. Stalkers do not lean to any particular alignment trend, running the gamut of all walks of life.

**Religion:** Some stalkers are deeply religious, finding solace in their meditations to gods of night, death, travels, or revelry. Other stalkers find no use for gods, for if the gods protected and cared for their flock, then they wouldn't make their followers so easy to kill.

**Background:** Stalkers often arise from the poor and underprivileged who live in city slums, trained from their youth to be unfeeling killers. Others are trained in remote areas in a more monastic fashion, taught to be warriors who strike from the shadows. The training of stalkers can also be an individual thing, each master teaching a student in their own way, the way they were taught.

**Races:** Humans and outcast races tend to be drawn to the path of the stalker. Half-orcs and half-elves make up a majority of the non-human stalkers, with goblinoids coming in next.

**Other Classes:** Stalkers get on well with rogues and rangers due to having complementary roles. Paladins and clerics often chafe when partied with stalkers, as their reputation as killers (rightly or wrongly) often sours opinions of them. Other classes generally have a neutral opinion of stalkers, unless that stalker has come for them.

**Role:** Striker. In the party, the stalker follows the heavily armored fighter into combat, using them as shields and distractions so they can inflict maximum damage on their foes. In addition, the stalker can serve quite well as the party scout, finding danger and warning the party before they stumble upon it.

**Abilities:** Dexterity and Wisdom are prime attributes for stalkers, as many of their skills are governed by these abilities and their combat capabilities are augmented by them as well. Wisdom is the primary initiating attribute for stalker. Strength is valuable for damage, but can fall behind Constitution for endurance in battle.
