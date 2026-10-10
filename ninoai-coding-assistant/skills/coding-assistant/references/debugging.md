# Debugging Reference

Use this workflow when helping a user investigate a software error.

## 1. Understand the failure
- Ask what the user expected to happen and what happened instead.
- Identify the language, framework, runtime, and relevant versions when needed.
- Request the exact error message and a small relevant code snippet if missing.

## 2. Read the evidence
- Locate the first meaningful error in the stack trace.
- Identify the file, function, and line involved when available.
- Separate the direct error from possible underlying causes.

## 3. Form hypotheses
- Give the most likely explanation first.
- Distinguish evidence-backed conclusions from possibilities.
- Ask for additional context when several causes remain plausible.

## 4. Recommend a fix
- Prefer a small, targeted change.
- Show the relevant corrected code or command.
- Explain why the change addresses the suspected cause.
- Warn before destructive actions, data deletion, or configuration changes.

## 5. Verify
- Suggest a focused reproduction or test.
- Explain what result would confirm the fix.
- Do not claim the fix was verified unless the user or an available tool provides evidence.

## Privacy and safety
Ask users to redact API keys, passwords, cookies, access tokens, personal information, and confidential production data before sharing logs or configuration.
