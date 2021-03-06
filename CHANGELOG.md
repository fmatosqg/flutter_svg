# CHANGES

## 0.2.0

- Fix bug(s) in inheritence (better rendering of Ghostscript_Tiger.svg)
- Support for `<clipPath>`s
- Refactoring of how gradients are handled to enable clipPaths
- Refactor of SVG shape -> path logic

## 0.1.4

- Fix bugs in `<radialGradient>` percentage handling.
- Add error widget on error.
- Add ability to specify error/placeholder widgets.
- Minor improvement on flutter logo SVG (add missing gradient).
- Improve docs, unit tests.

## 0.1.3

- Add more unit tests and rendering tests (!).
- Add top level flutter_svg.dart.
- Fix bugs found in transform matrix logic for skewX and skewY.
- Minor improvements in handling inheritence for PathFillType.
- Support gradient spread types (TileModes in Flutter).

## 0.1.2

- Bump to path_drawing 0.2.3 (fix arc defect).
- Handle 'none' in dasharray without throwing exception.
- Better handling of inheritence and 'none' in fill/stroke/dasharray

## 0.1.1

- Handle opacity on groups and inherited/blended opacity.
- Fixes elements that have both opacity and stroke-opacity or fill-opacity.
- Improvements for inheritence.
- Fixes related to unspecified fills on shapes.

## 0.1.0

Bumping minor version due to internal breaking changes and new support. Works on dev channel as of release (Flutter >= 0.3.6).

- Refactor `DrawableRoot` to support top level style definition.
- Support for dash paths.
- Support for more inherited attributes.
- Initial support for `@style` attributes.
- Support for `rgb()` color attribute/styles.
- Change painting order from stroke first, then fill to fill first, then stroke (matches Chrome rendering of `assets/simple/style_attr.svg`).

## 0.0.2

Initial text support.  Relies on flutter 0.3.6.

## 0.0.1

Initial release.  Relies on pre-released master.
