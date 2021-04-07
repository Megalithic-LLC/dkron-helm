# Dkron Helm Chart Changelog

## [Unreleased]
### Added
- [#1](https://github.com/Megalithic-LLC/dkron-helm/issues/1) Bundle `jq` so that automation works with standard Dkron and Dkron Pro images

### Changed
- [#5](https://github.com/Megalithic-LLC/dkron-helm/issues/5) Replace use of custom `--kubernetes` flag that requires a customized build with the standard `--raft-reconnect-timeout` flag

### Fixed
- [#3](https://github.com/Megalithic-LLC/dkron-helm/issues/3) Automation references a non-existent "dkron-server" service account
