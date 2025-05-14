---
type: "[[Goals]]"
tags: []
next: 
prev:
  - "[[Don't break the build (keep main branch build green)]]"
  - "[[Trunk-based development]]"
---
# What
Continuous integration (CI) is the practice of automating the integration of code changes from multiple contributors into a single software project. Usually, when paired with [[Trunk-based development]], it means always building and deploying changes to the main/trunk branch automatically and ensuring that all integrations work appropriately.
# Why
Highly important goal with reasons being:
1. Allows for early bug detection - finding issues automatically and early in the development cycle is easier and cheaper to fix
2. Reduces risk for integration problems as changes are constantly integrated
3. Increased engineer collaboration and productivity - provides a shared understanding of the project's health and frees up developers to focus on writing code rather than dealing with manual integration or branch/build/deployment management