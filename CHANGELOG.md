# Changelog

## 1.7.1 (2022-05-06)

### Changes

* The generated platform changes RSS feed now uses the configured title.

## 1.7.0 (2022-05-06)

### ⚠️ Breaking Changes

* Changed how the theme accent color gets configured with the `theme` configuration property (`light` and `dark` mode variants must now be set).

### New Features

* Support for Crisp Status (aside from Vigil).

## 1.6.4 (2022-02-13)

### Changes

* Moved the search engine opening shortcut from ⌘F to ⌘K (after gathering user feedback).

## 1.6.3 (2022-01-12)

### Bug Fixes

* Fixed an issue with non-highlighted code blocks in Dark Mode, where code text would appear black-on-black.
* Fixed an issue with inline code blocks in Dark Mode, where selected text would appear white-on-white.

## 1.6.2 (2022-01-11)

### Changes

* Improved management of CSS colors.

## 1.6.1 (2022-01-11)

### Changes

* Improved Dark Mode colors.
* Moved logos to embedded images (this prevents visual glitches when loading docs).

## 1.6.0 (2022-01-10)

### New Features

* Implemented Dark Mode.
* Added the ability to configure the theme accent color with the `theme` configuration property.

## 1.5.1 (2022-01-07)

### Changes

* Improved the performance of watching for changes in `data/` while using `chappe serve` or `chappe watch`.

### Bug Fixes

* Fixed Gulp meta-events showing in the Chappe CLI output when using `--verbose` (they are now hidden).

## 1.5.0 (2022-01-06)

### New Features

* The Chappe CLI now embeds a preview server, used to ease with writing and previewing docs (via `chappe serve`).

### Changes

* Improved logging in the Chappe CLI.

### Bug Fixes

* Fixed the abrupt stopping of the Chappe CLI whenever a resource build failed while using `chappe watch`.

## 1.4.1 (2022-01-06)

### Changes

* Refactored the README to add the Chappe logo.

## 1.4.0 (2022-01-05)

### Changes

* Moved the project to a dedicated GitHub organization: [Crisp OSS](https://github.com/crisp-oss).

## 1.3.2 (2022-01-05)

### Changes

* Moved the Chappe CLI from ES5 to ES6.

## 1.3.1 (2022-01-05)

### Changes

* Refactored Chappe CLI terminal outputs.
* Improved the `acme-docs` example.

## 1.3.0 (2022-01-05)

### Changes

* Reworked the lint pipeline to reduce the number of dependencies.

### Bug Fixes

* Fixed an issue where 404 and private pages appeared in the sitemap.
* Fixed the configuration path for the SASS linter, which could not read its configuration file in some cases.

## 1.2.1 (2022-01-05)

### Bug Fixes

* Fixed the normalization of paths passed to the Chappe CLI via `--config`.

## 1.2.0 (2022-01-05)

### New Features

* The Chappe CLI `--config` argument now accepts multiple configuration files (comma-separated, merged together).
* Added the ability to override certain Chappe internal values with the `overrides` configuration property.

### Bug Fixes

* Fixed an issue in Chappe CLI, where a build failure could cause the process to hang indefinitely.

## 1.1.2 (2022-01-04)

### Bug Fixes

* Fixed the NPMJS distribution package, that was missing some more hidden files (such as `.babelrc`).

## 1.1.1 (2022-01-04)

### Bug Fixes

* Fixed the NPMJS distribution package, that was missing the `.banner` file.

## 1.1.0 (2022-01-04)

### Changes

* Moved the build pipeline to Gulp 4.
* Improved the Chappe CLI with terminal spinners.

## 1.0.3 (2022-01-04)

### Changes

* Now showing a Chappe logo when calling the Chappe CLI.
* Better temporary files management.

### Bug Fixes

* All internal paths are now absolute (this fixes some build environments).

## 1.0.2 (2022-01-03)

### Bug Fixes

* Fix dependencies for published `chappe` package.

## 1.0.1 (2022-01-03)

### Bug Fixes

* Fix the path of Chappe CLI.

## 1.0.0 (2022-01-03)

### New Features

* Initial release.
