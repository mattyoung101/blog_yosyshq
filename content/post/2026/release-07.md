---
title: "Tabby CAD Suite version 20260709 released!"
date: 2026-07-09
description : ""
image: /static-2023/YOS_horiz.png
tags: ["release notes"]
draft: false
---

The July release of Tabby CAD Suite is now available for download. This version includes under-the-hood improvements to performance and bugfixes. Some notable changes affecting customers that maintain their own custom plugins or compile on their own:

* The project is now requiring CMake 3.28 or later as build system.
* The minimum supported C++ standard version has been updated to C++20 in the previous release. 
* We now support compilers from GCC-13 and Clang-16, but we recommend later versions for stability (like GCC-15 and Clang-21).
* This release includes [sv-elab](https://github.com/povik/sv-elab) built on top of the [slang](https://github.com/MikePopoloski/slang) library to provide fully open source SystemVerilog (but not yet SVA) support.

In other YosysHQ news:

* Come and meet us at ORConf - a weekend of presentations and networking dedicated to free and open source silicon. Register [here](https://fossi-foundation.org/orconf/2026).

Happy July,
The YosysHQ Team
