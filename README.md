# Discord Messages Releases

Public update feed for the Discord Messages Premiere Pro CEP extension.

The extension checks `updates.json` once per day. When `version` is newer than
the installed extension version, the update button glows and opens the release
page defined here.

## Live Feed

- Manifest: https://raw.githubusercontent.com/samblongchamps/DiscordMessagesReleases/main/updates.json
- Releases: https://github.com/samblongchamps/DiscordMessagesReleases/releases

## Manifest Fields

- `version`: latest available extension version.
- `minimumSupportedVersion`: oldest extension version supported by this update feed.
- `releaseDate`: release date in `YYYY-MM-DD` format.
- `downloadUrl`: direct download URL for the packaged extension.
- `releaseUrl`: human-readable release page.
- `notes`: short release notes shown in the extension.

## Publishing

1. Update `updates.json` with the new version, release date, Dropbox download URL, GitHub release URL, and notes.
2. Commit and push the manifest change to `main`.
3. Create a matching GitHub release tag, for example `v0.0.3`.
4. Verify both the GitHub release page and the raw manifest URL.
