# CODENAME: MUILS

What is "MUILS"? 
Muils is a YouTube episodic series where we play a heavily modified version of GTA 5 also known as "Real Life Mod"

## **Mods list for Bestassio's Moving Up In Los Santos**
A lot of mods are combined for Moving Up In Los Santos episodes to exist, this project started way back in April of 2024 and keeps on expanding with each day. Due to the size of the mods which are used in MUILS episodes, and not to spoil what's gonna happen next, this page will be updated with each episode. (Currently on episode 40)


Some of the mods which I use in the videos are no longer available, and while I do have them backed up, I don't want to distribute them, as they were removed for a reason. (Either a DMCA take down, or mod creator no longer wanting to work on them) Althrough you can find them elsewhere (be careful. and I don't recommend or endorse trying to get them elsewhere) a lot of mods which are un-available are really *unstable* and usually might require some maintenence.
For the mods, which are un-available, I will try my best to find a replacement, as soon as one is available.

Moving Up In Los Santos is running on older version of the game (GTA ONLINE Chop Shop Update *but modified to have latest content*), mostly because current latest version breaks a lot of older mods which are a necessary  

## Table of contents:

[Prerequisites](#Prerequisites)

[Essentials](#Essentials)

[Scripts](#Scripts)

[Enviroment](#Enviroment)

[Weapons](#Weapons)

[Vehicles](#Vehicles) WIP

# **Main mods:**

## Prerequisites:

### [ScriptHookV](http://www.dev-c.com/gtav/scripthookv/)

 Allows you to load scripts
 NOTE: Alexander blade (developer of scripthook) has been doing some.. shady stuff recently, as the latest version of ScriptHooKV contains new UI elements which no-one asked for, huge advertising banner, and some more inconveniences which break some stuff.
 Blade has recently announced that he will have the old version available soon, without the clutter, but it's questionable for how long that's going to be..

### [ScriptHookVDotNet](https://github.com/scripthookvdotnet/scripthookvdotnet/releases) / [ScriptHookVDotNet Nightly](https://github.com/scripthookvdotnet/scripthookvdotnet-nightly/releases)

Allows you to load scripts, and reload them, when they break
Nightly is recommended, but in some cases you might need the "normal" DotNet

### iFruitAddon2
 
Allows mods which require a phone to work. Usually included with the mods which require it
 
### [LemonUI](https://www.gta5-mods.com/tools/lemonui)
 
Allows mods which require interaction menu's to work
 
### [NativeUI](https://github.com/Guad/NativeUI/releases)
 
Allows mods which require interaction menu's to work. Older version of LemonUI, but some older mods might need it
 

### [Game Config](https://www.gta5-mods.com/misc/gta-5-gameconfig-300-cars)
 
Allows your game to not crash after installing 3 mods
 
 
Do note: While this is great as a baseline, it's mostly configured for car mods.
Adding too many weapon mods might still cause your game to crash.
Therefore you need to edit specific values to fix it.
In the case of addon weapons.
You need to add/increase this on line 312 of your game config:
```<Item> <PoolName>CPickupPlacement</PoolName> <PoolSize value="280"/></Item> ```
Just make sure to follow the formatting of how other lines are written

You might need to adjust other values, depending on what you have installed, or planning to install, that's where Pool Manager (listed below) comes in.
 
### [Heap Adjuster](https://www.gta5-mods.com/tools/heapadjuster)
 
Allows your game to not crash after installing few mods
 
### [PackfileLimit Adjuster](https://www.gta5-mods.com/tools/packfile-limit-adjuster)
 
Allows your game to not crash after installing few mods
 
### [Weapons Limit Adjuster](https://www.gta5-mods.com/tools/cweaponinfoblob-limit-adjuster)
 
Allows your game not to crash after installing weapon mods
 
### [Pool Manager](https://www.gta5-mods.com/tools/poolmanager-dilapidated)
 
Tells you what crashed your game, and what you need to change in game-config.

If upon installing a mod, your game crashes, and Pool manager doesn't show any error messages, that means, that, that mod is broken beyond fixing, and needs to be updated by it's developer
 

## Essentials:
These are essential. Without these, most of the episodes would be impossible or a huge pain 

### [TrainerV](https://www.gta5-mods.com/scripts/simple-trainer-for-gtav)
 
 Mostly used for loading the character and it's clothing 
 
### [Menyoo PC OG](https://www.gta5-mods.com/scripts/menyoo-pc-sp) / [Menyoo PC 2.0](https://www.gta5-mods.com/scripts/menyoo-2-0)
  
Mostly used for loading weapon loadouts with addon weapons or vehicles if persistance mod fails
 
 
I personally use the outdated OG version, but feel free to use 2.0
 
### [Rampage Trainer](https://www.gta5-mods.com/scripts/rampage-trainer)
 
Has some features which sometimes become useful
 
### [Time Scaler](https://www.gta5-mods.com/scripts/time-scaler)
 
Allows time-lapses to happen
 
### [Scene Director](https://www.gta5-mods.com/scripts/scene-director)
 
Allows cinematic shots to happen
 
### [Character Creation Script](https://www.gta5-mods.com/scripts/character-creation-script)
 
Allows to easily swap characters or clothing
 
### Character Swap -  Un-available, mod creator has deleted this mod 
 
Gives any character the all the featues that the main 3 characters have, essentially allowing to use any character with money, and other features that main characters have

There is an alternative, it's called [Playable Online Character](https://www.gta5-mods.com/scripts/playable-online-character) this mod, does essentially what Character swap did, but with a lot of stuff built in, like dealerships, working shops and more!

```
At this very moment, I would not be able to assist you with this mod, as I couldn't get it to work in time (most likely a me issue, as it's most likely colliding with something that I have installed) 
I would say give it a shot, as the mod is more stable then Character swap, and isn't as complicated.
```

## Scripts:

### [Enable All Interiors](https://www.gta5-mods.com/scripts/enable-all-interiors-wip)
  
Collides with a lot of MLO mods. 
And having this mod enabled while having more then 2 mlo's installed will cause map loading issues
 
### ASUniverse -  Mod un-available 

This mod was removed by it's creator, but there are some signs of the mod coming back sometime
 
Grab service, Jobs, Maze Bank account

Alternatives:

[JobsV](https://www.gta5-mods.com/scripts/jobsv) Jobs replacement

[Banking System](https://www.gta5-mods.com/scripts/fleeca-banking-system) a bit buggy, but it does the job.

[Account In Bank](https://www.gta5-mods.com/scripts/accountinbank) 

[Ride Share](https://www.gta5-mods.com/scripts/enhanced-taxi-missions) Cool taxi/uber mod, which has some great features, imo the best uber mod

[Lift Ride Share](https://www.gta5-mods.com/scripts/rideshare) Uber/Lift mod, has car ratings.

### [Persistance II](https://www.gta5-mods.com/scripts/i-m-not-mental-s-persistance-mod)
  
Allows you to lock your car, and save it
 
### [Seatbelt V](https://www.gta5-mods.com/scripts/seatbeltmod)
 
Keeps you from flying every time you get into a car accident
 
### [IV Style Exit](https://www.gta5-mods.com/scripts/iv-style-exit-vehicle-net)

[Alternative Version if one above doesn't work](https://www.gta5-mods.com/scripts/iv-style-exit-vehicle-net-optimized)
 
Be able to control if car engine stays on or off when exiting a vehicle
 
### [Automatic Vehicle Door Opener](https://www.gta5-mods.com/scripts/automatic-vehicle-door-opener)
 
Open or close car doors with a push of a button
 
### [Nitro](https://www.gta5-mods.com/scripts/nitro)
 
Car go brr fast, also has "animation" when using Nitro
 
### [Auto Center Steering Fix](https://www.gta5-mods.com/scripts/auto-center-steering-patch-temp-fix)
 
Prevents your wheels from auto-centering when exiting your vehicle
 
### [Winch](https://www.gta5-mods.com/scripts/winch-for-all-vehicles)
 
Allows you to winch and tow cars
 
### [Flatbed](https://www.gta5-mods.com/scripts/flatbed-script)
 
Allows you to put vehicles on a flatbed and tow them
 
### [Explosion-On-Crash disabler](https://www.gta5-mods.com/scripts/explosion-on-crash-disabler)
 
Allows cars to not go boom when you land on your roof
 
### [Repair At Home](https://www.gta5-mods.com/scripts/repairathome)
 
Repair your vehicle anywhere
 
### [Wash At Home](https://www.gta5-mods.com/scripts/washathome-glubbfreund)
 
Wash your vehicle anywhere
 
### [Lockpicking](https://www.gta5-mods.com/scripts/lock-picking)
 
Allows you to lockpick locked cars Mafia II style
 
### [Better Chases](https://www.gta5-mods.com/scripts/better-chases)
 
Makes police chases a little more realistic
 
### [Pull Me Over](https://www.gta5-mods.com/scripts/pull-me-over-daimian)
 
Allows police to pull you over, instead of them shooting you right away
 
### [BinocularsV](https://www.gta5-mods.com/scripts/binocularsv)
 
Allows you to use binoculars
 
### [Stance](https://www.gta5-mods.com/scripts/stance)
 
Allows you to crouch/prone
 
### [Addon Weapons](https://www.gta5-mods.com/scripts/addonweapons)
 
Allows you to purchase Add-On weapons, and save them when you leave and restart the game.. sorta.. I still wouldn't trust it 100%
 
### [GameplayFixesV](https://www.gta5-mods.com/scripts/gameplayfixesv)
 
A lot of fixes and QOL improvements
 
### [Don't Writhe](https://www.gta5-mods.com/scripts/don-t-writhe)
 
NPC's don't writhe and die right away from any impact
 
### [Throwing Knifes](https://www.gta5-mods.com/scripts/throwing-knives)
 
Allows you to throw your knifes
 
### [Phone Detonation](https://www.gta5-mods.com/scripts/phone-detonation)
 
Allows sticky bombs to be triggered by phone contact, instead of interaction button

### [Hostages](https://www.gta5-mods.com/scripts/hostagesv-net)
 
Allows you to take people hostages..

### [Dynamic Indicators](https://www.gta5-mods.com/scripts/dynamic-indicators)

Only supports a few cars

### [Action Gear](https://youtu.be/6C7A-5ryMgc)

Additional interaction gear for some actions ( I used it for equipping armor)

• [First Featured in Episode 17 of "Moving Up In Los Santos](https://youtu.be/6C7A-5ryMgc)

### [Casino](https://www.gta5-mods.com/scripts/diamond-casino-resort-business)

Adds fully functional Casino.

• [Featured in Episode 29 of "Moving Up In Los Santos](https://youtu.be/lNOsDB39W-k?si=TN3TlM5OhAukR0AC)

### [SPIKE STRIPS](https://www.gta5-mods.com/scripts/nfs-spikes-mod-work-in-car-on-foot)

• [Featured in Episode 35 of "Moving Up In Los Santos](https://youtu.be/nvJ0aE8DV0A?si=wE9PH-A9Ow5N1ciy)

## Earn and spend money:

### [Wheelman](https://www.gta5-mods.com/scripts/wheelman)
 
Rob stores with a crew.
 
• [Featured in Episode 1 of "Moving Up In Los Santos](https://youtu.be/hDrbQ1dGHS4)


### [Vlad's Export Garage](https://www.gta5-mods.com/scripts/vehicle-theft-missions-net)
 
Find steal and deliver cars for $.
Includes special missions - 
 
• [Featured in Episode 2 of "Moving Up In Los Santos"](https://youtu.be/iRI1DtHAJdc)


### [Dismantle Cars](https://www.gta5-mods.com/scripts/car-dismantling) -
 
Allows you to dismantle cars for $ 
 
• [Featured in Episode 3 of "Moving Up In Los Santos"](https://youtu.be/w2RuiOV4V6g)

### [Premium Deluxe Motorsport Dealership](https://www.gta5-mods.com/scripts/premium-deluxe-motorsports-car-shop)
 
Ultimate and BEST dealership mod.
Fully customizable. 
Allows you to add any car you want. 
Customize all prices, and more!
 
• [Featured in Episode 3 of "Moving Up In Los Santos"](https://youtu.be/w2RuiOV4V6g)

### [House Robberies](https://www.gta5-mods.com/scripts/house-robberies)
 
Allows you to rob houses. 
Steal:
TV's
Sound Systems
Art
Cash
Phones
Jewellery
Contents from safes
(Includes a safe cracking mini-game)
 
• [Featured in Episode 4 of "Moving Up In Los Santos"](https://youtu.be/njNFKDEHNSE)


### [LS Life](https://www.gta5-mods.com/scripts/ls-life)
 
Allows you to become a full time drug dealer. 
Althrough this mod might collide with most other mods. 
Recommended to use as standalone or with less mods 
(In my experience it collided with Persistance II, so if you are using that, change car lock keybind)
 
• [Featured in Episode 5 of "Moving Up In Los Santos"](https://youtu.be/dARdNsMDXR8)

### [ATM Robberies](https://www.gta5-mods.com/scripts/atm-robberies)
 
Allows you to rob ATM's
 
• [Featured in Episode 6 of "Moving Up In Los Santos"](https://youtu.be/mTSf0mYHiWA)

### [Convoys and Other hits](https://www.gta5-mods.com/scripts/convoys-and-other-hits)
 
Works, but can be problematic at times.
Mostly is good, if you don't stress test it / spam it.

If it breaks, reload all scripts with scripthook and it should work
 
• [Featured in Episode 6 of "Moving Up In Los Santos"](https://youtu.be/mTSf0mYHiWA)

### [Stockage Stickups](https://www.gta5-mods.com/scripts/stockade-stickups)

Allows you to rob stockades in freemode, similar to Convoy's and other hits, but this one is not a mission and only contains this "freemode" event

• [Featured in Episode 6 of "Moving Up In Los Santos"](https://youtu.be/mTSf0mYHiWA)

### [Hitman](https://www.gta5-mods.com/scripts/hitman-mod-updated-reloaded)
 
Works perfectly, as long as you install it properly, and follow all requirements
Also, when you start up the game, don't forget that, you need to press a hotkey (F10 by default) to make the contact appear in phone
 
• [Featured in Episode 7 of "Moving Up In Los Santos"](https://youtu.be/RBPAOvchIt8)
• [Featured in Episode 35 of "Moving Up In Los Santos](https://youtu.be/nvJ0aE8DV0A?si=wE9PH-A9Ow5N1ciy)

### [Paleto Bay Heist](https://www.gta5-mods.com/scripts/paleto-bay-bank-heist)
 
Pretty self-explanatory, paleto bank heist, has some variations, so it's not the same every time.
 
• [Featured in Episode 8 of "Moving Up In Los Santos"](https://youtu.be/Ck7jjGp3w0o)

### [Global Invest](https://youtu.be/8zJUx3L3jLk)
 
Invest in any property that is available, or add your own ones.
 
• [Featured in Episode 10 of "Moving Up In Los Santos"](https://youtu.be/8zJUx3L3jLk)

### [Sharmoota Heist](https://www.gta5-mods.com/scripts/sharmoota-art-heist)

Good heist, a bit too easy though

• [Featured in Episode 11 of "Moving Up In Los Santos"](https://youtu.be/7fowy98VgD4?si=YqPLBriWUb7MtIPH)

### [Bank Of Liberty Heist](https://www.gta5-mods.com/scripts/bank-of-liberty-heist)

Rob the bank of liberty, fun little heist mod, that is a bit too easy
Requires Bank of Liberty MLO (which can be found below, or in the mod description)

• [Featured in Episode 15 of "Moving Up In Los Santos"](https://youtu.be/S1tfQsuCBt4)

### [Simmy's Repo Service](https://www.gta5-mods.com/scripts/simmy-s-repo-service-los-santos)

Brand new mod, pretty cool, feels like some of the jobs from FiveM, but they are hand-crafted.

• [Featured in Episode 16 of "Moving Up In Los Santos"](https://youtu.be/K0cdeiVqFAo)

### [Car flipping business AKA "Garage Business"](https://www.gta5-mods.com/scripts/garage-business)

Pretty cool mod, which allows you to steal, race, sell cars, either stolen or your own, you can't set sell price though.

• [Featured in Episode 18 of "Moving Up In Los Santos"](https://youtu.be/boZ900RxFik)

### [Ride Share](https://www.gta5-mods.com/scripts/enhanced-taxi-missions)

Cool taxi/uber mod, which has some great features

• [Featured in Episode 21 of "Moving Up In Los Santos"](https://youtu.be/0zsaquAd5iY)

### [Lift Ride Share](https://www.gta5-mods.com/scripts/rideshare)

Uber/Lift mod, has car ratings.

• [Featured in Episode 21 of "Moving Up In Los Santos"](https://youtu.be/0zsaquAd5iY)

### [Valet](https://www.gta5-mods.com/scripts/valet-missions)

Great little mod which allows you to work as a valet
It is an older mod, so it does require you to have nightly version of scripthook

• [Featured in Episode 22 of "Moving Up In Los Santos"](https://youtu.be/YdiBwaRsXS8)

### [Sell Vehicles at Simeon](https://www.gta5-mods.com/scripts/sell-cars-at-simeon-s-premium-deluxe-autosport-v1-0-by-the-paradox)

Amazing mod to sell owned or stolen vehicles.
A little buggy sometimes

• [Featured in Episode 23 of "Moving Up In Los Santos"](https://youtu.be/zdocilupl_w)

### [The Mob](https://www.gta5-mods.com/scripts/the-mob)

Great work for mob/mafia mod.
Missions get triggered automatically, so sometimes you might need to wait.

• [Featured in Episode 24 of "Moving Up In Los Santos"](https://youtu.be/f0IMjEqeL2k)

### [Counterfit Warehouse Heist](https://www.gta5-mods.com/scripts/gta-offline-counterfit-cash-warehouse-heist-trailer)

Great little heist mod, customizable.

• [Featured in Episode 25 of "Moving Up In Los Santos"](https://youtu.be/PU4aXMGNzQY?si=8hBWTgjH6FHsgrRr)

### [Burglar Mod](https://www.gta5-mods.com/scripts/simmy-s-burglar-mod)

• [Featured in Episode 26 of "Moving Up In Los Santos"](https://youtu.be/EwbRnsGknc0?si=tvJmDyLBaAfNCfTP)

### [Property Manager - Buy / Rent / Maintain Houses](https://www.gta5-mods.com/scripts/propertymanager)

Allows you to buy / rent / maintain specific properties (add-on houses)

• [Featured in Episode 27 of "Moving Up In Los Santos"](https://www.youtube.com/watch?v=Hr8vYG8mP8w)

### [Meth empire - Cook mod](https://www.gta5-mods.com/scripts/meth-empire)

Pretty cool "business" which allows you to cook, there's upgrades and missions, pretty cool

• [Featured in Episode 27 of "Moving Up In Los Santos"](https://youtu.be/WZr0CV4BHA8?si=YBd63fCfxgEAi0n1)

### [Lottery](https://www.gta5-mods.com/scripts/san-andreas-lotto)

Adds the ability to buy lottery tickets.

• [Featured in Episode 29 of "Moving Up In Los Santos](https://youtu.be/lNOsDB39W-k?si=TN3TlM5OhAukR0AC)

### [Simmy's DineDash Job](https://www.gta5-mods.com/scripts/simmy-s-dinedash-job)

Door Dash /  Uber Eats delivery job.

• [Featured in Episode 31 of "Moving Up In Los Santos](https://youtu.be/Qg5g1Xi72K4?si=-rvn45enhj6O7aBU)

### [Gas Station Job](https://www.gta5-mods.com/scripts/gasstation-skyz)

• [Featured in Episode 32 of "Moving Up In Los Santos](https://youtu.be/trVUpqfyE7w)

### [JobsV](https://www.gta5-mods.com/scripts/jobsv)

Great little mod, get a degree, get a job, some jobs have minigames, while others just skip time.

• [Featured in Episode 36 of "Moving Up In Los Santos](https://www.youtube.com/watch?v=jJwMKmmmnQM)

### [The Pacific Standard Heist](https://www.gta5-mods.com/scripts/the-pacific-standard)

Amazing heist mod which brings the pacific standard job heist from online to SP, with the freedom of "choose your own getaway"

• [Featured in Episode 38 of "Moving Up In Los Santos](https://youtu.be/_onOfAO8re0)

### [Golden Train Heist](https://www.gta5-mods.com/scripts/the-golden-train-heist)

Pretty simple heist.

• [Featured in Episode 39 of "Moving Up In Los Santos](https://www.youtube.com/watch?v=5S1V0yyRmas)

## Enviroment

My personal favorite graphics mod is - 

### [VisualV](https://www.gta5-mods.com/misc/visualv)
 
There are a lot of great graphics mods, and you might ask why I went with VisualV, and the answer is simple:
It's a nice looking graphics mod, which is vanilla friendly, and most importantly light-weight.
GTA 5 is a old game, which has it's limitations. 
And running 400 car mods and a bunch of script mods + interior/building mods,
While having all online interiors loaded at all times really adds up quickly.
That can either break the game and it's limits or break your performance.
That's why while there are nicer looking graphics mods, this one is the best if you want more gameplay.

### [Forests Of San Andreas](https://www.gta5-mods.com/maps/forests-of-san-andreas-revised)

The famous forests mod, used by a lot of content creators and FiveM RP servers. Also includes some additions to the map, such as the wooden shack in Paleto forest.

### [Realistic Blood](https://www.gta5-mods.com/misc/realistic-blood-v)
 
Makes blood go places
 
### [Real Immersive Gun Sounds 1.2](https://www.gta5-mods.com/weapons/real-emersive-gun-sounds)
 
Makes guns sound more.. fun (also includes tire sounds and some other misc sounds)

Note: I use 1.2 version and not 1.3.
1.2 also has a issue with rifles not shooting.
Which can be fixed by downloading a different rifle sound

## Christmas Related

### [Enhanced Bridges](https://www.gta5-mods.com/maps/enhanced-bridges-v-ymap)

Good looking bridge decorations

### [Festive Streetlights V](https://www.gta5-mods.com/maps/festive-streetlights-v)

Good looking street light decorations

## Interiors 
Do note: Some or all of these interiors might cause issues, if you are running them with "Enable All Interiors" or Multiplayer Maps enabled. (The closer an interior is to a GTA ONLINE interior, the more likely it is, that it will make map not render anymore. When using these maps, I recommend either temporarily removing EAI mod, or re-enabling and disabling MP Maps in Simple Native Trainer
### [Marabunta Grande House](https://www.gta5-mods.com/maps/mlo-marabunta-grande-fivem-sp)
 
Amazing house mod for starting out located right next to Lester's house.
 
• [Featured in Episode 3 of "Moving Up In Los Santos"](https://youtu.be/w2RuiOV4V6g)

### [Casey's Diner GTA IV Interior](https://www.gta5-mods.com/maps/gtaiv-diner-mlo-interior-mlo)
 
Amazing interior perfectly ported from GTA IV and it fits in the game flawlessly 
 
• [Featured in Episode 11 of "Moving Up In Los Santos"](https://youtu.be/7fowy98VgD4)

### [Abandoned Laundromat](https://www.gta5-mods.com/maps/abandoned-laundromat-interior-singleplayer-fivem-gtadps)
 
Really cool, but small interior, can be used for oddly specific things, like businesses or kidnapping people 
 
• [Featured in Episode 11 of "Moving Up In Los Santos"](https://youtu.be/7fowy98VgD4)

### [Forest Mansion](https://www.gta5-mods.com/maps/forest-mansion)

Probably my favorite mansion.

• [Featured in Episode 27 of "Moving Up In Los Santos"](https://www.youtube.com/watch?v=Hr8vYG8mP8w)

### [Sanders Motors](https://www.gta5-mods.com/maps/mlo-sanders-motors-dealership-and-garage-sp-add-on)

Great spacious dealership. Branded as "Motors" instead of "Motorcycles" like other dealership mods at this place, which allows this to be any dealership

• [Featured in Episode 14 of "Moving Up In Los Santos"](https://youtu.be/NPptlGUzFc0)

### [Bank Of Liberty MLO Interior](https://www.gta5-mods.com/maps/mlo-gta-iv-bank-of-liberty-interior-fivem)

Cool port of Bank of Liberty City interior from GTA4.

• [Featured in Episode 15 of "Moving Up In Los Santos"](https://youtu.be/S1tfQsuCBt4)

### [Playboy Mansion](https://www.gta5-mods.com/maps/playboy-mansion-with-interior)

The only playboy mansion available at this moment

• [Featured in Episode 40 of "Moving Up In Los Santos"](https://youtu.be/wfh2u70HMc4?si=xzyzmeCnaXEpxq2S)

## Weapons

## PISTOLS:

### [Glock 20](https://www.gta5-mods.com/weapons/glock-20-sp-fivem)

The most used gun in the episodes, pretty fun, has decent amount of attachments.

### [Glock 19](https://www.gta5-mods.com/weapons/glock-19-gen-4-sp-fivem)

Same as one above, but different model, and color.

### [Service Pistols](https://www.gta5-mods.com/weapons/vom-feuer-service-pistol-pack-add-on-animated-tints-lore-friendly)

Second most used gun in the episodes. Includes 3 variants. 9mm, Full-Auto, and .45 ACB. Mostly used for the auto variant in the episodes

### [Pistol .44](https://www.gta5-mods.com/weapons/hawk-little-pistol-44-add-on-sound-animated-tints-lore-friendly)

Pretty cool pistol, first seen in Liberty City (GTA 4 TBOGT) hasn't been used in episodes yet, but it will

### [Five-7](https://www.gta5-mods.com/weapons/eft-fn-fiveseven)

Amazing pistol, hasn't been used in episodes yet, but it will

### [Five-7 509](https://www.gta5-mods.com/weapons/fn-509-mrd-le-add-on-animated)

Amazing pistol, hasn't been used in episodes yet, but it will

### [Pindad G2 Pistol](https://www.gta5-mods.com/weapons/pindad-g2-pistol-add-on-fivem)

Cool pistol, was used when trying to escape from the mafia in North Yankton

### [Vom Feuer CVP-9](https://www.gta5-mods.com/weapons/vom-feuer-cvp-9-lore-friendly-add-on-animated-tints)

Cool pistol, hasn't been used in episodes yet, but it will.

### [Dartgun](https://www.gta5-mods.com/weapons/dart-pistol-add-on-fivem-hud-icon)

Shoots darts, pretty cool

### [Auto-Crossbow](https://www.gta5-mods.com/weapons/shrewsbury-auto-crossbow-add-on-sound-animated-tints-lore-friendly)

It's not a pistol, but it is. Auto-Crossbow, pretty cool thing to have.


## Melee and Misc:

### [PocketLight](https://www.gta5-mods.com/weapons/sidio-pocket-flashlight-sp-fivem-add-on-hud-icon-customization-w)

Small little flashlight, has been used in some specific episodes, to light up stuff, like flashlights do. Great customization.
Allows White light (normal) Red light, and UV
Also comes in a traffic wand shape.

### [Colbaton](https://www.gta5-mods.com/weapons/prolaps-telescopic-baton-sp-fivem-add-on)

Honestly, a great baton, probably the best one available, has extend animations and stuff. hasn't been used in episodes yet, but it will have it's use.. soon enough..

### [Thermite Bomb](https://www.gta5-mods.com/weapons/thermite-bomb-add-on-sound-anim-lore-friendly)

Thermite Bomb, hasn't been used in episodes yet, but it will have it's use.. soon enough..

### [Wooden Bat](https://www.gta5-mods.com/weapons/wooden-bat-add-on)

Wooden bat, you know, in case the metal one isn't good enough. Hasn't been used in episodes yet, but it will have it's use.. soon enough..

### [Stalker Knife](https://www.gta5-mods.com/weapons/s-t-a-l-k-e-r-knife-add-on)

Knife from "Stalker" games, in case, you want a knife from Pripyat


## SMG:

### [Extended SMG](https://www.gta5-mods.com/weapons/shrewsbury-extended-smg-gold-smg-add-on-sound-animated-tints-lore-friendly)

Pretty cool SMG, originally first seen from Liberty City (GTA IV) as Yusuf's gun. Hasn't been used in episodes yet, but it will

## Rifles:

### [Combat Rifle](https://www.gta5-mods.com/weapons/vom-feuer-combat-rifle-add-on-animated-tints)

Cool lookin rifle, shoots like a rifle should. Sometimes may or may not have been used in specific episodes

### [M16A4](https://www.gta5-mods.com/weapons/m16a4-add-on-animated)

Cool lookin rifle, shoots like a rifle should. Has some attachments sometimes. May or may not have been used in specific episodes

### [M6IC](https://www.gta5-mods.com/weapons/modular-lwrc-m6ic)

Cool lookin rifle, shoots like a rifle should. Has some attachments sometimes. May or may not have been used in specific episodes

### [Military Carbine](https://www.gta5-mods.com/weapons/vom-feuer-military-carbine-lore-friendly-add-on-replace-animated-tints)

Cool lookin rifle, shoots like a rifle should. Sometimes may or may not have been used in specific episodes

### [KS1](https://www.gta5-mods.com/weapons/kac-ks-1)

Cool lookin rifle, shoots like a rifle should. Sometimes may or may not have been used in specific episodes

### [PP-19-01 Vityaz](https://www.gta5-mods.com/weapons/pp-19-01-vityaz-add-on)

It's a rifle, it shoots. Hasn't been used in episodes yet, but it will..

### [Israeli Rifle](https://www.gta5-mods.com/weapons/shrewsbury-israeli-rifle-add-on-animated-tints-lore-friendly)

It's a rifle, it shoots. Hasn't been used in episodes yet, but it will..

### [Scar-H Battle Rifle](https://www.gta5-mods.com/weapons/scar-h-battle-rifle-add-on)

It's a battle rifle, it shoots. Hasn't been used in episodes yet, but it will..

## Shotguns:

### [Riot Shotgun](https://www.gta5-mods.com/weapons/shrewsbury-riot-shotgun-add-on-animated-tints-lore-friendly)

It's a shotgun, but it doesn't kill people.



## Snipers:

### [Assault Sniper](https://www.gta5-mods.com/weapons/vom-feuer-assault-sniper-add-on-animated-tints-lore-friendly)

Cool Sniper. Sometimes may or may not have been used in specific episodes

### [VSS SNIPER RIFLE](https://www.gta5-mods.com/weapons/add-on-gun-vss-vintorez-special-sniper-rifle)

Fully-auto sniper, hasn't been used in episodes yet, but it will.



## Vehicles:
Vehicles with * sign have some slight issues, like mentioned in the showcase video


Due to the huge amount of vehicles in Moving Up In Los Santos, this list is still work in progress. Check back soon!

### [Audi RS6 2016](https://www.gta5-mods.com/vehicles/2014-audi-rs6)

### [Audi RS6 C8 2021](https://www.gta5-mods.com/vehicles/2021-audi-rs6-sedan-c8-add-on)

### [Audi R8 2020](https://www.gta5-mods.com/vehicles/audi-r8-2020-addon)

### [BMW M4 Competition G82 2021*](https://www.gta5-mods.com/vehicles/2021-bmw-m4-competition)

### [Dodge RAM LIMITED 2016](https://www.gta5-mods.com/vehicles/dodge-ram-limited-2016-1-0-replace-tuning-addon)

### [Ford Crown Victoria 2011](https://www.gta5-mods.com/vehicles/ford-crown-victoria-2011-add-on-replace-animations-lods)

### [Ford Crown Victoria 1998-2011](https://www.gta5-mods.com/vehicles/1998-ford-crown-victoria-lx-replace-unlocked)

### [Ford Explorer](https://www.gta5-mods.com/vehicles/ford-explorer-u502-2013-replace-ao-template)

### [Mercedes E55 AMG](https://www.gta5-mods.com/vehicles/mercedes-benz-e55-amg-add-on-replace-tuning-realistic-sound-handling)

### [Mercedes AMG S65](https://www.gta5-mods.com/vehicles/mercedes-s65-w222)

### [Mercedes S600](https://www.gta5-mods.com/vehicles/mercedes-s600-w220)

### [Mercedes E63S 2021](https://www.gta5-mods.com/vehicles/2021-mercedes-amg-e63-s-4matic-w213-facelift-add-on-fivem-extras)

### [Mercedes G63 2012](https://www.gta5-mods.com/vehicles/2012-mercedes-benz-g-63-amg-add-on-tuning-extras-vehfuncs-v)

### [Ford F150 Raptor](https://www.gta5-mods.com/vehicles/2012-ford-f150-svt-raptor)

### [Rolls Royce Wraith 2014](https://www.gta5-mods.com/vehicles/2014-rolls-royce-wraith-add-on-animated-extras-template)

### [Rolls Royce Wraith](https://www.gta5-mods.com/vehicles/rollse-royse-wraith-add-on-replace-animated-by-anertee)

### [Rolls Royce Cullinan Black Badge](https://www.gta5-mods.com/vehicles/rolls-royce-cullinan-black-badge-add-on-replace-fivem-lods)

### [Rolls Royce Dawn Onyx](https://www.gta5-mods.com/vehicles/2016-rolls-royce-dawn-onyx-concept-add-on-tuning-1-0-what-the-fuck)

### [Lamborghini Aventador](https://www.gta5-mods.com/vehicles/2013-lamborghini-aventador-lp720-4-50th-anniversary)

### [Nissan Skyline GT-R R34*](https://www.gta5-mods.com/vehicles/nissan-skyline-gt-r-bnr34-yca-y97y)

### [Nissan Skyline GT-R R35](https://www.gta5-mods.com/vehicles/2015-nissan-gtr-nismo-yca-y97y)

### [Nissan Qashqai](https://www.gta5-mods.com/vehicles/2016-nissan-qashqai-add-on-hq)

### [Volkswagen Golf GTI 2023](https://www.gta5-mods.com/vehicles/volkswagen-golf-gti-2023)

### [Ford F450 Platinum Tow Truck](https://www.gta5-mods.com/vehicles/2019-f450-superduty-platinum-4-door-tow-truck-pack-fivem)

Pretty cool tow truck, loaded it through LML (Lenny's Mod Loader) seems to be really buggy though

• [Featured in Episode 16 of "Moving Up In Los Santos"](https://youtu.be/K0cdeiVqFAo)

### [Peugeot 406 Taxi*](https://www.gta5-mods.com/vehicles/peugeot-406-taxi-2-addon-dials)

• [Featured in Episode 31 of "Moving Up In Los Santos"](https://youtu.be/Qg5g1Xi72K4?si=-rvn45enhj6O7aBU)

Note: Multiple Porsche cars have been featured in "Moving Up In Los Santos" episodes, but I'm unable to link them here, as they are no longer available, due to Porsche sending a DMCA take-down to GTA5 modding websites, few years back.
