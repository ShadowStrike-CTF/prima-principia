# prima-principia

Prerequisite-aware university course schedule generator.

Work out the fastest valid path through your degree — given which units you want, when you can start, and how many units per trimester you can handle. Works backwards from your target units through the full prerequisite chain and outputs a trimester-by-trimester schedule.

**Status: development in progress.** The algorithm and Deakin JD dataset are built and validated. The full web app and Python package are in active development.

---

## What it does

- Takes your target electives and start trimester as input
- Resolves the full prerequisite chain automatically
- Schedules units trimester-by-trimester, respecting offering constraints (T2-only, T3-only, etc.)
- Flags units offered only in specific years so you don't miss a narrow window
- Warns when prerequisite data is unverified

## Current support

- Deakin JD (M729) — 2026 and 2027 handbooks

## Planned

- Multi-university support (UTS JD, UNSW JD, UNE LLB)
- Semester structure (not just trimesters)
- iOS / Android (React Native + Expo)
- User accounts — track completed units, update schedule live

---

## Install

```
pip install prima-principia
```

> Stub release only. Full implementation coming — star the repo to follow progress.

---

## Licence

MIT — see [LICENSE](LICENSE)

© 2026 ShadowStrike. Licensed under the MIT Licence.
