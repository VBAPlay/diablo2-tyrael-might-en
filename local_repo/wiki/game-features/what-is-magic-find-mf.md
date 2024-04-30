## 👀 What is Magic Find? (MF)

### Magic Finding

#### Basics

* **arealvl**: The level of a specific area, the higher the level, the higher the arealevel. Mobs in this area have a minimum level equal to arealevel.

* **alvl**: Affix level. It means the prefixes and suffixes of an item at a level will determine what options that item has.

* **clvl**: Character level. This is only important when gambling.

* **ilvl**: Item level. Each item has its own level and can be determined by looking at the level of the mob that dropped the item (using c3po to check).

* **mlvl**: Mob level. Mlvl is used to determine whether it will drop an item with a high or low ilvl. Mlvl is always greater than or equal to a lvl. Champion mobs, ghostly mobs, etc., have mlvl = a lvl + 2. Random super unique and accompanying minions have mlvl = alvl + 3. Bosses and super uniques have their own mlvl.

* **qlvl**: Quality level of an item. Qlvl is used to determine what prefixes and suffixes an item can have.

#### Magic Finding

MF is your chance to find items. Your MF will increase when you wear an item with the line "Better Chance of Getting Magic Item".

The higher your MF, the higher the rate of dropping **magic + set + unique** items. Here is the MF calculation formula:

* Uniques = MF \* 250 / (MF+250)
* Sets = MF \* 500 / (MF+500)
* Rares = MF \* 600 / (MF+600)
* Magic = MF

This means that if you are wearing items with a total MF of 100%, your chance of picking up unique items will increase by 100\*250/(100+250) ~ 71%. Sets will increase by 83.3% and rares by 85.7%.```
Additionally, the number of players in the room also affects MF. If offline, typing player8 will give you the highest rate, but the monsters will also be stronger. Every time you defeat a monster, the game will determine what it drops for you. The more players there are, the higher the chance of monsters dropping items. Note that this only affects quantity, not item quality, but runes are an exception.When you kill a monster, the game will determine if it will drop an item or not. If it does, the game will identify what type of item it is, whether it's suitable for **mlvl**, taking your magic find (mf) into account to determine if it's unique, set, rare, magic, or normal.

Items that drop may have about 5% chance of being Ethereal, increasing either 50% enhanced damage if it is a weapon or 50% enhanced defense if it is armor, helm, etc. Items with "Indestructible" will not lose durability, some items always have this property, while others like Shadow Killer have both Ethereal and Indestructible, dealing double damage without breaking.

***Regarding MF for Summon & [Hireling](https://diablo2-en.com/hireling/), it will stack with your MF and that of your hireling (follower) for hirelings, and with your MF for summons.

![MF](https://i0.wp.com/tm.diablo2-en.com/app/uploads/2022/06/mf-300x254.png?resize=300%2C254&ssl=1)

![MFF](https://i0.wp.com/tm.diablo2-en.com/app/uploads/2022/06/MFF-1-300x232.png?resize=483%2C373&ssl=1)

MF chart by percentage from MF 1 > 1000%

### The Pit <a href="#the-pit" id="the-pit"></a>

Pits are areas with arealvl = 85. The monsters and chests here have a minimum level of 85.

* Act 1: The mausoleum (near quest 2).
* Act 1: Pits (a cave in Tamoe Highland).
* Act 2: Ancient Tunnel (found in Lost City).
* Act 4: River of Flame and Chaos Sanctuary.
* Act 5: From World Stone Keep onwards.

As you can see, the first 3 areas are the easiest for MF runs because the mobs in A1 and A2 are weaker compared to the Pits.
```* Andariel (Nightmare and Hell): The best boss for farming Stone of Jordan (Nightmare). In Hell, she has the highest chance to drop Gul.
* Council (Hell): Out of the 3 unique monsters, they are easy to defeat, run fast, and drop decent runes.
* Mephisto (Hell): The easiest boss to defeat, not very strong, low HP, and sorcerers can use the moat trick to trap him, more details will be explained later.
* Pindleskin (Hell): Quite an easy boss, slow, and simple to defeat. Each run only takes 20-30 seconds. You can do over 100 runs in an hour. Pindleskin is located in the nik temple, where Q4 is completed. Note that in order to farm this boss, DO NOT COMPLETE Q4 because once you finish or take the waypoint, the red portal will disappear—> no more runs

* Baal (Nightmare and Hell): Undoubtedly, this boss has the best drop rate in the game, but encountering it may take some time, nearly 6 minutes for each run.

* Countess: The rune drops are very good, and with high Magic Find (MF), Countess can also drop some valuable items. Below is a small table showing the rune drop probabilities when farming Countess:
  * Lo – 0.000312%
  * Ohm – 0.000468%
  * Vex – 0.000546%
  * Gul – 0.000819%
  * Ist – 0.074436%
  * Mal – 0.111654%
  * Um – 0.130038%
  * Pul – 0.195056%

