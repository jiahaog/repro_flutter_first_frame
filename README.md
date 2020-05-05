# repro_flutter_first_frame

`WidgetsBinding.instance.firstFrameRasterized` is always `false`.

Steps:

```
flutter run
```

Observe that the value in stdout is always false even when the app has been rendered.

## Status

Fixed in https://github.com/flutter/flutter/commit/d6f6fc4d6b8eb1e01523558691891f5fcaebfb0c
