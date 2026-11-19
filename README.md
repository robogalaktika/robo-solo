# Robo Solo Synth

An oscillator synth for playing solos live with a band, made for Robo Galaktika (new wave and 80s synth pop). Runs in a phone browser, no app store install needed.

## Features

- **Fretless ribbon**: slide left-right to change notes, up-down to control filter brightness. Only notes from the chosen scale are shown.
- **12 root notes** and **22 scales**: Natural Minor, Dorian, Phrygian, Harmonic Minor, pentatonics, blues, modes, jazz, and Pelog/Slendro approximations.
- **8 sounds**: PWM Lead, Scream Lead, Poly Saw, FM Bell, FM Brass, Resonant Mono Lead, Glass, Theremin Sine.
- **Note snap**: Hard, Expressive (wiggle = vibrato, slide = bend), Free (fretless).
- **Effects**: glide, auto vibrato, chorus, tempo-synced delay (with tap tempo), reverb.
- **Display**: a big oscilloscope as the background.
- **Other**: settings are saved automatically on the device.

## Put it online with GitHub Pages

1. Create a new GitHub repo, e.g. `robo-solo`.
2. Upload all files in this folder (**Add file → Upload files**).
3. Open **Settings → Pages**, set *Source* to **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. Wait 1–2 minutes. The app will be at `https://<username>.github.io/robo-solo/`.

## Install on your phone

Open that address in Chrome (Android) or Safari (iPhone) and choose **Add to Home Screen**. The app opens fullscreen in landscape.

## Stage tips

- Connect to the mixer or a DI box with a cable (3.5mm jack or USB-C adapter). Avoid Bluetooth: its delay is too long for live playing.
- Turn off notifications and battery saver so the audio doesn't cut out.
- Test the latency on your phone before the gig.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app (HTML, CSS, JS, Web Audio) |
| `manifest.webmanifest` | Data for "Add to Home Screen" |
| `icon-192.png`, `icon-512.png` | App icons |
| `.nojekyll` | Makes GitHub Pages serve the files as they are |
