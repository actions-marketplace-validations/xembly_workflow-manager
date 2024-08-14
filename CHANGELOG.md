# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2024-08-14

### Deprecated

- Cancel functionality should not be used. Use [GitHub's concurrency feature](https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/using-concurrency) to cancel any in-progress workflows.

### Security

- Updated project dependencies.
- Updated to run on NodeJS v20.

## [1.0.4] - 2021-03-25

### Added

- Created clean and cancel methods for GitHub workflows.
- Initial release.
