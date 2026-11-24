# Resolve AutoSort (`v5.74`)

Automated media organizer for **DaVinci Resolve** projects (`.drp`, `.otio`, `.xml`, `.fcpxml`) by **Ksajlu** (`@ksajlu.avi`).

Resolve AutoSort scans your project files, detects referenced media assets and image sequences, categorizes files automatically, flags offline media, and copies or moves everything into a clean folder structure—optionally packing the result into a `.ZIP` archive and generating reports.

---

## Key Features

* **Project Parsing**: Supports `.drp` (database & XML), `.otio`, `.xml`, and `.fcpxml`, including an option to scan **timeline clips only**.
* **Automatic Categorization**: Sorts media into **Footage**, **Voiceover**, **Music**, **SFX**, **Graphics**, and **Other**, with customizable keyword rules and double-click category overrides in the preview table.
* **Image Sequence Handling**: Detects numbered image sequences and organizes frames into dedicated sequence subfolders.
* **Copy & Move Modes**: Copy files safely or move source files with a confirmation prompt, custom worker thread count, and **BLAKE2b** checksum verification.
* **Offline Media Detection & Relinking**: Highlights missing files, generates `missing_files.txt`, and lets you search a folder to relink offline assets.
* **Export & Reports**: Exports asset lists (`.csv`, `.json`, `.txt`), writes transfer reports (`copied_files.txt` / `moved_files.txt`), and optionally zips the sorted output.
* **Customizable UI**: Dark studio interface with accent color presets, custom HEX / color wheel picker, operation history, and lifetime stats.

---

## Download & Installation

1. Download **`ResolveAutoSort_v5.74_Setup.exe`** from the **Releases** section.
2. Run the installer and follow the setup wizard (optional desktop shortcut and automatic launch after install).
3. Select your project file (`.drp` / `.otio` / `.xml` / `.fcpxml`), choose a destination folder, adjust options, and click **Sort & Copy Files** (or **Sort & Move Files**).

---

## License & Usage

Copyright © 2026 **Ksajlu** (`@ksajlu.avi`). All rights reserved.

Resolve AutoSort is free for personal and commercial use. Unauthorized redistribution, re-uploading, resale (including bundling in paid packs), reverse engineering, or decompilation without the author's explicit permission is strictly prohibited.

---

## Links

* Instagram: [@ksajlu.avi](https://instagram.com/ksajlu.avi)
