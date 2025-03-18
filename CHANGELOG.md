# CHANGELOG

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased] 

## [1.0.0] - 2025-3-18

### Added

- All commands according to data sheet. This introduces breaking changes!

### Breaking changes

- Class `SensirionI2CSfa3x` has been renamed to `SensirionI2cSfa3x` (note the casing of `I2c`!)
- `begin()` now requires you to also pass the I2C address
- `readMeasuredValues()` now already applies appropriate scaling to the values
    - Use `readMeasuredValuesAsIntegers()` if you want the values without scaling applied (same as in old version)

## [0.1.0] - 2021-2-5

- Initial Release

[Unreleased]: https://github.com/Sensirion/arduino-i2c-sfa3x/compare/1.0.0...HEAD
[1.0.0]: https://github.com/Sensirion/arduino-i2c-sfa3x/compare/0.1.0...1.0.0
[0.1.0]: https://github.com/Sensirion/arduino-i2c-sfa3x/releases/tag/0.1.0