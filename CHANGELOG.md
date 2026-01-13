# Changelog

## 1.0.2 - 2026-01-13

### Changed

- Updated YAML array format in `settings.yaml`.
    - Added `:id` to all `:forwarded_ports`.
- Updated `Vagrantfile` by adding local variables.
    - Modernized path in the `YAML.load_file()` call.
- Replaced `FORWARDED_PORT_80` variable with `HOST_HTTP_PORT` in 3 files.
    - Updated `provision.sh`, `adminer.conf`, `virtualhost.conf` with new variable name.
- Modified the version section of `provision.sh` for the section title and the Apache version output.
- Modified the system timezone.
- Updated the last section of `README.md`.

## 1.0.1 - 2025-10-13

### Added

- Added `CHANGELOG.md`

### Changed

- Updated `README.md`

### Fixed

- Updated Adminer to version 5+ plugin code and files

## 1.0.0 - 2022-04-29

_First release_
