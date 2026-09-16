# Third-Party Notices

Velvet Wire Studio includes third-party software used for its Electron desktop shell, React interface, animation, image export, and managed local video renderer. The generated `THIRD-PARTY-LICENSES.md` records the locked production graph and reproduces the Remotion 4.0.507 custom-license text and applicable MIT notice. Package-specific license and notice files are also retained under the installed application's `resources/app.asar.unpacked/node_modules` directory.

Velvet Wire Studio does not claim ownership of third-party software, trademarks, reference material, or user-imported media. Software-license status is separate from application-owned media provenance and from the user's responsibility for imported media.

## Remotion 4.0.507

The distributed Windows application includes 16 Remotion-related packages at version 4.0.507. Eight are identified as MIT packages and eight are governed by the custom Remotion License. The complete custom-license text and the applicable MIT copyright and permission notice are reproduced in `THIRD-PARTY-LICENSES.md`.

- License information: <https://www.remotion.pro/license>
- Source release: <https://github.com/remotion-dev/remotion/releases/tag/v4.0.507>

This public notice records the distributed software and applicable license material.

## Mozilla Public License 2.0 components

The following unmodified package releases are distributed under the Mozilla Public License 2.0:

- `mediabunny`, `@mediabunny/aac-encoder`, `@mediabunny/flac-encoder`, and `@mediabunny/mp3-encoder` 1.50.8. Corresponding source: <https://github.com/Vanilagy/mediabunny/tree/v1.50.8>
- `lightningcss` and `lightningcss-win32-x64-msvc` 1.33.0. Corresponding source: <https://github.com/parcel-bundler/lightningcss/tree/v1.33.0>

The MPL 2.0 text is retained with each installed package. The source locations above provide the Source Code Form for the exact package releases without requiring disclosure of Velvet Wire Studio's separate proprietary application source.

## Apache, BSD, ISC, CC BY, Unlicense, and 0BSD components

Complete package license files and supplied notice files are retained in `resources/app.asar.unpacked/node_modules`. This includes TypeScript's `ThirdPartyNoticeText.txt`.

- Apache-2.0: `@webassemblyjs/leb128` 1.13.2, `@xtuc/long` 4.2.2, `baseline-browser-mapping` 2.11.13, `detect-libc` 2.1.2, `human-signals` 2.1.0, and `typescript` 5.9.3.
- BSD-3-Clause: `@xtuc/ieee754`, `fast-uri`, `source-map` 0.6.1 and 0.8.0, and `source-map-js`.
- BSD-2-Clause: `eslint-scope`, `esrecurse`, `estraverse` 4.3.0 and 5.3.0, `glob-to-regexp`, and `terser`.
- ISC: `electron-to-chromium`, `graceful-fs`, `icss-utils`, `isexe`, `lru-cache`, `picocolors`, `postcss-modules-extract-imports`, `postcss-modules-scope`, `postcss-modules-values`, `semver` 7.5.3 and 7.8.5, `signal-exit`, `which`, and `yallist`.
- Unlicense: `fs-monkey` and `memfs`.
- 0BSD: `tslib` 2.8.1, including its packaged `CopyrightNotice.txt`.

`caniuse-lite` 1.0.30001809 is licensed under CC BY 4.0. Credit: Ben Briggs and contributors. Source: <https://github.com/browserslist/caniuse-lite>. License: <https://creativecommons.org/licenses/by/4.0/>. Velvet Wire Studio distributes the locked package data without modification.

## Electron and Chromium runtime

Velvet Wire Studio uses the official Electron 39.8.10 Windows runtime, which contains Chromium 142.0.7444.265, Node.js 22.22.1, and V8 14.2.231.22. Electron is MIT-licensed. `LICENSE.electron.txt` and Chromium's aggregate `LICENSES.chromium.html` are installed beside `Velvet Wire Studio.exe`; those files retain the runtime copyright, license, and third-party notices. Electron source: <https://github.com/electron/electron/tree/v39.8.10>. Chromium source: <https://source.chromium.org/chromium>.

