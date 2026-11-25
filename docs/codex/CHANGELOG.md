# Codex-wide instruction changelog

## 2026-11-25

- Published the global instructions and established a pull request workflow for keeping this copy aligned with the local rules.
- Added checks for the signed-in user journey, saved results, and required release configuration after a sample report passed while live evaluation failed.
- Required evidence for claims about output correctness, access boundaries, visual fixes, refactors, and root causes. Reports now identify failed and unverified requirements.
- Tied review, CI, and deployment claims to the revision or artifact checked and clarified the authorization needed for a public deployment.
- Defined approved public redactions and whole-file comparison so private instructions can remain local without hiding unexplained differences.
- Moved source identification and verification ahead of deployment and specified evidence for generated artifacts, failures, rollbacks, and Git exceptions. Required equivalent security scans when the Windows scanner is unavailable.
- Added reproducible baseline and candidate evaluations with per-case evidence so claims about AI and automated behavior can be checked. Clarified the learning objectives and edited the instructions for readability.
