# Change Log

All notable changes to this project will be documented in this file. This
project adheres to [Semantic Versioning](http://semver.org).

## [Unreleased (`master`)][unreleased]

### Changed

- Layout properties and values now use logical dimensions instead of physical
  dimensions, for example `width` is now `inline-size` and `height` is now
  `block-size`. The following classes were updated to match the new syntax:

    - `tbds-text-align-left` is now `tbds-text-align-start`
    - `tbds-text-align-right` is now `tbds-text-align-end`
    - `tbds-margin-top-*` is now `tbds-margin-block-start-*`
    - `tbds-margin-right-*` is now `tbds-margin-inline-end-*`
    - `tbds-margin-bottom-*` is now `tbds-margin-block-end-*`
    - `tbds-margin-left-*` is now `tbds-margin-inline-start-*`
    - `tbds-padding-top-*` is now `tbds-padding-block-start-*`
    - `tbds-padding-right-*` is now `tbds-padding-inline-end-*`
    - `tbds-padding-bottom-*` is now `tbds-padding-block-end-*`
    - `tbds-padding-left-*` is now `tbds-padding-inline-start-*`
    - `tbds-button__icon--text-to-left` is now `tbds-button__icon--gap-start`
    - `tbds-button__icon--text-to-right` is now `tbds-button__icon--gap-end`
    - `tbds-media--vertical-center` is now `tbds-media tbds-media--block-center`
    - `tbds-app-frame__body--vertical-middle` is now `tbds-app-frame__body--block-center`

[unreleased]: https://github.com/thoughtbot/design-system/compare/v0.2.0...HEAD

## [0.2.0] - 2019-05-10

### Added

- Global variables for styling focus outlines.
- `tbds-inline-stack` component.
- The block stack component now has a modifier to add a border between each
  item: `tbds-block-stack--bordered`.
- Added `tbds-icon` component for simple icons
- Added `breakpoints` to settings module which provides a few basic media
  queries

### Changed

- `$tbds-blue` is now `$tbds-brand-blue`, and its value changed from `#1568c1`
  to `#0b758c`.
- `tbds-stack` is now `tbds-block-stack`

### Removed

- `tbds-form__row` has been removed. Use the Stack component instead to achieve
  the same layout.

[0.2.0]: https://github.com/thoughtbot/design-system/compare/v0.1.0...v0.2.0

## [0.1.0] - 2019-04-19

### Changed

- Deprecated individual component packages (e.g. `@thoughtbot/tbds-button`)
  in favor of one primary package (`@thoughtbot/design-system`).

[0.1.0]: https://github.com/thoughtbot/design-system/releases/tag/v0.1.0
