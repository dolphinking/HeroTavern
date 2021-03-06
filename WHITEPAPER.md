# WhitePaper of HeroTavern
<br />

## Content ##############
* [Introduction](#introduction)
* [Hero System](#hero-system)
  * [Hero Property](#hero-property)
  * [Hero Generation](#hero-generation)
  * [Hero Upgrade](#hero-upgrade)
  * [Triggering Events](#triggering-events)
  * [Hero Talent Wash](#hero-talent-wash)
  * [Hero Equipment](#hero-equipment)
* [Monster System](#monster-system)
  * [Monster Property](#monster-property)
  * [Monster Generation](#monster-generation)
  * [Monster Attributes](#monster-attributes)
  * [Monster Reward](#monster-reward)
* [Items System](#items-system)
  * [Item Property](#item-property)
  * [Item Generation](#item-generation)
  * [Item Acquiring](#item-acquiring)
  * [Item Slot and Kind](#item-slot-and-kind)
  * [Special Attributes](#special-attributes)
  * [Equip/Take off Item](#equip-and-take-off-item)
* [Hero Market](#hero-market)
  * [Sales](#sales)
  * [Auction](#auction)
  * [Hire](#hire)
* [Hero Factory](#hero-factory)
  * [Hero Recast](#hero-recast)
  * [Hero Dissolve](#hero-dissolve)
* [Battle Mode](#battle-mode)
  * [Team Members](#team-members)
  * [Fight Monster](#fight-monster)
* [Treasure Hunt](#treasure-hunt)
  * [Treasure Map](#treasure-map)
  * [Treasure Hunt Requirement](#treasure-hunt-requirement)
  * [Treasure](#treasure)
* [Future Development](#future-development)
  * [Tribe Cultivation](#tribe-cultivation)
* [Appendix](#appendix)
  * [Appendix I](#i)
  * [Appendix II](#ii)
  * [Appendix III](#iii)
 
---

## Introduction #######################
  Hero Tavern is a decentralized app that based on Ethereum platform. It is also a classic Simulation game. In the Game, player can acquire Heroes via many different ways. For example, Heroes can be purchased directly from the Market. Some of those Heroes are generated by System, and some are put up for sale by other players. After players own at least one Hero, they can begin journals of training and cultivating their Heroes. Every Hero has talent values; these values pretty much determine the combat power of a Hero at certain level. If players do not satisfy heroes’ talent, they can wash talent. In order to have higher Combat Power, Heroes can equip better equipment or cumulate Exp to upgrade Levels. Firstly, Players can assign Heroes to fight and suppress Monsters. Players will gain weaponry of Heroes and Heroes will gain Exp. Also, there is a chance that a Hero can be rescued from Monsters. Secondly, Players can buy Treasure Maps from Auctions, then Heroes is able to go for Treasure Hunts. It is possible to meet a new Hero during the Treasure Hunt beside the chance of finding rare items. Moreover, if Players do not like or need their Heroes, and also do not want to put Heroes on Market to sale, the Factory offers Players another way to deal with their useless Heroes. By adding items, Players can recast their Heroes to generate a new one. Alternatively, Players can just simply dissolve their Heroes into items and bottles of Exp. There are more fun and more surprises for you to explore in the Game. There are more unique Heroes are waiting for you to collect. New Adventures are on the way!

#
<br />

## Hero System ########################
### Hero Property
Heroes’ visible properties include Heroes’ name, occupation, Exp, levels and combat power. At the same time, there are two conditional properties “if Ready” and “is in a Team”.
<br />

### Hero Generation
We plan to release 1,000 heroes during Beta testing period. We will reserve about 5%. There will be about 20% selling on the Auction. The rest 75% can be purchased directly. These first round heroes tend to have relatively high levels. When we officially launch the game, another 2000-5000 heroes will be put up for sale. After that, system will generate 50 - 100 heroes per week. Total heroes will be generated by system are 88,888. Total heroes will be limited within 888,888. Beside system generation, heroes can be also possibly obtained via monster hunt.  According to monster's star rate and level, there is certain possibility to rescue a hero from the monster. 
<br />

### Hero Upgrade
When a Hero cumulates enough Exp to upgrade, upgrade option is active. According to current level, it will take a certain amount of time to upgrade. After the process is done, the Hero levels up and gains a certain amount of combat power.
<br />

### Triggering Events
Every Hero has an event triggering function, such as battle, treasure hunt, or upgrade etc. When certain events are called, Hero’s event clock will start. One Hero can only trigger one event at a time. Also, if a Hero is on sale or on hire, this Hero cannot trigger any event. When event is triggered, event duration is based on current conditions of the Hero. When cool down time equals to zero, the event is over.
<br />

### Hero Talent Wash
If players do not satisfy Hero current combat power, they can wash heroes’ hiding talent to change combat power. Talent Wash can cast certain amount of fee, which is related to heroes’ current levels. The result is random, can be either good or bad.
<br />

### Hero Equipment
Every Hero has 13 equipment slots. Details please check [appendix II](#ii).

#
<br />

## Monster System #######################
### Monster Property
Monster Properties include name, geno, star rate, ideal combat power required and attributes. When a monster is conquered, it will show its conqueror.
<br />

### Monster Generation
Monsters are all generated by the System. Generating rate depends on kill rate.
<br />

### Monster Attributes
All Monsters have fortes and weaknesses. To some occupations, these Heroes have power boost when they face certain monsters, but some other heroes are weaken when they fight the same monster.
<br />

### Monster Reward
Monsters have higher star rates and levels means that better trophies, more Exp and high possibility of rescuing a Hero.

#
<br />

## Items System #######################
### Item Property
Items’ Properties include name, kind, rarity, power increment and special attributes.
<br />

### Item Generation
We will gradually release 10,000 items during the official launch, and more items will be generated every week as well. Conquering monsters will also bring you a decent amount of items. There will not be any limitation on items, but logically the amount of items cannot exceed 4.2 billions.
<br />

### Item Acquiring
Items can be acquired via fighting monster, treasure hunt, dissolving Heroes, or they can be purchased directly from Market. 
<br />

### Item Slot and Kind
There are many kinds of items, such as weapon, helmet, armor etc. They can be equipped on different equipment slots. One slot matches one correct kind of item at once.
<br />

### Special Attributes
Some items can grant extra combat power to certain occupation.
<br />

### Equip and Take off Item
When Heroes equip items, the items’ Id will be recorded in the hero equipment slots. At the same time, Heroes will gain the power provided by items. If occupation matches items’ attributes, extra power will be added to the Hero. The condition of items will show the items are worn. Similarly, when items are taken off, the power that is provided by items will disappear and items are unworn. When an item is equipped, it cannot be traded.

#
<br />

## Hero Market #######################
### Sales
There are two parts of Sales in Market, Hero Sales and Item Sales. When Players start Sales, they need input starting price, buy now price and duration of the Sale. Buyers have two way to purchase, bid and buy. If bidding, winning bidder need to wait until the Sale is over to claim the Hero or the Item. When Heroes equip items, they cannot be traded.
<br />

### Auction
There are two aspects of Auction in Market as well, Monster Auction and Treasure Map Auction. These two Auctions are both generated by the System. Auctions will last from 24 hours. If no one bid during the auction time, the auction will become a sale.
<br />

### Hire
There is another section in Market- Hire. Player can put leisure Heroes on the Hire Market. If some Players need extra Heroes to fight Monsters, they can hire other Player’s Heroes in the Market.

#
<br />

## Hero Factory #######################
### Hero Recast
Player can use a Hero and up to 3 items to recast a new Hero. After recasting, all materials are gone and Player will get a new Hero.
<br />

### Hero Dissolve
Player can dissolve a hero, gaining 1-3 items and a bottle of Exp. The amount Exp in this bottle depends on the level of Hero that is dissolved.

#
<br />

## Battle Mode #######################
### Team Members
There is at least one hero in a team. The maximum is five heroes.
<br />

### Fight Monster
After getting the approval in the Auction, Player can send maximum certain amount of Heroes to fight Monster. When total combat power of the team reaches the ideal combat power required of the Monster, Player can get all the trophies. If not, then Player can only acquire part of the trophies.

#
<br />

## Treasure Hunt #######################
### Treasure Map
There are two visible attributes of treasure maps, serial number and Explore Length.
<br />

### Treasure Hunt Requirement
Treasure Hunt can be assigned to any leisure Hero.
<br />

### Treasure
There could be or could not be a treasure; There could be a lot or a little of treasure; There could be either lucky or unlucky.

#
<br />

## Future Development #######################
### Tribe Cultivation
After Heroes, we will release Tribe Cultivation Module. Players can build their own ligeances, and form their own armies. Also, it will connect to Hero Tavern Module, inviting heroes to join the Tribe Wars.

#
<br />

## Appendix #######################
### I
**Occupation**  
1. "Assassin"   
2. "Archer" 
3. "Cavalier"  
4. "Reaper"  
5. "Hermit"  
6. "Wizard"  
7. "Magician"  
8. "Knight"  
9. "Gladiator"  
10. "Hierophant"  
11. "Militiaman"  
12. "Warlock"  
13. "Ranger"  
14. "Samurai"  
15. "Ninja"  
16. "Sword Master"  
17. "WitchBlade"  
18. "Warrior"  
19. "Slave"  
20. "Saber"  
21. "Lancer"  
22. "Berserker"  
23. "Dark Lord"  
24. "Priest"  
25. "Sorcerer"  
26. "Arch Mage" 

<br />

### II
**Equipment Category**  
1. "Weapon"  
2. "OffHand"  
3. "UpperArmor"  
4. "LowerArmor"  
5. "Helmet"  
6. "Boots"  
7. "Skills"  
8. "Gloves"  
9. "Sundries"  
10. "Earrings"  
11. "Extra Accessories"  
12. "Necklace"  
13. "Ring"  

<br />

### III
**Item Rarity**  
1. "Damaged"  
2. "Common"  
3. "Unusual"  
4. "Rare"  
5. "Epic"  
6. "Legendary"  
7. "Unique"  

---
