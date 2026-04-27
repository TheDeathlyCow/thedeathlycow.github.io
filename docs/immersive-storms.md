---
title: Immersive Storms
---
<style>
.md-main {
    background-image: url('/assets/immersive-storms/background.png');
    background-color: var(--md-default-bg-color);
    background-blend-mode: difference;
    background-size: cover;
    background-position: center top;
    background-attachment: fixed;
}
</style>

<div markdown style="text-align: center; justify-content: center;">

# Immersive Storms

---

=== "Sandstorms"
    ![Sandstorms](assets/immersive-storms/sandstorm.jpg)

=== "Blizzards"
    ![Blizzards](assets/immersive-storms/blizzard.jpg)

=== "Pale Gardens"
    ![Pale Gardens](assets/immersive-storms/pale_garden.jpg)

=== "Swamps"
    ![Swamps](assets/immersive-storms/swamp.jpg)

---

*Immersive fog and weather effects for mountains, deserts, pale gardens, and more!*

<div markdown>

<span style="padding: 0 1rem;">[:curseforge:](https://www.curseforge.com/minecraft/mc-mods/immersive-storms)</span>
<span style="border-left: 2px solid currentColor; padding: 0 1rem;">[:modrinth:](https://modrinth.com/mod/immersive-storms)</span>
<span style="border-left: 2px solid currentColor; padding: 0 1rem;">[:github:](https://github.com/TheDeathlyCow/immersive-storms)</span>

</div>

</div>

---

Immersive Storms is a small client-side mod that adds subtle and immersive fog and particle effects to various biomes, based on the weather. It was originally a part of [Scorchful](./scorchful.md), but many players loved the sandstorm effects in Scorchful and wanted to be able to use them standalone without the survival mechanics. Rather than adding a config option to strip out half the mod, I extracted the visuals into a standalone mod that is fully client sided, so it can be used easily anywhere by anyone.

Scorchful still uses Immersive Storms under the hood, embedded directly via jar-in-jar. This means the sandstorm visuals stay consistent between the two mods automatically, and I only have to maintain them in one place. I then built the gameplay features for sandstorms on top of it within Scorchful using visual foundation that Immersive Storms provides.

Once that extraction was done I started adding new weather effects beyond sandstorms. I added blizzards for snowy biomes, fog for swamps, ambient wind particles to mountains and windy biomes, and black rain for the Pale Garden. Pale Gardens in particular I felt still had a bit too much colour coming from the blue tint of vanilla rain that needed to be removed to make it a truly colourless biome.