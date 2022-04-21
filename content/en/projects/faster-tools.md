---
author: "Holly Gregorio"
title: "Faster Tools Mod"
date: 2022-02-10
description: "Increases the default tool speed of minecraft by 25% and allows for customization"
tags: ["minecraft", "faster", "tools", "speed"]
thumbnail: /faster-tools.png
---

This mod increases the default tool speed in minecraft by 25% and can be customized.

## About Development
Faster Tools is a minecraft mod made for the fabric loader. It is my second Minecraft mod; created in February of 2022. After creating my Mob Scarecrows mod I wanted to make a mod that fixed something that had always bugged me in minecraft which was the incredibly slow tool speed. Making this mod was harder than it seemed because initially I had to inject into 4 different places in both minecrafts and fabric’s code to modify the resulting tool speed. One of the places required me to inject into an anonymous class inside of fabric’s tool handler class. I ended up working with 5 different fabric modders over a couple hours just to figure out the proper way to inject into the anonymous class. Funnily enough in the next update of fabric which came about 2 weeks after the release of my mod the fabric team removed all of their tool handler classes making all the time I spent figuring out how to do that injection pointless.

## About The Mod
The mod simply increases the default tool speed by **25%**. The tool speed can be changed via the config where the default value is **125** which sets the current tool speed to 25% faster than default.

Check it out [HERE](https://www.curseforge.com/minecraft/mc-mods/faster-tools).

Come talk about the mod on the [discord](https://discord.gg/DWBttJkkrn).

[GitHub](https://github.com/ReillyGregorio/FasterTools)

