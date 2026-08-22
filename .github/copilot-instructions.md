# Copilot Instructions

## Project Overview

This repository is a fork of Alamofire, a Swift HTTP networking library. Treat changes as library work with broad platform and API compatibility impact.

## Engineering Rules

- Keep public API compatibility in mind for every source change.
- Prefer small, reviewable changes that preserve upstream style.
- Do not commit credentials, signing material, tokens, certificates, private package registry data, or local machine paths.
- For dependency updates, check CI, package resolution, docs tooling, and generated lockfiles.
- Avoid broad formatting churn or unrelated refactors.

## Validation

Use the repository's existing CI and project scripts where possible. For dependency updates, include the lockfile/package impact and any failing check details in the PR.

## Risk Areas

- public Swift API behavior
- platform compatibility across Apple and non-Apple targets
- dependency lockfiles and docs tooling
- GitHub Actions and release automation
