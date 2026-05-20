# Discord Messages Releases

Public update manifest for the Discord Messages Premiere Pro CEP extension.

The extension checks `updates.json` once per day. When `version` is newer than
the installed extension version, the update button glows and opens the URL
defined here.

## Manifest Fields

- `version`: latest available extension version.
- `minimumSupportedVersion`: oldest extension version supported by this update feed.
- `releaseDate`: release date in `YYYY-MM-DD` format.
- `downloadUrl`: direct download URL for the packaged extension.
- `releaseUrl`: human-readable release page.
- `notes`: short release notes shown in the extension.
