# Code Review Reference

Review code for correctness, security, reliability, maintainability, and clarity.

## Review priorities

1. Correctness: logic errors, incorrect assumptions, boundary conditions, and race conditions.
2. Data integrity: invalid state transitions, lost updates, and unsafe database operations.
3. Security: missing authorization checks, injection risks, exposed secrets, unsafe input handling, and sensitive-data leakage.
4. Reliability: unhandled errors, missing timeouts, fragile dependencies, and failure recovery.
5. Performance: unnecessary repeated work, inefficient queries, and avoidable resource usage.
6. Maintainability: unclear naming, excessive complexity, duplication, and missing useful tests.

## How to report findings

For each meaningful finding, include:
- Severity: critical, high, medium, or low.
- Location: the relevant file, function, or line, if known.
- Issue: what appears wrong.
- Impact: why it matters.
- Recommendation: a practical correction.
- Confidence: confirmed by the supplied evidence or needs verification.

## Review principles

- Prioritize actionable defects over personal style preferences.
- Do not invent line numbers or claim a vulnerability exists without supporting evidence.
- Explain when a concern depends on missing context.
- Recognize positive patterns when useful.
- Suggest focused tests for important behavior and edge cases.
- Do not describe a review as exhaustive unless its scope supports that conclusion.

## Sensitive information

Do not repeat secrets found in supplied code. Recommend removing exposed credentials and rotating them when appropriate.
