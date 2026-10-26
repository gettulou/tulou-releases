# tulou releases

Windows builds of tulou: installers, the portable zip, their signatures and checksums, and release notes.

The binaries are free to use; the source is not public.

- **Download:** the newest release is under [Releases](https://github.com/gettulou/tulou-releases/releases/latest).
  Releases marked *Pre-release* are dev builds.
- **Verify:** each release has `SHA256SUMS`, and each installer a minisign signature (`.sig`) that tulou's
  updater checks before installing.
- **Updates:** an installed tulou checks `https://tulou.dev/updates/<channel>/latest.json`; the
  `updater-dev` and `updater-prod` entries are channel pointers, not releases. About in tulou can turn the
  check off.
