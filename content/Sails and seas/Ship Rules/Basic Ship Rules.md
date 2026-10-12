---
title: Basic Ship Rules
draft: false
---
Back to [[Sails and Seas/Ship Rules/index|Ship Rules]]
# Basic Ship Rules
- [[#Ship Statistics]]
- [[#Size]]
- [[#Properties]]

Every ship has a stat block. Here's what each entry means.

# Ship Statistics
**Armor Class (AC):** Works exactly like a creature's AC. Attack rolls against the ship have to beat it.

**Hull Points (HP):** How much damage the ship can take before it's incapacitated and starts to sink. Hull Points come from **Hull Dice**, which work like a creature's Hit Dice. Maximum Hull Points = the highest number on one Hull Die x the number of Hull Dice (for example, 20d10 = 200 HP). See [[Damage and Repair]].

**Damage Threshold:** Any single instance of damage below this number (after modifiers) is superficial and doesn't reduce Hull Points.

**Crew Members (XX/YY):** The first number is the minimum able-bodied crew needed for the ship to barely function. The second is the most crew who can help run it.
- Below the minimum, the ship gets no benefit from the Sail Crew Action.
- Crew beyond the maximum can't take Crew Actions.

**Passengers:** How many creatures can live aboard comfortably and safely. This number includes the crew.

**Initiative:** Ships don't roll initiative and have no initiative bonus. They have a fixed initiative score that sets when they act in the Ship Phase. Crew can raise it for a round with the Command Crew Action. Smaller ships usually have higher scores, since they're easier to handle and need fewer hands.

**Tonnage:** How much weight the hold can carry safely. Carrying more puts the ship into Sinking status (see [[Damage and Repair#Sinking|Sinking]]). The weight of the ship's weapons doesn't count toward this.

**Weapon Slots:** The most ship weapons the ship can carry. A weapon can't be installed if its slots would push the total over this number.

**Speed Unit:** How much movement the ship gains from each successful Sail Crew Action.

**Sail Stations:** How many Sail Crew Actions can be taken at the same time aboard. A station might be rigging, a bank of oars, or a boiler. Mechanically they all work the same unless a ship says otherwise.

**Maximum Speed:** The most speed the ship can make on its own without outside bonuses: Speed Unit x Sail Stations. The number in parentheses is how fast it goes with every Sail Station crewed by an average sailor; it's mainly for the DM running NPC ships.

## Size
Size decides a ship's Hull Dice, how many crew can operate it, and which upgrades and Weapon Slots it can take. A stat block lists both the ship's dimensions (bow to stern and widest point) and its size category.

| Size   | Length         |
| ------ | -------------- |
| Small  | 30 ft. or less |
| Medium | 30 to 80 ft.   |
| Large  | 80 to 150 ft.  |
| Huge   | Over 150 ft.   |

# Properties
Many ships have properties that change how they're handled.

**Agile:** Can turn on the spot instead of having to move while turning. Turning costs no extra movement.

**Cumbersome:** Hard to sail. The DC for the Sail Crew Action goes up by 5, and turning requires moving forward two Speed Units' worth of distance instead of one.

**Helmsman Required:** The ship has a rudder or steering system separate from how it moves. It can only move in a straight line unless someone takes the Helm Crew Action that round.

**Independent Propulsion (XX):** The ship has a means of moving that only needs someone at the controls. Taking the Helm Crew Action automatically gives the ship the base movement speed in parentheses. Any Sail Crew Actions add on top of that.

**Mixed Propulsion (XX):** Uses sails in wind, with a backup way of moving in calm weather (listed in parentheses). With sails unfurled, it counts as Sail Powered. With sails furled or in a Dead Wind, it keeps its normal Speed Unit.

**Sail Powered:** Moves by wind in its sails. In a Dead Wind its Speed Unit is 0, and other wind conditions can give penalties or bonuses.
- **Furling:** On its turn, a Sail Powered ship that had at least half its Sail Stations successfully used that round can furl its sails instead of using its movement. While furled, it isn't Sail Powered and its Speed Unit is 0.
- **Unfurling:** Requires half the ship's Sail Stations to have been successfully used that round.
