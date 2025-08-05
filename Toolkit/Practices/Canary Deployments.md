---
type: "[[Practices]]"
tags: []
next:
  - "[[High Deployment Frequency]]"
  - "[[Low Change Failure Rate]]"
prev:
  - "[[Configure automated deployments]]"
---
# What
Canary deployment is a progressive delivery technique where new software versions are gradually rolled out to a small subset of users before full deployment. The name comes from "canary in a coal mine" - using a small group to detect problems early.
# Why
Canary deployments are valuable because they:
1. **Minimize blast radius** - Problems affect only a small percentage of users initially
2. **Enable early detection** - Issues can be caught with real user traffic but limited impact
3. **Support data-driven decisions** - Metrics from canary users inform rollout decisions
4. **Reduce deployment risk** - Gradual rollout prevents widespread failures
5. **Build confidence** - Successful canary deployments increase confidence in full rollout
6. **Allow performance validation** - Real-world performance can be validated under actual load 