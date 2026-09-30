# Repository Copilot instructions

## Maintainer-controlled rules

Automation MUST NOT modify this section.

- Follow least-privilege security practices.
- Keep learner-facing instructions concise and action-oriented.
- Use Node.js 20 for repository automation.

<!-- learned-rules:start -->
## Learned rules

Rules below are managed only through reviewed candidate pull requests.

### RULE-TEST-PARSER-001

- **Category:** TEST
- **State:** active
- **Rule:** Always add or update unit tests when parser behavior changes.
- **Rationale:** Parser changes require regression coverage.
- **Scope:** repository
- **Provenance:** bootstrap example; approved by repository maintainers

### RULE-TEST-8F61D4A1E65E

- **Category:** TEST
- **State:** active
- **Rule:** Add unit tests for every new exported function.
- **Rationale:** applyDiscount shipped without tests and CI did not catch the gap.
- **Scope:** path:src/
- **Provenance:** [PR #2 comment 5915843031](https://github.com/abel-dojo/self-correcting-copilot-instructions-live-demo/pull/2#issuecomment-5915843031) by @abelberhane

<!-- learned-rules:end -->
