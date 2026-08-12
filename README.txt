========================================================
  RAGE LIGHT EDITOR  —  Portable Edition
========================================================

A standalone tool for previewing and editing the lights embedded in GTA V
models (.ydr / .yft), using the game's real RAGE lighting so the preview
matches in-game / CodeWalker.


REQUIREMENTS
------------
  * Windows 10 or 11, 64-bit
  * A Direct3D 11 capable GPU
  * NOTHING TO INSTALL — the .NET runtime is bundled inside this package.


HOW TO RUN
----------
  1. Extract this ZIP anywhere.
  2. Double-click  "RAGE Light Editor.exe"  — that is the whole program,
     one single file, nothing to install.
  3. Drag & drop a .ydr or .yft onto the window to load it.
     Drop more files to add them to the same scene (shell + light proxies).

  (The first launch takes a few extra seconds while it unpacks internally;
   after that it starts quickly.)


QUICK START
-----------
  * Left-drag = orbit, right/middle-drag = pan, wheel = zoom, F = frame.
  * Click a light's marker (or the left list) to select it. Ctrl/Shift-click
    for multi-select.
  * Q / W / E = Select / Move / Rotate gizmo (like 3ds Max). Shift-drag the
    move gizmo to clone.
  * Arrow keys or V = walk through the scene; Enter/Esc exits walk mode.
  * The right panel edits every light parameter (colour, intensity, falloff,
    cone, corona, volume, shadows, flags, time flags, projected texture...).
  * Ctrl+S saves lights back into the file (a one-time .bak backup is kept).
    With several props loaded, each has its own Save (S) button.
  * Click "Tutorial" in the app for the full guide.

  Interiors with no lights look dark — raise "Ambient" or set Shading to
  "Unlit" to inspect the geometry.


NOTES
-----
  * This is a portable app. Your preferences (shortcuts, theme, panel sizes)
    are saved to settings.json next to the program. Delete it to reset.
  * Saved files are standard RSC7 (legacy/gen8) resources — import them back
    into your RPF with OpenIV or CodeWalker.
  * Projected textures you import are for PREVIEW; for the game the texture
    must be shipped inside a .ytd with the same name.

See CREDITS.txt for attributions and license information.
