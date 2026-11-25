# Public release gate

Maintainer approval required before changing visibility. This checklist is a process, not a certification.

- [ ] Review every tracked file, including examples, comments, diagrams and configuration.
- [ ] Check combinations of details for technology fingerprinting, organizational attribution, operational timing, coverage gaps and personal identifiers.
- [ ] Verify no private repository references, credentials, internal endpoints, actual source profiles, real incident records or populated configuration.
- [ ] Inspect all commits, branches, tags, issues, pull requests, releases, wiki, actions logs/artifacts and repository metadata.
- [ ] Run independent secret scanning and manual OPSEC review; automated scanning cannot establish absence of contextual leakage.
- [ ] Check account-level public metadata and attribution risk. Existing license and commit attribution may identify the maintainer.
- [ ] Confirm examples are synthetic, claims are supportable and no private deployment validation is implied.
- [ ] Obtain explicit maintainer approval.

Do not copy private history into a public repository. Removing content in a later commit does not erase earlier disclosure. Public copies and indexing cannot be reliably recalled.
