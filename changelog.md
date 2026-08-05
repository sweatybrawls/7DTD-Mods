# Changelog

All notable changes to this project will be documented in this file.

This project follows a simple versioning format:

- **Major** – Significant gameplay or compatibility changes
- **Minor** – New mods or quality-of-life additions
- **Patch** – Bug fixes, configuration changes, or mod updates

---

## [1.0.0] - 2026-08-05

### Initial Release

Initial Vanilla+ mod pack for a dedicated 7 Days to Die V3.1.x server.

### Added

- AGF BackpackPlus 60 Slots
  - Increased backpack size to 60 slots while preserving vanilla encumbrance progression.
  - Server-compatible and EAC-friendly.

- Craft From Containers
  - Craft using materials from nearby storage.
  - Supports repairing, upgrading, reloading, refueling, and trader purchases from nearby containers.
  - Configured with a **12-block crafting range**.

- Simple HP Bar V2
  - Displays health bars for zombies and animals.
  - Improves combat awareness without changing gameplay balance.

### Configuration

Craft From Containers:

- Range reduced from unlimited to **12 blocks**.
- Debug logging disabled.
- Repair and Upgrade enabled.
- Trader integration enabled.
- Refueling enabled.
- Reloading enabled.
- Vehicle inventory support enabled.

### Notes

- Designed to preserve the vanilla gameplay experience while reducing repetitive inventory management.
- QuickStack was evaluated but excluded due to compatibility issues with 7 Days to Die V3.1.x.
- This repository serves as the canonical source for all server and client mod versions.