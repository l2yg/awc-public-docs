# Security Policy

## Supported version

Security fixes are provided for the latest Marketplace release.

## Reporting a vulnerability

Do not open a public GitHub issue if a vulnerability report contains tokens, personal data, or reproducible exploit code. Contact the repository owner through a private channel and include:

- The affected version
- Preconditions and minimal reproduction steps
- The expected impact
- Relevant logs with sensitive information removed

Please avoid publicly disclosing vulnerability details until the report has been reviewed.

## Security model

Agent Workbench runs only in trusted workspaces. Command execution and file changes follow Codex permission policies and the Workbench approval UI. Review commands and diffs before approving them.
