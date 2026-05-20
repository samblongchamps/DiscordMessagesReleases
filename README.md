# Discord Messages Releases

Public update manifest for the Discord Messages Premiere Pro CEP extension.

The extension checks `updates.json` once per day. When `version` is newer than
the installed extension version, the update button glows and opens the URL
defined here.

## Release Flow

1. Package the CEP extension as a zip, for example `DiscordMessages-1.2.0.zip`.
2. Upload the zip to `releases/` or to a GitHub Release asset.
3. Update `updates.json` with the new version, URLs, date, and notes.
4. Push this repo to its public GitHub repository.

## Manifest Fields

- `version`: latest available extension version.
- `minimumSupportedVersion`: oldest extension version supported by this update feed.
- `releaseDate`: release date in `YYYY-MM-DD` format.
- `downloadUrl`: direct download URL for the packaged extension.
- `releaseUrl`: human-readable release page.
- `notes`: short release notes shown in the extension.
