# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.2] - 2020-03-22
### Changed
- Updated dependencies to latest NormForm (with Twig 3.0 support). This is a non-breaking, backwards-compatible change.
- Updated tests to work with PHPUnit 9.0.
- Updated normalize.css from 8.0.0 to 8.0.1.
- Updated Google Fonts import with font swap
- Updated template version numbers.

### Fixed
- Small CSS formatting fixes.

## [1.1.1] - 2018-10-12
### Fixed
- Forced LF line breaks on checkout to avoid unpredictable behavior.

## [1.1.0] - 2018-05-14
### Added
- Unit tests for NormFormDemo in folder ``/tests``.
- Empty constructor in NormFormDemo as a place for property initializations.

### Changed
- PSR-4 autoloader structure in composer.json generalized for more flexibility.
- Update normalize.css from 4.0.0 to 8.0.0.

### Fixed
- Typo in README.md: [1: Update README.md](https://github.com/Digital-Media/normform-skeleton/pull/1).
- Updated .gitignore to include directory css/vendor (for normalize.css)

## [1.0.0] - 2018-04-12
### Added
- Example files (concrete class, template, index file, CSS).
- Simplified example (template and index file).
- composer.json and composer.lock to declare project information and dependencies.
- PHP version 7.1 requirement.
- Project follows [Semantic Versioning](http://semver.org/spec/v2.0.0.html).
- Directory structure (src, docs) ready for [Composer](https://getcomposer.org/).
- API Documentation generated using [Sami](https://github.com/FriendsOfPHP/Sami). 
- Changelog (yes, this one) based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/).

[Unreleased]: https://github.com/Digital-Media/normform/compare/v1.1.2...HEAD
[1.1.2]: https://github.com/Digital-Media/normform-skeleton/compare/v1.1.1...v1.1.2
[1.1.1]: https://github.com/Digital-Media/normform-skeleton/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/Digital-Media/normform-skeleton/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/Digital-Media/normform-skeleton/releases/tag/v1.0.0
