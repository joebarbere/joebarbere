# Hi! My name is Joe Barbere. 🐬👊🏻

[![GitHub Sponsors](https://img.shields.io/github/sponsors/joebarbere?logo=githubsponsors)](https://github.com/sponsors/joebarbere)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-donate-ff5f5f?logo=kofi&logoColor=white)](https://ko-fi.com/joebarbere)

I'm building an **open-source radio telescope on a Philadelphia rooftop** — a 700 mm dish
listening to the hydrogen line at 1420 MHz, with the software, the science, and the build
guides all public.

## The jansky projects

Named after [Karl Jansky](https://en.wikipedia.org/wiki/Karl_Guthe_Jansky), who discovered
radio emission from the Milky Way with homemade equipment. Same spirit, smaller dish:

- 📖 [**jansky**](https://github.com/joebarbere/jansky) — a hands-on radio astronomy
  course in Python: executable notebooks from *"what is a radio wave from space?"* to
  downloading real telescope data, plus the tested helper library the other repos build on.
- 🔬 [**jansky-research**](https://github.com/joebarbere/jansky-research) — original
  amateur research with honesty as the first rule: tested tools, real public data, an
  adversarial science-review gate, and write-ups that report negatives plainly. The
  station track is aiming at a 12-month hydrogen-line Doppler curve, drift-scans
  validated against HI4PI, and a flux-calibrated quiet-Sun monitor.
- 📡 [**jansky-observe**](https://github.com/joebarbere/jansky-observe) — the station
  software, now **feature-complete through every planned milestone**: an SDR capture daemon +
  live waterfall, a session wizard and observing ladder, an HI-line classifier, PDF
  observation reports, calibration epochs + an unattended transit scheduler + drift-scan
  campaigns, a codified research-export bundle, printable build & observation guides, and
  az/el rotator control of the dish — all behind a 22-tool MCP surface so Claude can help run
  (and now point) the telescope. Real release engineering too: every install is gated on a
  QEMU boot of genuine Raspberry Pi OS. **What's left is first light** — the software's ready,
  the roof isn't wired yet.
- 🛠️ [**jansky-forge**](https://github.com/joebarbere/jansky-forge) — design, build and characterize
  radio-astronomy antennas, with a provenance-checked catalog of known telescope builds.
- 📚 [**awesome-radio-astronomy**](https://github.com/joebarbere/awesome-radio-astronomy) — a curated list of
  open data archives, surveys, software and learning resources, compiled along the way.

## Other recent projects

- 🧠 [**learn-jax**](https://github.com/joebarbere/learn-jax) — a hands-on course in deep learning, JAX and LLMs
  on a consumer AMD GPU (RX 7600 XT, ROCm). 40 marimo notebooks, from arrays and autodiff to training a small
  mixture-of-experts LLM, LoRA, local inference, profiling, sharding and running the same code on AWS, plus a
  family tree of ~50 foundation models and the building blocks each one added.
- 🐋 [**deepseek-v3-jax**](https://github.com/joebarbere/deepseek-v3-jax) — my replication of
  [Vaibhaav Tiwari's](https://github.com/Vaibhaav-Tiwari/deepseek-v3-jax) DeepSeek-V3 in 190 lines of pure JAX
  (MLA, DeepSeekMoE, aux-loss-free balancing, multi-token prediction), trained on the same AMD GPU.
- 💾 [**bayside**](https://github.com/joebarbere/bayside) — reverse engineering Tandy DeskMate 3.05 (1990) into
  clean, compilable C: all 87 binaries disassembled and annotated, transpilation to C89 under way.
- ☁️ [**aws-ai**](https://github.com/joebarbere/aws-ai) — Terraform and Python for the AWS AI services on the
  AI Practitioner exam, with a Claude agent that writes the infrastructure.
- ⚡ [**controls**](https://github.com/joebarbere/controls) — an electrician → controls-engineer simulation game
  (Electron, Angular, Three.js).
- 🤖 [**jezero-lab**](https://github.com/joebarbere/jezero-lab) — a local reinforcement-learning lab: NASA-JPL's
  Open Source Rover in a simulated Jezero Crater (ROS 2, Gazebo, Podman).

## ☕ Support the station buildout

If any of this is useful or just fun to watch, you can help fund the next piece of
hardware — every sponsorship goes to the buildout:

**[GitHub Sponsors](https://github.com/sponsors/joebarbere)** · **[Ko-fi](https://ko-fi.com/joebarbere)**

Current wishlist, roughly in order:
- RF test equipment
- Storage for IQ recordings
- Rooftop networking (PoE switch + access point)
- Discovery Drive rotator (automated pointing, jansky-observe already supports it)
- Second dish/feedhorn
- KrakenSDR (for coherent interferometry)

## Current interests include

- [ ] Claude Code and agentic engineering
- [ ] Deep learning and LLMs in JAX, on AMD GPUs
- [ ] Hydrogen-line radio astronomy & software-defined radio
- [ ] Raspberry Pi field systems that survive a rooftop
- [ ] Open reproducible amateur science

## 2026 Goals

- [ ] First light: detect galactic hydrogen (21 cm) from the roof
- [ ] Run the first end-to-end observing campaign (plan → observe → confirm → report) — jansky-observe v1.0.0
- [ ] Publish the station build guide
- [ ] AWS Certified AI Practioner
- [ ] AWS Certified Machine Learning - Specialty
