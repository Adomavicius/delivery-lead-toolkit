---
type: "[[Practices]]"
tags: []
next:
  - "[[High Deployment Frequency]]"
  - "[[Low Mean Time to Recovery]]"
prev:
  - "[[Configure automated deployments]]"
---
# What
Blue-green deployment is a technique that uses two identical production environments. Only one environment (e.g., Blue) serves production traffic while the other (Green) is idle. New releases are deployed to the idle environment, tested, and then traffic is switched over instantly.
# Why
Blue-green deployments provide significant advantages:
1. **Zero-downtime deployments** - Traffic switches instantly between environments with no service interruption
2. **Instant rollback** - If issues arise, traffic can be immediately switched back to the previous version
3. **Production testing** - New version can be thoroughly tested in production environment before receiving traffic
4. **Reduced deployment risk** - Problems are caught before affecting users
5. **Simplified deployment process** - Clear, repeatable deployment workflow
6. **Better disaster recovery** - Always have a complete backup environment ready 