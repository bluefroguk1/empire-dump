---
IgnoreLinking: True
Title: Campaign outcome
aliases: ['Campaign_outcome']
draft: False
revision_date: 2023-04-01 17:23:16+00:00
revision_id: 98562
tags: ['Game-Design']
---

## Overview
[[The Empire]] military [[Downtime|downtime]] system uses a simple mathematical framework to calculate the outcome each season of a campaign. The values are presented below, along with some worked examples, so that players who are interested can understand precisely how the results are derived.
## Fighting Strength
Each army has a fighting strength, a number that reflects the raw military strength of the army. Most armies begin with a fighting strength of 5,000 - roughly one point of military strength for each soldier. As an army suffers [[Casualties|casualties]] the fighting strength is reduced to reflect this.
## [[Rituals]]
RitualVictoryCasualties
[[Clarity of the Master Strategist]]+20000
[[Knights of Glory]]+2000+2000
[[Quickening Cold Meat]]+1000+1000
* [[Rituals]] that increase the fighting strength of an army are added on first
Some [[Rituals|rituals]] increase [[The Military|the military]] fighting strength of an army, either for purposes of calculating victory, [[Casualties|casualties]], or both. If such a [[Ritual|ritual]] is in place, then this is the first modifier added.
The table shows the [[Rituals|rituals]] in [[Imperial lore|Imperial Lore]] with the modifiers they provide.
## Military Units
* [[Imperial armies]] benefit from having military units assigned to support them
* A starting [[Military unit|military unit]] adds 100 fighting strength
* The fighting strength for military units is added second
The fighting strength of every [[Military unit|military unit]] that is assigned to support an army is added to the total military fighting strength for purposes of victory and inflicting casualties. A starting [[Military unit|military unit]] has a fighting strength of 100. Each additional rank of improvement increases the fighting strength by 20.
Military units do not suffer casualties like an army, they are always at full strength regardless of any campaigns they participate in.
## Orders
TypeOrderVictoryCasualties
AttackingCautious Advance-20%-20%
Balanced Attack00
Overwhelming Assault+20%+20%
DefendingGive Ground-40%-50%
Solid Defence0-20%
Heroic Stand+30%+20%
* Orders change the military fighting strength of an army
* The effects of orders are added third
The fighting strength of an army is then modified based on the orders submitted by their [[General]]. Negative modifiers from orders [[Will|will]] affect the strength of the army, any ritual on the army, and all military units attached to the army. Positive modifiers from orders [[Will|will]] only ever affect the strength of the army. Orders may change the fighting strength for purposes of calculating victory, casualties, or both.
There is no requirement for all the armies in a campaign to submit the same orders. The modifier an army receives is based on the order submitted for that army only.
## Miscellaneous Effects
RitualCasualties
[[Rivers Run Red]]+100%
[[Rivers of Life]]-50%
* Miscellaneous effects are applied at the same time as orders
Other effects may influence the campaign and are applied at this time. Examples include the [[Rituals|rituals]] [[Rivers Run Red]] and [[Rivers of Life]].
## [[Fortifications]]
* Fortifications in a [[Territory|territory]] add their fighting strength to the side that controls them
* A [[Fortification|fortification]] that isn't attacked adds its fighting strength only for calculating victory
* A [[Fortification|fortification]] that is attacked adds its fighting strength for casualties and twice its strength for calculating victory
A basic [[Fortification]] has a maximum of 3000 fighting strength, larger fortifications are stronger. If the region the [[Fortification|fortification]] is in is not attacked, then whichever side controls it adds the strength of the [[Fortification|fortification]] to their total but only for calculating victory. The fortification does not cause any casualties if it is not attacked.
If the region the fortification is in is attacked, then it adds its fighting strength to the total for causing casualties and adds twice its fighting strength to the total for the side that controls it for calculating victory.
A fortification takes a share of casualties as if it were an army, but only if the region it is in is attacked. Any fortification that falls below 1000 fighting strength is destroyed, regardless of its size.
## Total Strength
* The military fighting strength of all armies on the same side is added together.
If an army on either side has submitted an attack order, then the resulting campaign involves all opposing armies in the territory, regardless of what orders they have submitted. The military fighting strength of every army fighting on the same side is added together to calculate the total strength of each side.
## Victory Points
* The side with the highest military fighting strength is victorious.
* They gain 1 victory point for every complete 1000 points differential.
* It requires 10 victory points to take the first region in a season.
* Capturing additional regions in the same season is more difficult.
The fighting strength of the two sides is compared, the victor is the side with the highest total strength after adjustments for orders, military units, and any rituals that are in place.
The scale of the victory is equal to the difference in the two sides total fighting strength. Victory is quantified using victory points; one victory point is accumulated for each full 1000 points of difference in fighting strength.
If the victorious side includes armies that have submitted orders to attack, then their victory points translate into land captured by the side. It requires ten victory points to take control of a region. A partial capture is possible, victory points are recorded between campaigns, so no victory points are "wasted". It is possible to capture more than one region in a single season but each additional region is more difficult than the last. It requires an additional 12 victory points to take a second region in the same campaign season, 14 victory points to take the third - and so on.
If the victorious side includes armies that have submitted orders to defend, then the victory points translate into reduced casualties. Each victory point translates decreases the casualties taken by an army by 1%.
If the victorious side includes some armies with attack orders and some armies with defend orders, then the victory points are split pro-rata based on their military fighting strength between the two sides to determine land captured and casualties reduced.
## Casualties
* An army inflicts 10% of its military fighting strength as casualties
* Casualties are divided amongst the armies based on the orders submitted
* Some orders and some rituals affect the number of casualties taken
Both sides in a campaign [[Will|will]] inflict casualties on each other. The total military fighting strength of each side is recalculated using only the modifiers that apply for causing casualties. The base figure for the total casualties inflicted is 10% of this score.
If the enemy force includes more than one army, then the casualties are divided between the armies according to the orders submitted. Armies that submit attacking orders [[Will|will]] take a greater share of the casualties than armies which are defending. The final ratios are based on a qualitative [[Judgement|judgement]] of the in-character description of the orders submitted.
Casualties are then adjusted based on the orders submitted and the presence of any appropriate rituals. Modifiers to casualties are stated in percentage adjustments. All percentages are added together and then applied as a single adjustment to calculate the final total for the number of casualties incurred.
The final casualties incurred are applied to each army, reducing its remaining fighting strength.
## Calculations
* All positive modifiers are added together and then added to the base number
* Next, all negative modifiers are multiplied together and multiplied against the base number
All positive modifiers are applied first. They are all added together and then added to the base number.
Following this calculation, all negative modifiers are then applied. All negative modifiers are multiplied together and applied against the result of applying all the positive modifiers.
## Disbandment
* An army which falls below 20% of its maximum value automatically disbands
The fighting strength of any army that falls below 20% of its maximum value automatically disbands. A normal army that falls below 1000 fighting strength disbands (1500 for a large army). The army routs from the territory and is completely destroyed.
## Example 1
* [[Imperial army]] 1: 3500 fighting strength, Overwhelming Assault, [[Clarity of the Master Strategist]]
* [[Imperial army]] 2: 1500 fighting strength, Cautious Advance, supported by 40 military units
* [[Barbarian]] army 1: 7500 fighting strength, Heroic Stand, [[Quickening Cold Meat]]
* [[Barbarian]] army 2: 4000 fighting strength, Solid Defence
* [[Barbarian]] army 3: 2000 fighting strength, Give Ground
* Territory [[Curse]]: [[Rivers Run Red]]
### Victory
* [[Imperial army]] 1: 6200 ((3500 * 120%) + 2000)
* [[Imperial army]] 2: 4400 ((1500 + 4000) * 80%)
* [[Barbarian]] army 1: 10750 ((7500* 130%)+1000)
* [[Barbarian]] army 2: 4000
* Barbarian army 3: 1200 (2000 * 60%)
The total Imperial fighting strength for purposes of victory is thus 10,600. The total barbarian total is 15,950. The [[Barbarians|barbarians]] win by 5350 - gaining 5 victory points. All of which are spent reducing casualties. The Imperial side do not gain any victory points.
### Casualties
* [[Imperial army]] 1: 3500 fighting strength
* Imperial army 2: 5500 fighting strength (1500 + 4000)
* Barbarian army 1: 8500 fighting strength (7500 + 1000)
* Barbarian army 2: 4000 fighting strength
* Barbarian army 3: 2000 fighting strength
The Imperial total is 9,000, so the baseline figure for casualties inflicted is 900. The Barbarian total is 14,500, so the baseline figure for their casualties inflicted is 1450.
The plot team decide to split casualties evenly to the Imperials, inflicting 725 casualties to each attacking army. The casualties suffered by the barbarian forces are divided evenly between the barbarian armies. The effects of the orders and the [[Rivers Run Red]] ritual are then applied to find the final casualty figures.
The victory points gained by the defending barbarians reduces their casualties by a further 5%.
* Imperial army 1: 1595 (725 * 220%)
* Imperial army 2: 1160 (725 * 160%)
* Barbarian army 1: 627 (300 * 209%)
* Barbarian army 2: 456 (300 * 152%)
* Barbarian army 3: 285 (300 * 95%)
The casualties suffered by Imperial army 2 are so severe that it falls below 1000 fighting strength and is disbanded.
## Example 2
* Imperial army 1: 5000 fighting strength, Overwhelming Assault
* Imperial army 2: 4000 fighting strength, Overwhelming assault  
* Barbarian fortification: 3000 fighting strength
* Territory [[Curse]]: [[Rivers of Life]]
### Victory
* Imperial army 1: 6000 (5000 * 120%)
* Imperial army 2: 4800 (4000 * 120%)
* Barbarian fortification: 6000 (3000 * 200%)
The total Imperial fighting strength for purposes of victory is thus 10800. The total barbarian total is 6000. The Imperial forces win by 4800 - gaining 4 victory points. They [[Will|will]] need to accrue 6 more victory points to take the fortification.
### Casualties
* Imperial army 1: 5000 fighting strength
* Imperial army 2: 4000 fighting strength
* Barbarian fortification: 3000 fighting strength
The Imperial armies take 300 casualties divided evenly between them. The barbarian fortification takes 900 casualties.
* Imperial army 1: 90 (150 * 60%)
* Imperial army 2: 90 (150 * 60%)
* Barbarian fortification: 900 
The River of Life ritual does not affect the casualties taken by the fortification.
[[War]] Further Reading