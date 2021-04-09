# Dkron Helm Chart Changelog

## [Unreleased]
### Added
- [#19](https://github.com/Megalithic-LLC/dkron-helm/issues/19) Parameterize initial number of workers

### Changed
- [#14](https://github.com/Megalithic-LLC/dkron-helm/issues/14) Lint merge requests

## [0.1.0] - 2021-04-08
### Added
- [#10](https://github.com/Megalithic-LLC/dkron-helm/issues/10) Support installation into a custom namespace
- [#8](https://github.com/Megalithic-LLC/dkron-helm/issues/8) Support Dkron Pro through configurability of image and pull secrets
- [#1](https://github.com/Megalithic-LLC/dkron-helm/issues/1) Bundle `jq` so that automation works with standard Dkron and Dkron Pro images

### Changed
- [#7](https://github.com/Megalithic-LLC/dkron-helm/issues/7) Replace env var based configuration with a Helm values file
- [#5](https://github.com/Megalithic-LLC/dkron-helm/issues/5) Replace use of custom `--kubernetes` flag that requires a customized build with the standard `--raft-reconnect-timeout` flag

### Fixed
- [#3](https://github.com/Megalithic-LLC/dkron-helm/issues/3) Automation references a non-existent "dkron-server" service account
