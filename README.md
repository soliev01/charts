# Discontinued

**This project is no longer maintained**, and will not receive further updates. Community members interested in collaborating on a community-maintained fork can coordinate in [this issue](https://github.com/google/charts/issues/798).

---
To use this fork use a dependency override:

``` 
dependency_overrides:
  # Keep until https://github.com/google/charts/issues/798 is resolved.
  charts_flutter:
    git:
      url: https://github.com/fzyzcjy/charts.git
      ref: master
      path: charts_flutter
```

Charts is a general charting library, currently enabled for the
[Flutter mobile UI framework](https://flutter.io).

See the [online gallery](https://google.github.io/charts/flutter/gallery.html) for supported chart
types and examples of how to custom components of the chart.

*Note*: This is not an official Google product.

[![Travis CI Build Status](https://travis-ci.org/google/charts.svg?branch=master)](https://travis-ci.org/google/charts)

## charts_common

[![charts_common pub package](https://img.shields.io/pub/v/charts_common.svg)](https://pub.dartlang.org/packages/charts_common)

A common library for charting packages.

## charts_flutter

[![charts_flutter pub package](https://img.shields.io/pub/v/charts_flutter.svg)](https://pub.dartlang.org/packages/charts_flutter)

A charting package for [Flutter](https://flutter.io), supporting both Android
and iOS.

All charts packages are licensed under the Apache 2 license, see the
[LICENSE](LICENSE) and [AUTHORS](AUTHORS) files for details.
