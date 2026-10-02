# Pop Chain — test builds

A hypercasual puzzle game: tap a tray cube, it flies straight up its column and bursts into balls that chain through the
wall. **25 levels** across three worlds (Candy Garden 1–10 · Coral Cove 11–20 · Crystal Cave 21–25), with boosters,
lessons, a shop, a season board and a lives system.

## Mac

1. Download **[Popchain-Mac.zip](https://github.com/Kalempox/popchain/raw/main/Popchain-Mac.zip)**.
2. Double-click the zip (in Downloads); `Popchain.app` appears next to it.
3. The app is not signed by Apple, so macOS stops the first launch:
   - **Right-click (or Control-click) `Popchain.app` → Open → Open.**
   - If macOS only offers "Move to Trash" / "Done": press **Done**, then open **System Settings → Privacy & Security**,
     scroll down to *"Popchain" was blocked* and press **Open Anyway** (then **Open**).
   - If macOS says *"Popchain is damaged and can't be opened"*: open **Terminal** and run
     `xattr -cr ~/Downloads/Popchain.app` (the path where the app is), then open it again.
4. On a Mac with Apple silicon (M1–M4) the app runs through Rosetta; if macOS asks to install Rosetta, press **Install**.
   Needs macOS 12 or later.

## Windows

1. Download **[Popchain-Windows.zip](https://github.com/Kalempox/popchain/raw/main/Popchain-Windows.zip)** and extract it
   (right-click → **Extract All…**).
2. Double-click **`Popchain.exe`** in the extracted `Popchain` folder (the whole folder is needed).
3. If Windows says *"Windows protected your PC"*: **More info → Run anyway**.

## How to play

Click a cube in the tray: it flies straight up its column and bursts into balls; hold to see which cube it will hit,
release to fire. Clear the wall before the moves run out.

The app opens in a phone-shaped, resizable window; progress is saved between launches. Press **F** for the frame-rate
readout. Built with Unity 6 (6000.3.10f1), URP.
