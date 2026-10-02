# Mafia II First-Person — 120° FOV

A wider field of view for a Mafia II first-person camera configuration on PC.

This mod sets the main player-camera FOV to **120°**, indoors and outdoors, for standing, running, sprinting, climbing, and the normal aiming camera. The separate zoom-camera settings remain at **45°**.

## Download

[Download tables.sds](https://github.com/AygunVarol/mafia-ii-first-person-120-fov/releases/latest/download/tables.sds)

You can also download the ZIP package from the [Releases page](https://github.com/AygunVarol/mafia-ii-first-person-120-fov/releases).

## How to Install (Definitive Edition Example)

1. **Close the game and back up your original game files before making any changes.** Copy the existing `tables.sds` to a safe location outside the game's folder.
2. Download this repository's **120° FOV** `tables.sds` from the link above. If you download the ZIP package, extract it first.
3. Place the downloaded `tables.sds` directly into your game's directory:

   ```text
   Mafia II Definitive Edition/pc/sds/tables/
   ```

   Overwrite the existing `tables.sds` only after backing it up. The final file path should be:

   ```text
   Mafia II Definitive Edition/pc/sds/tables/tables.sds
   ```

4. Launch the game and try the wider first-person view.

The directory above is a Definitive Edition installation example. Use the matching `pc/sds/tables` folder inside your own Mafia II installation.

## Uninstall

Close the game, then restore your backed-up `tables.sds` to the same folder.

## Compatibility

- This is a replacement `tables.sds` archive. Other mods that replace this same file may overwrite each other's changes.
- Only the **120° FOV** variant is included in this repository.
- File structure, resource-header hashes, and the edited camera values have been checked. In-game behavior and compatibility across game editions have not been independently verified.

## File Verification

The included `tables.sds` is **2,330,589 bytes**. Its SHA-256 checksum is:

```text
68015a77474af8e460d530b242c25984429c51801ccfc794cfa8262959b917f1
```

The main FOV was changed from 55 to 120 in 14 player-camera settings. The first-person configuration comes from the supplied base archive; this release applies the FOV adjustment.
