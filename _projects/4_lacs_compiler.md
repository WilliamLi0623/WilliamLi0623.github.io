---
layout: page
title: Lacs Language Compiler
description: A full compiler from Lacs to MIPS, with a garbage-collected runtime.
importance: 4
category: systems
---

**Sept – Dec 2025** · MIPS, compiler construction

An end-to-end compiler for the Lacs language targeting MIPS.

- **Front end:** DFA-based scanning, CYK parsing, and lexical scoping.
- **Middle end:** lowering to an intermediate representation.
- **Back end:** MIPS code generation with a stack/heap runtime, **tail calls**, and a **Cheney copying garbage collector**.
