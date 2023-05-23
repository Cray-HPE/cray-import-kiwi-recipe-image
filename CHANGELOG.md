# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [4.0.0] - 2023-05-23

### Changed

- Utilize BOS Version 2 (BOS V2) endpoint for session templates. Further, change the variable name from `BOS_SESSION_ENDPOINT` to `BOS_SESSIONTEMPLATES_ENDPOINT`.

## [3.2.0] - 2023-04-06

### Changed

- Reverted github workflows back to Jenkins pipelines.
- Finished conversion to GitVersion; modified build and versioning process to match other CMS repositories.
- Update to cray-product-catalog-update version 1.8.x

### Removed

- Removed references to import-config chart which was removed long ago.
- Removed outdated maintainers information from chart.

## [3.1.0] - 2022-08-02

### Changed

- Update license text to comply with automatic license-check tool.
- CASMCMS-7970 - update dev.cray.com addresses.

## [3.0.2] - 2022-03-04

### Changed

- Use github public ubuntu runner instead of self-hosted on public repos.

## [3.0.1] - 2022-02-17

### Added

- Include additional changes for CASMCMS-7676 (IMS templating) missed during repo conversion

## [3.0.0] - 2022-02-14

### Changed

- Converted repository to just cray-import-kiwi-recipe-image, using GH actions and workflows to build (CASMCMS-7812)

- Converted repository to CSM gitflow development process (CASMCMS-7812)

- Updated GH artifact retention to 90 days for chart

- Update to cray-product-catalog-update version 1.5.2

- Publish location changed due to update to artifactory plugin

### Removed

- Chart no longer builds via Jenkins

## [2.0.0] - 2021-11-29

### Added

- See https://github.com/Cray-HPE/cray-product-install-charts for this release and prior.

[Unreleased]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v4.0.0...HEAD

[4.0.0]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v3.2.0...v4.0.0

[3.2.0]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v3.1.0...v3.2.0

[3.1.0]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v3.0.2...v3.1.0

[3.0.2]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v3.0.1...v3.0.2

[3.0.1]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v3.0.0...v3.0.1

[3.0.0]: https://github.com/Cray-HPE/cray-import-kiwi-recipe-image/compare/v2.0.0...v3.0.0

[2.0.0]: https://github.com/Cray-HPE/cray-product-install-charts/releases
