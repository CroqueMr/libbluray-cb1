# libbluray changes for LibreELEC × CB1

The official upstream is https://code.videolan.org/videolan/libbluray. The RC3 source import starts at `d75c88e54c893e5cbf4c61d356477655eb435769` and finishes at `ae3017f3cb97ec9052041b1cebb570c35d523a08`. The LibreELEC integration selects the version used to build an image.

[Full upstream-to-CB1 Git diff](https://github.com/CroqueMr/libbluray-cb1/compare/d75c88e54c893e5cbf4c61d356477655eb435769...ae3017f3cb97ec9052041b1cebb570c35d523a08)
 · [LibreELEC × CB1 releases](https://github.com/CroqueMr/libreelec-CB1/releases) · [RC3 integration PR](https://github.com/CroqueMr/libreelec-CB1/pull/260)

The list records the historical import and maps each original patch to its Git commit. The categories below describe the imported changes. Follow-up changes have their own PRs.

The Git tree pins the upstream libudfread submodule to `139a2194525f2745b98a98e4d8fa627d07440176`. The original RC3 tarball contains this source.

## Fix du dépôt

- 0001-set-headless-false [Original patch](https://github.com/CroqueMr/libreelec-CB1/blob/9e562e613c5f3c378d2143f771392b601112d49d/packages/multimedia/libbluray/patches/0001-set-headless-false.patch) · [Imported commit](https://github.com/CroqueMr/libbluray-cb1/commit/f86fcb696c8c1b787437726c0ea9c92afebe0327)
- 0002-bdj-video-and-stream-controls [Original patch](https://github.com/CroqueMr/libreelec-CB1/blob/9e562e613c5f3c378d2143f771392b601112d49d/packages/multimedia/libbluray/patches/0002-bdj-video-and-stream-controls.patch) · [Imported commit](https://github.com/CroqueMr/libbluray-cb1/commit/a0f3b4c488e574182471829749892e49cdbb8456)
- 0002-navigation-read-boundary [Original patch](https://github.com/CroqueMr/libreelec-CB1/blob/9e562e613c5f3c378d2143f771392b601112d49d/packages/multimedia/libbluray/patches/0002-navigation-read-boundary.patch) · [Imported commit](https://github.com/CroqueMr/libbluray-cb1/commit/5556d9dbb0e3845b86e869a0ca7474863d8f3ad2)
- 0003-hdmv-bc-compare [Original patch](https://github.com/CroqueMr/libreelec-CB1/blob/9e562e613c5f3c378d2143f771392b601112d49d/packages/multimedia/libbluray/patches/0003-hdmv-bc-compare.patch) · [Imported commit](https://github.com/CroqueMr/libbluray-cb1/commit/1258ba3940f9c5c79b45ee0da6809526281de085)
- 0004-bdj-bounded-repaint-sync [Original patch](https://github.com/CroqueMr/libreelec-CB1/blob/9e562e613c5f3c378d2143f771392b601112d49d/packages/multimedia/libbluray/patches/0004-bdj-bounded-repaint-sync.patch) · [Imported commit](https://github.com/CroqueMr/libbluray-cb1/commit/2e7bf18a3f6702a865663fa51bf2484729220d7f)
- 0005-pre151-hardening [Original patch](https://github.com/CroqueMr/libreelec-CB1/blob/9e562e613c5f3c378d2143f771392b601112d49d/packages/multimedia/libbluray/patches/0005-pre151-hardening.patch) · [Imported commit](https://github.com/CroqueMr/libbluray-cb1/commit/2ca6953e8e4bb6ff04c4e5a363e4b74042a6099b)
- 0006-bdj-leave-process-signals-to-host [Original patch](https://github.com/CroqueMr/libreelec-CB1/blob/9e562e613c5f3c378d2143f771392b601112d49d/packages/multimedia/libbluray/patches/0006-bdj-leave-process-signals-to-host.patch) · [Imported commit](https://github.com/CroqueMr/libbluray-cb1/commit/4f28491afb5dbfdff0b5e9576a76c87a129d6bfc)
- 0007-bdj-presentation-timing [Original patch](https://github.com/CroqueMr/libreelec-CB1/blob/9e562e613c5f3c378d2143f771392b601112d49d/packages/multimedia/libbluray/patches/0007-bdj-presentation-timing.patch) · [Imported commit](https://github.com/CroqueMr/libbluray-cb1/commit/ea6020670e709285621c88abbc30cba3e0b82a6d)
- 0008-bdj-use-the-player-clock [Original patch](https://github.com/CroqueMr/libreelec-CB1/blob/9e562e613c5f3c378d2143f771392b601112d49d/packages/multimedia/libbluray/patches/0008-bdj-use-the-player-clock.patch) · [Imported commit](https://github.com/CroqueMr/libbluray-cb1/commit/ae3017f3cb97ec9052041b1cebb570c35d523a08)

## Component repositories

- [Kodi for CB1](https://github.com/CroqueMr/xbmc)
- [FFmpeg for CB1](https://github.com/CroqueMr/FFmpeg)
- [libplacebo for CB1](https://github.com/CroqueMr/libplacebo)
- [CB1 rendering engine](https://github.com/CroqueMr/CB1)
- [LibreELEC × CB1 integration](https://github.com/CroqueMr/libreelec-CB1)
