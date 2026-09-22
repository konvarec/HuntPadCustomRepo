# HuntPad

<img src="https://raw.githubusercontent.com/konvarec/HuntPadCustomRepo/main/images/huntpad-v2.png" alt="HuntPad icon" width="128">

HuntPad is an FFXIV / Dalamud companion for hunt activity. Open it with `/huntpad`.

## Features

- Display nearby players, mobs, and FATEs on a map
- Show risky-mob spawn candidates and record observed spawn points
- Automatically fit the map to the hunt area's spawn points
- Count S-rank trigger progress
- Notify on unobserved spawns and check risky-mob respawn-time data

## Installation

1. Open Dalamud Settings and go to **Experimental**.
2. Add this URL under **Custom Plugin Repositories**:

   ```text
   https://raw.githubusercontent.com/konvarec/HuntPadCustomRepo/main/pluginmaster.json
   ```

3. Reopen the Plugin Installer and install **HuntPad**.
4. Enter the distribution access key on first launch, then open the map with `/huntpad`.

The access key is shared with Observer (HuntVoidWatcher). Do not post it in this repository or in Issues.

## Quick Start

- Open the map: `/huntpad`
- Show spawn points: enable **MOBPOS** in the area's settings
- Fit the map to spawn points: enable **Auto-fit map to hunt spawn points** in shared settings
- Inspect spawn records: use **Copy POP record diagnostics** in shared settings

## Moving from 0.1.0.19 or Earlier

HuntPad 0.2.0.0 and later use a new internal identity. Disable the older plugin, refresh the Plugin Installer, and install HuntPad as a new plugin. Do not enable both versions at the same time.

On first launch only, if `HuntPad.json` does not yet exist, HuntPad imports your previous spawn records, settings, and access state. The previous settings file is kept as a backup.

## Repository Contents

- `pluginmaster.json`: repository index
- `HuntPad/<version>/latest.zip`: plugin package
- `images/huntpad-v2.png`: Plugin Installer icon

This repository contains no source code, logs, or access keys.
