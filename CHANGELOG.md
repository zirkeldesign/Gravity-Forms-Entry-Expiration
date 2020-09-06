# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [2.1] - 2020-08-07
- Added capabilities.
- Added support for Gravity Forms 2.5.
- Updated installation instructions.
- Fixed fatal error during 2.0 upgrade process.
- Fixed PHP notices.
  - Fixed search criteria not correctly preparing in certain scenarios.
  - Fixed search criteria not correctly preparing the search end date.

## [2.0]
- Added additional logging
- Added expiration time and recurrence at the form level.
- Added filter for setting entry expiration time for each form
- Adjusted entry older than date to not be relative to midnight
- Changed plugin loading method.
- Rewrote expiration procedure to be more efficient.

## [1.2]
- Fixed update routine to not automatically enable forms for processing if running a fresh install
- Changed expiration time setting to allow choosing between hours, days, weeks and months

## [1.1]
- Switched forms from being able to be excluded to having to include them for processing
- Deletion cron now runs hourly instead of daily
- Cron now only deletes 1000 entries at a time to prevent long execution times
- Added filters for: payment status, number of entries to be processed at a time

## [1.0]

- Initial release