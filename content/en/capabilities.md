---
title: Capabilities
status: Completed
category: concept
tags: ["fundamental", "gemara"]
---

a. A capability is a feature or function of a system; the primary component comprising an attack surface.

b. Linux kernel uses capabilities to compartmentalize the UNIX root privilege into a set of non-overlapping sub privileges (called capabilities) that can be individually assigned where higher granularity than root/non-root is suitable.

## Problem it addresses

a. To manage [risk](risk.md) and [threat](threat.md)s, you must know what a system can do.
Vague or incomplete descriptions of functionality make it hard to identify where things can go wrong.

## How it helps

a. Naming capabilities makes it possible to map [threat](threat.md)s and [vulnerability](vulnerability.md)s to specific functions. It supports [risk assessment](risk-assessment.md) and the design of [control](control.md)s that protect or constrain those capabilities.

Source (a): [Gemara: A Governance, Risk, and Compliance Engineering Model for Automated Risk Assessment](https://openssf.org/resources/gemara-a-governance-risk-and-compliance-engineering-model-for-automated-risk-assessment/). 
Source (b): Reference for capabilities list: https://man7.org/linux/man-pages/man7/capabilities.7.html
