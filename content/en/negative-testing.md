---
title: Negative Testing
status: Completed
category: concept
tags: ["fundamental", "", ""]
---

Negative testing, also called “error path testing” or “invalid input
testing,” is a software testing methodology that evaluates how
systems and applications handle unexpected inputs and conditions.
This is contrasted with positive testing, that is, testing the "happy path"
initiated by expected inputs.

Negative testing includes testing to ensure that what should not happen
does not happen. This is vital for security.
For example, if a user should not be able to delete an object owned by another
user, it's important to *test* this is the case.
If a field is supposed to only provide a number, a negative test should
ensure that non-numbers are rejected.
Many test suites only test the "happy path" of expected values.
Many security properties are negative ("X should never happen"), so failing to
apply negative testing can lead to serious security vulnerabilities.

Source: https://www.ranorex.com/blog/positive-testing-vs-negative-testing-key-differences/
