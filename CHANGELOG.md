# Fictium Changelog

## Notes

- Newer changes should be on top.
- Release dates are at GTM-3, Argentina time zone.

## Format for changes

### [Version name] ([YYYY-MM-DD])

[Change!] Summary for the version

#### Changes

[Change!] Add a list of changes

## LOG

### 0.4.1 (2019-12-18)

Allowing to test specific lines.

#### Changes

- Fictium won't crash anymore when running tests for specific lines.

### 0.4.0 (2019-11-28)

Error messages

#### Changes

- Now the gem will check the configuration before running and give some nice error messages.

### 0.3.6 (2019-11-21)

Small fixes

#### Changes

- Fixes cases where parameters are not strings, it converts them into json.

### 0.3.5 (2019-11-20)

Remove require rspec

#### Changes

- Because fictium/rspec is required on rspec environments it is not needed anymore.

### 0.3.4 (2019-11-12)

Add correct action Method

#### Changes

- Use request to get action method

### 0.3.3 (2019-11-12)

Improve path recognition using controller actions.

#### Changes

- Use path parameters instead of formatting path.

### 0.3.2 (2019-11-12)

Use path parameters instead of formatting path.

#### Changes

- Use path parameters instead of formatting path.

### 0.3.1 (2019-11-12)

Added support for rails 5.1

#### Changes

- Add support for older Rails versions.

### 0.3.0 (2019-11-12)

New exporter: Postman.

#### Changes

- Allow to export the documentation as a Postman collection. (Even with examples)
- Added code climate's integration for test coverage.

### 0.2.0 (2019-11-12)

New exporter: API Blueprint.

#### Changes

- Fixed some autocomplete from RSpec.
- Created the new API Blueprint exporter.

### 0.1.0 (2019-11-06)

Initial release, with Swagger exporter and RSpec integration.

#### Changes

  - Add RSpec integration.
  - Add OpenAPI (V3) importer.
  - Add default configurations.
