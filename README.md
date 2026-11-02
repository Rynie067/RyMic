# Baritone Control UI

This repository now builds **Baritone Control UI 0.2.0-alpha.1**, a standalone Fabric client mod for Minecraft Java 26.2.

The source archive is stored as Base64 chunks under `archive-b64/`. GitHub Actions reassembles and validates it, builds with Java 25 and Gradle 9.5.1, then attaches the JAR to a GitHub pre-release.

- In-game screen: **Right Ctrl**
- Required separately: Fabric Loader, Fabric API, and Baritone Fabric 1.19.0
- The mod does not bundle Baritone.

Build status: [GitHub Actions](../../actions/workflows/build.yml)
