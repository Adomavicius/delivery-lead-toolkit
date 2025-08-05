---
type: "[[Practices]]"
tags: []
next:
  - "[[High Deployment Frequency]]"
  - "[[Low Change Failure Rate]]"
  - "[[Trunk-based development]]"
prev:
  - "[[Implement feature flag system]]"
---
# What
Feature flags (also known as feature toggles) are a software development technique that allows teams to turn features on or off without deploying new code. They enable deploying code to production with features disabled, then enabling them for specific users, environments, or conditions.
# Why
Feature flags are valuable because they:
1. **Decouple deployment from release** - Deploy code safely without immediately exposing features to users
2. **Enable gradual rollouts** - Release features to small user segments first, reducing risk
3. **Support A/B testing** - Compare different feature implementations with real users
4. **Provide quick rollback** - Disable problematic features instantly without redeploying
5. **Enable trunk-based development** - Multiple teams can work on the same codebase without branching
6. **Reduce deployment risk** - Failed features can be disabled without affecting other functionality 