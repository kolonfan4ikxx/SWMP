# Firefox — SWMP package

Mozilla Firefox for SolverUNIX x86_64.

## Package type

This entry is an **upstream binary package recipe**, not a copy of the Firefox binary. The official Mozilla download endpoint supplies the Linux x86_64 archive.

- Upstream: https://www.mozilla.org/firefox/
- Download: https://download.mozilla.org/?product=firefox-latest&os=linux64&lang=en-US
- License: MPL-2.0
- Install scope: per-user (`~/.local`)

## Installation requirements

The future `solpkg` implementation should:

1. Download the archive over HTTPS.
2. Verify a repository-pinned SHA-256 checksum before installation.
3. Inspect archive paths and reject absolute paths or any path containing traversal components such as `../`.
4. Extract into a staging directory, then install under the user's `~/.local/opt/firefox`.
5. Create a launcher in `~/.local/bin/firefox` and a desktop entry in `~/.local/share/applications/`.
6. Record every installed file as owned by the installing user so that `solpkg dlt firefox` only removes that user's installation.

## Important

The download endpoint selects the latest Firefox build, so this recipe is not yet reproducible. Before treating it as a stable SWMP package, pin a specific Firefox version and publish its verified SHA-256 checksum in the package metadata.

This package has not been tested on SolverUNIX yet.
