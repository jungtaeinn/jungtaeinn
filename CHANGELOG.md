# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2026-02-01

### Added
- Added `.changeset` configuration for version management
- Added `package.json` with changeset scripts
- Added `.gitignore` file with `.idea/` and common exclusions
- Added CHANGELOG.md for tracking project changes

### Fixed
- Fixed GitHub stats images not hiding properly on error
  - Improved `onerror` handlers to completely hide failed image sections
  - Added section IDs for better error handling
- Fixed GitHub Actions workflow parameter duplication bug
  - Removed `cache_seconds=0` parameter, using timestamp only
  - Improved regex patterns to prevent parameter accumulation
- Fixed Contribution Graph display issues
  - Added `hide_title=true` parameter for better rendering

### Changed
- Optimized GitHub stats image URLs
  - Removed unnecessary `cache_seconds` parameter
  - Simplified URL structure for better caching

## [1.0.0] - 2026-02-01

### Added
- Initial GitHub profile README setup
- GitHub Stats integration (github-readme-stats)
- Top Languages display
- GitHub Streak stats
- GitHub Trophies display
- Contribution Activity Graph
- Tech Stack section with badges
- Social media links
- Profile view counter
- GitHub Actions workflow for auto-updating stats cache

### Changed
- Redesigned README with enhanced GitHub profile stats
- Updated GitHub profile README structure

### Fixed
- Fixed GitHub Stats API errors by removing `cache_seconds` parameter
- Fixed Tech Stack badge display errors
- Fixed profile image border-radius styling
