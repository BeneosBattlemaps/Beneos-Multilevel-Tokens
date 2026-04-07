# Change Log

All notable changes to this module will be documented in this file.

## Updates
### 14.0.0 # 2026-04-07
- Update: Full compatibility with Foundry VTT V14 while maintaining V13 support
- New: **Pause MLT** setting — disable all teleportation and hide navigation map notes from players without deactivating the module. Ideal for using maps individually without world interconnectivity.
- New: **GM Teleport Notifications** — the GM receives a whispered chat message whenever a token teleports, showing the destination scene with a "View Scene" button to follow and center the camera on the token.
- New: **Teleport Sound Effects** — assign a custom sound file per teleport region (e.g. door creak, portal hum, staircase steps) that plays when a token teleports.
- New: **Teleport Arrival Animation** — tokens fade in smoothly at their destination for clear visual feedback.
- New: **Tooltip Help Icons** — every setting in the Drawing Config tab now has a hover tooltip explaining its function.
- Fixed: Replaced all deprecated `foundry.utils.duplicate()` calls with modern alternatives for future-proofing.
- Fixed: Replaced bare class references (`Token.embeddedName`, etc.) with version-safe string literals.
- Fixed: Chat bubble emote detection now works correctly in both V13 and V14.
- Fixed: Token actor linking is safely guarded for V14 compatibility.
- Fixed: HexagonalGrid snap and Combat API use feature detection for V13/V14 dual support.
- Improved: Drawing Config tab layout — checkboxes align properly next to their labels instead of floating to the far right.
- Improved: Module settings panel is now organized into clear sections (Pause, Teleportation, Token Cloning) with visual dividers.

### 13.0.3 # 2026-03-05
- Fixed: Error message on specific maps

### 13.0.2 # 2025-08-11
- Fixed: A bug that prevented players from leaving a teleporter field on teleporters without note activation.

### 13.0.1 # 2025-07-18
- Fixed: A CSS issue that was blocking some worlds with DD5

### 13.0.0 # 2025-05-20
- Update: V13 compatibility
- Removed: Added max Foundry Versions to older module versions to make them appear only in compatible versions.

### 1.7.5 # 2024-06-25
- Fixed a legacy bug leading to selecting shapes on the canvas when clicking on a teleport journal.

### 1.7.2 # 2024-06-21
- Fixed an legacy bug preventing MLT from being used with Foundry VTT V11

### 1.7.1 # 2024-06-16
- Beneos officially took over the development of the Multilevel Tokens module
- Added FoundryVTT V12 compatibility
- Fixed Token Cloning Error Messages