# Hi! My name is Joe Barbere. 🐬👊🏻

[![GitHub Sponsors](https://img.shields.io/github/sponsors/joebarbere?logo=githubsponsors)](https://github.com/sponsors/joebarbere)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-donate-ff5f5f?logo=kofi&logoColor=white)](https://ko-fi.com/joebarbere)

I'm building an **open-source radio telescope on a Philadelphia rooftop** — a 700 mm dish
listening to the hydrogen line at 1420 MHz, with the software, the science, and the build
guides all public.

## The jansky projects

Named after [Karl Jansky](https://en.wikipedia.org/wiki/Karl_Guthe_Jansky), who discovered
radio emission from the Milky Way with homemade equipment. Same spirit, smaller dish:

- 📡 [**jansky-observe**](https://github.com/joebarbere/jansky-observe) — the station
  software, now **feature-complete through every planned milestone**: an SDR capture daemon +
  live waterfall, a session wizard and observing ladder, an HI-line classifier, PDF
  observation reports, calibration epochs + an unattended transit scheduler + drift-scan
  campaigns, a codified research-export bundle, printable build & observation guides, and
  az/el rotator control of the dish — all behind a 22-tool MCP surface so Claude can help run
  (and now point) the telescope. Real release engineering too: every install is gated on a
  QEMU boot of genuine Raspberry Pi OS. **What's left is first light** — the software's ready,
  the roof isn't wired yet.
- 📖 [**jansky**](https://github.com/joebarbere/jansky) — a hands-on radio astronomy
  course in Python: executable notebooks from *"what is a radio wave from space?"* to
  downloading real telescope data, plus the tested helper library the other repos build on.
- 🔬 [**jansky-research**](https://github.com/joebarbere/jansky-research) — original
  amateur research with honesty as the first rule: tested tools, real public data, an
  adversarial science-review gate, and write-ups that report negatives plainly. The
  station track is aiming at a 12-month hydrogen-line Doppler curve, drift-scans
  validated against HI4PI, and a flux-calibrated quiet-Sun monitor.

## ☕ Support the station buildout

If any of this is useful or just fun to watch, you can help fund the next piece of
hardware — every sponsorship goes to the buildout:

**[GitHub Sponsors](https://github.com/sponsors/joebarbere)** · **[Ko-fi](https://ko-fi.com/joebarbere)**

Current wishlist, roughly in order: storage for IQ recordings → rooftop networking (PoE
switch + access point) → the Discovery Drive rotator (automated pointing — the software
already ships, waiting on the hardware) → a second dish → a KrakenSDR for coherent
interferometry. It's a general direction, not a promise — the roadmap changes as the station
meets the real sky.

## Current interests include

- [ ] Claude Code and agentic engineering
- [ ] Hydrogen-line radio astronomy & software-defined radio
- [ ] Raspberry Pi field systems that survive a rooftop
- [ ] Open, reproducible amateur science

## 2026 Goals

- [ ] First light: detect galactic hydrogen (21 cm) from the roof
- [ ] Run the first end-to-end observing campaign (plan → observe → confirm → report) — jansky-observe v1.0.0
- [ ] Publish the station build guide
- [ ] AWS Certified AI Practioner
- [ ] AWS Certified Machine Learning - Specialty
