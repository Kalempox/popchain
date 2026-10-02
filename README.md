# Pop Chain — Windows test build

A hypercasual puzzle game: tap a tray cube, it flies straight up its column and bursts into balls that chain through the
wall. **25 levels** across three worlds (Candy Garden 1–10 · Coral Cove 11–20 · Crystal Cave 21–25), with boosters,
lessons, a shop, a season board and a lives system.

## How to play

1. Download **[Popchain-Windows.zip](Popchain-Windows.zip)** (52 MB) — on its page, press **Download raw file** (the ↓ button).
2. Right-click the zip → **Extract All…**
3. Open the extracted `Popchain` folder and double-click **`Popchain.exe`**. No installation needed.

The game opens in a phone-shaped window (resizable). Play with the mouse: tap (click) a cube in the tray; hold to see which
cube it will hit, release to fire.

- **Windows 10/11, 64-bit.** The whole `Popchain` folder is needed — `Popchain.exe` alone will not start.
- Windows may say *"Windows protected your PC"* (the build is not signed): press **More info → Run anyway**.
- Progress is saved between launches. To start over as a first install, run `Popchain.exe -freshSave`.
- Press **F** to show or hide the frame-rate readout.

Built with Unity 6 (6000.3.10f1), URP. Measured on this build at level 24 under load: 400+ fps average, frame p95 ≤ 4.1 ms.
