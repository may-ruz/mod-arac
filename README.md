# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore
## ARAC - All Races All Classes
# ![ARAC icon](https://raw.githubusercontent.com/azerothcore/mod-arac/master/icon.png)

Azerothcore Build e0bc7d73ddaa 2024-03-14

This fork adds the following:
+ appropriate class eqquipment to new race-class combos
+ adds Hearthstone to new race-class combos
+ cleaned the abilities on the action bars, such as removing duplicate racial abilities
+ the hunter class learns the gun skill by default

Note: Orc, Blood Elf, and Draenei racial traits and abilities on new class-race combos remain broken.

## Screenshot

![arac](https://raw.githubusercontent.com/azerothcore/mod-arac/master/images/screen1.png)

![arac](https://raw.githubusercontent.com/azerothcore/mod-arac/master/images/screen2.png)


# Usage 

- Make a backup of your database before using this module.
- Apply [the SQL query](https://github.com/may-ruz/mod-arac/blob/master/data/sql/db-world/arac.sql) to your `world` database.
- Update your DBC files (client and server) contained in the release, so add [**Patch-A.MPQ**](https://github.com/heyitsbench/mod-arac/blob/master/Patch-A.MPQ) to your WoW/Data/ directory and update the DBC files in your server/data/dbc/ directory with the ones contained in [the DBFilesContent directory](https://github.com/heyitsbench/mod-arac/tree/master/patch-contents/DBFilesContent).

# Need help?

If you encounter a bug, please [open an issue](https://github.com/azerothcore/mod-arac/issues/new).
     

## Credits

* [iThorgrim](https://github.com/iThorgrim)

AzerothCore: [Repository](https://github.com/azerothcore) - [Website](http://azerothcore.org/) - [Discord chat community](https://discord.gg/PaqQRkd)
