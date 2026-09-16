# Chris Yanez

Independent systems and security researcher building defensive analysis tooling, secure software systems, and reproducible technical research infrastructure.

[LinkedIn](https://www.linkedin.com/in/chrisavor/) · [Research portfolio](https://github.com/chrisavor/windows-binary-analysis-research) · [WinBinTriage v0.1.0](https://github.com/chrisavor/windows-binary-analysis-research/releases/tag/v0.1.0)

## Featured project

### [WinBinTriage](https://github.com/chrisavor/windows-binary-analysis-research)

A bounded, static-only Windows PE analysis tool extracted from a larger private defensive-analysis laboratory.

- Performs race-safe, single-handle sample intake under immutable resource ceilings.
- Reports SHA-256 identity, PE structure, mitigations, sections, entropy, overlays, and defensive indicators.
- Emits schema-versioned JSON with constant-time-verifiable report integrity.
- Never executes, loads, injects into, or modifies the selected sample.
- Verified by 22 automated tests and public Windows CI on Python 3.11 and 3.12.

[Source and documentation](https://github.com/chrisavor/windows-binary-analysis-research) · [Latest release](https://github.com/chrisavor/windows-binary-analysis-research/releases/tag/v0.1.0) · [Public CI evidence](https://github.com/chrisavor/windows-binary-analysis-research/actions/runs/35047620401)

## Current areas of work

- Defensive Windows binary analysis and reverse-engineering methodology.
- Secure systems-code review and fail-closed safety boundaries.
- Synthetic laboratory targets for repeatable validation.
- Source-grounded research infrastructure with auditable provenance.
- Production software architecture, testing, and reliability engineering.

## Technical focus

`Python` · `C/C++` · `Windows internals` · `Binary analysis` · `Static analysis` · `Secure software design` · `Testing` · `GitHub Actions`

## Working principles

- Establish authorization and scope before testing.
- Prefer synthetic targets and controlled environments.
- Separate observed evidence from inference.
- Preserve negative results and documented limitations.
- Never publish credentials, private samples, customer data, or actionable bypass material.
