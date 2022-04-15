The addon makes it possible to pick up money from dead stalkers.

Fully customizable! You can change ammount of money, dropchance and more.

How to config:

Open the gamedata/configs/lootmoney_cfg.ltx and edit the variables:

``` ini
[global_config]
	lootmoney_dropchance = 100 ; the chance of the npc to drop money. 100 = 100% 
	lootmoney_multiplier = 1 ; change if you want less or more money per corpse. 1 = default (~ 500 RU), 2 = double, 0.5 = half.
	lootmoney_getstalkermoney = false ; instead of a random money value, you get the ammount of money that the dead npc had.
	lootmoney_stash = true ; should it create random stashes?
	lootmoney_stashchance = 10 ; chance of spawning a random stash. 10 = 10%. Wont work if lootmoney_stash not enabled.
	lootmoney_message = true ; should it show the found money message?
	lootmoney_npc_collect = true ; should npcs be able to collect money from dead stalkers? you wont be able to collect from these bodies anymore.
	lootmoney_debug = true ; should it show you debug messages? (for dev only, it will fill your pda with debug informations)
[rank_money] ; here you can setup the default ammount of money that you will get per corpse for each rank. (only if lootmoney_getstalkermoney isnt enabled ofc)
	novice = 25,400 ; rank = min,max. if you want more money either change these values or the lootmoney_multiplier value.
	trainee = 50,400
	experienced = 200,500
	professional = 400,600
	veteran = 400,700
	expert = 500,800
	master = 500,900
	legend = 600,1000
[locale]
	current = "eng" ; change current language here [eng, rus, spa, ptbr ...]
	eng = "Found money:","Dead Stalker:"
	rus = "Найденные деньги:","Труп:"
	spa = "Dinero encontrado:","Stalker muerto:"
	ptbr = "Dinheiro encontrado:","Stalker morto:"
```
How to install: 

	Copy and replace this mod's gamedata folder into your game's gamedata folder.
