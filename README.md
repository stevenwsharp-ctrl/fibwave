# Fibwave

**A music visualizer in one web page.** Fibwave listens to your music and turns it into moving art: golden-ratio patterns, GPU fractals, galaxies, oceans, mountains, sacred geometry, classic equalizers, the real night sky and 3D flights through space. Everything follows the beat, the bass, the melody, the key and the mood of the sound.

**Live site:** https://stevenwsharp-ctrl.github.io/fibwave/

- 87 scenes and 17 colour palettes
- No install, no account, no server: it runs in your browser
- Works on a laptop, on a 4K TV, and (with the microphone) on a phone

---

## Quick start

1. Open the live site in **Google Chrome** (best), or open `fibwave.html` on your Mac:
   ```
   open -a "Google Chrome" ~/Downloads/fibwave.html
   ```
2. Choose a **sound source** (see below).
3. Double-click the screen (or press **H**) to hide the controls. Double-click again to show them.
4. Use **← →** to change the scene and **↑ ↓** to change the colours.

---

## Sound sources

| Source | What it does | Notes |
|---|---|---|
| **Share a tab — YouTube or Spotify** | Takes the sound of another Chrome tab. | Chrome only. In the share window, select the music tab and keep **Share tab audio** on. Chrome shows a sharing bar at the top of the Fibwave tab. To see the visuals without it, use **Picture in picture** (Q). |
| **Microphone or BlackHole** | Listens to a sound input. | Use the microphone for room sound, or **BlackHole** for clean sound from any Mac app **with no sharing bar** (see below). |
| **Audio files** | Plays MP3, WAV, FLAC or M4A files from your computer. | You can also drag audio files onto the window. |
| **Paste a link** | Plays a YouTube or Spotify link inside Fibwave. | Only on the live site (not from a local file). Chrome shares the Fibwave tab, so the sharing bar shows. |
| **Demo beat** | A built-in 118 BPM loop. | For a quick test. |

On phones and tablets, browsers cannot share tab sound, so Fibwave uses the microphone. Turn the volume up.

### No sharing bar: BlackHole (Mac, free)

BlackHole is a virtual audio cable. The Mac sends its sound to your speakers (or TV) and to Fibwave at the same time, so Chrome never shares a tab and never shows a bar. It works with the Spotify app, Apple Music, YouTube and everything else.

**One-time setup (about 5 minutes):**

1. Download **BlackHole 2ch** from https://existential.audio/blackhole/ and install it. Restart the Mac if it asks.
2. Open **Audio MIDI Setup** (press Cmd + Space and type "Audio MIDI").
3. Click **+** (bottom left), then **Create Multi-Output Device**.
4. Select your normal output first (LG TV over HDMI, the Mac speakers or headphones), then select **BlackHole 2ch** and turn on **Drift Correction** for it.
5. Open **System Settings → Sound → Output** and choose **Multi-Output Device**.

**Each time:** play the music, click **Microphone or BlackHole** in Fibwave, and set **Sound input** to **BlackHole 2ch**. Fibwave remembers this choice.

With a Multi-Output Device, the Mac volume keys do not work. Set the volume on the TV, the speakers or the music app. When you are done, set the Mac output back to your normal speakers.

---

## Picture in picture (no sharing bar)

Click **Picture in picture** (or press **Q**). The visuals move into a floating Chrome picture-in-picture window. This window has no tabs, no address bar and no sharing bar, only a thin title bar.

- Drag it to the TV, then double-click it to make it as large as Chrome allows.
- Chrome limits its maximum size and does not allow full screen in it, so it does not cover the whole screen.
- Close it (or press **Q** again) to bring the visuals back. Needs Chrome 116 or newer on a computer.

## Playing on a TV

1. In the start card, set **Screen** to **Auto** (or choose your screen). Choices:
   - This computer screen
   - LG B6 55-inch 4K OLED TV
   - Other 4K TV
   - 1080p TV or projector
   - Phone or tablet
2. Click **Find my screens** one time and allow it. Fibwave then knows the TV by name.
3. Start the music, then press **W** (**Pop out**). The visuals open in a clean window on the TV. Click the picture once for full screen.
4. Keep the Fibwave tab with the controls on the Mac screen.