Electron's `ffmpeg.dll` is part of this vendor-supplied runtime and is separate from the renderer executable described below.

## Chrome Headless Shell

The offline renderer includes Google Chrome for Testing Headless Shell 149.0.7790.0. Its complete Chromium and third-party notices are retained at `resources/renderer-browser/chrome-headless-shell/win64/chrome-headless-shell-win64/LICENSE.headless_shell`. Project information: <https://github.com/GoogleChromeLabs/chrome-for-testing>. Chromium source: <https://source.chromium.org/chromium>.

The Apache-2.0 license of the Chrome for Testing distribution tooling does not replace the Chromium and third-party terms recorded in the bundled `LICENSE.headless_shell` file.

## Controlled FFmpeg renderer runtime and codecs

Velvet Wire Studio uses Remotion 4.0.507 with its supported `binariesDirectory` option to select a Velvet Wire-controlled Windows x64 renderer runtime. The runtime is FFmpeg 7.1 configured with GPL and linked only to x264 commit `b35605ace3ddf7c1a5d67a2eb553f034aef41d55` and zlib 1.3.2 as external codec/compression libraries. It does not enable libfdk-aac, x265, or FFmpeg's nonfree option. H.264 video uses x264; AAC-LC audio uses FFmpeg's native AAC encoder.

The complete GNU GPL version 2 text and the zlib notice are reproduced in `THIRD-PARTY-LICENSES.md`. The installed application includes the exact corresponding source archives, the reproducible build script, the unmodified Velvet Wire launcher source, and a detailed build/provenance record under `resources/renderer-source`:

- FFmpeg 7.1: `ffmpeg-7.1.tar.xz`, SHA-256 `40973D44970DBC83EF302B0609F2E74982BE2D85916DD2EE7472D30678A7ABE6`.
- x264 commit `b35605ace3ddf7c1a5d67a2eb553f034aef41d55`, Copyright (C) 2003-2025 the x264 project: `x264-b35605ace3ddf7c1a5d67a2eb553f034aef41d55.tar.gz`, SHA-256 `CD71A7515B0E9A012E1AC9B1F8415BEBCAF6FC97D4DB32286642AC4C0FBE24F9`.
- zlib 1.3.2: `zlib-1.3.2.tar.gz`, SHA-256 `BB329A0A2CD0274D05519D61C667C062E06990D72E125EE2DFA8DE64F0119D16`.

No source patch is applied to FFmpeg, x264, zlib, or Remotion. A separate Velvet Wire launcher translates Remotion's preprocessing-only `libfdk_aac` encoder name to the native `aac` encoder before starting the unmodified FFmpeg executable; the launcher is not linked with FFmpeg and its complete source is included.

FFmpeg license and source information: <https://ffmpeg.org/legal.html> and <https://ffmpeg.org/releases/ffmpeg-7.1.tar.xz>. x264 source: <https://code.videolan.org/videolan/x264/-/commit/b35605ace3ddf7c1a5d67a2eb553f034aef41d55>. zlib source: <https://zlib.net/>.

H.264 and AAC implementations can implicate patent rights separate from copyright and open-source licenses. Those questions can vary by jurisdiction, distribution model, and use. Neither the Remotion license nor these notices supplies a product-specific patent clearance. Obtain professional legal advice before public commercial distribution.

## Application-owned media

- Built-in BGM: none.
- Public default SFX: Wire Pop and Wire Send, first-party procedural assets.
- Phone frame: two first-party procedural Velvet Wire assets generated without third-party image input.
- Hand artwork: none in the public runtime package.
- Legacy private/third-party audio and unresolved legacy phone-template derivatives: not included in the production allowlist.

## Product terms status

The included Velvet Wire Studio Terms of Use apply to Velvet Wire Studio 0.1.0 and have an effective date of September 14, 2026. The Terms, Third-Party Notices, and Third-Party Licenses are separate documents. Third-party software remains governed by its applicable license terms. No attorney review or product-specific patent clearance is claimed.
