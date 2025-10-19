# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.10.0] - 2025-10-19

### Changed
- Updated Notion API version from 2022-06-28 to 2025-09-03 to support the latest API features including multi-source databases
- Updated all documentation and configuration examples to reflect the new API version
- Updated test suite to use the new API version

### Notes
- This version upgrade ensures compatibility with Notion's latest API features, including first-class support for multi-source databases
- The OpenAPI-to-MCP proxy architecture automatically adapts to new API parameters and endpoints as they're added to Notion's OpenAPI specification
- Users should ensure their Notion integrations are configured to work with API version 2025-09-03

## [1.9.0] - Previous Release

See git history for previous releases.
