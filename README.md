# tflite-runtime-builder

Build [TensorFlow Lite](https://www.tensorflow.org/lite) runtime with GitHub Actions

## Supported Platforms

You can download the runtime binaries `tflite-runtime.zip` from [Releases](https://github.com/stakemura/tflite-runtime-builder/releases).

| Platform | Type   | ABI         |  Directory                   |
|----------|--------|-------------|-------------------------------------|
| Android  | .so    | armeabi-v7a | `tflite-runtime-android_arm`        |
| Android  | .so    | arm64-v8a   | `tflite-runtime-android_arm64`      |
| Android  | .so    | x86_64      | `tflite-runtime-android_x86_64`     |
| Android  | .aar   | armeabi-v7, aarm64-v8a, x86_64 | `tflite-runtime-android_fat_aar` |
| iOS      | .framework  | arm64  | `tflite-runtime-ios_arm64`          |
| iOS      | .framework  | x86_64 | `tflite-runtime-ios_x86_64`         |
| Linux    | .so    | AArch64     | `tflite-runtime-elinux_aarch64`     |
| Linux    | .so    | x86_64      | `tflite-runtime-linux`              |
| macOS    | .dylib | universal (arm64, x86_64) | `tflite-runtime-macos` |
| macOS    | .dylib | arm64       | `tflite-runtime-macos_arm64`        |
| macOS    | .dylib | x86_64      | `tflite-runtime-macos_x86_64`       |
| Windows  | .dll   | x86_64      | `tflite-runtime-windows_x86_64`     |

## License

MIT License

## How to contribute

Open an issue or create a pull request.
