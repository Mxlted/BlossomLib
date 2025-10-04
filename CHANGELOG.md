# 2.5.15

* Update to support 1.21.9

# 2.5.14

* Update to support 1.21.6

# 2.5.13

* Fix issue with genericCountdown failing 

# 2.5.12

* Update to support 1.21.5

# 2.5.11

* Update to support 1.21.3

# 2.5.10

* Update to support 1.21.3

# 2.5.9

* Update to support 1.21.1

# 2.5.8

* Update to support 1.21

# 2.5.7

* Update to 1.20.6
* Bump gradle-wrapper version
* Bump dependency versions
* Bump loom version
* Add publishing to alternate repository (<https://maven.codedsakura.dev>)

# 2.5.6

* Update to 1.20.4
* Bump gradle-wrapper version
* Bump dependency versions

# 2.5.5

* Update to 1.20.2
* Bump server translation api

# 2.5.4

* Add extra trace logging

# 2.5.3

* Expand TeleportUtils for [BlossomBack#3](https://github.com/BlossomMods/BlossomBack/issues/3)

# 2.5.2

* Reuse bossbar if already present ([#BlossomHomes/10](https://github.com/BlossomMods/BlossomHomes/issues/10))
* Resolve [#BlossomTpa/8](https://github.com/BlossomMods/BlossomTpa/issues/8)

# 2.5.1-fix.1

* Fix 1.20 implementation for MC124177Fix

# 2.5.1

* Prevent unnecessary class loading in MixinConfigPlugin ([#5](https://github.com/BlossomMods/BlossomLib/issues/5))

# 2.5.0

* Allow checking permissions of Entities (!4)
* Add display key override to CommandTextBuilder

# 2.4.1

* Fix a StackOverflowError in TextSuperJoiner (BlossomWarps#2)

# 2.4.0

* Add cancelOnMove option to TeleportConfig (#2)
* Fix BossBar not appearing for countdowns

# 2.3.3

* Add Chinese translations (Simplified & Traditional), courtesy of @BackWheel

# 2.3.2

* Prevent MC124177Fix from causing "Invalid player data"
* Update CI

# 2.3.1

* Add Modrinth to CI

# 2.3.0

* Add MC-124177 fix
* Add bypass for custom logger to fix #1

# 2.2.1

* Add a toString method to TeleportDestination

# 2.2.0

* Add DimName helper

# 2.1.0

* Add TextSuperJoiner for use in item lists
* Bump ServerTranslationAPI

# 2.0.0

* Fix /tpcancel
* Remove deprecated files

# 1.4.0

* Add FOV animations
* Fix Text being incorrectly converted to as string

# 1.3.0

* Improve project structure

# 1.2.1

* Improve CI

# 1.2.0

* Add JoiningCollector

# 1.1.0

* Add another way to register commands

# 1.0.0-rc.3

* Fix CTB (CommandTextBuilder) failing when no description provided
* Add more options to CTB
* Add & document locale keys for CTB

# 1.0.0-rc.2

* Add CommandTextBuilder to simplify commands with hover action & click action
* Add ConfigManager to simplify config reloading
* Add commands for ConfigManager

# 0.2.0-rc.4

* Add more constructors to TeleportUtils.TeleportDestination
* Fix TextUtils.player not applying the style correctly

# 0.2.0-rc.3

* Fix ListDataController#getArrayClassType not being public

# 0.2.0-rc.2

* Add ListDataController for parsing JSON arrays

# 0.2.0-rc.1

* Remove CSV, NBT from SaveController
* Rename SaveController to DataController to better reflect its purpose
* Add more links to README.md

# 0.1.0-rc.2

* Fix SaveController not saving JSON properly

# 0.1.0-rc.1

* Add warn color to config
* 11 new translation keys: `blossom.config-reload`, `blossom.clear-countdowns.all`, `blossom.clear-countdowns.one`,
  `blossom.clear-cooldowns.all`, `blossom.clear-cooldowns.one`, `blossom.clear-cooldowns.type`,
  `blossom.debug.countdown.start`, `blossom.debug.countdown.end`, `blossom.debug.teleport.no-cooldown`,
  `blossom.debug.teleport.cooldown`, `blossom.tpcancel`
* Add SaveController for managing NBT, CSV, Json data

# 0.0.1-beta1

* Add teleport and cooldown helper to TeleportUtils
* Add previous location storing for /back
* Add allowBack config option
* Add /tpcancel
* Document commands in README.md
* Add command registration to reduce children mod dependency on FabricAPI

# 0.0.1-alpha2

* Add a config
* Update logger to use the config
* Add CHANGELOG.md
* Add TeleportUtils utility class
* Add README.md to document config shape
* Add Fabric API
* Add commands for reloading config, clearing countdown, debug
* Add [Server Translations API](https://github.com/arthurbambou/Server-Translations)
* Update config
* Update TeleportUtils to have translations
* Separate TeleportConfig into its own file

# 0.0.1-alpha1

* Initialize project
* Add [fabric-permissions-api](https://github.com/lucko/fabric-permissions-api) as an optional dependency
* Add custom logger that could write to a logfile
* Add GitHub CI
