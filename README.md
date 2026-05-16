# DMA Add-on Documentation
 
> **Note:** Sections marked `<!-- TODO -->` still need additional information.
 
---
 
## Table of Contents
 
- [Overview](#overview)
- [Getting Started](#getting-started)
- [Items](#items)
  - [Materials](#materials)
  - [Tools](#tools)
  - [Obsidian Buckets](#obsidian-buckets)
  - [Foundry Molds](#foundry-molds)
  - [Rare Drops](#rare-drops)
- [Blocks](#blocks)
  - [Foundry Mixer](#foundry-mixer)
  - [Ingot Mold Block](#ingot-mold-block)
  - [Smithing Anvil](#smithing-anvil)
- [Foundry Items](#foundry-items)
  - [Tier 1 Foundry Items](#tier-1-foundry-items)
  - [Tier 2 Foundry Items](#tier-2-foundry-items)
  - [Tier 3 Foundry Items](#tier-3-foundry-items)
- [How to Make Steel](#how-to-make-steel)
---
 
## Overview
 
The DMA add-on adds a metalworking and foundry progression system to Minecraft Bedrock. You'll smelt and cast new metals — steel and titanium — using custom blocks and tools, and eventually craft powerful foundry items that produce resources automatically.
 
---
 
## Getting Started
 
The core progression loop looks like this:
 
1. Craft an **Obsidian Brush**
2. Build a **Foundry Mixer** and fill it with lava, iron blocks, and coal
3. Use the brush to instantly receive **3× Steel Ingots**
4. Use steel ingots to craft tools, rods, plates, and eventually **Foundry Items**
---
 
## Items
 
### Materials
 
#### Steel Ingot
The core crafting material of the add-on. Produced by casting molten steel in the Ingot Mold Block.
 
**Obtained by:** Casting molten steel in the Ingot Mold Block, or using the Obsidian Brush on a ready Mixer.
 
---
 
#### Steel Rod
Made from two steel ingots stacked vertically. Used in tool recipes.
 
**Crafting (Crafting Table):**
```
s
s
```
`s` = Steel Ingot → **1× Steel Rod**
 
---
 
#### Steel Plate
<!-- TODO: Add crafting recipe and usage -->
 
---
 
#### Steel Block
A compact storage block made from 9 steel ingots. Also used as a crafting ingredient.
 
**Crafting (Crafting Table — shapeless):**
9× Steel Ingot → **1× Steel Block**
 
---
 
#### Smelted Titanium
Raw titanium ore that has been smelted. Must be refined further into a Titanium Ingot.
 
**Obtained by:** Smelting `dma:titanium_ore` in a **Blast Furnace**.
 
---
 
#### Titanium Ingot
A fully refined titanium ingot used in high-tier crafting.
 
**Obtained by:** Refining Smelted Titanium on the **Smithing Anvil** using a Dragon Scale Hammer.
 
---
 
### Tools
 
#### Hammer
A basic metalworking hammer with 5 uses. Required for certain crafting operations.
 
**Crafting (Crafting Table):**
```
  s D
  S s
  S
```
`D` = Diamond, `s` = Steel Ingot, `S` = Stick → **1× Hammer**
 
---
 
#### Dragon Scale Hammer
An epic-tier hammer made from dragon scales and steel rods. Has 50 uses — ten times more durable than the standard hammer.
 
**Crafting (Crafting Table):**
```
  D r
  r D
  r
```
`D` = Dragon Scale, `r` = Steel Rod → **1× Dragon Scale Hammer**
 
---
 
#### Obsidian Brush
Used to mix molten steel inside the Foundry Mixer. Returned to you after use. Does not stack.
 
**Crafting (Crafting Table):**
```
O
C
S
```
`O` = Obsidian, `C` = Copper Ingot, `S` = Stick → **1× Obsidian Brush**
 
**Usage:** Right-click the Foundry Mixer when it is ready (contains lava + iron block + coal) to mix it into molten steel. You receive 3× Steel Ingot and the brush back.
 
---
 
### Obsidian Buckets
 
Heat-resistant buckets used to transport molten steel. The empty bucket stacks to 16; all filled variants are limited to 1 per stack.
 
| Item | Fill Level | Stack Size |
|---|---|---|
| Obsidian Bucket | Empty | 16 |
| Quarter Full Molten Steel Obsidian Bucket | 25% | 1 |
| Half Full Molten Steel Obsidian Bucket | 50% | 1 |
| Three Quarter Full Molten Steel Obsidian Bucket | 75% | 1 |
| Molten Steel Obsidian Bucket | 100% (Full) | 1 |
 
**Crafting the empty Obsidian Bucket (Crafting Table):**
```
O O
 O
```
`O` = Obsidian → **1× Obsidian Bucket**
 
Buckets fill and empty progressively — each interaction with the Mixer or Ingot Mold moves the fill level up or down by one stage.
 
---
 
### Foundry Molds
 
Item-form molds used as crafting ingredients for Foundry Items. They are not placed as blocks.
 
#### Foundry Ingot Mold
Used to craft iron, gold, and lapis foundry items.
 
**Crafting (Crafting Table):**
```
 S
SIS
 S
```
`S` = Steel Ingot, `I` = Iron Ingot → **1× Foundry Ingot Mold**
 
---
 
#### Foundry Gem Mold
Used to craft diamond and emerald foundry items.
 
**Crafting (Crafting Table):**
```
 S
SeS
 S
```
`S` = Steel Ingot, `e` = Emerald → **1× Foundry Gem Mold**
 
---
 
### Rare Drops
 
#### Dragon Scale
An epic-quality material dropped by dragons. Used to craft the Dragon Scale Hammer and to upgrade Foundry Items to Tier 2.
 
<!-- TODO: Confirm dragon drop source -->
 
---
 
#### Dragon Star
An epic-quality item used in crafting Tier 3 Foundry Items.
 
**Obtained by:** Forging on the **Smithing Anvil** — place a Nether Star and 4 Dragon Scales, then strike with a Dragon Scale Hammer.
 
---
 
## Blocks
 
### Foundry Mixer
 
The Mixer is the centrepiece of steel production. You load it with lava, iron blocks, and coal, then mix it with the Obsidian Brush to produce molten steel that can be collected in Obsidian Buckets.
 
**Crafting (Crafting Table):**
```
D D
D D
ddd
```
`D` = Deepslate Bricks, `d` = Deepslate Brick Slab → **1× Foundry Mixer**
 
#### How to use the Mixer
 
1. Right-click with a **Lava Bucket** to fill it with lava (returns an empty bucket).
2. Right-click with an **Iron Block** to add iron.
3. Right-click with **Coal** to add coal.
4. Once all three are loaded, right-click with the **Obsidian Brush** — you instantly receive **3× Steel Ingot** and the brush back.
You can add ingredients in any order; what matters is that lava, iron, and coal are all present before brushing.
 
> **Tip:** Breaking the Mixer while it contains an iron block returns 1× Iron Ingot so you don't lose your materials.
 
---
 
### Ingot Mold Block
 
Used to cast molten steel from Obsidian Buckets into Steel Ingots. It is directional and will face you when placed.
 
**Crafting (Crafting Table):**
```
 I
IDI
 I
```
`I` = Iron Ingot, `D` = Deepslate Bricks → **1× Ingot Mold Block**
 
#### How to use the Ingot Mold Block
 
1. Right-click with a filled **Obsidian Bucket** (any fill level) to pour molten steel in. Each pour uses one quarter of steel and returns the bucket one stage emptier.
2. Wait **30 seconds** for the steel to cool and solidify.
3. Right-click with a **Steel Ingot** in hand to eject the finished ingot from the mold.
You can also extract steel back into buckets before it sets by right-clicking with an empty Obsidian Bucket.
 
---
 
### Smithing Anvil
 
A custom crafting station used to forge Steel Plates, Titanium Ingots, and Dragon Stars. You interact with it by placing items onto the **top face** one at a time, then striking with a hammer to process them. It is directional and will face you when placed.
 
**Crafting (Crafting Table):**
```
SSS
 s
sss
```
`S` = Steel Block, `s` = Steel Ingot → **1× Smithing Anvil**
 
#### How to use the Smithing Anvil
 
Always right-click the **top face** of the anvil. Clicking the sides does nothing.
 
Each recipe works by placing ingredients onto the anvil one at a time, then striking with a hammer. The anvil holds the items internally as a state — if you break it at any stage, it drops whatever was placed on it so far.
 
---
 
#### Recipe: Steel Plate
 
| Step | Action |
|---|---|
| 1 | Right-click the anvil (empty) with a **Steel Ingot** |
| 2 | Right-click with a **Hammer** or **Dragon Scale Hammer** to forge it |
| 3 | Right-click the anvil with an **empty hand** to collect the **Steel Plate** |
 
> Each hammer strike consumes 1 durability. The Hammer has 5 uses; the Dragon Scale Hammer has 50.
 
---
 
#### Recipe: Titanium Ingot
 
| Step | Action |
|---|---|
| 1 | Right-click the anvil (empty) with **Smelted Titanium** |
| 2 | Right-click with a **Dragon Scale Hammer** to refine it |
| 3 | Right-click the anvil with an **empty hand** to collect the **Titanium Ingot** |
 
---
 
#### Recipe: Dragon Star
 
This recipe requires building up the anvil state across multiple steps. The Nether Star and Dragon Scales can be placed in either order, as long as both are present before the final hammer strike.
 
| Step | Action |
|---|---|
| 1 | Right-click the anvil (empty) with a **Nether Star** |
| 2–5 | Right-click with a **Dragon Scale** four times |
| 6 | Right-click with a **Dragon Scale Hammer** to forge it |
| 7 | Right-click the anvil with an **empty hand** to collect the **Dragon Star** |
 
Alternatively, you can place Dragon Scales first and then add the Nether Star — the anvil accepts them in either order.
 
> The Dragon Scale Hammer loses 1 durability per strike. With only 50 uses, plan accordingly before attempting high-step recipes.
 
---
 
## Foundry Items
 
Foundry Items are powerful items that can be upgraded across multiple tiers. Higher tiers require rarer materials and produce better results.
 
### Tier 1 Foundry Items
 
All Tier 1 recipes follow the same pattern and are crafted at a **Crafting Table**:
 
```
BOB
xSx
BMB
```
`B` = Steel Block, `O` = Obsidian Bucket, `S` = Steel Ingot, `x` = material, `M` = mold (see below)
 
| Result | `x` Material | Mold (`M`) |
|---|---|---|
| Iron Ingot Foundry Tier 1 | Iron Block | Foundry Ingot Mold |
| Gold Ingot Foundry Tier 1 | Gold Block | Foundry Ingot Mold |
| Lapis Foundry Tier 1 | Lapis Block | Foundry Ingot Mold |
| Diamond Foundry Tier 1 | Diamond Block | Foundry Gem Mold |
| Emerald Foundry Tier 1 | Emerald Block | Foundry Gem Mold |
 
---
 
### Tier 2 Foundry Items
 
All Tier 2 items use the same cross pattern of **4 Dragon Scales** around the Tier 1 item.
 
**Crafting (Crafting Table):**
```
 D
DFD
 D
```
`D` = Dragon Scale, `F` = Tier 1 Foundry Item
 
| Result | `F` Input |
|---|---|
| Iron Ingot Foundry Tier 2 | Iron Ingot Foundry Tier 1 |
| Gold Ingot Foundry Tier 2 | Gold Ingot Foundry Tier 1 |
| Lapis Foundry Tier 2 | Lapis Foundry Tier 1 |
| Diamond Foundry Tier 2 | Diamond Foundry Tier 1 |
| Emerald Foundry Tier 2 | Emerald Foundry Tier 1 |
 
---
 
### Tier 3 Foundry Items
 
Tier 3 items require **Titanium Ingots** and **Dragon Stars**, making them the most expensive items in the add-on. All five materials share the same pattern.
 
**Crafting (Crafting Table):**
```
TST
TFT
TST
```
`T` = Titanium Ingot, `S` = Dragon Star, `F` = Tier 2 Foundry Item
 
| Result | `F` Input |
|---|---|
| Iron Ingot Foundry Tier 3 | Iron Ingot Foundry Tier 2 |
| Gold Ingot Foundry Tier 3 | Gold Ingot Foundry Tier 2 |
| Lapis Foundry Tier 3 | Lapis Foundry Tier 2 |
| Diamond Foundry Tier 3 | Diamond Foundry Tier 2 |
| Emerald Foundry Tier 3 | Emerald Foundry Tier 2 |
 
---
 
## How to Make Steel
 
A quick reference for the full steel production chain:
 
1. **Craft** an Obsidian Brush.
2. **Build** a Foundry Mixer.
3. **Fill** the Mixer: add a Lava Bucket, an Iron Block, and Coal (any order).
4. **Mix** with the Obsidian Brush → instantly receive **3× Steel Ingot** and the brush back.
