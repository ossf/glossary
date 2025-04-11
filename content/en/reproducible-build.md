---
title: Reproducible Build
status: Completed
category: concept
tags: ["fundamental", "", ""]
---

A build is *reproducible* if given the same source code, build environment and build instructions, any party can recreate bit-by-bit identical copies of all specified artifacts. This creates an independently-verifiable path from source to binary code and counters attacks on the build process.

A *verified* reproducible build is a build result that has been independently verified to reproduce. Verified reproducible builds allow multiple third parties to come to a consensus on a “correct” result, highlighting any deviations as suspect and worthy of scrutiny. See <https://reproducible-builds.org/docs/> for tips on how to achieve reproducible builds.

Source: https://reproducible-builds.org/docs/definition/