**LG B6 / OLED mode**
- Sharper rendering (about 1700p, scaled to 4K).
- True black: the shadows are not lifted to grey.
- Softer flashes and softer large bright areas.
- Text 60% larger.
- Burn-in care: the controls hide after 2 seconds, and on-screen text moves a few pixels very slowly.

If you drag the pop-out window from one screen to another, Auto mode sets itself up again for the new screen.

---

## Controls

### Keyboard

| Key | Action |
|---|---|
| **← / →** | Previous / next scene |
| **↑ / ↓** | Next / previous palette |
| **1 – 0** | Go to scene 1–10 |
| **Space** | Next scene |
| **[ / ]** | Previous / next preset (MilkDrop, Video Synth, photo scenes) |
| **H** or double-click | Hide / show the controls |
| **F** | Full screen |
| **W** | Pop-out window |
| **Q** | Picture in picture (a floating window with no Chrome bars) |
| **T** | TV mode |
| **C** | Cast help |
| **R** | Random scene |
| **O** | Random order on / off |
| **A** | Auto-change speed |
| **P** | Next palette |
| **L** | Names (explanations on screen) on / off |
| **K** | Key colours on / off |
| **G** | Film look on / off |
| **I** | Hit FX on / off |
| **J** | Test a big hit |
| **B** | Photo backdrop on / off |
| **U** | Music focus |
| **Y** | Photo spin |

In **Live Night Sky**, the arrow keys move your view around the sky.

In **DNA Helix**, **Chakras**, **Merkaba & Platonic Solids** and **Helix EQ**: drag on the screen to look around, and scroll (or pinch) to fly faster or slower.

### Control panel

- **Scene**, **Random**, **Auto** (change every N beats), **Order** (in order or random).
- **Palette**:
  - **🌈 Living Rainbow** follows the sound.
  - **🎲 Random** gives a new palette for each scene.
- **Names**: short explanations of the science, geometry or history in each scene.
- **Verses**: King James Bible verses in *Mirror Lake EQ* and *Eternal Voyage*.
- **Sung words**: shows a picture when the singer sings one of 189 words (see below).
- **Match style**: Fibwave guesses the music style (ambient, EDM, bass, hip-hop, rock, pop, classical, jazz) and picks suitable scenes and palettes.
- **Tone mood**: tempo, flow, warmth, brightness and harshness of the sound shape the visuals.
- **Guitar riffs**: listens to the song and writes 3 practice riffs in guitar tab: melody hook, groove riff and chord riff. **▶ Hear it** plays a riff at 100%, 75% or 50% speed.
- **Focus**: make the visuals follow one part of the music (bass, kick, snare, hi-hats, vocals, highs, melody or one note).
- **Photo backdrop**, **Photo shape** (card, glass sphere, prism, aquarium), **Photo spin**, **Captions**.
- **Gain**, **Trails**, **Impact**, **Glow**.
- **Hit FX**, **Film**, **Key colours**.
- **Gentle flashes**: softer flashes, for people sensitive to flashing light.
- **Dim when quiet**: quiet parts are darker; loud parts and new notes bring the light back.
- **Motion**: Smooth, Balanced or Punchy.
- **EQ overlay**: equalizer bars on top of any scene (bottom, centre, top, ring or sides), with **EQ strength** from 15% (mostly see-through) to 100%.
- **Quality**: render size (1080p, 1440p, TV 1700p, 4K).
- **Lights**: send colours to WLED light strips and Philips Hue lights (works when Fibwave runs from a local file, not from the website).

---

## Scenes (87)

**Golden ratio and geometry:** Sunflower · Golden Spiral · Kaleido Bloom · Spiral Scope · Fib Tunnel · Golden Tunnel · Flower of Life · Sri Yantra · Yin-Yang & Bagua · Merkaba & Platonic Solids · Tree of Life · Symmetric Maze · Quasicrystal · Cymatics

**Space and sky:** Solar System · Night Sky · Live Night Sky (the real sky over your location) · Moon Phases · Starfield · Deep Space · Nebula Flow · Particle Galaxy · Lunar Earthrise · Earth from Orbit · Eternal Voyage · Holographic Universe

**Higher dimensions and mathematics:** Hypercube 4D · Hopf Fibration · Clifford Torus · Torus Knots · Strange Attractors · Harmonograph · Möbius Wave · Möbius Flow · Pendulum Wave · Quantum Orbitals · Quantum Interference

