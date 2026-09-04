[README_GEN2_UPDATED.md](https://github.com/user-attachments/files/31843484/README_GEN2_UPDATED.md)

# Pokémon Recomp

A collection of mods for the **original Pokémon ** designed to make the game more modern, accessible, and content-rich.

All mods are available in the repository:

**[github.com/FAFF0x/gen2recomp](https://github.com/FAFF0x/gen2recomp)**

---

## Table of Contents

- [Quality of Life Mods](#quality-of-life-mods)
  - [Advanced Box System](#advanced-box-system)
  - [Area DexNav](#area-dexnav)
  - [DV/EV Editor](#dvev-editor)
  - [EXP Share Modes](#exp-share-modes)
  - [Free Master Ball + Rare Candy](#free-master-ball)
  - [HM Anywhere](#hm-anywhere)
  - [Instant Hatch Gen 2](#instant-hatch-gen-2)
  - [Item Shortcut](#item-shortcut)
  - [Modern Bag](#modern-bag)
  - [Move Learn Stats](#move-learn-stats)
  - [Moves Manager](#moves-manager)
  - [Nickname Changer](#nickname-changer)
  - [Pokédex Plus](#pokédex-plus)
  - [Trade Evolution Fix](#trade-evolution-fix)
  - [Quest System](#quest-system)
  - [Repel Reuse](#repel-reuse)
  - [Reusable Machines](#reusable-machines)
  - [Summon](#summon)
  - [Universal Free TM Shop](#universal-free-tm-shop)
- [ART Mods](#art-mods)
  - [Modern Battle UI](#modern-battle-ui)
  - [Modern UI Gen 2](#modern-ui-gen-2)
  - [new_icons](#new_icons)
  - [new_sprites](#new_sprites)
  - [New Item Icons](#new-item-icons)
- [Debugging](#debugging)
  - [Performance Monitor](#performance-monitor)
- [Quest Mods](#quest-mods)


---

# Quality of Life Mods

## Advanced Box System

**Current version: v1.0.0**

Expands the original PC Box interface with faster navigation, direct swapping, and improved Box management.

### WITHDRAW

While browsing stored Pokémon:

- press **Left / Right** to switch instantly between **BOX 1 and BOX 12**;
- Box switching remains available even when the current Box is empty;
- you can continue moving between Boxes without returning to the main PC menu.

### DEPOSIT

While viewing the party:

- remain directly in the party list;
- press **Left / Right** to change the destination Box in real time;
- if the selected Box is full, you can immediately move to the next Box without leaving the menu.

### SWAP POKéMON

Adds a dedicated **SWAP POKéMON** option.

To swap Pokémon:

1. select a Pokémon stored in a Box;
2. select a Pokémon in the party;
3. the two Pokémon are exchanged directly.

The swap system also works when:

- the party already contains **6 Pokémon**;
- the party contains only **1 Pokémon**.

Because the total number of party members does not change, the normal party-size restrictions do not prevent the swap.

### Quick SWAP

A direct **SWAP** action is also available inside both:

- **WITHDRAW**
- **DEPOSIT**

This allows Pokémon to be exchanged without returning to the main PC menu.

### RELEASE

The **RELEASE** menu also supports **Left / Right** Box switching, allowing you to move between Boxes without leaving the release screen.

---

## Area DexNav

Press **SELECT** while exploring the overworld to start an encounter with an uncaught Pokémon from the current area's real encounter table.

---


## DV/EV Editor

Adds a **DV/EV** option to each party Pokémon's submenu, allowing DVs and Stat EXP to be edited outside of battle.

### DV Page

Allows you to edit:

- Attack;
- Defense;
- Speed;
- Special.

Valid values range from `0` to `15`.

The HP DV is recalculated automatically from the four editable DVs, following Generation I mechanics.

### EV / Stat EXP Page

Allows you to edit the following values separately:

- HP;
- Attack;
- Defense;
- Speed;
- Special.

Features:

- exact values from `0` to `65,535`;
- displays the effective EV contribution from `0` to `63`;
- updates the resulting final stat in real time.

---

## EXP Share Modes

Adds three selectable Experience Point distribution modes.

| Mode | Behavior |
|---|---|
| **Off** | Only conscious Pokémon that participated in battle receive experience. |
| **Classic Even Split** | Default mode. The full experience pool is divided evenly among all conscious Pokémon in the party. |
| **Modern Progressive** | Participants split the normal 100% experience pool, while conscious Pokémon that did not battle split a second 50% pool. The total is approximately `1.5×`. |

---

## Free Master Ball + Free Rare Candy


Adds the **MASTER BALL** automatically to the **BUY** list of every standard Poké Mart.
Adds **RARE CANDY** to the **BUY** list of every standard Poké Mart.

### Features

- **MASTER BALL** is available in all normal Poké Marts.
- The purchase price is set to **¥0**.


- **RARE CANDY** is available in all normal Poké Marts.
- The purchase price is set to **¥0**.

---


## HM Anywhere

Allows owned HMs to be used without teaching them to a Pokémon.

You only need to have the corresponding HM in your Bag. The required Badges are still necessary.

### Controls

- **CUT** — press `A` while facing a cuttable tree or bush.
- **SURF** — press `A` while facing water; press `A` again toward land to dismount.
- **STRENGTH** — press `A` while facing a boulder to activate Strength and begin moving it.
- **FLASH** — open the Start menu, select the new **HM** submenu, and choose **FLASH**.
- **FLY** — open the Start menu, select the new **HM** submenu, and choose **FLY**.

---

## Instant Hatch Gen 2

**Current version: v1.0.0**

Adds a new **INSTANT HATCH** action directly to Egg Pokémon in the party menu.

### How to Use

1. Open **POKéMON**.
2. Select an **EGG**.
3. Choose **INSTANT HATCH** from the submenu.
4. The selected Egg hatches immediately.

---

## Item Shortcut

Press the default shortcut button in the overworld to open a menu containing five item slots.

### Default Controls

| Action | Keyboard | Controller |
|---|---|---|
| Open Shortcut Menu | `I` | `Y` |
| Use FAST Item | `K` | `X` |

### Slot Actions

Each assigned slot provides the following actions:

- **USE** — immediately uses the assigned item;
- **SET FAST** — marks the item for quick use;
- **CLEAR** — removes the item from the slot.

### Assigning an Item

Items are assigned directly from the Bag:

```text
BAG → Select Item → ASSIGN SHORTCUT → Choose Slot 1–5
```

One of the five slots can be designated as the **FAST** slot.

Press the assigned **FAST Item** button in the overworld to use that item immediately.

### Control Remapping

Both shortcut buttons can be remapped directly from the **Item Shortcut** menu.

Open the menu using:

- **Keyboard:** `I`
- **Controller:** `Y`

Then select **OPTIONS** to change the controls.

---

## Modern Bag

**Current version: v1.6.0**

Transforms the Bag into a modern inventory divided into multiple pockets, navigated with **Left** and **Right**.

It also removes the original 20-item-type capacity limit.

### Available Pockets

| Pocket | Contents |
|---|---|
| **FAVORITES** | Any items marked as favorites. Accessible by pressing **Left** from the Medicine pocket. |
| **MEDICINE** | Potions, status-healing items, Revives, Ether, Elixir, vitamins, PP Ups, and Rare Candies. |
| **BALLS** | Poké Balls, Great Balls, Ultra Balls, Master Balls, and Balls added by other mods. |
| **TM HM** | All TMs and HMs. |
| **BATTLE** | X items, Dire Hit, Guard Spec., and Poké Doll. |
| **KEY ITEMS** | Bicycle, Fishing Rods, Poké Flute, keys, cards, and other important items. |
| **OTHER** | Evolution Stones, Repels, Escape Rope, fossils, and general-purpose items. |

### Opening Pocket

A new **Opening Pocket** option lets you choose which Bag pocket is displayed when the Bag is opened.

Available choices:

- **Favorites**
- **Medicine**
- **Balls**
- **TM/HM**
- **Battle**
- **Key Items**
- **Other**
- **Last Used**

**Medicine** remains the default setting for backwards compatibility.

When **Last Used** is selected, the Bag remembers the pocket you were viewing and automatically reopens on that same pocket the next time.

### Hold Scroll Speed

A new **Hold Scroll Speed** option controls how quickly the item list scrolls while a direction is held.

Available settings:

- **Off**
- **Normal**
- **Fast**
- **Very Fast**

**Fast** is the new default setting.

### Favorites

A new **FAVORITES** pocket has been added.

It can be opened by pressing **Left** from the **MEDICINE** pocket.

Any item can be added to Favorites, and favorite items can be used normally directly from this section.

### Item Options

Press **SELECT** on an item to open the **ITEM OPTIONS** menu:

- **ADD FAVORITE** / **REMOVE FAVORITE**
- **PIN TO TOP** / **UNPIN ITEM**
- **MOVE ITEM**
- **CANCEL**

### Pinned Items

Pinned items:

- always remain at the top of their category;
- are not moved by alphabetical sorting;
- preserve the order in which they were pinned;
- remain pinned after closing and reopening the game.

### Indicators

The following indicators may appear next to an item's quantity:

| Indicator | Meaning |
|---|---|
| `F` | Favorite |
| `P` | Pinned to the top |
| `PF` | Favorite and pinned |

Favorite and pinned settings remain saved even when an item's quantity reaches zero.

When the item is obtained again, it automatically returns with the same settings.

### Automatic Sorting

Items are sorted automatically whenever the Bag is opened.

The sorting order is based on:

1. pocket;
2. pinned-item order;
3. item name.

TMs and HMs are sorted numerically, with HMs listed before TMs.

The automatic sorting is refreshed whenever you obtain a new type of item.

Manual reordering remains available through **SELECT → ITEM OPTIONS → MOVE ITEM** during the current play session.

### Quick Search

Press **START** while inside any standard Bag pocket to open the general search screen.

#### Controls

- **D-pad** — move across the on-screen keyboard;
- **A** — enter a character;
- **B** — delete a character or exit;
- **SELECT** — clear the current search;
- **START** or **GO** — display the search results.

The search checks every Bag pocket.

Selecting a result automatically returns you to the correct pocket with the matching item highlighted.

The search also correctly recognizes item names containing special characters, such as **POKé BALL**.

### TM/HM Search, Filters, and Sorting

While inside the **TM HM** pocket, press **START** to open a dedicated panel.

The panel provides the following options:

- **NAME** — search by move name, not only by TM or HM number;
- **TYPE** — filter by move type, including Fire, Water, Grass, Electric, Psychic, and others;
- **CLASS** — filter moves by category:
  - **PHYSICAL**
  - **SPECIAL**
  - **STATUS**
- **SORT** — choose one of the following sorting methods:
  - **Machine Number**
  - **Move Name**
  - **Power High to Low**
  - **Power Low to High**

All filters can be combined.

### TM/HM Move Information

With a TM or HM highlighted, press:

- **Controller:** `Y`
- **Keyboard:** `I`

The information screen displays:

- TM or HM number;
- move name;
- type;
- Physical, Special, or Status class;
- power;
- accuracy;
- PP;
- move effect.

---

## Move Learn Stats

**Current version: v1.0.0**

When a Pokémon already knows four moves and must forget one to learn a new move, the lower panel displays two comparison columns.

### SELECTED

Shows the currently highlighted move that would be forgotten:

- move name;
- **POWER**;
- maximum **PP**.

### LEARNING

Shows the new move the Pokémon is about to learn:

- move name;
- **POWER**;
- maximum **PP**.

---

## Moves Manager

Adds a **MOVES** option to each party Pokémon's submenu.

### Main Page

Displays:

- the four currently known moves;
- current and maximum PP;
- any empty move slots;
- move reordering with **SELECT**.

### Technical Pages

Each move has three information pages containing:

- type and physical, special, or status category;
- power and accuracy;
- PP, maximum PP, and PP Ups;
- priority;
- increased critical-hit probability;
- effect and effect type;
- fixed damage;
- number of hits;
- Counter compatibility;
- charging turns;
- semi-invulnerability;
- index;
- internal identifier;
- animation.

### Replacing Moves

Press `A` on a move's technical page to choose a replacement from the Pokémon's move memory.

The initial move memory is rebuilt using:

- currently known moves;
- starting moves from the evolutionary line;
- level-up moves learned up to the Pokémon's current level.

---

## Nickname Changer

Adds a new renaming option directly to the standard **POKéMON** menu.

When selecting a Pokémon, the submenu now includes:

```text
STATS → RENAME → SWITCH
```

### Features

- Change a Pokémon's nickname directly from the party menu.
- Nicknames can contain up to **10 characters**.

---

## Pokédex Plus

Pokédex Plus replaces the original Pokédex with a more complete and practical version.

For each Pokémon, it allows you to view general information, base stats, habitats, encounter rates, evolutions, and moves learned by leveling up.

### Features

- Caught Pokémon indicator.
- Automatic scanning of the current party and every PC Box.
- **STATS** tab showing type, base stats, and total base stat value.
- **HABITAT** tab showing areas, encounter methods, levels, and encounter rates.
- Direct access to the area map.
- **EVOLUTION** tab showing the evolution chain and evolution method.
- **LEVEL MOVES** tab showing moves learned by level and their details.
- Quick search by pressing **START**.
- Search Pokémon by name or type.
- Compatibility with Pokémon and encounters added by other mods.

---

## Trade Evolution Fix

Replaces the four Generation I trade evolutions with level-based evolutions.

The affected Pokémon evolve at **level 40**.

---

## Quest System

Adds a **QUESTS** option to the Start menu.

### Quest Log

The menu contains two sections navigated with **Left** and **Right**:

- **ACTIVE** — available, started, or failed quests;
- **COMPLETED** — completed quests.

Each quest displays:

- title and status;
- description;
- current objective;
- recommended location;
- numerical progress;
- progress bar;
- reward;
- source mod.

---

## Repel Reuse

When a Repel's effect expires, a choice is displayed automatically:

- **YES** — immediately consumes and activates another Repel;
- **NO** — continues without using another Repel.

The prompt is not displayed when no Repels remain in the Bag.

### Repel Selection Priority

The mod first attempts to use the same type of Repel that just expired. If none remain, it automatically selects one in this order:

1. **MAX REPEL**
2. **SUPER REPEL**
3. **REPEL**

---

## Reusable Machines

Improves how TMs and HMs work:

- TMs are no longer consumed when teaching a move;
- HM moves can be forgotten;
- the move assigned to each TM or HM is displayed directly in the Bag.

---

## Summon

Adds a **SUMMON** option to the Start menu.

It allows you to enter a Pokédex number and immediately begin a normal wild encounter with the corresponding Pokémon.

### Usage

1. Select **SUMMON**.
2. Enter the Pokédex number.
3. Check the Pokémon name displayed in the window.
4. Select **OK**.
5. Begin the wild encounter.

---

## Universal Free TM Shop

**Current version: v1.0.0**

Speaking to the clerk in any Poké Mart opens a new menu with the following options:

- **NORMAL SHOP** — opens the Mart's original item catalog;
- **TM SHOP** — opens a catalog containing every TM from TM01 to TM50;
- **LEAVE** — closes the shop menu.

### TM Shop Features

- TMs are sorted numerically.
- Each entry also displays the move contained in the TM.
- Every TM is sold for `0`.

---

# ART Mods

## Modern Battle UI


A complete overhaul of the battle interface, redesigned to provide a more modern, readable, and information-rich battle experience.

### Main Features

- **Completely redesigned battle HUD** with floating panels for the player's Pokémon and the opponent.
- Modern HP bars, level display, status information, and improved readability.
- **Fully redesigned command menu** with a true horizontal layout:

```text
FIGHT → BAG → POKéMON → RUN
```

### Modern FIGHT Menu

The **FIGHT** menu now displays:

- move name;
- PP;
- type;
- power;
- accuracy;
- additional move information.

It also shows the move's effectiveness against the current opposing Pokémon directly in the menu:

- **SUPER x4**
- **SUPER x2**
- **NORMAL x1**
- **RESIST x0.5**
- **RESIST x0.25**
- **NO EFFECT**

### Modern Party UI

The in-battle Party screen has been completely redesigned.

It uses a more efficient layout with:

- a compact Pokémon list on the left;
- a detailed information panel on the right.

The selected Pokémon panel immediately displays:

- icon;
- name;
- type;
- level;
- status;
- HP;
- main stats;
- moves.

The interface also analyzes the selected Pokémon's moves against the current opponent, allowing you to immediately identify the most effective options.

A **BEST OPTION** indicator highlights the move with the strongest matchup against the current enemy.

### Modern Battle Bag

The in-battle Bag has also been redesigned with:

- an item list on the left;
- a complete item information panel on the right.

The Bag displays:

- item icon;
- item name;
- category;
- quantity;
- description.

---

## Modern UI Gen 2

Improves the game's interface with a more modern, cleaner, and more readable design.

The mod refreshes the visual presentation of the game UI while preserving the original gameplay flow, making menus and interface elements easier to read and more pleasant to use.

---

## new_icons

**Current version: v1.0.2**

Replaces the game's **small Pokémon icons** with a new set of custom icons.

---

## new_sprites

**Current version: v1.0.0**

Replaces the original **Pokémon sprites** with a new set of **modern sprites**.

---

## New Item Icons

Adds a new icon set for items.

### Features

- Includes **88 images** in total.
- **70 sprites** for regular items.
- **18 dedicated sprites** for **TM/HM types**.

---

# Debugging

## Performance Monitor


A diagnostic tool designed to capture detailed performance data when you encounter lag in a specific area, menu, or battle.

### How to Use

Go to the area, menu, or battle where you notice performance issues and press **F8**.

The monitor records performance data for **10 seconds** and then automatically exports:

```text
performance_report_latest.json
```

It also creates a human-readable version:

```text
performance_report_latest.txt
```

After the test, you can press **F9** at any time to export the latest report again.

### Report Contents

The exported report includes:

- every **frame time** recorded during the 10-second capture;
- real FPS;
- average frame time;
- median frame time;
- **P95** and **P99** frame times;
- **1% low**;
- worst frame;
- number of frames exceeding the **16.67 ms** frame budget;
- number of frames above **18.5 ms**;
- number of frames above **33.3 ms**;
- every individual **slow frame**, including the exact time when it occurred;
- active map and screen at the time of the slow frame;
- the mod consuming the most CPU during that frame;
- second, third, and fourth highest contributors;
- **Deep Lua Profiler** results;
- exact performance hotspot, for example:
  - `main.lua:428`
  - `render.hud`
  - a quest callback
  - other exact Lua hotspots;
- exclusive CPU usage for each mod;
- worst callback for each mod;
- calls per second;
- draw calls generated by each mod;
- canvas switches;
- shader switches;
- Lua RAM usage;
- texture memory usage;
- performance trends sampled every **0.25 seconds**;
- real Logic Steps;
- complete list of loaded mods;
- **exact version of every mod**;
- priority;
- dependencies;
- load order.

### Export Location

Reports are exported to:

```text
AppData\Roaming\pokemon-love2d\mod_storage\
```

---

# Quest Mods


---

## Download

Download all mods from the official repository:

**[github.com/FAFF0x/gen2recomp](https://github.com/FAFF0x/gen2recomp)**
