# Changelog
All notable changes to this project will be documented in this file.

## [3.0.1] - 12-21-2018

### Changed
- Removed VendorConsent class that was deprecated since version 2.0.1
- Better handle index out of bounds conditions with corrupt consent strings

## [2.0.2] - 06-19-2018

### Changed
- Add a new API fromByteArray() to avoid the base64 decoding. Thanks to **hydrogen2**

## [2.0.1] - 06-13-2018

### Changed
- Optimize isPurposeAllowed() to just check the bit instead of creating unnecessary Set. Thanks to **hydrogen2**

## [2.0.0] - 06-07-2018

### Changed
- Refactored code to separate vendor consent string decoding, encoding and representation concerns
- Deprecated VendorConsent class
- Setup Maven publishing
- Updated documentation