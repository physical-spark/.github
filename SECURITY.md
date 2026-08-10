# Security Policy

## Reporting a vulnerability

Email **security@incufield.com**. Do not open a public issue.

Include:
- What the problem is
- How to reproduce it
- What an attacker could do with it

We reply within 3 business days.

## If a secret gets committed

Deleting the commit is **not** enough. The value is already exposed.

1. Rotate the credential immediately. This is the only real fix.
2. Tell the team in the internal ops channel.
3. Remove it from history with `git filter-repo`.
4. Ask GitHub Support to purge cached views.

## If personal data gets committed

1. Stop. Do not push more commits.
2. Tell the person responsible for privacy at Incufield.
3. Follow the deletion steps in `handbook/privacy/incident-response.md`.