**Fractals:** Fractal Bloom · Julia Set · Mandelbrot Zoom · Burning Ship · Newton Fractal · Phoenix Fractal · Apollonian Gasket · Lyapunov Space · Mandelbox 3D

**Body, mind and spirit:** Chakras · DNA Helix · Giza & Eye of Horus · Gateway · Earth Resonance · Entropy & Order · Song Mandala

**Music made visible:** Harmonic Strings · Note Patterns · Cascade EQ · Retro LED EQ · Radial Echo EQ (rings, city skyline, and an eye) · Helix EQ · Mirror Lake EQ · Waterways EQ

**Physics of spin:** Spin in Space · Spin in Air · Spin in Water · Spin in Honey · Spin in Plasma

**Nature and elements:** Aspen Grove · Flock · Moonlit Ocean · Alpine Lake · Glacier Fjord · Red Rock Canyon · Desert Dunes · Green Plains Storm · Northern Forest · Alien World · Living Water · Cloudscape · Brilliant Horizons · Fire & Smoke

**Materials and light:** Gemstones & Crystals · Silk Tapestry · Prism Light

**Photos and presets:** Nature & Wonders · Ancient & Esoteric (Wikimedia Commons photos; photos with people are skipped) · MilkDrop Classics · Video Synth

---

## Sung words

When **Sung words** is on, a small speech-recognition model (Whisper base, about 75 MB) downloads one time and stays in Chrome. It listens to the music **in your browser only**. No sound goes to a server.

When it hears one of 189 words (for example coffee, moon, rain, fire, ocean, rose, love, gold, dance, God, butterfly), a picture of the word appears with its own animation: steam, rain, petals, embers, sparkles, hearts, confetti, light rays or ripples.

- Clear vocals work best. Dense mixes and fast rap give fewer words.
- A word can appear 2–5 seconds after the singer sings it.
- To test without music, open Chrome's JavaScript console and type `fibwaveWord('coffee')`.

---

## Privacy

- Fibwave has no account, no tracking and no server of its own.
- Sound analysis, the speech model, the people check on photos and the guitar riffs all run in your browser.
- Settings are kept only in your browser (localStorage).

## Internet use

Fibwave works offline for most scenes. These parts need the internet:
- MilkDrop presets
- Video Synth
- The photo scenes (Wikimedia Commons)
- The full star catalogue
- The speech model, the first time only

**Save an offline copy** (in the start card) downloads one file with the presets, the video synth and the star data inside, for travel or camping.

## Browsers

| Browser | Support |
|---|---|
| **Chrome / Edge** (Mac, Windows) | Full support, including tab sound sharing. |
| **Firefox / Safari** | Visuals work. Use the microphone, BlackHole or audio files: these browsers do not give tab sound to web pages. |
| **Phones and tablets** | Visuals work with the microphone. |

A graphics card with WebGL 2 is needed for the 3D scenes. Fibwave lowers its resolution by itself on slower computers.

---

## Files

| File | What it is |
|---|---|
| `index.html` | The website (the same as `fibwave.html`). |
| `fibwave.html` | The full app in one file. You can open it directly from your computer. |
| `README.md` | This file. |

**To update the website:** in the GitHub repository, click **Add file → Upload files**, drop in the new `index.html` and `fibwave.html`, and click **Commit changes**. GitHub Pages updates the site in about one minute. In Chrome, reload with **Cmd + Shift + R** to get the new version.

---

## Credits

These outside libraries and data load from public CDNs or sites:

- **MilkDrop presets:** [Butterchurn](https://github.com/jberg/butterchurn) and butterchurn-presets (WebGL port of Winamp MilkDrop).
- **Video Synth:** [Hydra](https://hydra.ojack.xyz/).
- **Star data:** [d3-celestial](https://github.com/ofrohn/d3-celestial).
- **Photos:** [Wikimedia Commons](https://commons.wikimedia.org/) (each photo shows its own title and credit) and NASA images.
- **People check for photos:** TensorFlow.js COCO-SSD.
- **Speech recognition:** [Transformers.js](https://huggingface.co/docs/transformers.js) with OpenAI Whisper (Xenova/whisper-base.en).
- **Bible verses:** King James Version (public domain).

All the other visuals are drawn by Fibwave's own code, live, from the music.
