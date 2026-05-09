# HS Value Scanner

Part of the **Hero Siege Offline Toolkit**.

> Offline / single-player value scanning tool for Hero Siege.  
> Main hub: https://github.com/falorfrozen-cmd/hero-siege-offline-toolkit

---

HS Value Scanner v1.0.1
=======================

Unofficial value scanner/editor for Hero Siege offline/single-player use.

What is included
----------------
- HSValueScanner.exe: Standalone Windows executable.
- HS_Value_Scanner_Instructions.txt: Full usage guide.
- Step1.png, Step2.png, Step3.png: Visual guide for persistent pointer addresses.
- RELEASE_NOTES.md: Update notes for this release.

Quick start
-----------
1. Start Hero Siege in offline/single-player mode.
2. Run HSValueScanner.exe.
3. Click Select Process and choose Hero_Siege.exe.
4. Scan for your value as usual.
5. Add the correct address to Favorites.
6. Right-click the favorite and choose Find Pointer Path.
7. Wait until the Log says Pointer path found.
8. Save your preset.

Persistent addresses and presets
--------------------------------
Favorites can now store pointer paths. When a pointer path is found, the editor can resolve that saved address again after the game is restarted.

Presets let you organize groups of favorites. For example, you can create a preset for Magic Find or another preset for a different stat setup.

Important notes
---------------
- Intended for offline/single-player use only.
- Do not use with multiplayer, online characters, leaderboards, trading, or anti-cheat protected modes.
- Pointer paths may need to be recreated after major game updates.
- Run the tool as administrator if Windows asks for permission.
