# 2025class5.github.io

English | [简体中文](README_zh.md)

A static browser music player with playback, progress and volume controls.

## Overview

The page packages audio playback in a responsive single-page interface. Playback runs in the browser without an application backend. The landing page excludes class photographs and personal bylines.

## Technology and Dependencies

HTML, CSS, JavaScript and the browser audio API. Python 3 is optional for serving local files. Audio assets are stored alongside the pages.

## Repository Structure

- `index.html` — main player page
- `music.html` — alternate music page
- `music.mp3` — audio asset
- `.github/` — hosting workflow

## Quick Start

Run a static server from the repository root:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000/`. No frontend compilation is required. Network access is needed for externally hosted resources.

Start playback with the play button, drag the progress control and adjust volume. Browser autoplay restrictions may require a user gesture.
