---
title: Refreshing the Dungeon Textures
description: New dungeon walls and floors, with moss, cracks, and water stains to give them an older feel.
pubDate: 2026-09-19
draft: false
language: en
translation: dungeon-texture-renewal
---

I refreshed the dungeon wall and floor textures. I made them with Codex's image generation tool, then refined them as I tried them out in the dungeon.

The development comparison images are separate renders of the game's models and materials.

## The First Three Corridor Concepts

I started with three cave corridors: grey limestone, mossy bedrock, and brown shale.

![The first grey limestone, mossy bedrock, and brown shale corridor concepts](../../../assets/blog/dungeon-cave-sets.webp)

The brown shale felt too similar to the mossy bedrock, so I replaced it with bricks and tiles. Below is an intermediate version with red bricks, broken tiles, and small rocks on the floor.

![An intermediate comparison of two natural caves and a corridor with red bricks and pale tiles](../../../assets/blog/dungeon-masonry-damage-v5.webp)

## A More Weathered Look

I added moss, water stains, and grime to the walls and floors. The red bricks became grey stone, and the pale floor became dark grey tiles.

Together with the puddles, these changes gave the dungeon an older, damper feel.

![Limestone, mossy bedrock, and grey masonry corridors with added moss and water stains](../../../assets/blog/dungeon-weathered-corridors.webp)

## Making Individual Blocks Read Clearly

The masonry texture had so many fine markings that the blocks were hard to distinguish. I reduced the markings and made the joints clearer so the stacked stones would read better from a distance.

I also toned down the protruding bricks and improved how walls fade when they block the view of the character.

![The previous masonry wall on the left, the revised wall in the center, and its transparent state with a blue character stand-in on the right](../../../assets/blog/dungeon-stone-blocks-v10.webp)

## Cracks, Moss, Water Stains, and Cobwebs

Finally, I layered cracks, moss, water trails, and cobwebs over the walls. Varying their position and size gives walls a slightly different look even when they share the same material.

These details also went onto the existing dungeon room walls. Below is the result with those finishing touches added.

![The three corridor types and an existing dungeon room wall with cracks, moss, water stains, and cobwebs](../../../assets/blog/dungeon-room-decals-v12.webp)

## In the Game

Here are screenshots taken in the game after the refresh.

![A cave corridor and room entrance with cobwebs and water stains](../../../assets/blog/dungeon-in-game-cave-junction.png)

![A character holding a torch beside a cave wall with water stains](../../../assets/blog/dungeon-in-game-cave-corridor.png)

![A character in combat in a corridor with cracked masonry walls and broken floor tiles](../../../assets/blog/dungeon-in-game-masonry.png)

## The Sound of Dripping Water

I also added the sound of water dripping into the puddles. Turn on the sound for the clip below.

<video controls playsinline preload="metadata" style="width: 100%; height: auto;" aria-label="Dungeon video with the sound of dripping water">
  <source src="/videos/blog/dungeon-dripping-water.mp4" type="video/mp4" />
  <a href="/videos/blog/dungeon-dripping-water.mp4">Watch the dungeon clip with dripping water sounds</a>
</video>
