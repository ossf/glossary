---
title: Fuzzing
status: Completed
category: concept
tags: ["fundamental", "", ""]
---

Fuzzing, also called fuzz testing, is an automated verification technique that involves providing invalid, unexpected, or random data as inputs to a computer program. The program is executed and monitored for exceptions such as crashes, failing built-in code assertions, or potential memory leaks. 

Fuzz testing differs from traditional software testing. A traditional software tests sends a known input, executes the program, and verifies that the output is correct. Traditional software tests are much more sensitive to incorrect outputs, but these tests take time to create because the correct output must be determined (requiring an "oracle"). Fuzz testing abandons the need to know the correct output, making it easy to apply many more inputs but reducing the ability to detect errors in each execution. Many systems use traditional software testing to check basic functionality and combine that with fuzzing to attempt to detect problems like security vulnerabilities.

The term "fuzz" and the concept of fuzz testing originates from work by Prof. Barton Miller at the University of Wisconsin published in 1990.

Source: https://en.wikipedia.org/w/index.php?title=Fuzzing&oldid=1270167521
