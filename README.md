# Silent Hill Homecoming – Fix Patch

An unofficial fix-and-enhancement patch for the **Steam PC version** of Silent Hill Homecoming. It fixes many of the port's long-standing problems: broken audio panning, missing display options, camera clipping, crashes, stutter and limited controller support. It also adds proper 16:10 support and new options to the in-game menus.

Everything is applied by a small installer that checks your game files, keeps backups, and can restore the original game at any time.

---

## Display & Graphics
- **Display Mode:** Borderless, Fullscreen or Windowed.
- **Resolution list** read from your graphics card.
- **Screen Fit: Letterbox or Fill.**
  - Fill gives true **16:10** (and taller) output with a wider vertical view.
  - Menus, HUD, inspected items and documents stay at their correct 16:9 shape in the centre.
- **Black bars in Fill mode** around menus, loading screens and the inventory and combat wheels, so nothing outside the menu shows.
- **FMVs play at 16:9** instead of being stretched.
- **FPS limit** (30 / 60 / 120 / 144 / 160 / 240) and **VSync**.
- **Field of View**, **Anisotropic Filtering** (up to 16x), **Shadow Resolution**, **Reflections** and other graphics toggles.
- **Camera clipping fixed** on the map, documents and item inspection; inspected items keep their proper proportions.
- **Alt-tab fixed** in exclusive fullscreen: no crash, and the menu video and textures come back correctly.

## Audio
- New **Speakers** option: Stereo, Headphones or 5.1.
- **Dialogue and mono sounds** no longer play only from the left speaker.
- **Full stereo panning** in Stereo and Headphones, instead of a narrow folded-down surround mix.
- **Nearby sounds** (Alex's voice, doors) no longer snap hard left or right.
- **Cutscene soundtracks** (5.1 audio) are downmixed properly, so cutscene dialogue is centred.
- **Voice volume slider** goes up to twice the original maximum.
- Lower audio latency; fixed ambient volume not coming back.

## Controls
- **Button prompts:** PC, Xbox or PlayStation, switching instantly from the options menu.
- **Redesigned controller icons.**
- **Correct struggle prompt.**
- **Controller hot-plug:** connect a pad after starting the game without one.

## Stability & Performance
- Fixed the **progressive stutter and eventual freeze** caused by the game's memory tracking.
- No false "Not Responding" during boot logos and loading.
- **4 GB memory support** (Large Address Aware).
- **DPI-aware:** no blur or wrong sizing with Windows display scaling.
- The launcher waits for a closing previous session instead of silently quitting.
- New options are translated in **English, French, German and Spanish** menus.

---

## Installation
1. Close the game.
2. Extract the zip and run **SHH_Fix_Patch.exe**. Keep **SHH_Patch.dat** in the same folder.
3. Confirm the detected game folder (or use **Browse…**) and click **Install**.
   - If Windows blocks changes to the game folder (for example under Program Files), the installer offers to restart itself as administrator. Click **Yes**, then **Install** again.

The installer:
- checks each file against the original Steam version before changing it, and verifies it again afterwards
- keeps untouched copies of the originals next to each file as `*.shhorig`
- is safe to run again: files that are already patched are skipped

## Uninstallation
Run **SHH_Fix_Patch.exe** and click **Uninstall**. The original files are restored from the backups.

## Requirements
- Steam PC version of Silent Hill Homecoming (unmodified files).
- 64-bit Windows 7 or later.

## Notes
- The installer isn't code-signed, so Windows SmartScreen may show "Windows protected your PC". Click **More info → Run anyway**.
- A few antivirus engines that are prone to false positives (such as Bkav Pro) may flag the unsigned installer. It only reads and writes the game files listed above.
- Fill mode currently targets displays taller than 16:9, such as 16:10. Ultrawide support is planned.
- In 5.1 mode, cutscene soundtracks play as the game's original 5.1 mix.
- The "Press Start" screen at boot doesn't get black bars in Fill mode.

## Credits
Developed with AI (Claude by Anthropic); directed and tested by the mod author.
