# Change Log

All notable changes to the "Nasal Language (FlightGear)" extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.0.7] - 2023-04-10

### Changed

- Add spaces to GPLHeader snippet for better reading
- Now using props.nas in Class snippet as getprop(); is slower than props.nas getValue();

## [0.0.6] - 2022-11-17

### Changed

- Display name changed from "Nasal-lang" to "Nasal Language (FlightGear)"

### Added

- Additional information to the readme

### Fixed

- Badges of readme not showing, changed to [shields.io](https://shields.io)

## [0.0.5] - 2019-09-04

### Fixed

- Removing True and False keywords as nasal uses 1 and 0 to represent that
- Keywords are now case sensitive to avoid parsing errors such as 'undefined symbol FUNC'

### Added

- Badges to the Readme
- .gitignore file

## [0.0.4] - 2019-08-17

### Fixed

- Fixed snippet typo

## [0.0.3] - 2019-08-11

### Added

- Added class function template snippet

### Fixed

- Class and Func snippets headers

## [0.0.2] - 2019-08-09

### Added

- Missing maketimer variables and methods
- Func and Class snippets
- GPL-2 file header template snippet, type gplheader
- GUI.nas variables and methods syntax highlighting

### Fixed

- Setlistener snippet parameters wrongly set

## [0.0.1] - 2019-08-08

### Added

- LICENSED over GPL-3
- Added basic snippets for loops, conditions, timers
- Added basic Syntax highlighting for Nasal
