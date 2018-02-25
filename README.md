for use with [godmode9](https://github.com/d0k3/GodMode9).

> disclaimer: i'm not responsible for anything that happens as a result of using these scripts. it is up to the user's responsibility to review the code and create backups before use

> [recommendations for any improvements to existing scripts are welcome](https://github.com/zweilous/gm9scripts/issues)

---

1. [extract pokémon game `.code`](gm9/scripts/extract%20pokemon%20game%20.code.gm9)
  - extract `.code` from the main or update title from any 3DS pokémon game installed as an SD title
2. [reset activity log](gm9/scripts/reset%20activity%20log.gm9)
  - for use with USA/JPN/EUR/KOR systems only
  - create a backup of ptm or activity log savedata on sysnand
    - saves in output folder with the following format: `yymmdd_serial_title_###`
  - delete existing ptm and activity log savedata
3. [restore activity log](gm9/scripts/restore%20activity%20log.gm9)
  - for use with USA/JPN/EUR/KOR systems only
  - restore a backup of ptm or activity log savedata on sysnand
    - must be located in the output folder with the following format: `yymmdd_serial_title_###`
    - to be used with the backup functions from the "[reset activity log](gm9/scripts/reset%20activity%20log.gm9)" script
