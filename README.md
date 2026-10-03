# GisTvm Privacy Policy

Public privacy documentation for **GisTvm**, the GIS iOS application (iPhone / iPad).

Published with GitHub Pages:

- Privacy Policy: https://gis1948.github.io/gistvm-privacy-policy/
- Account & Data Deletion: https://gis1948.github.io/gistvm-privacy-policy/delete-account.html

These URLs are configured in the app via the `GISPrivacyPolicyURL` Info.plist key
and are also used for App Store Connect → App Privacy → Privacy Policy URL.

## Content

`index.html` and `delete-account.html` describe the app's actual data behaviour:
guest mode (nothing sent), device-local storage, Keychain material, what is sent
to the Gis sync service and how it is encrypted, retention, and exactly what is
removed on a confirmed in-app account deletion versus what is deliberately kept
as device-level state.

## Editing

Edit the HTML directly and push to `main`; GitHub Pages rebuilds automatically.
Keep the "Last updated" date in sync with any substantive change.