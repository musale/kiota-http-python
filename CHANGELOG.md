# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.6.0] - 2023-09-01

### Added

- Added support for continuous access evaluation.

### Changed

## [0.5.0] - 2023-07-27

### Added

- Added a translator method to change a `RequestInformation` object into a HTTPX client request object.
- Enabled backing store support

### Changed

## [0.4.4] - 2023-05-31

### Added

- Added a url replace handler for replacing url segments.

### Changed

## [0.4.3] - 2023-05-16

### Added

### Changed

- Fixes bug in getting content from redirected request.

## [0.4.2] - 2023-05-02

### Added

### Changed

- Includes Response headers in APIException for failed requests.

## [0.4.1] - 2023-03-29

### Added

### Changed

- Fixed bug with mapping when deserializing primitive response types.

## [0.4.0] - 2023-02-06

### Added

- Added the HTTP response status code on APIError class.
### Changed

- Fixed bug with middleware not respecting request options.

## [0.3.0] - 2023-01-20

### Changed

- Enabled configuring of middleware during client creation by passing custom options in call to create with default middleware. [#56](https://github.com/microsoft/kiota-http-python/issues/56)

## [0.2.4] - 2023-01-17

### Changed

- Changes the ResponeHandler parameter in RequestAdapter to be a RequestOption