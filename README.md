# DMA Add-on Documentation
 
> **Note:** Sections marked `<!-- TODO -->` still need additional information.
 
---
 
## Table of Contents
 
- [Overview](#overview)
- [Getting Started](#getting-started)
- [Items](#items)
  - [Materials](#materials)
  - [Tools](#tools)
  - [Foundry Molds](#foundry-molds)
  - [Rare Drops](#rare-drops)
- [Blocks](#blocks)
  - [Foundry Mixer](#foundry-mixer)
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

## How to Make Steel
 
A quick reference for the full steel production chain:
 
1. **Craft** an Obsidian Brush.
2. **Build** a Foundry Mixer.
3. **Fill** the Mixer: add a Lava Bucket, an Iron Block, and Coal (any order).
4. **Mix** with the Obsidian Brush → instantly receive **3× Steel Ingot** and the brush back.
## Items
 
## Materials
#### Steel Rod
Made from two steel ingots stacked vertically. Used in tool recipes.
 
**Crafting (Crafting Table):**
```
s
s
```
`s` = Steel Ingot → **1× Steel Rod**
 
---
 
#### Steel Block
A compact storage block made from 9 steel ingots. Also used as a crafting ingredient for the [Smithing Anvil](#smithing-anvil).

<img width="481" height="219" alt="image" src="https://github.com/user-attachments/assets/0a6dbeaa-913d-4f1e-8922-2a8b2aff0273" />

---
 
#### Smelted Titanium
Raw titanium ore that has been smelted. Must be hammered further into a Titanium Ingot on a [Smithing Anvil](#smithing-anvil).
 
**Obtained by:** Smelting `dma:titanium_ore` in a **Blast Furnace**.

<img width="170" height="115" alt="image" src="https://github.com/user-attachments/assets/895920b6-1d4f-49db-b867-71c1cc67dac0" />

---
 
#### Titanium Ingot
A fully refined titanium ingot used in high-tier crafting.
 
**Obtained by:** Refining Smelted Titanium on the **Smithing Anvil** using a Dragon Scale Hammer.
 
---
 
## Tools
 
#### Hammer
A basic metalworking hammer with 5 uses. Required for certain crafting operations.
 
**Crafting (Crafting Table):**

<img width="240" height="109" alt="image" src="https://github.com/user-attachments/assets/5fc6ca10-0018-4ab7-b198-d1fd2d35fc92" />

---

#### Dragon Scale Hammer
An epic-tier hammer made from dragon scales and steel rods. Has 50 uses — ten times more durable than the standard hammer.
<img width="242" height="111" alt="image" src="https://github.com/user-attachments/assets/8fdca1c1-84c0-427a-bb7f-c946852c3764" />

---
 
#### Obsidian Brush
Used to mix molten steel inside the Foundry Mixer. Returned to you after use. Does not stack.
 
**Crafting (Crafting Table):**

<img width="240" height="109" alt="image" src="https://github.com/user-attachments/assets/dc288f2b-c2af-464a-be07-297440d0815c" />

 
**Usage:** Right-click the Foundry Mixer when it is ready (contains lava + iron block + coal) to mix it into molten steel. You receive 3× Steel Ingot and the brush back.
 
---
 
### Foundry Molds
 
Item-form molds used as crafting ingredients for Foundry Items. They are not placed as blocks.
 
#### Foundry Ingot Mold
Used to craft iron, gold, and lapis foundry items.
 
**Crafting (Crafting Table):**

<img width="243" height="110" alt="image" src="https://github.com/user-attachments/assets/4b4c2941-bd7e-4900-8d01-704ba3eefbf7" />

---
 
#### Foundry Gem Mold
Used to craft diamond and emerald foundry items.
 
**Crafting (Crafting Table):**

<img width="243" height="110" alt="image" src="https://github.com/user-attachments/assets/6ff1aebf-f797-4c66-9193-03f2679f38d4" />

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

<img width="241" height="110" alt="image" src="https://github.com/user-attachments/assets/4e2135f2-c057-463b-8bdf-0dcc7df64053" />

#### How to use the Mixer
 
1. Right-click with a **Lava Bucket** to fill it with lava (returns an empty bucket).
2. Right-click with an **Iron Block** to add iron.
3. Right-click with **Coal** to add coal.
4. Once all three are loaded, right-click with the **Obsidian Brush** — you instantly receive **3× Steel Ingot** and the brush back.
You can add ingredients in any order; what matters is that lava, iron, and coal are all present before brushing.
 
> **Tip:** Breaking the Mixer while it contains an iron block returns 1× Iron Ingot so you lose most of your materials.
 
---

### Smithing Anvil
 
A custom crafting station used to forge Steel Plates, Titanium Ingots, and Dragon Stars. You interact with it by placing items onto the **top face** one at a time, then striking with a hammer to process them. It is directional and will face you when placed.
 
**Crafting (Crafting Table):**

<img width="241" height="107" alt="image" src="https://github.com/user-attachments/assets/316e54bc-b29a-4a4f-bfb4-5e21213dd019" />

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

