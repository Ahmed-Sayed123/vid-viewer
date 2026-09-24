# ReelRoom

A clean, single-file video viewer that plays videos from your own device. No backend, no build step, no dependencies.

## Features

- Add multiple videos from your device (or drag and drop on desktop)
- Library with auto-generated thumbnails and durations
- Portrait and landscape layouts. Switches automatically when you rotate your phone, or manually with the layout button. In landscape the screen fills with the video, even if the phone is held upright.
- Double-tap the right side of the video to skip forward 10 seconds, the left side to go back. Keep tapping to add more.
- Settings button (top right of the video): playback speed, fit/fill, loop, play next, light/dark
- Light and dark themes (follows your device, remembers your choice)
- Seek bar, volume, fullscreen, keyboard shortcuts (Space, ←, →, F)
- Portrait videos are shown at their natural size without cropping

## Run locally

Open `index.html` in a browser. Videos never leave your device.

## Deploy on GitHub Pages

1. Create a new repository and upload the contents of this folder.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your viewer will be live at `https://<your-username>.github.io/<repo-name>/`.

## Notes

- Videos live only in the current browser session. Reloading the page clears the library.
- Playback depends on the formats your browser supports (MP4/H.264 and WebM work almost everywhere).
- The font is loaded from Google Fonts. Offline, the page falls back to system fonts.
