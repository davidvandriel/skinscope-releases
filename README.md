# SkinScope

Real-time skin tone and exposure analysis for video professionals.

## What is SkinScope?

SkinScope captures any region of your screen and displays it with broadcast-style analysis overlays. Use it to evaluate skin tone accuracy and exposure while color grading, shooting tethered, or reviewing footage.

A free, lightweight alternative to ScopeBox.

## Features

- **Real-time capture** — 30 fps screen region capture
- **Skin Exposure mode** — False color overlay showing under/over exposure zones
- **Skin Tone mode** — Vectorscope-style color cast detection (neutral, green, magenta)
- **Face detection** — Automatic analysis suggestions when faces are detected
- **Always-on-top** — Keep the preview visible while you work

## Download

**macOS** (Big Sur+): [Download .app](https://github.com/davidvandriel/skinscope/releases/latest)

**Windows** (10+): [Download .exe](https://github.com/davidvandriel/skinscope/releases/latest)

## Quick Start

1. **macOS**: Grant Screen Recording permission when prompted
2. Drag to position the capture region over your video
3. Press **1**, **2**, or **3** to switch analysis modes

## Analysis Modes

| Key | Mode | What it shows |
|-----|------|---------------|
| 1 | Passthrough | Original image with face detection |
| 2 | Skin Exposure | False color: green=dark skin, gray=midtones, pink=light skin |
| 3 | Skin Tone | Color cast: yellow=neutral, green=green cast, magenta=magenta cast |

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| 1 / 2 / 3 | Switch modes |
| Cmd/Ctrl+T | Toggle always-on-top |
| Cmd/Ctrl+Q | Quit |

## Building from Source

```bash
git clone https://github.com/davidvandriel/skinscope.git
cd skinscope
pip install -r requirements.txt
python3 main.py
```

## License

MIT
