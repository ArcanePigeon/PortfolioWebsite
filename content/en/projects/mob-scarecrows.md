---
author: "Holly Gregorio"
title: "Mob Scarecrows Mod"
date: 2022-01-08
description: "Adds plushie, statues, and scarecrows into minecraft that scare away monsters"
tags: ["minecraft", "scarecrow", "plushie", "statue"]
thumbnail: /mob-scarecrows.png
---

This mod adds many cute plushies and scarecrows into minecraft which can be used to scare away mobs or attract them.

**500,000 + Downloads**

## About Development
Mob scarecrows is a minecraft mod made for the fabric loader. It was my first Minecraft mod; created in January of 2022. I had never made a minecraft mod before and thought I would do something simple like making a scarecrow to keep mobs away. It turned out that this was not a simple idea and in fact was something no one had really done before, at least on fabric, and I ended up having to read the minecraft source over several days to figure out how to scan for blocks and run that check inside my own custom AI goal. I also had to learn how to use mixins to inject into an existing mob's AI and add the custom goal. Overall the mod turned out great and I have big plans for it in the future. I still need to add a run away task for enemies that use mojang’s brain class that is separate from their other AI system and is significantly more complicated to inject into without breaking everything.

## About The Mod
The mod has many different scarecrows which look like plushies and statues that are used to keep mobs away from your base. The scarecrows are blocks that can be placed anywhere and different scarecrows scare different mobs. Some scarecrows attract mobs making them very useful for mob farms. The mod has a config so that the radius in which the scarecrows scare mobs can be changed. The default scare radius is **8 blocks**.

### Scarecrow Types
- Normal Scarecrow : Scares most mobs
- Cat Plushie & Statue : Scares creepers
- Wolf Plushie & Statue : Scares skeletons
- Pigeon Plushie & Statue : Scares spiders
- Iron Golem Plushie & Statue : Scares zombies
- Turtle Plushie & Statue : Attracts zombies
- Endermite Plushie & Statue : Attracts endermen

![Scarecrows](/mob-scarecrows-info-card-1.png)

## Future Plans
I plan on a massive overhaul of the mod in the future. At the moment the scarecrows are blocks and require mobs to scan for it by looking at many blocks which is inefficient. I plan on solving this by making the scarecrows entities that can be placed in the same way you place an armor stand. This change would also make it significantly easier to add giant plushies and statues to the game. I also plan on reworking all of the scarecrow models and textures to make them look better in game. For features I will be adding many more scarecrow variants so that every hostile mob has its own plushie as well as making it more difficult to get these scarecrows as with their basic recipes the scarecrows are kind of overpowered.

Check it out [HERE](https://www.curseforge.com/minecraft/mc-mods/mob-scarecrows).

Come talk about the mod on the [discord](https://discord.gg/DWBttJkkrn).

[GitHub](https://github.com/ReillyGregorio/MobScarecrow)
