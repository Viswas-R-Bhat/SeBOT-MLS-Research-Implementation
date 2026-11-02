# Contributing

Thank you for improving this research implementation. Contributions should make the project more reproducible, testable, documented, or useful for responsible bot-detection research.

## Before you start

- Search existing issues and pull requests before opening a new one.
- Open an issue first for substantial features, architectural changes, or benchmark claims.
- Do not add MGTAB data, trained checkpoints, credentials, personal data, or material you are not permitted to redistribute.
- Preserve all upstream notices and licenses under `vendor/` and `src/sebot_mls/legacy/`.

## Development workflow

1. Create a focused branch from `main`.
2. Install the supported environment described in the README.
3. Run `python -m pytest -q` before submitting a pull request.
4. Explain the motivation, tests performed, and any reproducibility or performance impact in the pull request.

## Research claims

Do not state that this project reproduces a paper exactly unless the relevant assumptions and measurements demonstrate that result. Report the dataset, split, configuration, seed, hardware, and evaluation protocol for new benchmark results. Distinguish upstream methods from implementation additions.

## Pull requests

Keep each pull request small and reviewable. By contributing, you agree that your contribution is licensed under the repository's Apache License 2.0.
