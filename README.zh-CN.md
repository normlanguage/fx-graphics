# fx.graphics

[English](README.md) | [简体中文](README.zh-CN.md)

模块身份和依赖见 [module.norm](fx/graphics/module.norm)，发布使用的工具链见[工作流](.github/workflows/package.yml)。

构建：`norm package fx/graphics --output build/repository`。

已在 Windows x64 验证 JVM 执行和 Native 应用启动。JavaFX 制品从 Maven Central 解析；Norm 包通过 GitHub Releases 分发。[Native 可达性元数据](fx/graphics/resources/META-INF/native-image/org.openjfx/javafx-graphics/reachability-metadata.json)遵循 [GraalVM 格式](https://www.graalvm.org/jdk25/reference-manual/native-image/metadata/)；升级 OpenJFX 时用[核查脚本](scripts/verify-native-image-metadata.py)对照 Windows JAR。

[示例归属](samples/README.zh-CN.md)。
