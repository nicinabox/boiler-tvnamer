# tvnamer

Automatic TV episode file renamer, uses data from thetvdb.com via tvdb_api.
See [dbr/tvnamer](https://github.com/dbr/tvnamer) for full usage.

## Config

Configuration at `/boot/plugins/custom/tvnamer/config/tvnamer.json`

## Notable defaults

    "batch": true,
    "move_files_destination": "/mnt/user/TV Shows/%(seriesname)s/Season %(seasonnumber)s",
    "move_files_enable": true,
    "recursive": true

## Cron

    * * * * * tvnamer /mnt/user/Downloads
