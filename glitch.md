# Glitches

==- Stale-State - Using items more than once

**Usage**

1. `/bag`
2. Repearedly click on the item you want to use more often than you have it in your bag

**Effect** You get a few items from the item with the one larger ItemID.
- The itemcount in the menu is not updated (but it is internally, so you will end up with 0 of this item later).
- For each usage after you depleted your storage, the app sends you an error message but also gives you another item a few times.
- The Item you get it the one with an ID one larger than the current. The number of items you get is `58 - used itemID`.
- There are some items which cannot be used outside battle. Those block access to some Items with this bug. Notable is the `Pulpa Berry (ID 12)`. This makes it not possible to glitch the `Green Cyberdrug (ID 13)`.

**Profits**
- Special items to get with this glitch are: `00 Berry (ID 0)`, `CM08 (ID 38)` and `CM15 (ID 45)`.
- You can make **a lot** of money: Get `Herbal Medicine` and apply the glitch to it. For each usage, you get `41 Herbal Remedy` which are worth `98400 bits`. This allows for about `1-2 Million bits / Minute`.
- Glitch the `Green Powderbag (ID 20)` to rapidly level up your Cybermon.

**Tricks** 
- Sell all but one instance of the item before to faster deplete your stack

**Underlaying Bug**
The discord component with the bag is not updated upon item usage and the used item is not again checked on the server side.

===

==- @-Move Glitch

**Usage**

1. Teach a Cybermon `@` (glitch Item `CM15 (ID 45)`)
2. Repeatedly use the attack

**Effekt** You can change your Cybermon.
- Each usage will shorten your team's name by one character until it has a length of 1
- Than, the cybermon's name is shortened
- Than, the cybermon's ID is decreased by one.

**Profits**
- Change your cybermon into any other cybermon, including glitch cybermons
- (to be investigated) How does this affect the stats? Getting ID19 sets all base stats to 1.
- You get one of those *cool* one-letter names.

**Tricks**
- Nickname your cybermon to a one letter word to speed up the process.

===

==- All-Dead Glitch

**Usage**
0. Careful, the cybermon at position #0 before you trigger the glitch will be replaced!
1. Let 5 of your Cybermon die and win the battle.
2. Swap one dead cybermon with a fresh one, so you have 2 alive
3. Fight again to let one more die and win again.
4. Swap the dead cybermon in your bag with the only alive cybermon, so you have 6 dead Cybermon active
5. Start a battle to trgger the gltich

**Effekt** You get a random glitch cybermon with random stats
- You cybermon #0 will be replaced with a random cybermon in the range 65-68 (to be investigated: is 64 possible?)
- The cybermon has random stats, including negative ones

**Profits**
- Glitch Cybermon, possibly with good stats
- (to be investigated: How do negative stats effect a battle)

**Tricks**
- The process takes a lot of work to setup. With careful switching you can repeat the final glitch quite fast numerous times.
- There are other options to get an all-dead team (`White Cyberdrug`)
===

==- Baby's first Underflow Glitch

**Usage**
1. Apply `Purple Cyberdrug` until your stats would become negative

**Effekt**
- (flag)
- to be investiaged

**Profits**
- flag

**Tricks**
- Catch a new cybermon with low stats or use glitch Cybermon ID 19

===

==- Wrong place, wrong time?
**Usage**
1. `/bag`
2. Start a battle
3. Use items from the previously opened bag, (to be investigated: that are unavailable during battle?)

**Effekt**
- `Red Powderbag` to fully heal during battle (with all those one-shot attacks, effect is neglectable)

**Profits**
- Heal during battle


===
