---
title: "GMTK 2020"
excerpt: "Entry for gmtk 2020 gamejam, made with Godot"
permalink: /portfolio/gmtk2020/
header:
  teaser: /_assets/images/gmtk2020/Main.png
---

![img](/_assets/images/gmtk2020/Main.png)

The theme for the GMTK jam was "out of control", for this I had the idea of a turn based game where the player decides their actions and has a chance of their action being taken from them. To help make the game not feel so bad when the player loses control their action is buffed if they lost control to act as an upside. Additionally the same was true for enemies, they could lose control and receive buffs. The player also did not have full control over which action they selected, the player had 10 points to assign to choose what to do, the more points the higher the chance the action would happen, to prevent the player from always acting as they wanted the sliders were capped at 5, and some points pre spent for them.

The game was made using Godot with GDScript, personally I ended up not liking GDScript due to its lack of strict types, additionally when I tried to use static typing as it supports it often begins to cause circular dependencies making it rather frustrating to use. Outside of this aspect though Godot was nice to use for a 2d project, if I am to use it again, I will certainly look at its C# support instead.

The game is available on [itch](https://skuuully.itch.io/out-of-control-gmtk)