# CHANGELOG

## 1.1.5+1

- Remove/update some invalid assertions related to image formats.

## 1.1.5

- Support for decoding control points as IEEE 754-2008 half precision
  floating point values.
- Migrate the test to extend DefaultWidgetsLocalizations.
- Added an error builder property to provide a fallback widget on exceptions.

## 1.1.4

- Support more image formats and malformed MIME types.
- Fix inheritence for `fill-rule`s.

## 1.1.3

- Further improvements to whitespace handling for text.

## 1.1.2

- Fix handling and inheritence of `none`.

## 1.1.1

- Multiple text positioning bug fixes.
- Preserve stroke-opacity when specified.

## 1.1.0

- Fix a number of inheritence related bugs:
  - Inheritence of properties specified on the root element now work.
  - Opacity inheritence is more correct now.
  - Inheritence of `use` elements is more correctly handled.
- Make `currentColor` non-null on SVG theme, and fix how it is applied.
- Remove the opacity peephole optimizer, which was incorrectly applying
  optimizations in a few cases. A future release may add this back.
- Add clipBehavior to the widget.
- Fix patterns when multiple patterns are specified and applied within the
  graphic.

## 1.0.1+1

- Fix bug in asset loading from packages.

## 1.0.1

- Fix handling of fill colors on use/group elements.

## 1.0.0+1

- Fix issue in pattern decoding.
- Fix issue in matrix parsing for some combinations of matrices.

## 1.0.0

* Stable release.
* Use `ImageCache` for images.
* Bug fixes for image rendering.
* Better support for synchronous usage in testing.
* Make clipping the viewbox optional.

## 0.0.3

  * Improvements to CLI utilities.
  * Dispose unused objects.
  * Improved support for HTML backend.
  * Less aggressive rasterization strategy for flutter_svg compatibility.

## 0.0.2
  * Support for drawing images

## 0.0.1
  * Added `VectorGraphic` which consumes encoded vector graphics assets using
    a `BytesLoader`.
  * Added `AssetBytesLoader` and `NetworkBytesLoader` as example loader
    implementations.

## 0.0.0

* Create repository
