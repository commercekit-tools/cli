# CommerceKit CLI

This is the official CommerceKit CLI binary distribution repository.

CommerceKit CLI provides SAP Commerce developer tools for terminals, scripts,
and CI pipelines. The CommerceKit CLI source monorepo remains private; this
repository contains public release metadata and compiled distribution assets.

## Downloads

Download the explicitly named release assets from the repository's
[Releases](https://github.com/commercekit-tools/cli/releases) page:

- `commercekit-v<version>-darwin-arm64.tar.gz`
- `commercekit-v<version>-darwin-x64.tar.gz`
- `commercekit-v<version>-linux-arm64.tar.gz`
- `commercekit-v<version>-linux-x64.tar.gz`
- `commercekit-v<version>-windows-arm64.zip`
- `commercekit-v<version>-windows-x64.zip`
- `release-manifest.json`
- `SHA256SUMS`

These named release assets are the supported downloads. GitHub's generated
source archives do not contain the CommerceKit CLI implementation; they contain
only this distribution repository's public metadata.

## Verification

Each release provides `SHA256SUMS` for file-level SHA-256 verification and a
versioned `release-manifest.json` describing the expected targets, filenames,
sizes, checksums, source build identifier, release channel, and signing state.
Verify an archive before extracting or running it. Release notes provide the
commands for the published version.

## Release status

Initial releases are unsigned preview releases:

- macOS binaries are unsigned and are not Apple-notarized.
- Windows binaries are unsigned and may encounter SmartScreen or reputation
  warnings.

The release notes identify these limitations for every affected version. Do
not assume a preview is signed, notarized, stable, or available through a
package manager.

## Documentation and support

- Product and documentation: <https://commercekit.tools>
- Contact: <https://commercekit.tools/contact>
- Security reports: [SECURITY.md](SECURITY.md)

This repository does not contain the private source project. See
[CONTRIBUTING.md](CONTRIBUTING.md) for the public feedback and collaboration
boundary.

## License and distribution terms

Repository metadata is provided under the terms in [LICENSE](LICENSE). Each
CommerceKit CLI release archive also contains its applicable project license
and `THIRD_PARTY_NOTICES` for bundled runtime components and dependencies.
