# Craftable Ender Pearls (Minecraft Bedrock Add-On)

A lightweight, survival-friendly Minecraft Bedrock Edition add-on that adds a balanced crafting recipe for Ender Pearls while preserving achievement compatibility.

## Crafting Recipe

Craft **1 Ender Pearl** at a Crafting Table using **4 Amethyst Shards** and **1 Slimeball**:

| | | |
| :---: | :---: | :---: |
| — | Amethyst Shard | — |
| Amethyst Shard | Slimeball | Amethyst Shard |
| — | Amethyst Shard | — |

The recipe automatically unlocks in the Recipe Book upon picking up an Amethyst Shard or a Slimeball.

## Features

* **Survival Balanced:** Requires exploring geodes (Amethyst Shards) and swamps/slime chunks (Slimeballs) rather than bypassing early-game progression.
* **Achievement Compatible:** Packaged as a paired Behavior Pack and Resource Pack utilizing `"product_type": "addon"` manifest metadata without experimental toggles.
* **Zero Dependencies:** Uses native vanilla item identifiers (`minecraft:amethyst_shard`, `minecraft:slime_ball`, `minecraft:ender_pearl`).

## Repository Structure

```text
craftable-ender-pearls/
├── CraftableEnderPearls_BP/
│   ├── manifest.json
│   └── recipes/
│       └── ender_pearl.json
├── CraftableEnderPearls_RP/
│   └── manifest.json
└── README.md
```

## Installation
### From Source 
Compress both CraftableEnderPearls_BP and CraftableEnderPearls_RP into a single .zip archive.

Rename the file extension from .zip to .mcaddon (e.g., CraftableEnderPearls.mcaddon).

Double-click the .mcaddon file to import both packs into Minecraft Bedrock Edition.

Edit your world settings, navigate to Behavior Packs, and activate Craftable Ender Pearls BP (the companion Resource Pack will link automatically).

### Manual Installation (Windows)
Copy CraftableEnderPearls_BP and CraftableEnderPearls_RP directly into your Bedrock com.mojang directory:

```
%APPDATA%\Minecraft Bedrock\Users\Shared\games\com.mojang\
```

## Compatibility
Minecraft Version: Bedrock Edition 1.21.0+

Experimental Toggles Required: None

### License
MIT License