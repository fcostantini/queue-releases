# Queue

A turn-based roguelike where you program your moves instead of making them. Write a short queue of instructions, read the enemies' scripts, and press RUN: everything happens at the same time.

You play **Q-1**, a small garbage-collection robot sent into a data center that has been shut down, to clean up the rogue processes before they take over the machine.

This repository only holds the ready-to-play builds. The game is in early development: Sector 1 is playable from start to finish, with its boss.

## Download

Get the latest version from **[Releases](../../releases/latest)**:

| System | File |
|---|---|
| Windows (64-bit) | `Queue-windows-….zip` |
| macOS (Intel and Apple Silicon) | `Queue-macos-….zip` |
| Linux (64-bit) | `Queue-linux-….zip` |

Unzip it and follow the steps for your system below. Each zip also includes a `HOW-TO-PLAY.txt` with the same instructions.

## Opening the game

The builds aren't signed, since that requires paid developer accounts, so your system will warn you the first time.

- **Windows:** double-click `Queue.exe`. If Windows says it protected your PC, click **More info**, then **Run anyway**.
- **macOS:** right-click `Queue.app` and choose **Open**. If it still refuses, go to **System Settings > Privacy & Security**, scroll down, and click **Open Anyway** next to Queue. Or run `xattr -cr /path/to/Queue.app` in Terminal.
- **Linux:** run `chmod +x Queue.x86_64` once, then `./Queue.x86_64`.

## How to play

- **Goal:** destroy every enemy in the room before your HP runs out.
- **Build a program:** click chips at the bottom, or use the arrow keys, **H** (HIT), **B** (BLOCK), **W** (WAIT), **T** (TURN) and the number keys. **Enter** runs it. Click a slot to remove a chip.
- **Read the board:** red tiles show where enemies will attack and on which tick. Amber numbers show where you will be.
- **Everything runs at once:** your program and every enemy's script play out tick by tick at the same time.
- **Hover anything** (chips, enemy script steps, enemies, tiles) to see what it does.
- **During playback:** hold **Space** to speed it up, and press **Esc** to skip to the end.
- **Between fights:** pick new chips, visit shops and compilers, and choose your path up the map to the boss.

Your run is saved automatically, so choose **CONTINUE** on the title screen to pick up where you left off. **SANDBOX** lets you try every room and chip freely.

## Feedback

Found a bug, or something that felt unfair or confusing? Tell me! It helps to mention the room, what you expected, and what happened. Screenshots help too.
