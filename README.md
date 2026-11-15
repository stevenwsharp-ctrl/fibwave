# Fibwave

**A music visualizer in one web page.** Fibwave listens to your music and turns it into moving art: golden-ratio patterns, GPU fractals, galaxies, oceans, mountains, sacred geometry, classic equalizers, the real night sky and 3D flights through space. Everything follows the beat, the bass, the melody, the key and the mood of the sound.

**Live site:** https://stevenwsharp-ctrl.github.io/fibwave/

- 88 scenes and 17 colour palettes, plus a Health Laboratory with 18 molecules of the body
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

## Guitar coach

Click **Guitar** in the controls (or press **X**). The coach from Fibwave Guitar opens over the visuals.

- **Modes:** Jam & scales, Chords, Riffs, Strumming, Fretboard notes, Ear training, Key & theory, Tuner and **Pentatonic** (Shift+1 … Shift+9; **M** = next mode).
- **Pentatonic:** the 5 standard boxes (two notes on each string). **Root**: the song's key, or any note you select (for example E with *Major pentatonic*; Fibwave also shows the relative scale with the same notes). Type: minor, major or minor blues (♭5). **Box practice**: stay in one box, or move to the next box every 2, 4 or 8 bars on the beat, or to a random box every 4 bars (a countdown shows the next box). Layouts: *One box*, *All 5 boxes* (each box has its colour) and *Connect the boxes* (outlines and the slides between them). For each box: the roots, the chord tones to aim for now, the usual bends, the blues note, a double stop, the slide to the next box, ▶ Hear the box and a new lick in the box. Your root, type, box, practice and layout are saved for each song.
- **Song chart:** a chord progression with chord shapes for your level and how they sit in the pentatonic box. Presets: your friend's progression (E major, 85 BPM, 10 bars, 2 loops), a 12-bar blues in A and a pop I–V–vi–IV in G, or type your own (one word = one bar, `E+A` = two chords in one bar). **Beginner** = easy open shapes, **Intermediate** = 7th and barre chords, **Advanced** = extended voicings (maj9, m(add9), slash chords); **Other shape** shows a different voicing. **Moves**: *Static* (the whole chart, best for beginners), *Step with the beat* (now and next) or *Step, and the box follows the chord*; loops as written, once, twice or always; a 4-beat count-in, a click and the chords. The fretboard shows the chord shape (R, 3, 5, 7, 9) inside the nearest copy of the pentatonic box; a gold ring = a note in the chord and in the scale (a safe target). The text explains which chord notes are outside the pentatonic and which note to target.
- **Fretboards:** large string names (e B G D A E) on tags and a number under every fret (marker frets in gold).
- **Layouts:** Large, Side, Small (**V** changes it), ✕ hides the coach.
- **Move and resize:** drag the title bar to move the coach or the Guitar riffs box, and drag the bottom-right corner to resize it. Each layout remembers its place. Double-click the title bar to reset it.
- **Guitar scenes:** Neon Fretboard, Six Strings, Chord Wheel and Soundhole Rosette.

---

## Playlist

When you play audio files, a **Playlist** panel opens (the **Playlist** button in the controls opens and closes it).

- Choose many files at once, use **+ Add files**, or drop audio files on the panel or on the visuals to add them.
- **⏮ previous, ⏪ rewind, ▶/❚❚ play and pause, ■ stop, ⏩ fast forward, ⏭ next**: ⏪ and ⏩ jump 10 s on a click and move fast while you hold them. A position bar and the time.
- **Speed**: 0.25× (slow motion) to 2×, with **Keep pitch** on (normal pitch) or off (slower is lower, like a tape).
- **Repeat**: off (stop after the last track), all (start the list again) or one (repeat this track). Your choice is saved.
- **Shuffle**: every track plays once before one repeats.
- Click a track to play it, drag tracks to change the order, and × removes a track. **N** goes to the next track.

---

## Health Laboratory

Click **Health Lab** in the controls (or choose the scene **Health Laboratory**). A panel opens on the right.

**Six body systems**, each from the whole body down to the molecule or atom:

