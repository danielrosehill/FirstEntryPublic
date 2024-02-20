Synology -> Control panel -> Task scheduler -> Add user defined task - > Run daily

rsync -arvz /volume1/docker/homebox/ /volume1/HomeboxBackup/dataauto/

Replace target with backup directory. Then use CloudSync to duplicate offsite to a cloud.

Creates incremental daily backup.
