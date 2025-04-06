# postgres-backup

`postgres-backup` is a Helm chart that renders a CronJob with a script to backup, compressed and optionally PGP-encrypted, a postgres database to S3 by means of `pg_dump`.

It's not great and by any means production ready, but gets the job done and is better than no backup at all.

