# tvnamer

A utility to rename and move tv shows

## Config

Configuration at `/boot/plugins/custom/tvnamer/config/tvnamer.json`

## Notable defaults

    "batch": true,
    "move_files_destination": "/mnt/user/TV Shows/%(seriesname)s/Season %(seasonnumber)s",
    "move_files_enable": true,
    "recursive": true

## Cron

    * * * * * tvnamer /mnt/user/Downloads
