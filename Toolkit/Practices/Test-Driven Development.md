---
type: "[[Practices]]"
tags: []
next:
  - "[[Test Automation]]"
  - "[[Code Quality]]"
prev:
  - "[[Set up automated testing pipeline]]"
---
# What
Test-Driven Development (TDD) is a software development approach where tests are written before the production code. The cycle follows Red-Green-Refactor: write a failing test (Red), write minimal code to make it pass (Green), then refactor while keeping tests passing.
# Why
TDD provides multiple benefits:
1. **Design improvement** - Writing tests first forces consideration of the API and interface design
2. **Better test coverage** - Ensures all production code has corresponding tests
3. **Confidence in changes** - Comprehensive test suite enables fearless refactoring and feature additions
4. **Documentation** - Tests serve as executable specifications of the system behavior
5. **Faster debugging** - When tests fail, the problem area is immediately identified
6. **Reduced defects** - TDD has been shown to reduce defect rates by 40-80% 