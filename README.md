# 🎬 Movie Frame Extractor

A simple, browser-based tool to extract frames from video files (.mov, .mp4) and save them as PNG images.

## Features

- **Drag & Drop** - Simply drag your video file onto the page
- **Frame Scrubber** - Slide through your video to find the exact frame
- **Live Preview** - See the frame before you extract it
- **Quick Navigation** - Jump to first/last frame or step through one at a time
- **Full Resolution Export** - Extracted PNGs match your video's resolution
- **Keyboard Shortcuts** - Arrow keys, Home/End, and S to save

## Usage

1. Open `index.html` in your browser
2. Drag a .mov or .mp4 file onto the drop zone (or click to browse)
3. Use the scrubber or buttons to navigate to your desired frame
4. Click "Extract as PNG" to download the frame

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| ← | Previous frame |
| → | Next frame |
| Home | First frame |
| End | Last frame |
| S | Save current frame |

## Technical Notes

- Works entirely in-browser (no server required)
- Uses the Canvas API to capture frames
- Assumes 30fps for frame estimation
- No dependencies - pure HTML/CSS/JS

## License

MIT
