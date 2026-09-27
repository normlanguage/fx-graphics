# fx.graphics

[English](README.md) | [简体中文](README.zh-CN.md)

Module identity and dependencies: [module.norm](fx/graphics/module.norm). Package toolchain: [workflow](.github/workflows/package.yml).

Build: `norm package fx/graphics --output build/repository`.

Validated on Windows x64 with JVM execution and Native application startup. JavaFX artifacts are resolved from Maven Central; Norm packages are distributed through GitHub Releases. The [Native reachability metadata](fx/graphics/resources/META-INF/native-image/org.openjfx/javafx-graphics/reachability-metadata.json) follows [GraalVM's format](https://www.graalvm.org/jdk25/reference-manual/native-image/metadata/); [verify it against the OpenJFX Windows JAR](scripts/verify-native-image-metadata.py) when updating OpenJFX.

[Sample ownership](samples/README.md).
