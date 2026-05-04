## HS Value Scanner v1.0.1

This update focuses on persistent addresses, preset management, and a cleaner value scanning workflow.

### Highlights

- Added persistent pointer path support for favorite addresses.
- Added automatic pointer resolving for saved favorites after attaching to `Hero_Siege.exe`.
- Added preset support for organizing different groups of favorite addresses.
- Added a visual instruction guide for creating persistent addresses.
- Simplified the scan type selector by keeping the practical visible types: `Float`, `Double`, and `4 Bytes`.
- Improved the Favorites workflow with pointer resolve tools and preset saving.

### Persistent Address Workflow

1. Find the value/address as usual.
2. Right-click the result and choose `Add to Favorites`.
3. Right-click the favorite and choose `Find Pointer Path`.
4. Wait until the Log says `Pointer path found`.
5. Save the preset.

After this, the editor can automatically resolve that saved address again when the game is restarted.

### Notes

- Intended for offline/single-player use only.
- Do not use with multiplayer, online characters, leaderboards, trading, or anti-cheat protected modes.
- Pointer paths are generally stable, but major game updates may require creating them again.
- Presets are saved locally next to the executable in `hs_favorites.json`.
