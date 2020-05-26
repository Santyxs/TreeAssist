# TreeAssist

**Auto Destroy, Auto Replant, and more!**

This plugin will replant trees when they are cut down (or burnt down), and will keep it the same tree type.
It also will take down an entire tree when it is enabled in the config.

***

## Features

- Replants trees (by placing saplings)
- Replants saplings of the tree type you broke
- Automated tree destruction
- Force break command - breaks all trees in a configurable range
- Force grow command - grows all saplings into trees in a configurable range
- mcMMO EXP integration

### Options

- Faster leaf decay
- Incrementing of minecraft block break / pickup statistics
- Require certain tool for automated destruction or sapling replanting
- Require lore tool for automated destruction or sapling replanting
- Require breaking of bottom block for automated destruction or sapling replanting
- Prevent tool damage from the automation
- Automatically add broken blocks to the inventory
- Automatically plant saplings that fell from trees
- Only allow automated destruction when sneaking
- Only allow automated destruction when NOT sneaking
- Only allow automated destruction in certain worlds
- Custom item drops, with individual chances

***

## Dependencies

- Spigot 1.13

***

## Downloads

- [spigotmc.org](https://www.spigotmc.org/resources/treeassist.67436/)
- [jenkins - dev builds](https://ci2.craftyn.com/job/TreeAssist/)


***

## How to install

- Stop your server
- Place jar in plugins folder
- Run a first time to create config folder
- Configure if you wish to
- Done !

***

## Documentation

- [Commands](doc/commands.md)
- [Permissions](doc/permissions.md)
- [Configuration](doc/configuration.md)

***

## Changelog

- v7.0-SNAPSHOT:
  Working:
  - all trees
  - automated removal of trunk logs, branches and some leaves
  - neighbor trees leaves do not get cut in (worst case we only remove a trunk and leave all leaves)
  Still working on:
  - implement configuration settings about when and how to remove trees automatically or to clean up
- [read more](doc/changelog.md)

// TODO: move all node implementation to tree types where it makes sense   
// TODO: add force comments for the default config

***

## Phoning home

By default, the server contacts www.bstats.org to notify that you are using my plugin.

Please refer to their website to learn about what they collect and how they handle the data.

If you want to disable the tracker, set "enabled" to false in __/plugins/bStats/config.yml__ !

***

## Credits

- FriendlyBaron aka itsatacoshop247 for the original source, the stable foundation that to this day runs strong in TreeAssist
- Bradley Hilton for the Jenkins
- pop4959 for the 1.13 update, and a kick in the butt at the right time
- btilm305 for keeping the repo together in time of need
- uroskn for some critical fixes regarding durability


***