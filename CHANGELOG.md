# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0] - 2026-04-25

### Fixed
- Final placeholder: `${0}` instead of `$0` or `${0:}`

### Added
- `${0}` placeholder for `enums` (at the end of the line) and a newline placeholder for `conf`

## [1.1.1] - 2026-04-23

### Documentation
- Enhanced README with per-project configuration guide and team collaboration setup

## [1.1.0] - 2026-04-22

### Fixed
- Improved description field extraction from API with proper first sentence detection (handling dots, newlines, and skipping common abbreviations like e.g.)

## [1.0.1] - 2026-04-17

### Change
- Gallery banner color in package.json

## [1.0.0] - 2026-04-09

### Added
- Initial public release
- Full support for **LÖVE 11.5** API
- Coverage: modules, callbacks, functions, constructors, getters/setters, enums
- `conf.lua` configuration snippet
