# Security policy

This public fork is maintained as an AI comic and short-video creation app
experiment. Security work focuses on safer API configuration, token handling,
and dependency review.

## Supported version

The `master` branch is the maintained branch for this fork.

## Reporting a vulnerability

Please open a GitHub issue for non-sensitive security concerns, such as unsafe
defaults, exposed sample tokens, dependency warnings, or reproducible crashes.

For sensitive reports, please avoid posting secrets, tokens, private logs, or
exploit details publicly. Open a minimal issue first so a private follow-up path
can be arranged.

## Current security priorities

- Keep API tokens out of committed source and examples.
- Document safer local configuration for API providers.
- Review dependency updates before accepting them.
- Add small smoke tests around API configuration behavior.
