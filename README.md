## Author

Chinmay Rozekar

# mpv Stream Console

A lightweight terminal-based media launcher built around **mpv** and **yt-dlp**. Perfect for long Terminal/ coding sessions.

This tool allows you to quickly stream online audio or video sources directly from the terminal, including YouTube live streams, YouTube search results, and SoundCloud links. It is designed to be simple, fast, and scriptable.

---

## Features

- Play YouTube live streams via search
- Stream individual YouTube videos
- Stream SoundCloud tracks
- Predefined station list support
- Simple interactive terminal menu
- Minimal dependencies
- Fully scriptable and customizable

---

## Requirements

Make sure the following tools are installed:

- `mpv`
- `yt-dlp`
- `bash` (version 4 or higher recommended)

### Install on macOS (Homebrew)

```bash
brew install mpv yt-dlp

---

## Platform Support

This project is developed and tested on **macOS** using Homebrew.

It can also run on:

- **Linux** (install `mpv` and `yt-dlp` via your distribution’s package manager)
- **Windows** using WSL (Windows Subsystem for Linux) or Git Bash

Note: The script uses Bash features such as arrays, so it must be run in a Bash-compatible shell.
