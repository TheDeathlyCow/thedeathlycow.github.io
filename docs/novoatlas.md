---
title: NovoAtlas
---
<style>
.md-main {
    background-image: url('/assets/novoatlas/coast.png');
    background-color: var(--md-default-bg-color);
    background-blend-mode: soft-light;
    background-size: cover;
    background-position: center top;
    background-attachment: fixed;
}

.md-content {
    background-color: var(--md-default-bg-color);
}
</style>

<div markdown style="text-align: center; justify-content: center;">

# NovoAtlas

---

![](./assets/novoatlas/mountain.png)

---

*A data-driven image based world generator for Minecraft.*

<span style="padding: 0 1rem;">[:curseforge:](https://www.curseforge.com/minecraft/mc-mods/novoatlas)</span>
<span style="border-left: 2px solid currentColor; padding: 0 1rem;">[:modrinth:](https://modrinth.com/mod/novoatlas)</span>
<span style="border-left: 2px solid currentColor; padding: 0 1rem;">[:github:](https://github.com/TheDeathlyCow/novoatlas)</span>
<span style="border-left: 2px solid currentColor; padding: 0 1rem;">[:book:](https://github.com/TheDeathlyCow/novoatlas/wiki)</span>

---

</div>

NovoAtlas is a mod that allows you to paint a world's height map and biome map, and then import that to a datapack and allow the Minecraft world generator to fill in the rest of the details. It is a fork of the original [Atlas](https://modrinth.com/mod/atlas), made with their permission under its CC0 license. I made a few contributions to Atlas, but I felt that the changes I wanted to make were substantial enough to warrant a fork. I have used NovoAtlas on my own SMP server, which has been a good real-world testing environment for it as well.

Improvements over the original Atlas include NeoForge support, improved structure-terrain blending, improved underwater cave generation, cave biome maps, and a slightly more ergonomic data format.