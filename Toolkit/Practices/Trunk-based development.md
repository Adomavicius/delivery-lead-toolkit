---
type: "[[Practices]]"
tags: 
next:
  - "[[Continuous Integration]]"
prev:
  - "[[Set up main branch to allow changes only via pull requests]]"
  - "[[Don't break the build (keep main branch build green)]]"
---
# What
Taken directly from https://trunkbaseddevelopment.com/:
>A source-control branching model, where developers collaborate on code in a single branch called ‘trunk’, resist any pressure to create other long-lived development branches by employing documented techniques. They therefore avoid merge hell, do not break the build, and live happily ever after.
# Why
As mentioned in the section above - by developers frequently committing (merging, unless the team is very small) to a single shared branch you:
1. Avoid majority of merge conflicts
2. Enable faster feedback loops to detect issues and resolve them
3. Simplifies the development process removing the overhead of managing multiple long-lived branches
4. Main branch is kept in a releasable state, which drives towards continuous delivery readiness