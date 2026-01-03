# Mostly Hard RuneLite Plugin

## Overview
Mostly Hard is a RuneLite plugin built specifically for the Mostly Hard clan in Old School RuneScape. This clan is exclusively for Hardcore Ironmen.

## Project Type
This is a **Java Gradle library/plugin** - not a web application. It compiles into a JAR file that gets loaded by the RuneLite client.

## Build System
- **Language**: Java 11
- **Build Tool**: Gradle 8.10 (via gradlew wrapper)
- **Dependencies**: RuneLite client API, Lombok, JUnit

## Project Structure
```
src/
├── main/java/com/oneshot/     # Plugin source code
│   ├── modules/               # Feature modules (Discord, Rankings, etc.)
│   ├── utils/                 # Utility classes
│   ├── OneShotPlugin.java     # Main plugin entry point
│   ├── OneShotConfig.java     # Plugin configuration
│   └── OneShotPanel.java      # UI panel
├── main/resources/            # Plugin assets/icons
└── test/                      # Unit tests
```

## Commands
- Build: `./gradlew build --no-daemon`
- Test: `./gradlew test --no-daemon`
- Create fat JAR: `./gradlew shadowJar --no-daemon`

## Features
- Live clan roles display
- Clan rankings comparison
- Discord integration link

## Recent Changes
- 2026-01-03: Initial import and Replit environment setup
