
Enter file contents here
# 源码压缩包

本目录存放完整的 Android 工程源码压缩包（zip）。

## 内容

- 完整源码：`GamepadMouse-source.zip`
- 包含：`GamepadMouse/app` 工程全部代码、签名 keystore、README
- 包名：`com.gamepadmouse.app`

## 构建

环境：JDK 17 + Android SDK（compileSdk 34）

```bash
gradle assembleRelease lintRelease testReleaseUnitTest
```

产物：`app/build/outputs/apk/release/app-release.apk`

## 测试

- Lint：0 error
- 单元测试：13/13 通过（摇杆数学 / 后端决策）
