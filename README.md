# Queue

A turn-based roguelike where you program your moves instead of making them. Write a short queue of instructions, read the enemies' scripts, and press RUN: everything happens at the same time.

You play **Q-1**, a small garbage-collection robot sent into a data center that has been shut down, to clean up the rogue processes before they take over the machine.

This repository only holds the ready-to-play builds. The game is in early development: Sector 1 is playable from start to finish, with its boss.

## Download

Get the latest version from **[Releases](../../releases/latest)**:

| System | File |
|---|---|
| Windows (64-bit) | `Queue-windows.zip` |
| macOS (Intel and Apple Silicon) | `Queue-macos.zip` |
| Linux (64-bit) | `Queue-linux.zip` |

Unzip it and follow the steps for your system below. Each zip also includes a `HOW-TO-PLAY.txt` with the same instructions.

You only need to do this once. From version 0.2.1 on, the game updates itself (see [Updates](#updates)). If you have an older version, download 0.2.1 or newer one last time.

## Opening the game

The builds aren't signed, since that requires paid developer accounts, so your system will warn you the first time.

- **Windows:** double-click `Queue.exe`. If Windows says it protected your PC, click **More info**, then **Run anyway**.
- **macOS:** first move `Queue.app` out of Downloads, for example into Applications, so it can update itself. Then double-click it. When macOS says it can't verify the developer, click **Done**, then go to **System Settings > Privacy & Security**, scroll down to "Queue was blocked", and click **Open Anyway**. If macOS instead says the app is **damaged**, open Terminal and run `xattr -cr /Applications/Queue.app` (use the path where you put it), then open it again.
- **Linux:** run `chmod +x Queue.x86_64` once, then `./Queue.x86_64`.

## Updates

When a new version is out, the title screen shows it in the bottom-right corner. Click **UPDATE** to download it; you can cancel while it downloads. Then click **INSTALL & RESTART**: the game closes, installs the new version and opens again. Your saved run is kept, and if anything goes wrong, the old version is put back. The game shows its version in the bottom-left corner of the title screen.

Updates installed this way don't bring back the Windows or macOS warning. If the game can't update itself (for example, a Mac app still in Downloads, or a folder you can't write to), it offers a button to this download page instead.

## How to play

- **Goal:** destroy every enemy in the room before your HP runs out.
- **Build a program:** click chips at the bottom, or use the arrow keys, **H** (HIT), **B** (BLOCK), **W** (WAIT), **T** (TURN) and the number keys. **Enter** runs it. Click a slot to remove a chip.
- **Read the board:** red tiles show where enemies will attack and on which tick. Amber numbers show where you will be.
- **Everything runs at once:** your program and every enemy's script play out tick by tick at the same time.
- **Hover anything** (chips, enemy script steps, enemies, tiles) to see what it does.
- **During playback:** hold **Space** to speed it up, and press **Esc** to skip to the end.
- **Fullscreen:** press **F11**.
- **Between fights:** pick new chips, visit shops and compilers, and choose your path up the map to the boss.

Your run is saved automatically, so choose **CONTINUE** on the title screen to pick up where you left off. **SANDBOX** lets you try every room and chip freely.

## Feedback

Found a bug, or something that felt unfair or confusing? Tell me! It helps to mention the room, what you expected, and what happened. Screenshots help too.
