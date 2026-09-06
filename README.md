# ORPIN AI IDE — downloads

This repository is the download channel for the ORPIN AI IDE, the desktop IDE
for the ORPIN AI platform. It holds release binaries and release notes only;
the IDE's source is not published here.

## Download

Every release is under **Releases**. Each release lists the platforms it has
a build for and whether that build is signed. The current builds are
developer previews, unsigned:

- **macOS**: right-click the app → Open the first time, or run
  `xattr -dr com.apple.quarantine "/Applications/ORPIN AI IDE.app"`.
- **Windows**: SmartScreen will warn; choose *More info* → *Run anyway*.
- **Linux**: unpack and run `orpin`.

The IDE checks for newer releases itself (Help → Check for Updates…) and
offers a download; it never installs anything on its own.

## Verifying a download

Each release lists the SHA-256 of every file. On macOS or Linux:
`shasum -a 256 <file>`; on Windows: `certutil -hashfile <file> SHA256`.

## Problems

Open an issue here. Include the version from Help → About and your platform.
