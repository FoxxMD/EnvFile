# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## 2.0.0 - 2017-01-16

### Added

- Integration with IDEA
- Integration with RubyMine
- Support for multiple files

### Changed

- The `.env` parser now strips trailing `"` and `'`
- UI is moved to a separate tab
- API for extension point `envfileParser`
- The way how plugin settings saved into project definition

### Removed

- Extension point `envfileFormat`

## 1.0.1 - 2016-05-09

### Fixed
- UI components overlap with multiple projects opened within same window

### Changed
- Change Log to [Keep a CHANGELOG](http://keepachangelog.com) format


## 1.0.0 - 2015-07-18

### Added
- Added support for .env file format
- Added support for YAML dictionary format
- Added support for JSON dictionary format (handled by YAML parser)
- Initial Release