| System | Levels |
|---|---|
| Muscles | 3D muscle map (a GPU-rendered figure seen from the front and back, turning slowly; drag to rotate; 28 muscle groups, activation for walking, squat, push-up, pull, curl and plank) → muscle fibers → actin and myosin |
| Breathe | Lungs, heart and blood → **the heart in section** (4 chambers, valves that open and close in phase, ECG with P, QRS, T and heart sounds S1, S2) → alveoli → red blood cell → heme and oxygen → electron clouds |
| Move | Skeleton and muscles → muscle fibers → actin and myosin → ATP → electron clouds |
| Signal | Brain and nerves → neuron → nerve meets muscle → acetylcholine → electron clouds |
| Clean | Liver, kidneys and lymph → liver lobule → **the nephron** (every segment with its function and drug targets: SGLT2, loop diuretics, thiazides, ADH, aldosterone) → kidney filter → albumin → urea |
| Fuel | Food to energy → mitochondrion → glucose → ATP → electron clouds |

**Atlas style:** anatomical body (skeleton, organs, vessels, nerves, muscles with fiber direction), textbook labels with leader lines on every level, a lub-dub heartbeat, breathing with the diaphragm, and correct sarcomere banding (A band constant, I band and H zone shorten).

**Look:** a deep navy backdrop with soft drifting glows, a fading grid, a holographic platform, a slow light scan, cool key and rim lighting with filmic tone mapping, and a glass information panel.

**Lecture layout:** an information panel on the left (title, simple text, medical text, Activate line, rhythms in Hz, optimal ranges, activation list and scale ladder), the picture on the right.

**Detail:** *Simple*, *Medical* or *Simple + medical* (for a mixed audience).

**Clinical orientation:** anterior view with the patient's right and left marked; the **Landmarks** option shows vertebral levels and surface landmarks (C7, sternal angle T4/T5, transpyloric plane L1, umbilicus L3/L4, iliac crests L4/L5). The spine has correct proportions (small cervical, large lumbar vertebrae). The neuron trace shows rest, threshold and peak and the phases of the action potential. Standard textbook colours: red = oxygenated blood and arteries, blue = deoxygenated blood and veins, yellow = nerves, green = lymphatics, ivory = bone.

**Presenter controls:** Back, Pause and Next in the panel, or Page Up / Page Down (a presentation clicker), `,` / `.` and Enter.

**Views:** **Overview**, **Zoom in** and **Journey** (random). **Molecule lab** gives the free molecule explorer below.

### Molecule lab

**Molecules** (real structures, built from their chemical formulas with real bond lengths and angles):

| Group | Molecules |
|---|---|
| Filters | Activated carbon, albumin, glutathione, heme of cytochrome P450, bilirubin, cholic acid, urea, creatinine, cellulose |
| Movement | Actin and myosin, ATP, acetylcholine, collagen, hydroxyapatite, lactate |
| Blood | Heme with oxygen, glucose, water |

Albumin, collagen, actin and myosin are coarse-grained (one bead for each amino acid or protein subunit). Hydroxyapatite is a hexagonal crystal with approximate positions.

**Views:** Overview, Travel around, Inside, Between (the camera flies through the gaps between atoms), Through, Quantum (electron probability clouds) and Auto tour (changes view every 16 beats).

**Cinematic look:** every atom is lit like a film shot (a key light, a coloured rim light, a sharp highlight and soft shadow where atoms crowd together). Near and far things go out of focus (depth of field). Each body system has its own world: clear fluid with floating particles for the filters, warm muscle fibers for movement, and drifting red blood cells for blood. Light shafts, a vignette, wide-screen cinema bars and a title card for each molecule finish the picture. You can turn each part off in the panel.

**Random journey** (the default for *Next molecule*): every 18 to 45 seconds, on a downbeat, the lab changes the shot. Sometimes the same molecule gets a new view or style, sometimes another molecule comes. It visits all 18 molecules before one repeats, and it uses Bind, Explode and Contract by itself.

**Things to play with:**
- **Bind**: molecules fly in and stick. Chloroform adsorbs on carbon, drugs and bilirubin dock in albumin, oxygen binds to the iron of heme, water bonds to oxygen and nitrogen atoms.
- **Explode**: the atoms move apart and come back together.
- **Contract** (actin and myosin): the myosin heads pull the actin filaments to the centre. Muscles only pull.
- **Vibrate**: the atoms move with the bass.
- Style (ball and stick, space filling, sticks, glow), colours (by element or palette), hydrogens, info, music link, speed, and an automatic change to the next molecule.
- Drag the screen to look round. Scroll to change the flight speed.

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
