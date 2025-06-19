## What's Changed

* Fixed "Saturation" blend mode for layers [#4593](https://github.com/aseprite/aseprite/issues/4593)
* Fixed drawing semi-transparent slices on the canvas [#5027](https://github.com/aseprite/aseprite/pull/5027)
* Fixed straight line via <kbd>Shift + click</kbd> on Tiled mode [#4999](https://github.com/aseprite/aseprite/issues/4999) (thanks to [@lightovernight](https://github.com/aseprite/aseprite/pull/5029)) and tilemaps on manual mode [#4623](https://github.com/aseprite/aseprite/issues/4623)
* Fixed onionskin bug switching layer visibility [#4969](https://github.com/aseprite/aseprite/issues/4969)
* Fixed crash rendering sprites with custom pixel ratios [#4632](https://github.com/aseprite/aseprite/issues/4632)
* Fixed timeline thumbnails to use the full available space [#4974](https://github.com/aseprite/aseprite/issues/4974)
* Lua API:
  * Update [API version](https://www.aseprite.org/api/app#appapiversion) to 32
  * Don't allow to set invalid pixel ratios for sprites [#3285](https://github.com/aseprite/aseprite/issues/3285)
  * Fixed `Image:drawImage()` when `BlendMode.SRC` is used [#5001](https://github.com/aseprite/aseprite/issues/5001)

## Merged PRs
* Fix timeline thumbnail zoom can't scale beyond 1:1 pixels (fix [#4974]) by @Gasparoken in https://github.com/aseprite/aseprite/pull/4992
* Fix crash with custom pixel ratios (e.g. Size(4, 3)) (fix [#4632]) by @Gasparoken in https://github.com/aseprite/aseprite/pull/4965
* Fix image:drawImage+BlendMode.SRC doesn't draw mask pixels (fix [#5001]) by @Gasparoken in https://github.com/aseprite/aseprite/pull/5004
* Fix "Straight Line from Last Point” bug in Tilemaps (fix [#4623]) by @Gasparoken in https://github.com/aseprite/aseprite/pull/4949
* Fix onionskin visiblity is not updated if cel is empty (fix [#4969]) by @Gasparoken in https://github.com/aseprite/aseprite/pull/4994
* Fix Straight line via SHIFT + Tiled mode starts at wrong position by @lightovernight in https://github.com/aseprite/aseprite/pull/5029
* Fix set_sat() blend function by @Liebranca in https://github.com/aseprite/aseprite/pull/5002
* Fix when Slices are set to a semi-transparent color they become opaque as we draw by @Gasparoken in https://github.com/aseprite/aseprite/pull/5027

## New Contributors
* @lightovernight made their first contribution in https://github.com/aseprite/aseprite/pull/5029

**Full Changelog**: https://github.com/aseprite/aseprite/compare/v1.3.12...v1.3.13