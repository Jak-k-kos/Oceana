---
title: Damage and Repair
draft: false
---
Back to [[Sails and Seas/Ship Rules/index|Ship Rules]]
# Damage and Repair
- [[#Hull Points]]
- [[#Sinking]]
- [[#Repairing Damage]]
- [[#Long-Term Repairs]]
- [[#Crew Members]]
- [[#Fire]]

# Hull Points
Hull Points work like a creature's Hit Points, with two big differences.
- **Damage keeps counting past 0.** A ship's Hull Points can drop as low as negative half its maximum. (A ship with 100 max HP can drop to -50.)
- **Damage slows the ship.** Below half its maximum Hull Points, the ship's maximum speed is halved. Any movement from Sail Crew Actions above that limit is wasted. The penalty ends once the ship is repaired above half again.

Remember the ship's **Damage Threshold**: any single instance of damage below it is ignored (see [[Basic Ship Rules#Ship Statistics|Ship Statistics]]).

# Sinking
At 0 Hull Points a ship doesn't fall unconscious. It is immobilized and **sinking**. A ship carrying more than its Tonnage is also sinking.
- Its Speed Unit drops to 0.
- All Crew Actions aboard are rolled with disadvantage.
- All attacks against it have advantage.
- At the start of each of its turns, it takes Sinking Damage equal to 1/10 of its maximum Hull Points (rounded down).

At negative half its maximum Hull Points, the ship is damaged beyond repair and goes under. It can't act and can't be repaired by anything less than powerful magic or divine intervention. It's out of play.

# Repairing Damage
A ship is an object, so healing magic doesn't work on it. Repairs take labor and spare materials.
- During the Character Phase, a creature can take the **Repair** action: patching holes, tying ropes, fixing valves, or bailing water. This is **not** a Crew Action, so it happens immediately.
- **Check:** DC 10 Strength or Intelligence (player's choice). The DM decides whether tool proficiencies (like carpenter's or tinker's tools) apply.
- **Success:** Spend and roll one of the ship's Hull Dice, adding the result to its Hull Points. If a part of the ship has its own hit points (like many ranged weapons), you can add the roll to that part instead.

# Long-Term Repairs
Field patches won't hold forever. Proper repairs need the ship docked somewhere with room to house it and the facilities to fix it, from a beach shed for a rowboat to a city dry dock for a bigger ship. The DM decides whether a location is suitable.
- A skilled laborer works 8 hours a day for **1300 SH** a day.
- Using free labor (like a crew member already on your payroll) costs **1000 SH** a day for materials.
- Each day a skilled laborer works, the ship regains either Hull Points equal to the maximum roll of one Hull Die, or one spent Hull Die.

# Crew Members
Battle takes its toll on the crew as well as the ship.
- The ship's crew count drops whenever a crew member can no longer do normal ship duties and Crew Actions. They aren't necessarily dead, and may just be unconscious or incapacitated (DM's call).
- Other effects can stop crew from taking Crew Actions, even briefly: being knocked prone by wind, charmed, frightened, and so on. Effects in these rules say how they affect crew; for anything else, the DM decides.
- The Repair action doesn't help crew. They're restored with normal healing for creatures. For example, Lay on Hands can restore one crew member, and Mass Healing Word can restore up to six.
- Back in port, you can hire new crew to replace those who were lost.

# Fire
A wooden or otherwise flammable ship can catch fire. A ship made of metal or stone can't, unless its description says otherwise.
- **Catching fire:** the weapon or item that sets the fire says how big it starts, measured in d6s (a flaming bolt starts a 2d6 fire, a fire pot 1d6).
- **Burning:** at the start of each of its turns, a burning ship rolls its fire dice and takes that much fire damage. This damage ignores the ship's Damage Threshold. After that, the fire grows by 1d6, so it deals 1d6 more damage every turn until it's put out.
- **Feeding the fire:** when a fire weapon hits a ship that's already burning, the fire grows by 1d6 instead of starting a new one.
- **Rain:** in heavy rain, a fire shrinks by 1d6 at the end of each of the ship's turns.

## Fighting Fires
During the Character Phase, a creature aboard can use its action to fight the fire with buckets, wet sail and sand. Like Repair, this is not a Crew Action, so it happens immediately.
- **Each creature fighting it** shrinks the fire by 1d6.
- **With [[Ship Upgrades#Fire Troughs|Fire Troughs]]**, it shrinks by 2d6 instead.
- **With a bucket of [[Ship Supplies#Boarding and Defense|fire sand]]**, it shrinks by 2d6, or 3d6 with Fire Troughs. The sand is used up.
- **When the fire reaches 0 dice,** it goes out.

Fire damage hurts the ship's Hull Points. It doesn't harm the crew unless an effect says it does.