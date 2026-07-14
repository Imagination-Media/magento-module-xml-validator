# Changelog for XML Validator by Imagination Media

All notable changes to this extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this extension adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

For more information about the extension, please refer to the
[README](./README.md) document.

## [Unreleased]

## [0.3.0] — 2026-07-14
### Changed
- Added support for Magento 2.4.8 and newer by using `CommandLoader.php`
  instead of the removed `CommandList.php` file
- Updated the README post-installation instructions to distinguish Magento
  2.4.8+ from Magento 2.4.7 and older

## [0.2.1] — 2022-11-17
### Fixed
- Warnings for missing Magento schema declarations are no longer returned as
errors

## [0.2.0] — 2022-11-07
### Changed
- Refactored loading of dependencies to allow the command to be run with only
  the Magento files installed and no database (useful in CI/CD environments)

## [0.1.0] — 2022-10-31
### Added
- Created initial rough MVP of tool with support for CLI and GitHub Actions

[Unreleased]: https://github.com/Imagination-Media/magento-module-xml-validator/compare/0.3.0...develop
[0.1.0]: https://github.com/Imagination-Media/magento-module-xml-validator/releases/tag/0.1.0
[0.2.0]: https://github.com/Imagination-Media/magento-module-xml-validator/releases/tag/0.2.0
[0.2.1]: https://github.com/Imagination-Media/magento-module-xml-validator/releases/tag/0.2.1
[0.3.0]: https://github.com/Imagination-Media/magento-module-xml-validator/releases/tag/0.3.0
