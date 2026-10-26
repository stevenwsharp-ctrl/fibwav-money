# Fibwave

### ▶ Open Fibwave: **[https://stevenwsharp-ctrl.github.io/fibwav-money/](https://stevenwsharp-ctrl.github.io/fibwav-money/)**

Repository: https://github.com/stevenwsharp-ctrl/fibwav-money

**Music you can see.** Fibwave is a music visualizer that runs in your web browser. It listens to your music and turns the beat, the bass and the melody into moving light: golden-ratio spirals, fractals, oceans and mountains, liquid feedback trails, a video synth, the real night sky and more.

Fibwave is **one file** (`index.html`). There is nothing to install. You can use it as it is, or change it with any AI assistant (Claude, ChatGPT, Gemini or another).

---

## Contents

- [Start in one minute](#start-in-one-minute)
- [What is inside](#what-is-inside)
- [Touch mode](#touch-mode)
- [How to play music into Fibwave](#how-to-play-music-into-fibwave)
- [Controls](#controls)
- [Keyboard shortcuts](#keyboard-shortcuts)
- [Show it on a TV](#show-it-on-a-tv)
- [Room lights (WLED)](#room-lights-wled)
- [Change Fibwave with an AI](#change-fibwave-with-an-ai)
- [Put it online (GitHub Pages)](#put-it-online-github-pages)
- [Requirements](#requirements)
- [Safety](#safety)
- [Privacy](#privacy)
- [Credits](#credits)
- [Licence](#licence)

---

## Start in one minute

**Way 1: open the file**

Double-click `index.html`. It opens in your browser. Use Chrome or Edge for the best result.

**Way 2: a small local web server (recommended)**

Some features (for example sound from another tab) work best from a web address. Open a terminal in the folder with `index.html`, then run:

```
python3 -m http.server 8080
```

Then open http://localhost:8080 in Chrome.

**Then:**

1. Select a sound source on the start card. To test quickly, click **Demo beat**.
2. Double-click the screen to hide the controls.
3. Press **←** and **→** to change the scene. Press **↑** and **↓** to change the colours.

---

## What is inside

About **90 scenes**, plus **36 Liquid Feedback presets** with an **Endless Mix** that makes new ones without end, and **16 Signal Synth patches**.

| Family | Examples |
|---|---|
| Golden ratio | Sunflower, Golden Spiral, Fib Tunnel, Kaleido Bloom, Spiral Scope |
| Liquid Feedback | Smoke Signals, Whirlpool, Crystal Fold, Twin Storms, Liquid Gold, Endless Mix |
| Signal Synth | Liquid Kaleido, Golden Weave, Moiré Rings, Interference, Topo Lines, Glitch Scan |
| Nature and worlds | Moonlit Ocean, Alpine Lake, Glacier Fjord, Desert Dunes, Northern Forest, Cloudscape, Living Water, Earth Flight, Fire & Smoke, Lava Rivers |
| Space | Night Sky, Live Night Sky (real stars and planets for your location), Solar System, Moon Phases, Nebula Flow, Particle Galaxy, Earth from Orbit |
| Fractals | Mandelbrot Zoom, Julia Set, Burning Ship, Newton, Phoenix, Apollonian Gasket, Mandelbox 3D, Fractal Bloom |
| Sacred geometry | Flower of Life, Sri Yantra, Chakras, Yin-Yang & Bagua, Merkaba & Platonic Solids, Tree of Life, Giza & Eye of Horus |
| Science | **DNA Coaster** (a roller-coaster ride around and through winding DNA, with RNA strands), Strange Attractors, Harmonograph, DNA Helix, Cymatics, Quantum Orbitals, Hypercube 4D, Hopf Fibration, Torus Knots, Pendulum Wave, Spin in Water and Plasma |
| Equalizers | Mirror Lake EQ, Waterways EQ, Cascade EQ, Retro LED EQ, Radial Echo EQ, Helix EQ |
| Your Photos | Drag your own photos onto the window. Fibwave animates them with the music. |

**Smart features**

- **Music brain:** Fibwave finds the tempo (BPM), the key, the drum hits, the build-ups and the drops. The visuals change on the beat and jump on a drop.
- **Match style:** Fibwave guesses the style of the music (for example EDM, rock or ambient) and picks scenes that suit it.
- **Music focus:** the visuals can follow only the kick drum, the vocals, the hi-hats or the bass.
- **Auto and Random:** the scene changes every 8 to 55 beats, in order or at random. Random is the default.
- **Song changes:** when the song changes a lot (verse to chorus, a breakdown, a key change, a new sound), the scene changes with it.
- **Scene length:** scenes with a lot of change inside them (DNA Coaster, Liquid Feedback, Earth Flight) stay longer; simple scenes (Flower Fields, the EQs) change sooner.
- **Guitar riffs:** Fibwave listens to a song for 20 seconds and writes 3 practice riffs in the song's key, with guitar tab.
- **Offline copy:** one button saves a copy that works with no internet.

---

## Touch mode

Play with the visuals by finger or mouse, with or without music. Click **✋ Touch & play** on the start card, or **✋ Touch** in the controls, or press **M**.

In Touch mode, the picture is **wet ink**. A small fluid simulation runs under every scene. When you move through the picture, it moves with you: it swirls, curls and keeps the shape you gave it. Then it slowly settles back.

| Action | What happens |
|---|---|
| **Draw** (drag a finger or the mouse) | The picture is pushed and molded along your path. Fast strokes make it wet: its colours smear and flow like paint, and the wet edges catch the light. |
| **Hold still** | You dive into the picture at that point: it opens up round your finger and slowly turns. A Fibonacci bloom grows. Let go to make it burst. |
| **Tap** | A ripple and sparks. |
| **Flick** (a fast swipe) | A shockwave. |
| **Two fingers** | Pinch to zoom, twist to turn. Let go and it springs back. |
| **Three-finger tap** | A new scene. |
| **Mouse wheel** / **Shift + drag** | Zoom / twist. |
| **〰 Line** (or **X**) | Draws a glowing line where you touch. Click to change: **off** (the default) → **fading** (a trail behind your finger) → **locked** (lines stay where you drew them, so you can draw on top of the moving picture). |
| **↺ Clean** (or **C**) | Makes the picture clean again at once, and removes all lines. |

The small buttons at the top right are **〰 Line**, **♪ Sound**, **↺ Clean** and **✕ Leave**.

### Touch sound

Sound is **off** at the start. Click **♪ Sound off** (or press **V**) to turn it on. Fibwave remembers your choice.

When the sound is on, where you touch changes the sound:

| Where | Sound |
|---|---|
| **Left to right** | Five instruments: Marimba · Pluck · Bell · Glass · Air |
| **Low to high** | Low notes and a soft tone at the bottom; high notes and a bright tone at the top |
| **Near the edges** | More echo |
| **The four corners** | A strummed chord |
| **Drag** | Notes play like a harp when you cross a step of the scale or into a new instrument |
| **Hold still** | A soft chord in the sound of that part of the screen |
| **Flick** | A whoosh: higher when it is high on the screen |

All notes are in the key of the song. Without music, the visuals react to the notes you play.

In **Liquid Feedback**, your light is also painted into the flow itself.

To change how the ink feels, ask your AI to change `FL.relax` (how fast the shape settles back), `FL.dry` (how fast wet paint dries), `FL.vort` (how curly the flow is) or `FL.visc` (how thick the ink is). To change the instruments, ask it to change `TM_INSTR` and `tmVoice`.

## How to play music into Fibwave

| Source | How |
|---|---|
| **Sound from another tab** | Play music in another Chrome tab. Click this button, select that tab, and keep **Share tab audio** on. Chrome and Edge on a computer only. |
| **Microphone** | Fibwave listens to the room. Works on phones and in all browsers. |
| **Virtual audio driver (Mac)** | Install a free virtual audio driver such as BlackHole. Then select it under **Sound input** to send the sound of any music app straight in, with no room noise. |
| **Audio files** | Play MP3, WAV, FLAC or M4A files from your computer. You can also drag them onto the window. |
| **Demo beat** | A built-in 118 BPM loop for testing. |
| **✋ Touch & play** | No music needed: mold the picture like wet ink with your fingers. Sound is optional (see Touch mode). |

---

## Controls

The control deck is at the bottom of the screen. It hides when you do not move the mouse.

| Control | What it does |
|---|---|
| **Scene** | Selects a scene. |
| **Preset** | Shows for Liquid Feedback, Signal Synth and Your Photos. Selects a preset, patch or photo. |
| **Palette** | The colours. **Living Rainbow** (the default) follows the sound. Select **Random** to change the palette with each scene. |
| **Auto** | Changes the scene every 8, 13, 21, 34 or 55 beats (Fibonacci numbers). |
| **Order** | In order, or Random (everything). |
| **Gain** | How strongly Fibwave hears the music. |
| **Trails** | How long the light stays on the screen. |
| **Impact** | How strongly the visuals react to hits. |
| **Glow** | The glow around bright light. |
| **Hit FX** | Short effects on big hits and drops. |
| **Gentle flashes** | Softer flashes (recommended for long sessions). |
| **Dim when quiet** | The picture gets darker in quiet parts. |
| **EQ overlay** | Adds an equalizer bar over any scene. |
| **Quality** | Render size, from Fast (1080p) to Ultra (4K). |
| **Lights** | Room lights (see below). |
| **Cast to TV** | Help to show Fibwave on a TV. |
| **Pop out / Picture in picture** | Shows the visuals in their own window. |

---

## Keyboard shortcuts

| Key | Action |
|---|---|
| **H** or double-click | Hide or show the controls |
| **← →** | Previous or next scene |
| **↑ ↓** | Previous or next palette |
| **1 – 0** | Scenes 1 to 10 |
| **Space** | Next scene |
| **[ ]** | Previous or next preset (Liquid Feedback, Signal Synth, Your Photos) |
| **M** | Touch mode on or off |
| **V** | Touch sound on or off |
| **X** | Touch line: off, fading or locked |
| **R** | Random scene and look |
| **O** | Random order on or off |
| **A** | Auto-change speed |
| **P** | Next palette |
| **K** | Key colours (colours follow the key of the song) |
| **U** | Music focus (kick, vocals, hi-hats and more) |
| **I** | Hit FX on or off |
| **J** | Test a big hit |
| **G** | Film look on or off |
| **L** | Names on or off (shows what each scene is) |
| **B** | Photo backdrop on or off |
| **Y** | Photo spin |
| **F** | Full screen |
| **T** | TV mode (full screen, no controls) |
| **W** | Pop-out window |
| **Q** | Picture in picture |
| **C** | TV help (in Touch mode: clean picture) |
| **Esc** | Close a panel |

---

## Show it on a TV

- **HDMI cable:** the easiest way, with no delay. Click **Full screen** and select the TV.
- **Mac:** Control Center → Screen Mirroring → select your TV.
- **Windows:** press the Windows key + K, then select your TV.
- **Chrome:** menu (⋮) → Cast, save, and share → Cast → Sources → Cast tab.

Then press **T** for TV mode. For an OLED TV, select **4K OLED TV** under **Screen** on the start card. This setting protects the screen from burn-in.

---

## Room lights (WLED)

Fibwave can send its colours to **WLED** LED strips on your home Wi-Fi. WLED is free, open-source firmware for LED controllers.

1. Click **Lights**.
2. Type the IP address of your WLED controller (it shows in the WLED app), then click **Add strip**.
3. Select a role for each strip: scene colours, pulse on the kick, moving wave, spectrum, copy the screen, or flash on drops.
4. Turn on **Lights on**.

Note: browsers block connections from a secure (https) web page to devices on your home network. For lights, open Fibwave from the file on your computer.

---

## Change Fibwave with an AI

Fibwave is made to be changed. A guide for AI assistants is at the top of the code, inside `index.html`. The guide tells the AI the rules, the names of the music values, and how to add scenes, presets and palettes.

**How to do it**

1. Open a chat with your AI assistant.
2. Attach `index.html` (or paste all of it).
3. Say what you want. Ask for the complete new file back.
4. Save the new file as `index.html` and open it.

**Example requests**

- "Add a scene of a jellyfish that pulses on the kick drum."
- "Add three new Liquid Feedback presets that look like underwater light."
- "Make a palette called Sunset Mesa with deep red, orange and purple."
- "Make the Sunflower scene turn faster on the bass."
- "Add a Signal Synth patch with rotating hexagons that split into colours on the snare."
- "Remove the scenes I do not use: Chakras and Tree of Life."

**Tips**

- Ask for one change at a time. Test it, then ask for the next change.
- Keep a copy of the last good file (for example `index-backup.html`).
- If a scene shows an error, copy the red text from the browser console (press **F12**) and give it to the AI.
- The file is large (about 0.5 MB). If your AI cannot take the whole file, ask it to change only the part you name, and to tell you exactly where to paste it.

---

## Put it online (GitHub Pages)

1. Make a new repository on GitHub.
2. Upload `index.html` and this `README.md`.
3. Open **Settings → Pages**. Set **Source** to **Deploy from a branch**, the branch to **main** and the folder to **/ (root)**. Click **Save**.
4. After 1 to 3 minutes, the site is at https://stevenwsharp-ctrl.github.io/fibwav-money/

   For your own copy, the address is `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

---

## Requirements

- A computer with a graphics card made in the last 8 years or so. Most scenes use WebGL2.
- **Chrome or Edge** is recommended. Firefox and Safari work, but they cannot take sound from another tab (use the microphone or a virtual audio driver).
- Phones and tablets work with the microphone. Use **Quality: Fast** on older devices.
- An internet connection only for the fonts and the full star catalog. Without internet, Fibwave uses your computer's fonts and a built-in list of the brightest stars. The **offline copy** puts both inside the file.

---

## Safety

Fibwave shows moving and flashing light. **If you or a viewer has photosensitive epilepsy, ask a doctor before use.** Turn on **Gentle flashes** for softer light changes. Stop if you feel unwell.

---

## Privacy

- The sound stays on your device. Fibwave does not record or upload it.
- Your photos stay on your device. Nothing is uploaded.
- Fibwave has no accounts, no tracking and no ads.
- Settings are saved only in your browser.

---

## Credits

- **Fonts:** Chakra Petch, Syncopate and VT323, from Google Fonts (SIL Open Font License).
- **Full star catalog:** d3-celestial data by Olaf Frohn (BSD-3-Clause licence), from the Hipparcos catalogue and the IAU constellation data.
- Everything else in Fibwave (code, scenes, presets, patches and palettes) is original work.

---

## Licence

Copyright © 2026 Steven Sharp. All rights reserved.

You may use Fibwave for yourself, and change it for your own use. You may not sell, share or publish Fibwave, or a changed copy of it, without written permission.
