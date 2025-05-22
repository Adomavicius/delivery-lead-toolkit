---
type: "[[Practices]]"
tags: 
next:
  - "[[Continuous Integration]]"
  - "[[Trunk-based development]]"
prev:
  - "[[Set up main branch to allow changes only via pull requests]]"
  - "[[Set up pull request builds]]"
---
# What
Main/trunk branch build should always be a successful/green state and if it is not - the #1 priority of the engineering team should be to make it successful/green again.
# Why
Several reasons for this:
1. It's a prerequisite for practicing [[Trunk-based development]] - having a single branch that developers know is a reliable starting point enables for higher developer productivity
2. If the main branch breaks it immediately signals an integration problem, allowing the team to address is quickly before it escalates.