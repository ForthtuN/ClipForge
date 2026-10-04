<div align="center">

<img src="docs/images/clipforge-hero.png" alt="ClipForge — Your best plays. Ready to share." width="100%" />

# ClipForge

### Turn hours of gameplay into the moments worth keeping.

**Stop scrubbing through recordings by hand. ClipForge scans your gameplay locally, finds the moments you care about, lets you review them on a visual timeline, and exports the clips you actually want.**

<p>
  <img src="https://img.shields.io/badge/Windows-10%20%2F%2011-6C4BFF?style=for-the-badge&logo=windows&logoColor=white" alt="Windows 10/11" />
  <img src="https://img.shields.io/badge/LOCAL--FIRST-NO%20CLOUD%20UPLOAD-151B2E?style=for-the-badge" alt="Local first" />
  <img src="https://img.shields.io/badge/NVIDIA-NVDEC-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="NVIDIA NVDEC" />
  <img src="https://img.shields.io/badge/BUILT%20FOR-GAMERS%20%26%20CREATORS-B94CFF?style=for-the-badge" alt="Built for gamers and creators" />
</p>

## **Find. Review. Export. Relive.**

[**🚀 Get started**](#get-started) · [**⭐ Star ClipForge**](https://github.com/ForthtuN/ClipForge-releases) · [**🐛 Report an issue**](https://github.com/ForthtuN/ClipForge-releases/issues)

</div>

---

## Your best clips are already in your recordings.

The problem is finding them.

*The images above and below are marketing illustrations based on ClipForge, with generated gameplay and example data.*

A two-hour session can contain a few seconds you actually want for YouTube, Shorts, TikTok, Discord, a montage, or just your own archive. ClipForge is built around one job: **get you from raw recording to usable highlights without the grind.**

- 🎯 **Detect the moments you define** — kills, headshots, objectives, wins, deaths, HUD icons, text, or your own custom triggers.
- ⚡ **GPU-first scanning** — NVIDIA-accelerated scanning for supported gameplay recordings.
- 👁️ **Visual Match + Windows OCR** — use fast visual matching for icons/text appearances, OCR for text targets, or combine them adaptively.
- 🎞️ **Review everything visually** — filmstrip timeline, event markers, clip details, scrub/playback, fullscreen, trim and navigation.
- ✂️ **Export only what matters** — include/exclude clips, adjust ranges, then export the moments you chose.
- 🔒 **Local-first** — your footage stays on your PC. No cloud upload required.

---

## The Results page is built for speed

<img src="docs/images/clipforge-results.png" alt="ClipForge Results workflow with visual timeline and detected clips" width="100%" />

Once a scan finishes, ClipForge gives you a proper review workspace instead of a dump of timestamps.

**See where the action happened. Jump straight to it. Decide what stays.**

- large video preview with playback controls
- visual filmstrip across the source recording
- highlight/event markers directly on the playback timeline
- detected moments table with previews and trigger information
- clip details with grouped event counts
- fullscreen playback and fast clip navigation
- trim controls without destroying the original analysis
- export inclusion per clip

---

## Build the detector around your game

ClipForge is not locked to a small list of supported games. Create profiles around **your game, your HUD, and your definition of a highlight**.

Pause on the event you care about, draw the area ClipForge should inspect, capture a reference and tune the detector while seeing what ClipForge sees.

A profile can contain multiple independent triggers and can use:

- **Visual Match** for HUD icons, words and shapes
- **multiple visual references** for alternate appearances
- **Windows OCR** with contains / exact / regex matching
- **custom trigger names** that flow through Results and event summaries
- **configurable event grouping** so one on-screen event does not become dozens of duplicate detections

No hardcoded `KILL` logic. No one-game-only detector.

---

## Drop in footage. Build a queue. Scan.

<img src="docs/images/clipforge-library.png" alt="ClipForge Library — add recordings, choose a profile and scan for highlights" width="100%" />

ClipForge is designed for real recording folders, not toy demo files. Add individual recordings or entire folders, choose a scanning profile, and let the app work through the queue while keeping the source files read-only.

The workflow stays simple: **add footage → choose a profile → scan → review → export.**

---

## Fast enough to attack long recordings

ClipForge was designed around the fact that gameplay recordings are huge.

On the development RTX 5080, the real 14:37 1440p AV1/HDR Wardogs workload measured roughly **36× realtime** with the tested profile and SSD configuration.

Actual speed depends on your recording, scanning profile, GPU and storage.

> This is a measured development workload, not a guaranteed speed on every PC.

---

## Built for gameplay footage

### HDR-aware playback
Review gameplay in a large preview or fullscreen. HDR presentation adapts to the active display; appearance can vary with Windows HDR settings and your GPU/driver.

### Timeline that shows you where things happened
Detected events live on the timeline instead of disappearing into a log. Scrub the whole recording, jump between moments, inspect grouped triggers, and edit the range only when you need to.

### Smart event grouping
A HUD notification may remain visible across many sampled frames. ClipForge groups those raw matches into logical events so the UI reports **moments**, not meaningless duplicate sample counts.

### Source-safe workflow
Recordings are treated as read-only. Exported clips go to separate files, and edited ranges are handled independently from the source footage.

---

## Perfect for

| | |
|---|---|
| 🎥 **YouTube creators** | Pull the usable moments out of long recording sessions. |
| 📱 **Shorts / TikTok** | Build a pile of candidate clips without manually scrubbing everything. |
| 🎬 **Montage editors** | Find fights, kills, objectives and other repeated HUD events fast. |
| 🎮 **Players who record everything** | Keep the best moments without turning review into a second job. |
| 🧪 **Power users** | Build custom profiles around your own triggers instead of waiting for game-specific support. |

---

## Get started

**ClipForge is currently a development preview. A packaged Windows release has not been published yet.**

The first Windows installer has not been released yet. Downloads and release notes will appear on the [Releases page](https://github.com/ForthtuN/ClipForge-releases/releases).

You'll need Windows 10/11 x64. GPU scanning requires a compatible NVIDIA GPU, driver and codec. The planned installer will include the media components needed to run ClipForge.

Once installed, the workflow is simple:

1. Add your gameplay recordings.
2. Create or import a profile for the HUD events you want to find.
3. Start scanning, then review the detected moments.
4. Keep the clips you like, adjust their ranges and export.

## Help improve ClipForge

Found a bug or have a feature idea? [Open an issue](https://github.com/ForthtuN/ClipForge-releases/issues). Include your app version, Windows version, GPU, recording codec and steps to reproduce. Remove personal information from logs and screenshots before sharing them.

This repository contains the ClipForge presentation, downloads and issue tracker. Application source code is maintained privately.

---

<div align="center">

# ClipForge

### **Your gameplay already has the moments. Stop wasting time finding them.**

[**Get started with ClipForge →**](#get-started)

</div>
