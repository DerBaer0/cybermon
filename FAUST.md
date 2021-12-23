# FAUST
### What we did / what we have

- Explore the whole map
- Enumerate Cybermon and Items
- A bot that can
	- Move to any location as fast as possible (6-step at a time)
	- Explore unseen areas, built a map with the images and collision
		1. Find the closest unseen position where we can get close to
		2. Go there, take the image
		3. Segment the map into the 13x13 cells and compute a hashsum on all sub-images (simply add all pixel values is enough)
		4. Loop-up the hashvalue to find the collision data for this field (the database is automated generated with a few manual fixes: Let the player walk at an unknown position and detect if we get an error).
		
		*All the battles our bot encountered during it's exploration leveled one cybermon without glitches up to about Lvl. 45*
	- Battle (either using attacks from a prefered list or swapping cybermon indefinitely)
	- Level a cybermon by running through grass as fast as possible and fighting battles and the NPC (this is a glitchless way of leveling up quite fast)
	- Use Items repeatedly (especially to level up with `Green Powderbag` and farming money)
	- Farm money buy generating and selling `Red Powderbag`s at a rate of about `30.000 bits per second`
	- View and Parse move and cybermon infos
	- Small stuff
	
#### CTF / Tournament
- Most of the time went into the bot exploring the map (esp. the battles it encounters on it's way)
- We found 4 glitches during the CTF, about one per day, but did not realize they are actually built to give us more than a flag until the weekend and can be repeated.
- On the last day, we leveld 8 cybermon to level 255 and tried to give them strong attacks.
- In the last minutes before the tournament, we tried to give them powerful attacks, but could not complete this in time. That's why you have seen some `@` attacks etc. We also don't know how effective the moves `Sp▲ïÖ« Si` and `REMOVE_THIS` are.
- Also, we wanted to built an unkillable cybermon with the move `Sure Hit` (with a PP of 999) and try to struggel the enemy, but again .. time. Unsure if this would be possible and it can probably be prevented by swapping / items.
- We tought about (but did not) *exploit* the tournament by watching the enemies discord channel to see his current cybermon's moves and HP and see if the enemy will use an item / swaps cybermon in which case we could maybe react more efficiently.

#### Other stuff / Ideas
- [x] Enumerate the map images (hoped to find something for the *Wrong time wrong place* Glitch)
- [ ] Enumerate the battle images to get to know about other peoples cybermon
- [ ] Parse the two discord channels to know about other teams cybermon
- [ ] Automatically parse and analyze the battle reports to generate insights about attacks and cybermon
- [ ] There are a few items, we could not obtain yet (CM17, coin, completion_medal, quequequequeque, qz-, t, ありつなまぁおこいの). Maybe they are not implemented at all.