* Chaos Sanctuary is another great place for farming, but you might need a hammerdin build to be able to farm it as the monsters there are tough, deal different elemental damage, and have curses, especially Iron Maiden and Amplify Damage.

### Rune Finding <a href="#rune-finding" id="rune-finding"></a>

#### Overview of Runes <a href="#so-luoc-ve-rune" id="so-luoc-ve-rune"></a>

A rune is a special type of item in Diablo II. It is similar to gems and jewels, but the main difference is that runes can create unique items with special properties by combining the right rune with the right item. It's important to note that the rune drop chance is not affected by a character's Magic Find (MF) but only by the mob's mlvl (monster level). Specifically:

| **mlvl** | **Possible Rune Drops** || -------- | ---------------------- |
| 66       | Vex                    |
| 69       | Lo                     |
| 74\[75]  | Ber                    |
| 78\[79]  | Cham                   |
| 83\[84]  | Zod                    |

The number in brackets applies to melee mobs. This means that a melee mob with mlvl 75 is required to drop a Ber rune. The more players in a game, the higher the chance to drop runes. When rune hunting, always remember: the more high-level mobs you kill, the better. All high-level mobs are equally valuable, and if you kill them all, the rune drop chance will be higher. The next section covers different strategies for rune hunting.

### The Countess

Introducing a bit about Countess. Countess has mlvl 82 and TC 66. TC 66 allows Countess to drop up to Lo rune and other lovely items such as thunderstroke, ormus robe, mara,... and so on. In addition, Countess also has the ability to drop special runes, allowing drops up to Ist rune. When Countess dies, the game first checks how many items Countess drops (up to 5, and this is called "no drop check").

If Countess drops all 5 items, the game will stop checking and it means that Countess's special rune check will be skipped. If Countess drops fewer than 5 items, the special rune check will be "noted," but a maximum of 3 runes. If you still don't understand, I will explain further as follows: when Countess dies, the first no drop check will start. If the no drop check fails, it means Countess drops 1 item like other mobs. If the no drop check succeeds, then the special rune check comes into play. Then continue with the 2nd no drop check and this happens 5 times for Countess to drop you 5 items. Maximum of 3 special rune checks. The "no drop" chance for a solo game is about 26%. When you play with more people, this chance decreases, so it is very likely that the special rune check will not be checked. Therefore: When planning to run Countess, solo is the best option.### What is Diablo 2 Game ?

Next is about the types of runes Countess can drop. This is divided into 2 types: regular (mentioned "no drop check" above) and special (this is Countess's unique rune drop ability). I only mention this at Hell level because Nightmare and Normal are not worth our attention. At this level, Countess drops the highest Lo rune for regular and Ist for special. The table below shows all the possible runes that Countess can drop:

* Lo – 0.000312%
* Ohm – 0.000468%
* Vex – 0.000546%
* Gul – 0.000819%
* Ist – 0.074436%
* Mal – 0.111654%
* Um – 0.130038%
* Pul – 0.195056%
* Lem – 0.259175%
* Fal – 0.388763%
* Ko – 0.514776%
* Lum - 0.772164%
* Io – 1.015448%
* Hel – 1.523172%
* Dol – 1.976007%
* Shael – 2.964010%
* Sol – 3.744013%
* Amn - 5.616020%
* Thul - 6.126567%
* Ort - 9.189850%
* Ral - 8.752238%
* Tal - 13.128357%
* Ith - 10.502686%
* Eth - 15.754029%
* Nef - 15.003837%
* Tir - 22.505755%
* Eld - 27.006907%
* El - 40.510360%

As mentioned above, the Lo rune falls under the regular drop category, so when playing in a crowded game with 8 players, the drop rate will be higher. Specifically, the chance of dropping a Lo rune in an 8-player game is 0.00056%. Therefore, if you want to find a Lo rune, playing in a crowded game increases your chances of success. However, with more players, the chance of dropping runes from special rune checks decreases. If you think you are lucky, play an 8-player game to run Countess. But if you prefer the "safe and steady" approach, solo play is the best. Personally, I still support solo play because the odds of cubing from Ist up to Lo are only 1/16. 
P/S: The above statistics are for LoD Original, and there may be some changes for D2VN, but I don't think they are significant.

Best running characters:

* Hammerdin: chaos sanc: mobs there are immune to all 4 elements, plus iron maiden and lower resist
* BlizSor: Mep, ancient turnel, can also run Andariel but it takes a while and is dangerous
* FireSor: Mep, Andariel (very fast), Andariel has -50 fire resistance, excellent for firesor".* LightSor: Pin, Shrek, Edrick, various super uniques, many minions, low health (if equipped with Infinity, still great for running chaos sanctuary)
* Winddruid: from Spider Forest to Lower Kurast, mobs here are numerous but have low health, perfect for wind".