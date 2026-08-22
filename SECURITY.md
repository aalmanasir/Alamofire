# Security Policy

## Supported Scope

This repository is a fork of Alamofire, a Swift HTTP networking library. Security review should prioritize:

- HTTP request/response behavior
- authentication, header, cookie, and redirect handling
- TLS/security configuration behavior
- dependency and supply-chain risk
- CI/release automation and package metadata

## Reporting a Vulnerability

Do not open a public issue for a suspected vulnerability.

Use GitHub's private vulnerability reporting or contact the repository owner through a trusted private channel. Include:

- affected file, API, or feature
- reproduction steps
- expected impact
- affected platforms and package versions when known

## Secret Handling

Never commit credentials, certificates, signing material, private package registry tokens, GitHub tokens, recovery codes, or screenshots containing secrets. If a secret is exposed, revoke it immediately and replace it with a new value.

## Response Standard

Security fixes should be reviewed before merge and include validation notes covering platform and API impact where relevant.
