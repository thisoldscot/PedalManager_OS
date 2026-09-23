# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Removed (2026-09-18) — the leftover PyInstaller build recipe

`PedalManager_OS.spec` deleted. Every application in the portfolio is built by
**Project Builder** (`01_Projects/Project_Builder`), which has been the
one build tool since 2026-08-16; a spec file sitting beside the app is a
second recipe that nobody keeps in step, and the README said it was the
build. Project Builder autodetects this project's profile — checked
before deleting, not assumed.


### Added
### Changed
### Fixed

## [1.0.0] - 2026-06-15

### Added
- Initial release. Consolidated from the previous `Pedal_Manager` and `fabOS`
  repositories (the same application) into a single repository.
