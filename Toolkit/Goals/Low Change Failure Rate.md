---
type: "[[Goals]]"
tags: []
next: 
prev:
  - "[[Set up pull request builds]]"
  - "[[Don't break the build (keep main branch build green)]]"
  - "[[Feature Flags]]"
  - "[[Canary Deployments]]"
  - "[[Small Batch Sizes]]"
  - "[[Automated Rollback Procedures]]"
  - "[[Post-Incident Reviews]]"
  - "[[Set up code quality gates]]"
---
# What
Low Change Failure Rate measures the percentage of deployments that result in degraded service or require immediate remediation (hotfix, rollback, patch). This DORA metric indicates deployment quality. Elite performers have change failure rates of 0-15%.
# Why
Low change failure rate is important because:
1. **Service stability** - Fewer failed deployments mean more stable and reliable services for users
2. **Reduced toil** - Less time spent on incident response and emergency fixes means more time for feature development
3. **Improved confidence** - Teams develop confidence in their deployment processes when failures are rare
4. **Lower stress** - Predictable, successful deployments reduce team stress and on-call burden
5. **Better resource utilization** - Time saved from not fixing broken deployments can be invested in new features and improvements 