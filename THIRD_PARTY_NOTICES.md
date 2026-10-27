# Third-Party Notices

## ripgrep

The Windows package includes the ripgrep executable.

- Project: https://github.com/BurntSushi/ripgrep
- Version: 15.2.0
- Copyright: Andrew Gallant and ripgrep contributors
- License: MIT License or The Unlicense

The complete license texts are included at:

- `resources/bin/windows-x86_64/LICENSE-MIT`
- `resources/bin/windows-x86_64/UNLICENSE`
- `resources/bin/windows-x86_64/COPYING`

## Electron and Chromium

AWC Browser downloads the Electron runtime, with Chromium and its third-party
components, on first use. Runtime binaries are not included in the VSIX.

- Project: https://github.com/electron/electron
- Electron version: 44.7.2
- Electron license: MIT License
- Chromium project: https://www.chromium.org/

Complete runtime license texts and third-party notices are included in the
downloaded runtime directory under VS Code extension storage:

- `browser-runtime/runtimes/<version>-<platform>-<arch>-<sha256>/LICENSE`
- `browser-runtime/runtimes/<version>-<platform>-<arch>-<sha256>/LICENSES.chromium.html`

## Browser runtime restoration

Runtime restoration uses extract-zip 2.0.1 (BSD-2-Clause) and its dependencies.
The complete license texts are included in `dist/browser-runtime-licenses/`.

- Project: https://github.com/max-mapper/extract-zip
