# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.1] - 2019-01-22

### Changed

- Update `charts.js` and `embed.chart.frame.js` to use Wazimap releases features including showing release information on all charts
- Update `settings_js.html` to include `SITE_TAGLINE` & `SITE-DESCRIPTION`, used to provide extra application information on about view of all embedded charts
- Ensured that `dist` metadata are initialized in JavaScript before being accessed to avoid `TypeError` on accessing `undefined` objects

## [0.1.0] - 2019-01-14

### Added

- Improve HURUmap to use data sets & releases
- Improve Docker support
- Decouple `hurumap.dashboard`
- Added new Wazimap logo for dark backgrounds
- Added multiple chart qualifiers support

### Changed

- Hide Empty sections on the profile page
- Rename `wazi-logo` to `wazi-logo-white`
- Replace sourceAFRICA with openAFRICA
