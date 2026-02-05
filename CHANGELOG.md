# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Features

- Repository caching with fresh threshold to avoid unnecessary git fetches
- Descriptive finding codes (e.g., `missing-version` instead of `DRIFT002`)
- Graceful handling of unparseable version constraints with warnings
- Redesigned text reporter with table-based output grouped by repository
- Redesigned JSON reporter with structured format
- Redesigned HTML reporter with modern dashboard UI
- Support for GitHub, GitLab, Bitbucket, and Azure DevOps
- Configurable cache settings (TTL, fresh threshold, max size)

### Bug Fixes

- Fixed resource name extraction in reports
- Fixed file path display to show relative paths within repository

## [0.1.0] - Initial Release

### Features

- Terraform/OpenTofu module constraint analysis
- Dependency graph generation (DOT, JSON, Mermaid formats)
- Version constraint conflict detection
- Deprecation tracking for modules and providers
- Multi-repository scanning via VCS APIs
- Policy-based analysis with configurable severities
- Multiple output formats (Text, JSON, HTML)
