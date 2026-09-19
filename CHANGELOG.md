# CHANGELOG

All notable changes to the **psudoFont Liga Mono** font will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Non-Breaking Versioning](https://github.com/NonBreakVer/NonBreakVer).

## [2.2.0] - 2026-01-31

### Added

- `sub uni01CE by uni01CE.alt01;` missing line to font feature `cv01`
- alternative character `k` and `uni0137`
- alternative character `v`
- alternative character `w`, `wacute`, `wcircumflex`, `wdieresis` and `wgrave`
- alternative character `x`
- font feature `cv20`: alternative `k` for `italic` and `bold italic`
- font feature `cv21`: alternative `v` for `italic` and `bold italic`
- font feature `cv22`: alternative `w` for `italic` and `bold italic`
- font feature `cv23`: alternative `x` for `italic` and `bold italic`

### Changed

- character `a` and alternative `a` (and all their variants) for `italic` and `bold italic`
- character `k` for `italic` and `bold italic`
- character `x` for `italic` and `bold italic`

### Fixed

- Unicode Character `¡` (U+00A1) positioning

### Removed

- font feature `ss16`
- font feature `ss17`

## [2.1.1] - 2025-10-04

### Fixed

- `ї` (U+0457) in both `regular` and `bold`

## [2.1.0] - 2025-10-04

### Added

- `"editor.fontLigatures": "'ss16'"`: allows users to select alternative letter "a" for both `regular` and `bold`
- `"editor.fontLigatures": "'ss17'"`: allows users to select alternative letter "a" for both `italic` and `bold italic`

### Changed

- minor change for "@" for `regular` and `italic`

### Fixed

- size and alignment for "G" `regular`
- size for "¥" and "₩" `bold`

## [2.0.0] - 2025-10-01

### (new) psudoFont Liga Mono V2

This is a new font, a lot of glyphs were redesigned, some resemble `Menlo/Meslo`, some `IBM Plex Mono/Lilex`, and some others are unique to `psudoFont Liga Mono`. The changes and adjustments vary from small details to entire characters but always keeping the core identity within the font family.

## [1.0.0] - 2025-08-08

### Initial Release

Characteristics of the **psudoFont Liga Mono**:

- Regular: Liga Meslo LG M DZ Regular
- Italic: Lilex Italic
- Bold: Liga Meslo LG M DZ Bold
- Bold Italic: Liga Meslo LG M DZ Bold Italic
