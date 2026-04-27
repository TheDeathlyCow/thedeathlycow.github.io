---
title: Scorchful
---
<style>
.md-main {
    background-image: url('/assets/scorchful/background.png');
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
# Scorchful

<div markdown style="text-align: center; justify-content: center;">
![](./assets/scorchful/title.png)

*A Dune-inspired mod about heat-based survival and combat.*

<div markdown style="display: flex; gap: 2rem; flex-wrap: wrap; width: 100%; padding: 1rem 0; font-size: 1rem;">

<span style="padding: 0 1.5rem;">[:curseforge: **CurseForge**](https://www.curseforge.com/minecraft/mc-mods/scorchful)</span>
<span style="border-left: 2px solid currentColor; padding: 0 1.5rem;">[:modrinth: **Modrinth**](https://modrinth.com/mod/scorchful)</span>
<span style="border-left: 2px solid currentColor; padding: 0 1.5rem;">[:github: **GitHub**](https://github.com/TheDeathlyCow/scorchful)</span>
<span style="border-left: 2px solid currentColor; padding: 0 1.5rem;">[:book: **Wiki**](https://modded.wiki/w/Scorchful)</span>

</div>

</div>

---

Scorchful grew out of [Frostiful](./frostiful.md), primarily based on community feedback (even the name Scorchful comes from a community suggestion!). Many players were asking for a heat-based counterpart to Frostiful, as that mod focused exclusively on cold. If they wanted to have heat as well, they had to create some weird Frankenstein setups with Frostiful and EnvironmentZ/Tough as Nails, or just not use Frostiful at all. It took me some time to warm up to the idea (so to speak), as hyperthermia is a mechanic that is fairly underexplored in most games and media, and I did not feel confident that I had a solid jumping off point to start with it.

However, the jumping off point came from *Dune*. The Fremen's relationship with water and the brutality of Arrakis provided the inspiration for me to develop a new heat system based around sweating and soaking. What I found interesting was that sweating and soaking are essentially the same thing -- they both get you wet, and you cool down because of it. This became my primary mechanic for cooling, similar to fire in Frostiful. Swimming, standing in the rain, or drinking water and sweating it out all provide methods for getting wet, and in turn, cooling down.

With Scorchful I also decided to give a shot at learning shader programming properly for the first time. The heat stroke and fear effects use custom GLSL post-processing shaders rather than simple static overlays, which makes them much more dynamic and interesting than just a simple overlay texture. It was a steep learning curve but the result is one of the things I'm most proud of across all my mods.

---

## LTS Policy

Scorchful is a mod that I have maintained for many years at this point across many different Minecraft versions. While I would love to support this mod as widely as possible, my time is limited. Therefore, I publish this LTS policy to inform users of what versions and loaders I intend to maintain and support. This page is updated regularly, be sure to check back often (especially when asking for support in [my Discord](https://discord.thedeathlycow.com)).

This is my current intended support status for each version of Minecraft that Scorchful is available for. The current Long-Term Support (LTS) policy for Scorchful versions is to fully support the first game drop of the current year. If a patch for that game drop breaks compatibility with Scorchful somehow, then I will only support the latest patch.

Supported versions will receive all new features, fixes, and updates.

Version 1.21.1 will receive limited fixes only support (for things such as minor changes and bug fixes), but no new major features.

Unsupported versions version will receive no future updates, except for critical security fixes.

| Minecraft Version | Support Status |
|-------------------|----------------|
| 26.1.x            | ✅ Supported    | 
| 1.21.2-11         | ❌ Unsupported  | 
| 1.21.1            | ⚠️ Fixes only  | 
| 1.20.4            | ❌ Unsupported  | 
| 1.20.2            | ❌ Unsupported  | 
| 1.20.1            | ❌ Unsupported  |
| 1.19.4            | ❌ Unsupported  |
| 1.19.2            | ❌ Unsupported  | 
