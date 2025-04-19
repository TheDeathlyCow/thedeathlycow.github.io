---
title: Minecraft Mods
---
# Minecraft Mods

This is an overview of my mods for the game *Minecraft: Java Edition* by Mojang Studios. All of these mods are primarily written in the Java programming language, however I have also worked with Kotlin to a small degree as well. My Minecraft mods are primarily published onto the platforms [:curseforge: CurseForge](https://www.curseforge.com/members/thedeathlycow/projects) and [:modrinth: Modrinth](https://modrinth.com/user/TheDeathlyCow), which are more player-centered. I also always publish my source code on my [:github: GitHub account](https://github.com/TheDeathlyCow/).

---

## Frostiful
**Frostiful** is a mod focused on cold-weather survival and magic that I have developed and maintained since February 2022. It was inspired by games such as *Subnautica*, *Subnautica: Below Zero*, and *The Long Dark*, as well as the *Skyrim* mod *Frostfall*. My primary goal was to create a temperature system that is **immersive**, **intuitive**, and **interesting**. I did not want to just create a another tedious layer of difficulty for the player to manage. 

Along the way I have had to take on feedback, run play tests, handle bug reports, review pull requests from the community, provide player and developer support and documentation, ensure inter-mod compatibility, and continuously iterate on new features to make them as fun as possible.

**Technologies used**: Java 21, Gradle, Git, Photoshop (for textures), [Blockbench](https://www.blockbench.net/) (for 3D Models and animations), [Fabric Mod Loader](https://fabricmc.net/)

=== "Youtube Trailer"
    <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/nXbpWYjgo-Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    <center></center>

=== "Frostologer's Castle"
    ![](./assets/frostiful/castle.jpeg)
    <center>A custom dungeon structure that naturally generates in the world. It is desinged to provide an ultimate challenge for players to overcome and gain more power over freezing temperatures.</center>

=== "Custom Monsters"
    ![](./assets/frostiful/mobs.png)
    <center>**From left to right**: Chillager (Captain), Chillager, Frostologer, Biter. These monsters were created for the Frostologer's Structure. They were based on the Illager class of monsters and drew inspiration from the Iceologer in *Minecraft: Dungeons*. These monsters are meant to integrate temperature into the wider world of Minecraft and make the mechanic a more intentional part of the world, rather than just an afterthought meant solely to increase difficulty.</center>

=== "Temperature HUD"
    <center markdown>![](./assets/frostiful/temperature-hud.png)
    <br/>The temperature indicator of Frostiful is displayed as a frosty overlay of the vanilla heart bar. As temperature is, in general, not a relevant outside of a select set of cold biomes in the Overworld, it is important to not impose it upon the player when it is not necessary. By displaying temperature in this manner, it balances information with UI-noise and is often cited as a highlight of this
    </center>

- [:github: GitHub Source](https://www.github.com/TheDeathlyCow/frostiful) 
- [:curseforge: CurseForge Project Page](https://www.curseforge.com/minecraft/mc-mods/frostiful)
- [:modrinth: Modrinth Project Page](https://www.modrinth.com/mod/frostiful)

---

## Scorchful
**Scorchful** is a mod focused on warm-weather survival and mind control. It is a warm temperature companion mod to [Frostiful](#frostiful) but came with its own set of unique challenges. Warm temperatures are not a common mechanic in video games; and when it is present it is often a very surface level mechanic, such as only requiring to remove heavy armor when in warm areas. So, I set off to design my own **golden mechanic** for handling cooling that would be just as intuitive and useful as making fire is in Frostiful. My solution was **soaking**. Quite simply: when the player is wet, they will be cooled off. Drinking water allows the player to sweat, but going for a swim will work just the same. This intuitive mechanic has made Scorchful an increasingly popular alternative to many other temperature mods that exist for Minecraft today.

With Scorchful, I also decided to focus on **rendering** effects, such as creating custom post-processing effects for the various temperature effects. This challenged me to delve into Minecraft's **rendering pipelines** and **shader programming**. The effect is a more dynamic and immersive visual experience for the player with greater "movement" than comparatively simple static images. 

**Technologies used**: Java 21, Gradle, Git, Photoshop (for textures), [Blockbench](https://www.blockbench.net/) (for 3D Models and animations), [Fabric Mod Loader](https://fabricmc.net/), GLSL

=== "Title Image"
    [![Scorchful banner showing a Sandstorm and a Crimson Lily side by side](https://raw.githubusercontent.com/TheDeathlyCow/scorchful/main/docs/banner.png)](https://www.curseforge.com/minecraft/mc-mods/scorchful)

=== "Heat Stroke Shader Effect"
    ![](./assets/scorchful/heat-stroke.gif)
    <center>A mix of a periodic blur and wobble effect using shaders written in GLSL.</center>

=== "Fear Particles"
    ![](./assets/scorchful/fear.gif)
    <center>When a player is feared, their screen will be desatured using a GLSL shader, and custom animated bat particles will be displayed around their player model.</center>

- [:github: GitHub Source](https://www.github.com/TheDeathlyCow/scorchful) 
- [:curseforge: CurseForge Project Page](https://www.curseforge.com/minecraft/mc-mods/scorchful)
- [:modrinth: Modrinth Project Page](https://www.modrinth.com/mod/scorchful)

---

## Thermoo

**Thermoo** is a library mod that is used by [Frostiful](#frostiful) and [Scorchful](#scorchful) to provide for common facilities