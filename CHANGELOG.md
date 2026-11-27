# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0] - 27 November 2026
### Added
- Initial release: a frontend route `yireo_empty/index/index` that renders a page using the empty layout

### Fixed
- Empty page is no longer indexed by search engines (adds NOINDEX,NOFOLLOW robots meta)
- Added the missing dependency on Magento_Store
- Require magento/framework 103.0.7 (Magento 2.4.7) or newer
