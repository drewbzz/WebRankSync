
# WebRankSync Plugin

A Minecraft plugin to sync player ranks from an Azuriom website's MySQL database to LuckPerms on a Spigot server.

## Features
- Automatically applies player ranks on join
- Manual sync command: `/syncwebrole <player>`
- Fully configurable MySQL and role mappings

## Setup
1. Edit `config.yml` (auto-generated on first run).
2. Place the `.jar` in your server's `/plugins/` folder.
3. Restart server.

## Build Instructions
1. Open project in IntelliJ or Eclipse (Gradle project).
2. Use `gradle build` or IntelliJ's Build Artifact feature.
3. Compiled `.jar` appears in `/build/libs/`.
