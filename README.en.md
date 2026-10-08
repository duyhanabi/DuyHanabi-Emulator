# DuyHanabi Emulator 1.0.0

[Bản tiếng Việt](README.md)

**DuyHanabi Emulator** runs Java ME (J2ME/MIDP) games on Windows. Select a JAR or JAD file to run it in the built-in Java ME environment.

## Features

- A standalone Windows x64 EXE bundling the application and Java runtime; Java does not need to be installed separately.
- Vietnamese by default, with an option to switch to English.
- Uses **Resizable device** by default; choose another device profile or resize the emulated screen.
- Nearest-neighbor scaling to keep pixel art crisp, plus GIF screen recording.
- FPS, CPU, and RAM display; log viewer, thread information, and RecordStore management.
- Coordinate-based auto-click, keyboard and mouse macro recording/playback, and automatic sleep after hiding the window.
- Up to 50 emulator sessions, arranged in horizontal rows, vertical columns, or automatically; choose a master tab and synchronize controls.
- Manage imported JARs, clear an individual game's data, or clear all emulator-managed data.

## Download and run

Download **DuyHanabi Emulator.exe** from **Releases** and run it on 64-bit Windows. The first launch may take longer because the EXE extracts the application and runtime to a cache; later launches reuse the extracted files.

Settings and game data are stored in `%USERPROFILE%\.duyhanabiemulator`. If older data exists in `%USERPROFILE%\.microemulator`, the application copies it to the new folder on first launch.

## Notes

- Compatibility depends on the APIs used by each game.
- Frame rate is controlled by the game; the emulator does not force every game to run at a fixed FPS.
- RAM optimization requests Java garbage collection; it cannot free objects that a game is still using.
- The package contains MicroEmulator and Java runtime components. See the license and attribution notices included with each release.

This GitHub page is for product information and binary releases. Project source code is not included.
