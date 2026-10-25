# Security Policy

This policy covers every Automatiqa Lab repository that does not carry its own `SECURITY.md`.
Where a repository has one, that file takes precedence.

Automatiqa Lab publishes open-source code and templates. The lab operates no service, hosts no
instance and receives no data: everything runs inside the deployer's own boundary. Vulnerability
reports are taken seriously all the same.

## Reporting a vulnerability

Please report privately - do not open a public issue for a security problem.

- Preferred: open a private advisory via GitHub Security Advisories ("Report a vulnerability" on
  the repository's Security tab).
- Or email **aleks@automatiqa.io**.

Include the repository, what you found, how to reproduce it, the impact, and any suggested fix. If
you have a proof of concept, attach it.

Expect acknowledgement within 3 business days, and a disclosure timeline agreed with you. Credit
is given unless you prefer otherwise.

## Supported versions

Lab projects are pre-1.0 unless their README says otherwise. Fixes land on `main` and in the next
release; older tags are not patched.

## Scope

In scope:

- Prompt injection in an input document or message that changes a decision, alters stored
  records, or causes data to be sent anywhere other than the configured endpoints
- Any path that bypasses an approval gate or lets an agent act without the recorded approval the
  project says it needs
- Secrets recoverable from logs, error messages, exported workflows or other artefacts
- Missing or strippable AI-generated marking where a project's `COMPLIANCE.md` says it applies

Out of scope:

- The security of the language model endpoint you configure and hold the key for
- Vulnerabilities in upstream components (Python packages, n8n, databases, model providers) -
  report those upstream, though a note here is appreciated if the combination is what makes it
  exploitable
- Findings that require an attacker to already hold deployer credentials
- Reports produced solely by an automated scanner with no demonstrated impact
