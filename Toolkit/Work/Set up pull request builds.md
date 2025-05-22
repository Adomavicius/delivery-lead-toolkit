---
type: "[[Work]]"
tags: []
next:
  - "[[Don't break the build (keep main branch build green)]]"
prev:
  - "[[Source control repository access]]"
  - "[[Build and deployment tool access]]"
---
# What
Every pull request should have a build executed for it, ideally preventing merging of the pull request unless the build passes. The build should include not only building code, but also executing tests upon it.
# Why
Needed to help drive the practice of [[Don't break the build (keep main branch build green)]] - prevent breaking the `main` branch.