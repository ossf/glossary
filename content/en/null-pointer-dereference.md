---
title: NULL Pointer Dereference
status: Completed
category: concept
tags: ["vulnerability", "", ""]
---

The product dereferences a pointer that it expects to be valid but is NULL.
A NULL pointer dereference usually results in the failure of the
process unless exception handling (on some platforms) is available
and implemented. Thus, it often leads to a failure of availability (a part
of the definition of security).
In C, dereferencing a null pointer is undefined behavior (UB),
permitting any result including any kind of security vulnerability.

This is weakness CWE-476.

Source: https://cwe.mitre.org/data/definitions/476.html
