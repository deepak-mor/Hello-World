# Cue Island

A teleprompter for iPhone. Your script scrolls in a dark window right under the front camera (by the Dynamic Island), so you read while looking at the lens.

## Features
- **Voice following**: listens as you read and keeps your place word by word. It waits when you pause and skips ahead when you jump.
- **Auto scroll** with adjustable speed (tap − / + while prompting).
- **Drag to scrub, tap to pause.** Space bar works with a keyboard.
- **Camera preview + recording**: see yourself behind the script and record a take, then Save to Photos.
- Window height from a slim strip under the camera to full screen, text size, mirror mode for glass rigs, countdown.
- Works offline once installed. Your script is saved on the phone.

## Put it on your iPhone
1. Host this folder on any HTTPS site. With GitHub Pages: repo **Settings → Pages → Deploy from a branch**, pick the branch and `/ (root)`.
2. Open the Pages URL in **Safari** on your iPhone.
3. Tap **Share → Add to Home Screen**. It opens full screen like an app.

Voice following uses Safari's speech recognition (iOS 14.5+). The first time, iOS asks for Microphone and Speech Recognition access.

## Files
- `index.html`: the whole app
- `manifest.webmanifest`, `sw.js`, `icons/`: home-screen install and offline support
