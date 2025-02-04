# Tigera Operator Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!-- ## [UNRELEASED]
### Added
### Changed
### Deprecated
### Removed -->

## [v1.3.4] - 2021-10-20

### Changed

- Update _Tigera Operator_ image to [v1.22.4](https://github.com/tigera/operator/releases/tag/v1.22.4).

## [v1.3.3] - 2021-10-20

### Changed

- Update _Tigera Operator_ image to [v1.22.3](https://github.com/tigera/operator/releases/tag/v1.22.3).

## [v1.3.2] - 2021-10-13

### Changed

- Update _Tigera Operator_ image to [v1.22.2](https://github.com/tigera/operator/releases/tag/v1.22.2).

## [v1.3.1] - 2021-10-07

### Changed

- Update _Tigera Operator_ image to [v1.22.1](https://github.com/tigera/operator/releases/tag/v1.22.1).

## [v1.3.0] - 2021-10-04

### Added

- Remaining _Tigera Operator_ CRDs.

### Changed

- Update _Tigera Operator_ image to [v1.22.0](https://github.com/tigera/operator/releases/tag/v1.22.0).

## [v1.2.3] - 2021-10-04

### Changed

- Update _Tigera Operator_ image to [v1.21.3](https://github.com/tigera/operator/releases/tag/v1.21.3).

## [v1.2.2] - 2021-10-04

### Changed

- Update _Tigera Operator_ image to [v1.21.2](https://github.com/tigera/operator/releases/tag/v1.21.2).

## [v1.2.1] - 2021-09-02

### Changed

- Use metadata to get operator namespace in env.

## [v1.2.0] - 2021-09-02

### Added

- Locking secret `tigera-operator-lock` in the `kube-system` namespace to stop the chart being deployed more than once.
- Support for the `installation.spec` to be provided as a templatable string as an alternative to structured configuration.

## [v1.1.2] - 2021-09-01

### Changed

- Fix cluster role.

## [v1.1.1] - 2021-09-01

### Changed

- Update _Tigera Operator_ image to [v1.21.1](https://github.com/tigera/operator/releases/tag/v1.21.1).

## [v1.1.0] - 2021-08-24

### Changed

- Updated _Tigera Operator_ image to [v1.21.0](https://github.com/tigera/operator/releases/tag/v1.21.0).
- Enable customisation of deployment `hostNetwork` & `dnsPolicy` for users who aren't using Calico as the CNI.

## [v1.0.5] - 2021-08-11

### Changed

- Improve documentation.

## [v1.0.4] - 2021-08-05

### Changed

- Fixed _Tigera Operator_ namespace support.

## [v1.0.3] - 2021-08-04

### Removed

- Removed `tigeraWatchNamespace` value as it would be ignored.

## [v1.0.2] - 2021-08-03

### Changed

- Use default custom resource name.

## [v1.0.1] - 2021-08-03

### Added

- New `env` & `envFrom` values to set the environment.
- Correct metadata to installation resource.

### Changed

- Fix watch namespace to watch all namespaces by default.

## [v1.0.0] - 2021-08-03

### Added

- Initial release based on _Tigera Operator_ [v1.20.0](https://github.com/tigera/operator/releases/tag/v1.20.0).
