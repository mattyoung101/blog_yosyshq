---
title: "Interim YosysHQ LLM Policy"
date: 2026-08-26
description : ""
tags: ["blog"]
draft: false
---

### Foreword

As the maintainers of OSS CAD suite and Tabby CAD suite, we’ve seen an increasing number of pull requests containing LLM generated code. Developing a consistent and unanimously accepted approach on how we intend to handle these, requires time. In the meantime, pending a more holistic policy, we are announcing the following interim YosysHQ LLM Policy/FAQ:

# Interim YosysHQ LLM Policy

As a general rule: **Please do not file pull requests to our GitHub projects containing LLM generated code.**

YosysHQ does not currently support the use of LLMs. LLMs do not have a mind and are incapable of original thought. Time spent on reviewing contributions authored by humans is time invested in building a stronger community by spreading our shared understanding of the project. We view our projects as critical infrastructure and thus deem it important that we, the engineers at YosysHQ as well as the wider developer community, stay in control of our code base, maintain our shared understanding of it, and keep providing software that is trustworthy and can easily be understood and extended by human beings.

* **PRs for “vibe-coded” features or extensions**

    We now live in a new world where it is easy to use an AI to patch arbitrary features into a codebase we do not understand. However, these patches, even when they yield the intended effect for the user who created them, and thus have value to them personally, are effectively spam when turned into upstream pull requests. __We ask users to instead create an issue if they request a feature in our products.__ That issue may contain a statement such as “I used this or that LLM with the following prompt and it produced a working prototype”, but please refrain from sending us the LLM generated code changes.

* **PRs for LLM-generated bugfixes**

    In case of a bugfix or other small change we will, if the code appears to be LLM generated, fix the bug using either another equivalent or better code change. Or, if the proposed change turns out to be the one and only reasonable way to do it, copyright does not apply due to lack of room for creativity, and we will independently apply that change without attribution. __Therefore we also ask users to refrain from sending us LLM generated bugfixes and instead use LLMs to produce a minimal failing test case and submit a regular issue instead.__

* **Attribution means responsibility**

    Every code change in our projects should be attributed to a human being that authored the code change and can explain it and answer questions about it, both during review and also later. We generally do allow “AI assisted” code. However, we understand “AI assisted” as implying the commitment to defend the choices made in that code as *your* choices, even if an AI suggested those choices to you.

* **Exceptions on a case-by-case basis**

    Exceptions can be made on a case-by-case basis, especially when the prompt is specific enough so that different models will yield identical or almost identical code, and the task is simple enough so that a student would be expected to be able to produce the same (identical or almost identical) code. In such cases the commit message should contain all relevant information, including the full prompt that yielded the code.

* **Complete ban of LLM-generated code comments and commit messages**

    Just. Don't.

This policy is not set in stone and we will revise it over time as we deem necessary.
