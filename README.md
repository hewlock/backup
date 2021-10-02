# backup

Incremental backup script leveraging rsync

## Usage

`./backup.sh SRC DEST`

## Example

Backup a home partition to a backup partition.

`bash ./backup.sh /media/$(whoami)/home /media/$(whoami)/backup`
