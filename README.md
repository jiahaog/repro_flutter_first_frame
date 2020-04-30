# repro_flutter_first_frame

`WidgetsBinding.instance.firstFrameRasterized` is always `false`.

Steps:

```
flutter run
```

Observe that the value in stdout is always false even when the app has been rendered.