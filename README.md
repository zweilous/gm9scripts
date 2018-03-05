for use with [godmode9](https://github.com/d0k3/GodMode9).

> disclaimer: i'm not responsible for anything that happens as a result of using these scripts. it is up to the user's responsibility to review the code and create backups before use

> [recommendations for any improvements to existing scripts are welcome](https://github.com/zweilous/gm9scripts/issues)

---

1. [clear home menu icon cache](gm9/scripts/clear%20home%20menu%20icon%20cache.gm9)
  - delete the files associated with the home menu icon cache from your sd card
    - the home menu will create a new cache on boot and will remove any old installed theme
2. [dump cartridge](gm9/scripts/dump%20cartridge.gm9)
  - dump `.3ds` file as `.cia` from a CTR cartridge or dump `.nds` file from a NTR cartridge
3. [extract pokémon game files](gm9/scripts/extract%20pokemon%20game%20files.gm9)
  - extract `romfs` or `.code` from the main/update title from any 3DS pokémon game installed as an SD title
4. [reset activity log](gm9/scripts/reset%20activity%20log.gm9)
  - create backups of ptm and activity log savedata from sysnand
    - saves in output folder with the following format: `yymmdd_serial_title_###`
  - delete existing ptm and activity log savedata
5. [restore activity log](gm9/scripts/restore%20activity%20log.gm9)
  - restore a backup of ptm or activity log savedata to sysnand
    - must be located in the output folder with the following format: `yymmdd_serial_title_###`
    - to be used with the backup functions from the "[reset activity log](gm9/scripts/reset%20activity%20log.gm9)" script
6. [swap splashpin.bin](gm9/scripts/swap%20splashpin.bin.gm9)
  - swap the current `splashpin.bin` located in `/luma` with a backup in `/luma/splashpin`
    - files placed in `/luma/splashpin` must be named `splashpin_###.bin` to be detected
