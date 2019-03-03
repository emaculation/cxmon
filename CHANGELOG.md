# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/) and this project adheres to [Semantic Versioning](https://semver.org/).

## [Unreleased]
### Added

### Changed
- Change Log into Markdown format

### Deprecated

### Removed

### Fixed

### Security


# Pre-KeepAChangelog releases

## [v3.2.0] (V3.2) - (date unknown)
### Added
- added `AltiVec` instructions to PPC disassembler

### Fixed
- 64-bit fixes to 680x0 disassembler
- fixes to Z80 disassembler (`hl->ix/iy` and relative jumps)

## [v3.1.0] (V3.1) - (date unknown)
### Changed
- make `LowMem` globals as predefined variables
- enable x86-64 disassembler with `d8664` command

### Removed
- removed input line length restrictions

### Fixed
- fix 64-bit support

## [v3.0.0] (V3.0) - (date unknown)
### Added
- added symbolic display of MacOS low memory globals to PPC disassembler
- extended 8080 disassembler to Z80

### Changed
- replaced 680x0 and 80x86 disassemblers with the ones from GNU binutils
- MacOS features in PPC disassembler are controlled by `-m` argument
- real memory mode is entered by `-r` argument
- name changed from `mon` to `cxmon`

## [v2.2.0] (V2.2) - (date unknown)
### Added
- added binary `dump (b)` command

### Changed
- switched to `autoconf` and `automake`
- commands made modular

### Fixed
- fixed some minor bugs in the PPC disassembler

## [v2.1.0] (V2.1) - (date unknown)
### Added
- compiled for BeOS R4
- implemented 8080 disassembler
- included Unix makefile

### Changed
- opens Terminal window when started from Tracker

## [v2.0.0] (V2.0) - (date unknown)
### Changed
- unified PPC and x86 release

## [v1.5.0] (V1.5) - (date unknown)
### Changed
- non-interactive mode, real mode

## [v1.4.0] (V1.4) - (date unknown)
### Added
- implemented 6502 and 680x0 disassemblers

## [v1.3.0] (V1.3) - (date unknown)
### Changed
- now uses `libreadline`
- disassembler: prints SPR names instead of numbers

### Fixed
- fixed bugs

## [v1.0.0] (V1.0) - (date unknown)
### Added
- initial release
