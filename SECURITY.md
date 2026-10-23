# Security

Jigsaw desktop binaries are published with SHA-256 checksums in every release.
Always verify a download before running it.

## Reporting a vulnerability

Please do not open a public issue for security problems. Email
**jinosh05@gmail.com** with:

- the affected version and platform,
- steps to reproduce,
- any relevant logs or screenshots.

You will receive an acknowledgement as soon as possible.

## Release integrity

- Only compiled, obfuscated release binaries are published in this repository.
- Source code and debug symbol maps are not distributed.
- Each release includes `SHA256SUMS.txt` and a machine-readable `latest.json`.
- Build artifacts are produced by a private CI pipeline from the tagged source
  revision and published directly to GitHub Releases.
