# .github

- GitHub organization: `eia-open-insurance`
- Repository URL: https://github.com/eia-open-insurance/.github
- Type: Organization profile
- Deployable: No
- Owner: Platform
- Runtime: GitHub Actions and YAML
- Data store: Not applicable
- Depends on: None

## Purpose

Organization profile, issue and pull-request templates, reusable GitHub Actions workflows, and organization-level policy.

## Responsibilities

- Keep this repository focused on one deployable component or one platform concern.
- Follow the repository standard in `../CONVENTIONS.md` and the specification in `../../SPEC.md`.
- Publish and consume contracts through `eia-contracts`.
- Maintain README, CODEOWNERS, SECURITY, CHANGELOG, tests, and CI.
- Contain no business logic in shared libraries or front-end remotes.

## Required checks

- Lint and format
- Unit tests with 100% business-logic coverage where applicable
- Contract tests
- Integration or Playwright tests where applicable
- Security scan and SBOM
- Build and publish

## Notes

This is the GitHub organization .github repository.

## License

Apache License 2.0. See [LICENSE](LICENSE) and [NOTICE](NOTICE).
