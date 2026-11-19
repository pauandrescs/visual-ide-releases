# Visual IDE — releases

Published versions of **Visual IDE**, the visual builder for native Android apps by ARK PLATFORMS.

This repository holds only what is published: each release has its notes and, when they are
available, the installers. The source code is not here.

## How Visual IDE uses this repository

When it starts, Visual IDE asks GitHub for the latest release listed here and compares its version
with its own. If a newer one exists it shows an **Update** button; pressing it opens the page of that
release in your browser.

- The request carries no account, token or identifier, and nothing about your projects.
- Visual IDE downloads and installs nothing by itself. You choose whether to get the new version.
- The check can be turned off in **Settings › Editor › Look for updates**, and run by hand from
  **Help › Check for Updates**.

## Versions

Releases are tagged `v` followed by the version number, for example `v0.2.0`.
Drafts and pre-releases are not offered as updates.

The newest version is always at
https://github.com/pauandrescs/visual-ide-releases/releases/latest

Packages are not signed with a certificate yet: macOS and Windows warn before opening them. Each
release lists the SHA-256 checksum of its files in `SHA256SUMS.txt`.
