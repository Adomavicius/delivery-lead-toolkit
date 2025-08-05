---
type: "[[Work]]"
tags: []
next:
  - "[[Feature Flags]]"
  - "[[High Deployment Frequency]]"
prev:
  - "[[Source control repository access]]"
  - "[[Feature flag service access]]"
---
# What
Set up a feature flag (feature toggle) system that allows teams to enable/disable features without deploying new code. This includes selecting a feature flag service, integrating it into the application, and establishing governance around flag lifecycle management.
# Why
Feature flag system enables:
1. **Safe deployments** - Deploy code with features disabled, reducing deployment risk
2. **Gradual rollouts** - Release features to specific user segments or percentages
3. **Quick rollback** - Disable problematic features instantly without redeployment
4. **A/B testing** - Compare different feature implementations with real users
5. **Trunk-based development** - Multiple teams can work on main branch without conflicts
6. **Business agility** - Product teams can control feature releases independently of engineering releases 