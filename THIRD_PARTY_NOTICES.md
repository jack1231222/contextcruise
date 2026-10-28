# Third-party notices

ContextCruise includes third-party components whose own licenses remain in force. Their license texts are bundled under `Contents/Resources/Runtime/licenses/`; the embedded Python distribution also retains its applicable notices. The ContextCruise free-use license does not override these licenses.

| Component | Version / source | License location in the app |
|---|---|---|
| Sparkle | 2.10.1, sparkle-project/Sparkle | Runtime/licenses/Sparkle/LICENSE |
| CPython | 3.12.13 | Runtime/licenses/Python/LICENSE.txt |
| python-build-standalone | 20260623 matching distribution | Runtime/licenses/python-build-standalone-20260623/ |
| Zstandard | 1.5.7 | Runtime/licenses/zstd-1.5.7_1/ |

Python's compiled dependencies have separate notices retained with the exact distribution metadata, including OpenSSL and compression/database libraries. The packaged notices, rather than this abbreviated table, govern each component.

The current matching-runtime inventory reports no missing license files. Final redistribution review and final-package verification remain release requirements. This file does not claim that unpublished candidates have completed release acceptance.

The Zstandard executable is built for macOS 13 and links only the system runtime. Optional LZ4/XZ command-line format support is not included. Python retains its own compression-library notices.
