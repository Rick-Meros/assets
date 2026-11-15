<p align="center">
  <img src=".github/assets/logo.png" alt="Companion Assets logo" height="96">
</p>

<h1 align="center">Companion Assets</h1>

<p align="center">Public icon assets for Companion and Sidekick.</p>

## Files

All three files are 1024 x 1024 PNG images with an alpha channel.

| File | Purpose |
|---|---|
| `sidekick-icon-transparent.png` | Sidekick icon with a transparent background |
| `sidekick-icon.png` | Sidekick icon, the "radiant 4-lobed star emblem with white background" version described in the latest commit message |
| `companion-assistant-icon.png` | Companion assistant icon. At the time of writing it is byte-identical to `sidekick-icon.png`. |

Nothing in the repository documents where these files are consumed, so check before renaming, moving or replacing one, because other projects may link to its public URL.

## Using the assets

Reference a file by its path in this repository, or download it.

## Adding or changing an asset

- Keep filenames lower case with hyphens, matching the existing files.
- Export at 1024 x 1024 PNG. Say in the commit message which icon changed and why.
- Do not add anything private. This repository is public, and everything in it is visible to anyone.
