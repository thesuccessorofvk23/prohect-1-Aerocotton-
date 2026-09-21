# BRIEF — Aero Cotton cinematic loader

---
workflow: motion-graphics
flow: automation
storyboard: no
message: "Nature → fiber → thread → precision → weaving → fabric → Aero Cotton — one continuous four-second cinematic camera move that ends on the brand lockup and hands off into the website's fabric hero."
destination: videos/aero-cotton-loader (HyperFrames project; composition also embedded live in the site's preloader)
aspect: 16:9 web (1920×1080 master render; live in-page layer is viewport-sized)
language: en
length: 4.0s
export: mp4
---

## Intent

The user handed a complete cinematic storyboard (six beats: fiber → thread → loom →
weaving → fabric → brand reveal) for a **4-second website loading transition** for
Aero Cotton — not an ad. Ultra-photorealistic direction, low-key warm industrial
lighting, physically believable cotton, no CGI-plastic, no neon, no sci-fi, no
spinners, no counters. Final frame must hand off seamlessly into the homepage's
procedural fabric 3D hero (the woven surface **becomes** the fabric the hero
continues).

Route: `/motion-graphics`, category `logo-reveal` (hand-authored path — the
six-beat procedural fabric journey has no catalog equivalent; the finale follows
logo-outro's spirit). `asset_needs: [factory textile weaving MP4]`.

## Customizations

- Palette locked to the brand: espresso `#050403` / charcoal `#171614` / cocoa
  `#2a211c` / ivory `#e9e2d4` / flax `#b9a98f` / brass `#b08d57` / warm flax `#c9b99a`.
- Typography: the site's own Fraunces (self-hosted `assets/fraunces.woff2` copied
  from the site's `next/font` build), tracked uppercase ivory wordmark.
- Beats: fiber 0–0.70 · thread 0.70–1.45 · loom 1.45–2.25 · weaving 2.25–3.15 ·
  fabric 3.15–3.70 · brand 3.70–4.00.
- The finale's woven surface must sit directly under the homepage hero's fabric
  drape (matching cocoa `#2a211c` + weave pattern + same 0.9s ease family) so the
  cinematic "never ended".
- User constraint: **no changes outside the loading page.**

## Assets

- `assets/fraunces.woff2` — site's self-hosted Fraunces variable font (latin).
- `assets/readex-pro.ttf` — local Readex Pro loading-page font.
- `assets/Loom_weaving_fabric_in_factory_20260911224432.mp4` — supplied factory weaving footage.

## Notes

- Duration fixed at 4.0s, 30fps, 1920×1080 master.
- Live in-page version targets 60fps capture for a smooth browser playback.
- Render only after explicit user approval (workflow gate).
