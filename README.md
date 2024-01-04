# tflite-runtime-builder

Build [TensorFlow Lite](https://www.tensorflow.org/lite) runtime with GitHub Actions

## Supported Platforms

You can download the archived files of the runtime binaries from [Releases](https://github.com/stakemura/tflite-runtime-builder/releases).

| Platform | Type   | ABI         |  Archived file         |
|----------|--------|-------------|---------------------------------------|
| Android  | .so    | armeabi-v7a | `tflite-runtime-android-arm-*.tgz`    |
| Android  | .so    | arm64-v8a   | `tflite-runtime-android-arm64-*.tgz`  |
| Android  | .so    | x86_64      | `tflite-runtime-android_x86_64-*.tgz` |
| Android  | .aar   | armeabi-v7, aarm64-v8a, x86_64 | `tflite-runtime-android-fat-aar-*.tgz` |
| iOS      | .framework  | arm64  | `tflite-runtime-ios-arm64-*.zip`      |
| iOS      | .framework  | x86_64 | `tflite-runtime-ios-x86_64-*.zip`     |
| Linux    | .so    | AArch64     | `tflite-runtime-linux-arm64-*.tgz`    |
| Linux    | .so    | x86_64      | `tflite-runtime-linux-x86_64-*.tgz`   |
| macOS    | .dylib | universal (arm64, x86_64) | `tflite-runtime-osx-universal2-*.tgz` |
| macOS    | .dylib | arm64       | `tflite-runtime-osx-arm64-*.tgz`      |
| macOS    | .dylib | x86_64      | `tflite-runtime-osx-x86_64-*.tgz`     |
| Windows  | .dll   | x86_64      | `tflite-runtime-win-x86_64-*.zip`     |

## License

MIT License

## How to contribute

Open an issue or create a pull request.
