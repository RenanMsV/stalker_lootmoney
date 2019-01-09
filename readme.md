The addon makes it possible to pick up money from dead stalkers.

Fully customizable! You can change ammount of money, dropchance and more.

How to config:

Open the gamedata/configs/lootmoney_cfg.ltx and edit the variables:

	```
	lootmoney_dropchance = 100 ; the chance of the npc to drop money. 100 = 100% 
	lootmoney_multiplier = 1 ; change if you want less or more money per corpse. 1 = default (~ 500 RU), 2 = double, 0.5 = half.
	lootmoney_stash = true ; should it create random stashs?
	lootmoney_stashchance = 10 ; chance of spawning a random stash. 10 = 10%. Wont work if lootmoney_stash not enabled.
	lootmoney_message = true ; should it show the found money message?
	lootmoney_npc_collect = true ; should npcs be able to collet money from dead stalkers? you wont be able to collect from those bodies anymore.
	lootmoney_debug = false ; should it show you debug messages? (for dev only, it will fill your pda with debug informations)
	```
How to install: 

	Copy and replace this mod's gamedata folder into your game's gamedata folder.