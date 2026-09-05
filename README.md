<div align="center">

<img src="assets/hero-macbook.png" alt="Chili RAW on a MacBook Pro" width="900">

<br>

![macOS 15+](https://img.shields.io/badge/macOS-15%2B-1c1c1e?style=flat-square&logo=apple&logoColor=white)
![Apple silicon](https://img.shields.io/badge/Apple%20silicon-M1%20or%20newer-1c1c1e?style=flat-square)
![Version](https://img.shields.io/badge/version-1.0.0-E5402A?style=flat-square)
![Free](https://img.shields.io/badge/Chili%20RAW%20Free-free%20forever-2e9e5b?style=flat-square)
![Pro](https://img.shields.io/badge/Pro-%2429.99%20once-F5194E?style=flat-square)
[![Manual](https://img.shields.io/badge/manual-wiki-4a6fa5?style=flat-square)](https://github.com/halebop17/chili-raw-photo-developer/wiki)
[![Issues](https://img.shields.io/github/issues/halebop17/chili-raw-photo-developer?style=flat-square&color=6b5b95)](https://github.com/halebop17/chili-raw-photo-developer/issues)

</div>

# Chili RAW

> A photo culler, RAW developer, and asset manager, built just for the modern Mac.

Chili RAW takes a card full of frames and gets you to finished pictures — cull the shoot,
develop the keepers, and keep your whole library searchable, all in one window and all on
your own disk. It never imports, copies, or uploads a single file.

It runs on Apple silicon and nothing else. The develop pipeline is built on Metal and
Core Image, the AI runs on the Neural Engine, and the interface is native AppKit and
SwiftUI rather than an imitation of one.

<div align="center">

<table>
<tr>
<td align="center" width="420">
<h3>⬇︎ Download Chili RAW</h3>
<p>The free version is fully featured.<br>macOS 15 or later, Apple silicon.</p>
<p><b><a href="https://github.com/halebop17/chili-raw-photo-developer/releases/latest">Get the latest release →</a></b></p>
</td>
<td align="center" width="420">
<h3>📖 Read the manual</h3>
<p>Every part of the app, chapter by chapter,<br>from a first cull to the darkroom.</p>
<p><b><a href="https://github.com/halebop17/chili-raw-photo-developer/wiki">Open the manual →</a></b></p>
</td>
</tr>
</table>

</div>

---

## Free, and free forever

**Chili RAW Free is a real photo application, not a trial.** It is its own build — not the
paid one with features switched off — and it stays free.

- No time limit, no watermark, no export cap.
- **Nothing interrupts you to sell you something.** No nag screens, no upgrade prompts, no countdown timers.
- **Nothing is padlocked.** Pro features aren't greyed-out teasers; they simply aren't in this build.
- No account. Nothing to sign in to.
- Every future release of Free stays free.

---

## What it does

### Cull
Ratings, picks, rejects and colour flags from the keyboard · burst **Stacks** · **Compare**
and **Survey** side-by-side modes · a hover **Loupe** with focus peaking · a distraction-free
Darkroom · an on-device Vision score that puts the likely keepers first.

### Develop
**Three RAW decoders you choose between** — Apple CIRAWFilter, the Adobe DNG SDK, and LibRaw
with your own DCP profiles — and **three tone mappers** (AgX, Standard, Neutral), so the same
raw file has nine starting points before you touch a slider.

Tone, curves, colour mixing, texture, clarity and physical dehaze · RAW highlight recovery ·
**eleven kinds of mask** that add, subtract and intersect · heal, clone and cross-frame dust
detection · crop, straighten, perspective · **lens corrections** from your camera's own tables
or the bundled Lensfun database · multiple **versions** per photo · **Proof** mode.

### Organise
A searchable catalog with Smart Folders and Collections · text search across filenames, IPTC
and Vision keywords · geotagging with **offline** place names — no geocoding service, no network
request · EXIF/IPTC editing in bulk · Vault backups to another drive.

### Export
JPEG (jpegli), JPEG XL, HEIC, 16-bit TIFF and layered PSD · resize with output sharpening ·
batch renaming, metadata policy, GPS and person-info stripping · a processing panel that
doesn't block the app.

### Video
Clips sit in the grid with the photos, play full screen, and take a colour grade applied
frame by frame on export — HEVC or H.264, in a MOV or MP4.

---

## What Pro adds

Pro is for what you *make* with the app, and costs **$29.99 once** — no subscription, updates included.

<!-- TODO: point this at the Payhip page once the URL exists. -->
**[Get Chili RAW Pro → ](#)** *(link coming — Pro is sold through Payhip, which also handles the licence key)*

| | |
|---|---|
| **Film Labor** | Eighteen film stocks and eight papers, each modelled from published datasheets, run through the stages a real frame goes through: exposure onto the negative, halation, grain, the print, and the light you view it under. |
| **Pixels** | A layer canvas over the developed photo — type, borders, glowing date stamps, dithered gradient washes, a Deluxe-Paint palette, and **Enlarge**. Exports as a layered PSD or TIFF. |
| **AI, on your Mac** | Sky, Object and Depth masks · portrait editing by face part · Generative Remove · AI denoise · upscaling on export · search by what's in the picture · People. |
| **Bokeh** | A depth-driven optical blur, run in scene-linear before the tone map, with a five, six or seven-blade iris. |

---

## Installing

1. Download the `.dmg` from [Releases](https://github.com/halebop17/chili-raw-photo-developer/releases/latest).
2. Drag **Chili RAW** to your Applications folder.
3. Open it.

<!-- TODO: once notarization is in the release pipeline, say so here — until then,
     macOS may ask you to confirm the first launch (right-click ▸ Open). -->

---

## Requirements

|  |  |
|---|---|
| **macOS** | 15 Sequoia or later |
| **Chip** | Apple silicon — M1 or newer |
| **Intel** | Not supported |

---

## Privacy

- **Your photos stay where they are.** Chili RAW reads folders on your disk. It never imports, copies or moves your originals, and never overwrites your pixels.
- **No account, no telemetry, no analytics, no crash reporting.**
- **The app makes exactly one kind of network request:** downloading an AI model, when you press Download. Nothing else in it talks to the internet — place names come from a table inside the app, and no image ever leaves your Mac.

---

## Bugs, requests, questions

Open an [issue](https://github.com/halebop17/chili-raw-photo-developer/issues). For anything
that looks like a bug, four things make it fixable in one pass:

- your macOS version and Mac model,
- the camera and file type (`.ARW`, `.CR3`, `.NEF`, `.DNG`, …),
- which RAW decoder you have selected in **Settings ▸ General ▸ RAW decoding**,
- what you expected to see, and what you saw instead.

---

## About this repository

This is where Chili RAW is **distributed and supported** — releases, the manual, and issues.
The application's source is not in here.

## Built on the work of others

Chili RAW bundles or builds on ExifTool (Phil Harvey), libjxl / jpegli, LibRaw, the Adobe DNG
SDK, the Lensfun calibration database, GeoNames place data (CC BY 4.0), Marco S Hyman's GeoTag
(MIT), and Jan Lohse's spectral_film_lut as a reference for the film pipeline. The optional AI
models are open models, each under its own licence — the app lists every one under
**Settings ▸ AI ▸ Model Licenses**.

<!-- TODO: ship NOTICE alongside the app and link it here. -->

---

<div align="center">

© 2026 <!-- TODO: your name or company -->  ·  Not affiliated with Adobe, Apple, Fujifilm,
Kodak or any other manufacturer named in the app.<br>
Film and paper names identify the stock being emulated; the emulations are built from
published datasheets and are not replicas.

</div>
