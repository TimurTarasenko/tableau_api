# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added
- `TableauApi::Resources::Groups` added to support API calls for adding/deleting/updating groups.
- `TableauApi::Resources::Workbook#remove_permissions` added, including support for user and group permissions.
- `TableauApi::Resources::Workbook#add_permissions` supports group permissions.

### Changed
- `TableauApi::Resources::Workbook#permissions` now returns existing permissions instead of adding new
  permissions. New permissions can be added with `TableauApi::Resources::Workbook#add_permissions`.

## [1.0.0] - 2016-06-06
### Added
- Initial Release

[Unreleased]: https://github.com/civisanalytics/tableau_api/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/civisanalytics/tableau_api/tree/v1.0.0
