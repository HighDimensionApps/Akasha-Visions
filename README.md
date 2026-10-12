✦ Akasha Visions ✦

**Real-time psychedelic visuals that react to your music.**
An audio-reactive generator built with WebGL: a single HTML file—no libraries, no installation, and no server required.

> 🔗 **Live Demo:** _(https://highdimensionapps.github.io/Askasha-Visions/)_

---

## ✨ Features

### 🎨 Visuals
- **12 shader-generated modes:** Neon Fractal, Liquid Plasma, Infinite Tunnel, Mandala Warp, Animated Julia Set, Chladni Figures, Liquid Voronoi, Sacred Geometry (Flower of Life & Metatron's Cube), Menger Sponge (raymarching), Metaballs, Flow Particles, and Expanding Universe.
- **Real video feedback:** each frame blends with the previous one—rotated and scaled—to create infinite tunnels and trails.
- **9 color palettes:** Rainbow, Sunset, Toxic, Ice, Monochrome, Fire, Ocean, Pastel, and Neon.
- **Over 15 real-time controls:** speed, rotation, zoom, kaleidoscope, distortion, hue, saturation, brightness, and more.
- **Ready-to-use presets** plus random mode and auto-mutation buttons.

### 🎵 Audio
- **Built-in player:** load your songs or drag and drop them into the window; features playlist, shuffle, repeat, and live spectrum display.
- **Three audio sources:** local files, microphone, and **tab audio** (Spotify Web, YouTube, etc.).
- **Band-based analysis:** bass, mid, and treble frequencies control zoom, color, and distortion.
- **Beat detection:** triggers light pulses and rotation, plus automatic visual switching synchronized to the rhythm. ### 🛠️ Tools
- **Video recording with audio** in WebM format, ready for social media upload.
- **MIDI support:** control sliders using a physical controller (assign via double-click).
- **Touch-reactive waves** and **gyroscope support** on mobile devices.
- **Song title display** with typographic effects.
- **Dynamic resolution:** automatically lowers quality if the frame rate drops.
- **Screenshot** and full-screen mode.

### 🌐 More
- **Bilingual:** Spanish and English.
- **Installable as an app** on PC and mobile (PWA), with offline mode.
- **Safe mode** to soften flashes, with a photosensitivity warning upon startup.

---

## 🚀 Usage

1. Download or clone the repository.
2. Open `akasha_visions.html` in your browser or visit the demo.
3. Load music using the 📂 button or by dragging and dropping files, then adjust the panel controls.

To install it as an app, you need to serve it via **HTTPS** or from **localhost**. For example:

```bash
python -m http.server 8000
# open http://localhost:8000/akasha_visions.html
```

## ⌨️ Shortcuts

| Key | Action |
|---|---|
| `Space` | Pause visuals |
| `R` | Randomize |
| `H` | Hide panel |
| `F` | Full screen |
| `S` | Screenshot |
| `1`-`9`, `[` `]` | Change mode |
| `P` | Play / pause music |
| `N` / `B` | Next / previous |
| `←` / `→` | Rewind / fast-forward 5s |
| `M` | Mute | Show or hide the player |

## 🎹 MIDI

CC controls 21 and up move the sliders in order. To assign your own, double-click the slider and move a knob on your controller.

## 🌍 Compatibility

- **Chrome and Edge** (recommended): all features, including MIDI and tab audio.
- **Safari and Firefox:** visuals, player, and microphone. Web MIDI and app installation depend on the browser.
- Requires a device with **WebGL**.

## ⚠️ Photosensitivity warning

This application displays flashing lights, rapid movement, and intense patterns that may trigger seizures in people with photosensitive epilepsy. Use **safe mode** or avoid using the app if you are sensitive.

## 🧩 Technology

Vanilla HTML, CSS, and JavaScript; GLSL (WebGL 1); Web Audio API; MediaRecorder; Web MIDI; and Service Workers. No external dependencies.

## ❤️ Credits and support

Created by **High Dimension Apps**.
If you like the project, you can support it:
