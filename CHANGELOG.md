# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

N/A

## [1.4.0] - 2021-01-28

### Added
- Added `declare(strict_types=1);` to PHP templates.
- Added `translate="title"` to XML templates where appropriate.

### Updated
- Fixed inconsistent indentation with some XML templates.

## [1.3.2] - 2020-10-11

### Removed
- Removed parent from being added to submenu id (unneeded) in `magentoMenuXml` template.

## [1.3.1] - 2020-10-11

### Updated
- Simplified attributes within `magentoMenuXml` template.

## [1.3.0] - 2020-10-11

### Added
- Added `magentoAclXml` for acl.xml.

## [1.2.0] - 2020-10-06

### Added
- Added `magentoMenuXml` for menu.xml.

## [1.1.0] - 2020-09-04

### Added
- Added `magentoCspXml` for csp_whitelist.xml.

## [1.0.0] - 2020-03-27

### Added
- Initial release.
