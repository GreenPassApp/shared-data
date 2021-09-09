
[![Logo](https://greenpassapp.eu/assets/presskit/logos/GreenPass_Logo.svg)](https://greenpassapp.eu/)
# GreenPass - Shared Data

This repository contains information shared with GreenPass services.

File | Content Description
--- | ---
`current-app-version.json` | This file contains information about the current version of the mobile app. Currently, this file only contains information about the Android app.
`outdated-app-versions.json` | This file contains a list of regular expressions matching outdated mobile app versions. This is useful for older app versions to alert the user that a new update is required for continued reliable validations.
`validation-by-country.json` | This file contains the regulations for the EU countries. We use the [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601 "ISO 8601") standard for durations.
`validationByCountry.json` | This is a mirror of `validation-by-country.json`, since older versions of the mobile app (1.0.0 and 1.0.1) use this filename. A GitHub Actions workflow ensures that this file is always mirrored.

## Feedback

If you have any feedback, please reach out to us at team@greenpassapp.eu

## License

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/GPL-3.0)
