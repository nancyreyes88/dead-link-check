![Dead Link Check](assets/hero.png)

# Dead Link Check

*Broken links in a docs folder.*

## About

**Dead Link Check** runs on your own PC. Check markdown and HTML files for http links that do not return 200.

A README collects dead URLs over a year.

Meant for a local repo or a config file on disk. No hosted workspace.

## Editions

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Highlights

- md and html
- Status CSV
- Timeout
- Skips localhost optional

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/nancyreyes88/dead-link-check

MIT license. See `LICENSE`.
