# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
- Introduced a roadmap document describing feature implementation order.
- Added a features document under `docs/`.
- Established this changelog.
- Updated the feature list with status markers for each entry.
- Implemented browser-memory check with size warnings for large PDFs.
- Fixed page range detection for per-section extraction.
- Added text extraction output for individual sections.
- Added automatic iteration over all sections with optional ZIP export.
- Fixed PDF.js configuration to load the worker script correctly.

## [0.1.0] - 2025-05-18
### Added
- Initial browser interface (`index.html`) for viewing a PDF outline and extracting sections.
- Basic project README.
