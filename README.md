# Ground Control releases (testing)

Signed release builds of Ground Control, used to test how installs find and
verify new releases. Not yet for general use.

Each release will carry the binaries, `SHA256SUMS` and a signed manifest
(`release.json`). Installs check the manifest's signature against the
release key built into them, and every file's hash against the manifest,
before they use anything from here.
