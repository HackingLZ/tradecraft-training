# Adversarial Tradecraft: Operational Security Training

Interactive slide deck covering operational security principles for authorized red team operations and penetration testing engagements.

**Live site:** [hackinglz.github.io/tradecraft-training](https://hackinglz.github.io/tradecraft-training/tradecraft-training.html)

## Overview

Module 1 of an adversarial operations training series. Derived from analysis of real-world operations — focused on generalizable principles rather than specific tools or targets.

17 slides covering:

- Why operations fail (predictable, avoidable mistakes)
- 13 core principles of adversarial tradecraft
- Quick reference summary of all principles

## The 13 Principles

| # | Principle |
|---|-----------|
| 01 | Separate environments — dedicated VM per engagement, encrypted vaults |
| 02 | Cleanup is doctrine — automated first, manual verification second |
| 03 | Map EDR coverage — know detection rules and altitude before moving |
| 04 | Blend in — exact metadata match, OS-native mechanisms, no novel patterns |
| 05 | Survey first — enumerate defenses, environment drives tool selection |
| 06 | C2 discipline — sleep before first contact, unique IDs per deployment |
| 07 | Fail-safes — one-action burn, exposure timers, cryptographic command auth |
| 08 | Depth over speed — fixed cadence, timing tuned per target |
| 09 | Layer everything — independent mechanisms, compartmented components |
| 10 | Pre-access OSINT — know the stack and defenders before touching anything |
| 11 | Post-access recon — read the host before moving |
| 12 | Cloud & identity — PRT extraction, Bearer token reuse, Graph API recon |
| 13 | Hide from EDR — ETW patching, direct syscalls, timestamp matching |

## License

[CC BY 4.0](LICENSE) — free to use and share with attribution to HackingLZ.

## Navigation

Arrow keys, on-screen buttons, or swipe to move between slides.

## Deployment

Deployed via GitHub Actions to GitHub Pages on every push to `main`. See `.github/workflows/deploy.yml`.
