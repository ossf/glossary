---
title: DAST
status: Completed
category: concept
tags: ["fundamental", "acronym", ""]
---

DAST is an acronym for Dynamic Application Security Testing.

There is agreement that DAST executes a program (that is, it uses dynamic analysis instead of static analysis) to find vulnerabilities. However, while the term DAST is often seen in the literature, the *meaning* of DAST has variation in industry.

By some definitions, DAST is dynamic analysis for finding vulnerabilities in (only) web applications (see VeraCode, [*DAST TEST: Benefits of a DAST test for application security*](https://www.veracode.com/security/dast-test), 2020). This makes the term DAST mostly equivalent to the use of *web application scanners*. John Breeden II ([*9 top fuzzing tools: Finding the weirdest application errors*](https://www.csoonline.com/article/3487708/9-top-fuzzing-tools-finding-the-weirdest-application-errors.html), 2019) states this and expressly differentiates DAST from fuzzing.

Others definitions use the term DAST more broadly, where dynamic analysis is used to find vulnerabilities where the "tester has no [necessary] prior knowledge of the system". Under this definition, DAST includes web application scanners, fuzzers, and other dynamic approaches that can be applied to applications. Examples include Thomas Scanlon ([*10 Types of Application Security Testing Tools: When and How to Use Them*](https://insights.sei.cmu.edu/sei_blog/2018/07/10-types-of-application-security-testing-tools-when-and-how-to-use-them.html), 2018) and Sergej Dechand ([*What is FAST?*](https://blog.code-intelligence.com/what-is-fast), 2020) includes web application scanners and fuzzers under “DAST”.

[NIST Special Publication 800-204C](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-204C.pdf)
attempts to split the difference, defining DAST as analyzing
"applications in their dynamic, running state during testing or
operational phases. They simulate attacks against an application
(typically webenabled applications, services, and APIs), analyze
the application’s reactions, and determine whether it is vulnerable."

Source: https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-204C.pdf

