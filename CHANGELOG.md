# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.

## 2.6.0 - TBD

### Added

- [#8](https://github.com/zendframework/zend-i18n/pull/8) adds support for
  Vietnamese postal codes.
- [#18](https://github.com/zendframework/zend-i118n/pull/18) adds support for
  `NumberFormatter` text attributes to the `NumberFormat` view helper.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [#12](https://github.com/zendframework/zend-i18n/pull/12),
  [#21](https://github.com/zendframework/zend-i18n/pull/21), and
  [#22](https://github.com/zendframework/zend-i18n/pull/22) update the
  component to be forwards compatible with the v3 versions of zend-stdlib,
  zend-servicemanager, and zend-eventmanager.
- [#8](https://github.com/zendframework/zend-i18n/pull/8) updates the regex for
  the Mauritius postal code to follow the currently adopted format.
- [#13](https://github.com/zendframework/zend-i113n/pull/13) updates the regex for
  Serbian postal codes to only accept 5 digits.