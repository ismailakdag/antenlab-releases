# antenlab releases

Downloads for **antenlab**: openEMS antenna and RF structure simulation with a 3D viewer, results,
technical drawings and CST export. There are desktop apps for Windows and macOS, and a browser
demo at <https://antenlab.akdag.dev/app/>.

This repository holds only release files: desktop installers and the runtime components the
desktop app downloads on first start. It contains no source code.

## Runtime components

The desktop app installs its own runtime per user: Python, the Python packages and openEMS. On
Windows it uses the official openEMS build from
[thliebig/openEMS-Project](https://github.com/thliebig/openEMS-Project/releases). There is no
official openEMS build for macOS, so releases named `openems-macos-arm64-*` provide one, built
from the unmodified openEMS sources. Every download is pinned by SHA-256 inside the app.

## Licenses

openEMS is GPL-3.0-or-later, and CSXCAD and fparser are LGPL-3.0-or-later. Each pack includes the
license texts and a `NOTICE.md`. The notice lists every component with its version or commit and
the location of its corresponding source. To request the complete corresponding source, open an
issue in this repository.
