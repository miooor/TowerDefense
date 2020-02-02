Simple plugin that lets you AFK with necro.

# Features

1. Build towers in small range near pump (empower, meteor, arc, chill and stone supported). About 2 screens wide area by default
2. Summons skeletons, vaal skeletons, zombies, use offering
3. Upgrades towers
4. Works on any resolution
5. Moves in between enemy and pump
6. Can skip prepare phase
7. Black list feature. Plugin keep tracks of build attempts and after 10 retries wont use that spot anymore
8. Every click/dealy is randomized

# Video in action (early release)

[![Tower Defense plugin](https://i.imgur.com/CiemHav.png)](https://youtu.be/l3qag50mLSs?t=9 "Tower Defense plugin")

# Download
[Download](https://cloud.mail.ru/public/aX3U/4CpuEeicD) (plugin + optional lootfilter)

[Virus Total](https://www.virustotal.com/gui/file/d39a8cf1047167b7b6f7f504b766db81b32431c024e77f9d58dcf36022bb8c4e/detection) 0/67

[Discord](https://discord.gg/krU2DUs)

# Setup 
Make sure POE is on main monitor!
Extract to PoeHelper\Plugins\Compiled\TowerDefense
![https://cdn.discordapp.com/attachments/669645106231508992/669686434596257812/unknown.png](https://cdn.discordapp.com/attachments/669645106231508992/669686434596257812/unknown.png)

# Troubleshooting
Trying to tick the box but it doesnt work ?

Check
1. Free version doesnt work in first 2 months of league
2. You have correct system date
3. Not running https sniffers (wireshark, fiddler, some AV). I am using KIS and its fine here
4. ExileAPI Loader.exe is not blocked in firewall
5. Running Windows 10

Another suggestions I didnt test but was reported helpful
1. Disable zoom hack and bright
2. Disable CoPilot
3. Change key to something simple like middle mouse button
4. Delete setting file ( PoeHelper\config\global\TowerDefense )
5. Run ExileAPI Loader.exe as admin

Kicked for performing too many actions ?

I use global 40-60 ms delay after every action but maybe I missed smth. Try predictive mode in PoE
 ![https://i.imgur.com/uZqF3oD.png](https://i.imgur.com/uZqF3oD.png)

Other issue ? Go here https://github.com/vadash/TowerDefense/issues

# Profit
Watch netflix and farm blight for atleast 4 ex per hour. I tracked 60+ maps in 3.9 patch 3rd week and got 90c profit per map

8 * 90 / 110 = **6.5 ex per hour** easily cashable loot. Here is [another report from 3.9](https://old.reddit.com/r/pathofexile/comments/evqeza/loot_from_40x_blighted_maps/)

![t13 with teal](https://i.imgur.com/hATpF1r.png)

# Minimal gear:
Recomended links are
1. Minion damage
2. Melee physical damage
3. Melee splash (must have, you will be overwhelmed without it)
4. Impale (with dread banner generocity)
5. Empower (in +3 staff ONLY) / Ruthless

Never use in main links:
1. Feeding frenzy (too weak after nerf)
2. Meat shield (skeles will be too passive)
3. Multistrike (Multistrike cannot support Vaal Skills)

white blight:
1. lvl 17+ gems
2. 5L femurs or 6L rare armor
3. Spirit offering (unsocket CWC pls)

yellow:
usualy not worth it, skip

red t13:
same as last +
1. lvl 19+ gems
2. 6L femurs
3. 4L zombies with maim, meat shield, feeding frenzy
4. flasker with granite, basalt, karui
5. 8000 EHP (life + es) with offering up
6. poison immunity (via pantheon)
7. saqawal's nest with aspect of avian (count skeles as mions and as allies for 300% effect)
8. chill tower annointment
![https://i.imgur.com/XFMP9k8.png](https://i.imgur.com/XFMP9k8.png)

red t14+:
same as last +
1. lvl 20+ gems
2. 6L +3 stuff (with fortify 1 support or 80%+ minion damage)
3. BYOR with bone armor, VMS, covocation
4. 9000 EHP

My gear 

[PoE Buddy - lv97 Summon Skeletons Witch (Necromancer)](https://poe.technology/poebuddy/Cr8LSnuv#items-view)

per skeleton damage with melee splash

![Deeps](https://i.imgur.com/BpDirWA.png)

# Extra plugins
1. Use auto flasker https://github.com/sychotixdev/BasicFlaskRoutine
2. AutoOpen plugin to open chests https://github.com/vadash/AutoOpen
3. Stashie to sort https://github.com/Qvin0000/ExileApiPlugins/tree/master/Stashie

Best map:

![https://i.imgur.com/ktBsci3.png](https://i.imgur.com/ktBsci3.png)

Use 3 teal (7 lucky chests with awakener 8) / 3 crimson (11 lucky chests with awakener 8)

# Bild Your Own Routine (BYOR) Guide
This plugin is a part of BasicFlaskRoutine https://github.com/sychotixdev/BasicFlaskRoutine

Download [BYOR.7z](https://cloud.mail.ru/public/aX3U/4CpuEeicD/BYOR/)

Extract necroQWT.json to PoeHelper\Plugins\Compiled\BasicFlaskRoutine\Profile\necroQWT.json

![Extract path](https://i.imgur.com/jbuQ13i.png)

Run Loader **AS ADMIN**! Activate plugin in ExileAPI

![Activate](https://i.imgur.com/uo8VWAx.png)

Go to Profile -> Clear -> Load

![Plugin](https://i.imgur.com/FU4012J.png)

Select our profile and load

![Profile](https://i.imgur.com/aWuNRSt.png)

Press Reload here.

![Reload](https://i.imgur.com/ZfPZOSy.png)

What necroQWT will do for you ?

1. Press Granite flask (5 key) + Vaal molten shell (W) for fat 9k shield
2. Activate bone armor (T)
3. Recall AG and zombies (we track boots buff, so make sure your AG has it)
https://pathofexile.gamepedia.com/Victario%27s_Flight

How to edit it ?

Right click part of tree you dont need and press Remove

![Edit](https://i.imgur.com/dcLvQHx.png)

Press reload to save changes and close menu. Remember if you dont run it as admin plugin wont be able to send keys on some machines!
