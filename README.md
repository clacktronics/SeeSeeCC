# SeeSeeCC

A simple local HTML app for viewing MIDI Control Change (CC) messages from MIDI files, displayed as DAW-style automation lanes.

**Vibe coded with [Claude Code](https://claude.ai/code)**

## Features

- **Drag & drop** or click to load MIDI files (.mid, .midi)
- **DAW-style automation lanes** showing CC data over time
- **Step visualization** matching how most DAWs display automation
- **Filter by channel and CC number** to focus on specific data
- **Zoom control** with fit-to-view button for quick overview
- **Hover tooltips** showing exact time and value
- **60+ standard CC names** (Modulation, Volume, Pan, Sustain, etc.)

## Usage

Just open `index.html` in any modern browser. No server or build step required.

1. Drop a MIDI file onto the upload area (or click to browse)
2. View CC automation across all channels and controllers
3. Use filters to narrow down to specific channels or CC numbers
4. Zoom in/out or click "Fit" to see the full duration

## Screenshot

![SeeSeeCC Screenshot](screenshot.png)

## Tech

- Pure HTML/CSS/JavaScript - no dependencies except [Skeleton CSS](http://getskeleton.com/) via CDN
- Parses MIDI binary format directly in the browser
- Canvas-based rendering for smooth automation display

## License

MIT
