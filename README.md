# Health Indicators for Minecraft 26.2

This Fabric port is based on [AdyTech99's Health Indicators](https://github.com/AdyTech99/HealthIndicators).
See the [original Modrinth page](https://modrinth.com/mod/health-indicators) for features and default key bindings.

## Installation

Use Minecraft Java Edition 26.2 with Java 25 and Fabric Loader 0.20.1 or newer. Add the mod JAR and the 26.2 Fabric releases of [Fabric API](https://modrinth.com/mod/fabric-api/version/0.161.0%2B26.2), [Architectury API](https://modrinth.com/mod/architectury-api/version/21.1.12%2Bfabric), and [Yet Another Config Lib](https://modrinth.com/mod/yacl/version/3.9.7%2B26.2-fabric) to the client instance's `mods` folder. [Mod Menu](https://modrinth.com/mod/modmenu/version/20.0.3) is optional. Press `I` in-game to open the configuration.

## Build

Run `./gradlew :fabric:build` with JDK 25 (`gradlew.bat :fabric:build` on Windows). The installable JAR is in `fabric/build/libs`.
