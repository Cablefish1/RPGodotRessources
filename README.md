# RPGodot Ressource Library
This document contains all the ressources collected from the **[RPGodot Discord Community](https://discord.gg/hHJkVXDV3X).**

## Tutorials and guides

**[Create an RPG in Godot](https://gamedevacademy.org/rpg-godot-tutorial/)** - Written Tutorial for Godot 3.X by GameDevAcademy

A very basic tutorial for making a simple action RPG in Godot. It's text and not video-based however it doesn't really explain a lot. The best thing i can say about it is that you'll have a working RPG prototype really fast if you're following this one.

**[Make an Action RPG in Godot](https://www.youtube.com/watch?v=mAbG8Oi-SvQ&list=PL9FzW-m48fn2SlrW0KoLT4n5egNdX-W9a)** - Video Tutorial for Godot 3.X by Heartbeast

Heartbeast's excellent action RPG tutorial. It's free and a really good introduction to many godot features. He's really pleasant to listen to and explains the stuff really well!

**[Ressource based RPG Items](https://www.youtube.com/watch?v=nR0nCFJ8-qM)** - Video Tutorial for Godot 3.X by Jacob Foxe

The videos are a bit messy and lacks the grace of HeartBeasts videos. But they are nice. He's obviously RPG oriented and he does manage to get tools and tips across.

**[Godot 2D Secrets](https://gdquest.mavenseed.com/courses/godot-2d-secrets)** - Paid tutorial by GDQuest.

This is an intermediate godot course that covers a wide range of topics and game genres. It has a few rpg specific courses such as:
- Japanese RPG Combat: core systems
- Tactical JRPG movement
- Japanese RPG Combat: User Interface

Even the non-rpg tutorials are useful such as the best practices and the visual  novel. Also the gdquest team are very responsive on the site and their discord server(anyone can join that even if they have not paid for a course).

**[3D Level Prototyping and Finalizing in Godot](https://www.youtube.com/watch?v=lJoCutmpZuU)** - Video tutorial by Feyter Nerd World
You can use csg nodes in godot to block out your level, design the layout, make rough estimations of everything, and then export it from godot and send it to blender to make the art for the level.

**[Godot Theme Editor](https://www.youtube.com/watch?v=3AGGBZVVVTw) - Tutorial from GDQuest. 
Teach you to install themes to the Godot Editor. Published at godot 3.4 but might still work the same in later versions. Sample theme:  https://mounirtohami.itch.io/godot-dark-theme

**[Game Programming Patterns](https://gameprogrammingpatterns.com/)** 
An online book on how to more effectively tie your code together. Contains loads of useful advice and practices for anyone just beyond absolute beginner level. 

## Other usefull ressources
**[Yanfly Comics](http://yanfly.moe/comics/)** - comics about RPGs and game design. Not Godot specifically.

While this comic is aimed at people who use rpgmaker the advice can extend to anyone making a jrpg, especially people who have never finished their own games. It attempts to give advice on how to finish your rpg by addressing common pitfalls people fall into while making their games and offering solutions.

## Plugins and scripts

**[Kanban tasks](https://github.com/HolonProduction/godot_kanban_tasks)** - Trello like todo plugin.

The hardest part of development may as well be organization, this plugin trivializes that aspect. It is similar to Trello as it can store color coded notes in several lists and each note is also a text file on itself which can store even more info inside it. It also supports having multiple lists and is highly customizable. Available for the asset store for both 3.5 and 4.0 (the latter is in beta).

**[godot dice syntax](https://godotengine.org/asset-library/asset/1282)** - Adds dice syntax to your code.

This nifty little script bag makes it possible to roll all kinds of RPG dice using simple text commands. While very awesome it's a bit unfriendly to noobs like me. The roll functions returns dictionaries with the results where it would mostly be easier to just have the numeric value. The code could be commented a bit more. However it can do anything tabletop RPG dice is supposed to be doing so it is probably useful for people above the beginner skill level. Available for both Godot 3.5 and 4.0.

**[Godot dice bag](https://godotengine.org/asset-library/asset/1658)** - Various dice and rng functions.
This is a quite simple script that allows the roll of many types of dies and rolls through functions instead of syntax commands. The scripts are understandable and more beginner friendly. However it is not as functional and flexible as the Dice Syntax. It's for both 3.5 and 4.0.

**[Panku Console](https://godotengine.org/asset-library/asset/1558)** 
Enables a console that allows for simple debugging tools when the game is running.
In addition there is MooseNotifications, this is a extracted from the panku console. See example scene and script for how to use. it adds popup style notifications with a simple Notifications.add_message("text") and Notifications.add_alert("text"). Not super polished, but works ok. Does have room for improvement. https://github.com/sxmxc/MooseNotifications
