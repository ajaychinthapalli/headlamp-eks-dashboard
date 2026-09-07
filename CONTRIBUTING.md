# Contributing

Thanks for helping improve this EKS + Headlamp setup guide.

## How to contribute

- Open an issue for larger changes or questions before writing a large patch.
- Keep changes focused on the setup, security, and operational guidance described in this repository.
- Prefer clear, copy-pastable commands and secure defaults over shorthand examples.

## Pull request guidelines

1. Create a branch from the latest `main`.
2. Make the smallest change that addresses the issue or improvement.
3. Update the relevant documentation so the instructions remain consistent.
4. Verify commands still reflect current Kubernetes / Helm / Headlamp usage.
5. Open a PR with a short summary of the change and why it matters.

## Documentation expectations

- Use plain, readable English.
- Include commands in fenced bash blocks where appropriate.
- Call out security warnings and production hardening steps clearly.
- Avoid recommending insecure defaults for shared or public-facing environments.

## Review expectations

This repository is intentionally small and operationally focused. Reviews will prioritize:

- correctness of Kubernetes and Helm commands
- security impact and least-privilege guidance
- clarity for operators setting up or maintaining the dashboard

## Questions

If you are unsure whether a change fits the project, open an issue first and describe the goal, the risk, and the expected outcome.
